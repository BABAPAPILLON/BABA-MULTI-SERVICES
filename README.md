# BABA-MULTI-SERVICES
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Baba-Multi-Services | Contact</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f8fc;
      color: #333;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 700px;
      margin: 50px auto;
      padding: 30px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }
    h1 {
      text-align: center;
      color: #0056b3;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    label {
      margin-top: 15px;
      font-weight: bold;
    }
    input, textarea {
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      margin-top: 20px;
      padding: 12px;
      background-color: #0056b3;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }
    button:hover {
      background-color: #004494;
    }
    .whatsapp {
      margin-top: 30px;
      text-align: center;
      font-size: 18px;
    }
    .whatsapp a {
      color: #25d366;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Contactez-nous</h1>
    <form action="mailto:babapapillon2003@gmail.com" method="POST" enctype="text/plain">
      <label for="nom">Nom complet :</label>
      <input type="text" id="nom" name="Nom" required>

      <label for="tel">Téléphone :</label>
      <input type="tel" id="tel" name="Téléphone" required>

      <label for="email">Adresse email :</label>
      <input type="email" id="email" name="Email" required>

      <label for="ville">Ville :</label>
      <input type="text" id="ville" name="Ville">

      <label for="message">Message :</label>
      <textarea id="message" name="Message" rows="6" required></textarea>

      <button type="submit">Envoyer</button>
    </form>

    <div class="whatsapp">
      📱 Vous pouvez aussi nous écrire sur WhatsApp :<br>
      <a href="https://wa.me/22658233491" target="_blank">Cliquez ici pour discuter</a>
    </div>
  </div>
</body>
</html>
