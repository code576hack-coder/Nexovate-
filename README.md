# Nexovate-
Nexovate officiel

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nexovate - L’expertise tech à domicile</title>
  <style>
    body {
      background: linear-gradient(120deg, #0d0f25, #0a1f44);
      color: #f0f0f0;
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      text-align: center;
    }
    header {
      padding: 2rem;
    }
    h1 {
      font-size: 2.5rem;
      color: #00bfff;
    }
    p.slogan {
      font-size: 1.2rem;
      color: #ccc;
    }
    .contact-btn {
      margin-top: 2rem;
    }
    a.whatsapp-button {
      background-color: #25D366;
      color: white;
      padding: 1rem 2rem;
      text-decoration: none;
      border-radius: 30px;
      font-size: 1.2rem;
      display: inline-block;
      margin: 10px;
    }
    .socials {
      margin-top: 3rem;
    }
    .socials a {
      margin: 0 15px;
      color: #00bfff;
      font-size: 1.1rem;
      text-decoration: none;
    }
    .footer {
      margin-top: 4rem;
      font-size: 0.8rem;
      color: #555;
    }
  </style>
</head>
<body>

  <header>
    <h1>Nexovate</h1>
    <p class="slogan">L’expertise tech à domicile</p>
  </header>

  <section class="contact-btn">
    <a href="https://wa.me/50934372781" class="whatsapp-button" target="_blank">📲 Contact via WhatsApp</a>
  </section>

  <section class="socials">
    <h2>Suivez-nous</h2>
    <a href="https://www.instagram.com/nexovate_official" target="_blank">Instagram</a>
    <a href="https://facebook.com/TON-LIEN" target="_blank">Facebook</a>
    <a href="https://pinterest.com/TON-LIEN" target="_blank">Pinterest</a>
    <a href="mailto:businessman.h4@gmail.com" target="_blank">Email</a>
  </section>

  <div class="footer">
    <p>© 2025 Nexovate. Tous droits réservés.</p>
  </div>

</body>
</html>

<!-- formulaire.html --><!DOCTYPE html><html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Formulaire de réparation | Nexovate</title>
  <style>
    body {
      background: #0e1c2f;
      color: white;
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    form {
      background: rgba(255, 255, 255, 0.05);
      padding: 2rem;
      border-radius: 10px;
      backdrop-filter: blur(10px);
      box-shadow: 0 0 20px rgba(0,0,0,0.3);
      width: 90%;
      max-width: 500px;
    }
    h2 {
      color: #4da8f0;
      text-align: center;
      margin-bottom: 1.5rem;
    }
    label {
      display: block;
      margin-bottom: 0.5rem;
      margin-top: 1rem;
    }
    input, textarea {
      width: 100%;
      padding: 0.8rem;
      border: none;
      border-radius: 5px;
      margin-top: 0.3rem;
    }
    button {
      margin-top: 1.5rem;
      background: #4da8f0;
      border: none;
      padding: 1rem;
      color: white;
      width: 100%;
      border-radius: 5px;
      font-size: 1rem;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <form id="repairForm">
    <h2>Demande de réparation</h2>
    <label for="type">Type d'appareil</label>
    <input type="text" id="type" placeholder="Ex: Smartphone, Laptop..." required /><label for="modele">Modèle</label>
<input type="text" id="modele" placeholder="Ex: iPhone 13, Dell XPS..." required />

<label for="temps">Temps de fonctionnement</label>
<input type="text" id="temps" placeholder="Ex: 2 ans, 6 mois..." required />

<label for="heure">Heure souhaitée pour l’intervention</label>
<input type="time" id="heure" required />

<label for="details">Détails supplémentaires</label>
<textarea id="details" rows="4" placeholder="Explique ton problème ici..." required></textarea>

<button type="button" onclick="envoyerWhatsApp()">Envoyer sur WhatsApp</button>

  </form>  <script>
    function envoyerWhatsApp() {
      const type = document.getElementById('type').value;
      const modele = document.getElementById('modele').value;
      const temps = document.getElementById('temps').value;
      const heure = document.getElementById('heure').value;
      const details = document.getElementById('details').value;

      const message = `Demande de réparation :\n\nType: ${type}\nModèle: ${modele}\nTemps de fonctionnement: ${temps}\nHeure souhaitée: ${heure}\nDétails: ${details}`;

      const numero = '50912345678'; // ← Remplace par TON numéro WhatsApp sans + ni espace
      const lien = `https://wa.me/${numero}?text=${encodeURIComponent(message)}`;
      window.open(lien, '_blank');
    }
  </script></body>
</html>
