<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Courir pour un Monde Meilleur</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background: url('https://images.unsplash.com/photo-1602323895218-0636a2b59b2e') center/cover no-repeat;
      height: 60vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
    }
    header h1 {
      font-size: 3em;
      background-color: rgba(0, 0, 0, 0.6);
      padding: 1rem 2rem;
      border-radius: 15px;
    }
    nav {
      background-color: #1e90ff;
      padding: 1rem;
      text-align: center;
    }
    nav a {
      margin: 0 1rem;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 3rem 1rem;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #1e90ff;
      margin-bottom: 1rem;
    }
    .btn {
      display: inline-block;
      margin-top: 1.5rem;
      padding: 0.75rem 1.5rem;
      background-color: #1e90ff;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      transition: background 0.3s;
    }
    .btn:hover {
      background-color: #156dc1;
    }
    footer {
      background-color: #1e90ff;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 3rem;
    }
  </style>
</head>
<body>

<header>
  <h1>Courir pour un Monde Meilleur</h1>
</header>

<nav>
  <a href="#a-propos">À propos</a>
  <a href="#mission">Notre mission</a>
  <a href="#soutien">Soutien</a>
</nav>

<section id="a-propos">
  <h2>Qui sommes-nous ?</h2>
  <p>Nous sommes une équipe de jeunes motivés qui ont décidé d’unir sport et solidarité. Notre objectif est simple : mettre notre énergie au service d’une cause qui nous dépasse.</p>
</section>

<section id="mission">
  <h2>Notre mission</h2>
  <p>À travers des événements sportifs comme des courses, des tournois ou des défis collectifs, nous collectons des fonds pour soutenir l’éducation et des projets locaux dans des pays en développement.</p>
</section>

<section id="soutien">
  <h2>Nous soutenir</h2>
  <p>Vous pouvez nous aider en partageant notre projet, en venant courir avec nous, ou en faisant un don. Chaque geste compte !</p>
  <a class="btn" href="https://www.helloasso.com/" target="_blank">Faire un don</a>
</section>

<footer>
  <p>Contact : projet.sportif@exemple.com | Instagram : @notreprojet</p>
</footer>

</body>
</html>
