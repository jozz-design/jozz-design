
- <!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Ma Page de Garde</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #000; /* fond noir */
      color: white;
      display: flex;
      flex-direction: column;
      height: 100vh;
    }

    .hero {
      flex: 1;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 2rem;
      background: linear-gradient(to bottom, #000, #001f3f); /* noir -> bleu foncé */
    }

    .hero h1 {
      font-size: 3rem;
      color: #FFD700; /* or */
      margin-bottom: 1rem;
    }

    .hero p {
      font-size: 1.3rem;
      color: white;
      max-width: 600px;
      margin-bottom: 2rem;
    }

    .hero button {
      background-color: #0056b3; /* bleu vif */
      color: white;
      border: none;
      padding: 1rem 2rem;
      font-size: 1rem;
      border-radius: 8px;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    .hero button:hover {
      background-color: #FFD700; /* or */
      color: black;
    }

    footer {
      background-color: #111;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #aaa;
    }
  </style>
</head>
<body>
  <section class="hero">
    <h1>Bienvenue sur MonApp Futbol</h1>
    <p>Améliore ton jeu, suis ton progrès et deviens un joueur d'élite. Rejoins notre communauté dès aujourd'hui.</p>
    <button>Commencer</button>
  </section>
  <footer>
    &copy; 2025 MonApp Futbol. Tous droits réservés.
  </footer>
</body>
</html>


<!---
jozz-design/jozz-design is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
