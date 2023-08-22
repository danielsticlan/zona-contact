# zona-contact
<!DOCTYPE html>
<html>
<head>
  <title>Formular de Contact</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }
    .contact-form {
      max-width: 400px;
      margin: 0 auto;
    }
    .contact-form label, .contact-form input, .contact-form textarea {
      display: block;
      margin-bottom: 10px;
    }
    .contact-form button {
      background-color: #007bff;
      color: #fff;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="contact-form">
    <h2>Contactează-ne</h2>
    <form action="procesare_formular.php" method="post">
      <label for="nume">Nume:</label>
      <input type="text" id="nume" name="nume" required>
      
      <label for="email">Adresă de E-mail:</label>
      <input type="email" id="email" name="email" required>
      
      <label for="subiect">Subiect:</label>
      <input type="text" id="subiect" name="subiect" required>
      
      <label for="mesaj">Mesaj:</label>
      <textarea id="mesaj" name="mesaj" rows="4" required></textarea>
      
      <button type="submit">Trimite</button>
    </form>
  </div>
</body>
</html>
