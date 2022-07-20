# second
coucou
my name is moez 
hyyyyy
<!DOCTYPE html>
<html>

<head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      font-family: "Trebuchet MS";
    }

    .menu {
      display: flex;
      /* Transformation en flexbox */
      padding: 0;
      /* Suppression des marges internes */
      background-color: #ccc;
      /* Ajout de la couleur d'arrière-plan */
      justify-content: space-around;
      /* Alignements des liens dans le menu */
    }

    .menu li {
      list-style-type: none;
      /* Suppression des puces */

    }

    .menu a {
      display: block;
      /* Transformation en block */
      min-width: 120px;
      /* Largeur minimale des liens */

      margin: 0.5rem;
      /* Marges externes */
      padding: 0.4rem 0;
      /* Marges internes */
      text-align: center;
      /* Centrage du texte */
      background-color: #1ABC9C;
      /* Arrière-plan */
      color: #fff;
      /* Couleur du texte */
      text-decoration: none;
      /* Suppression du soulignement */
      border: 1px solid #fff;
      /* Ajout d'une bordure */
      border-radius: 4px;
      /* Arrondis des bordures */

      transition: all 1s;
      /* Ajout des effets de transition */
    }

    .menu a.actif {
      background-color: #000;
      color: #1ABC9C;
      border-color: #1ABC9C;
    }

    .menu a:hover,
    .menu a:hover.actif {
      background-color: #ed2794;
      color: #ffe843;
      border-color: #ffe843;
    }

    .logo {
      background-color: #04AA6D;
    }

    /* Green */
    .logo:hover {
      background-color: #46a049;
    }

    .home {
      background-color: #2196F3;
    }

    /* Blue */
    .home:hover {
      background: #0b7dda;
    }

    .produit {
      background-color: #ff9800;
    }

    /* Orange */
    .produit:hover {
      background: #e68a00;
    }

    .equipe {
      background-color: #f44336;
    }

    /* Red */
    .equipe:hover {
      background: #da190b;
    }

    .contact {
      background-color: #e7e7e7;
      color: black;
    }

    /* Gray */
    .contact:hover {
      background: #ddd;
    }
  </style>
</head>

<body>
  <img src="jackie-chan-biography.jpg" alt="Trulli" width="500" height="333">
  <ul class="menu">
    <li>
      <a href="index.html" class="actif">LOGO</a>
    </li>
    <li>
      <a href="JACKIE CHAN.html" width="500" height="600">HOME</a>
      
    </li>
    <li>
      <a href="#">produit</a>
    </li>
    <LI>
      <a href="#">equipe</a>
    </LI>
    <LI>
      <a href="#">contact</a>
    </LI>
  </ul>

  <h1>BIENVENUE</h1>

  <button class="btn logo"><a href="https://www.w3schools.com">logo</a></button>
  <button class="btn home">home</button>
  <button class="btn produit">produit</button>
  <button class="btn equipe">equipe</button>
  <button class="btn contact">contact</button>

</body>

</html>

</html>
