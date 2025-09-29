<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Heilig Geist Institut</title>
  <style>
    /* --- RESET --- */
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f5f7fa;
      color: #333;
    }

    header {
      background: #0A1D4A;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    header h1 { margin-bottom: 5px; }
    nav {
      margin-top: 10px;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover { color: #FFD700; }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #0A1D4A;
    }

    .btn {
      display: inline-block;
      padding: 10px 20px;
      background: #FFD700;
      color: #0A1D4A;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }
    .btn:hover { background: #e6c200; }

    /* FORMULAIRE */
    form {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      max-width: 600px;
      margin: auto;
    }
    form label { display: block; margin: 10px 0 5px; }
    form input, form select, form button {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form button {
      background: #0A1D4A;
      color: white;
      border: none;
      cursor: pointer;
    }
    form button:hover { background: #062864; }

    footer {
      text-align: center;
      padding: 20px;
      background: #0A1D4A;
      color: white;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Heilig Geist Institut</h1>
    <p>Votre premier choix pour une préparation réussie en Allemagne</p>
    <nav>
      <a href="#accueil">Accueil</a>
      <a href="#apropos">À propos</a>
      <a href="#formations">Formations</a>
      <a href="#inscriptions">Inscriptions</a>
      <a href="#contacts">Contacts</a>
    </nav>
  </header>

  <!-- ACCUEIL -->
  <section id="accueil">
    <h2>Bienvenue à l’Institut Heilig Geist</h2>
    <p style="text-align:center; margin:20px 0;">
      Nous vous offrons une préparation linguistique de qualité pour vos études et projets en Allemagne.
    </p>
    <div style="text-align:center;">
      <a href="#inscriptions" class="btn">S’inscrire maintenant</a>
    </div>
  </section>

  <!-- A PROPOS -->
  <section id="apropos">
    <h2>À propos de nous</h2>
    <p>
      L’Institut Heilig Geist est spécialisé dans l’enseignement de la langue allemande pour vous préparer à vos études, votre travail et votre intégration en Allemagne.  
      Nous mettons l’accent sur la qualité, la discipline et la réussite de nos étudiants.
    </p>
  </section>

  <!-- FORMATIONS -->
  <section id="formations">
    <h2>Nos Formations</h2>
    <ul>
      <li><strong>A1 et A2 :</strong> Mardi, jeudi, samedi (17h30 – 20h30)</li>
      <li><strong>B1 et B2 :</strong> Lundi, mercredi, vendredi (17h30 – 20h30)</li>
    </ul>
    <p style="margin-top:10px;">
      📌 Durée : 3 mois par niveau  
      🎁 Réduction de 5 % pour les 5 premiers inscrits
    </p>
  </section>

  <!-- INSCRIPTIONS -->
  <section id="inscriptions">
    <h2>Inscription en ligne</h2>
    <form action="https://formspree.io/f/xgvnavlq" method="POST">
      <label>Nom complet :</label>
      <input type="text" name="Nom" required>

      <label>Email :</label>
      <input type="email" name="Email" required>

      <label>Téléphone :</label>
      <input type="tel" name="Téléphone" required>

      <label>Module choisi :</label>
      <select name="Module">
        <option value="A1">A1</option>
        <option value="A2">A2</option>
        <option value="B1">B1</option>
        <option value="B2">B2</option>
      </select>

      <button type="submit">S’inscrire</button>
    </form>
  </section>

  <!-- CONTACTS -->
  <section id="contacts">
    <h2>Nous contacter</h2>
    <p style="text-align:center;">
      📧 Email : <a href="mailto:heiliggeistinstitut@gmail.com">heiliggeistinstitut@gmail.com</a><br>
      📞 Téléphone : (+228) 92 63 91 38 / 99 64 49 27 / 99 92 15 91<br>
      📍 Adresse : Agbata-zivé, non loin de la nationale N°2
    </p>
  </section>

  <footer>
    <p>&copy; 2025 Heilig Geist Institut - Tous droits réservés</p>
  </footer>

</body>
</html>
