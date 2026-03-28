<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Khadija Créations</title>
<style>
  body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f9f9f9; }
  header { background: #4CAF50; color: white; padding: 30px 20px; text-align: center; }
  header h1 { margin: 0; font-size: 2.2em; }
  header p { margin: 5px 0 0 0; font-size: 1.1em; }

  nav { text-align: center; margin: 15px 0; }
  nav a { margin: 0 15px; color: #4CAF50; text-decoration: none; font-weight: bold; }
  nav a:hover { text-decoration: underline; }

  .portfolio { display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; padding: 20px; }
  .item { border: 1px solid #ccc; border-radius: 8px; background: white; padding: 10px; width: 200px; text-align: center; transition: transform 0.2s; }
  .item:hover { transform: scale(1.05); }
  .item img { width: 180px; border-radius: 5px; }
  .item button { margin-top: 10px; background: #4CAF50; color: white; border: none; padding: 8px 12px; border-radius: 5px; cursor: pointer; }
  .item button:hover { background: #45a049; }

  section.contact { padding: 20px; max-width: 500px; margin: 40px auto; background: white; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1); }
  section.contact h2 { text-align: center; color: #4CAF50; }
  section.contact form { display: flex; flex-direction: column; gap: 10px; }
  section.contact input, section.contact textarea { padding: 8px; border: 1px solid #ccc; border-radius: 5px; width: 100%; }
  section.contact button { background: #4CAF50; color: white; border: none; padding: 10px; border-radius: 5px; cursor: pointer; }
  section.contact button:hover { background: #45a049; }

  footer { text-align: center; padding: 15px; background: #f1f1f1; margin-top: 20px; }
</style>
</head>
<body>

<header>
  <h1>Khadija Créations</h1>
  <p>Logos et T-shirts customisés</p>
</header>

<nav>
  <a href="#portfolio">Galerie</a>
  <a href="#contact">Contact</a>
</nav>

<section id="portfolio" class="portfolio">
  <div class="item">
    <img src="logo1.png" alt="Logo 1">
    <p>Logo Créatif 1</p>
    <button onclick="window.location.href='https://www.paypal.com/https://paypal.me/DijaN976/nianekhadijadieng@gmail.com'">Acheter / Télécharger</button>
  </div>
  <div class="item">
    <img src="tshirt1.png" alt="T-shirt 1">
    <p>T-shirt Virtuel 1</p>
    <button onclick="window.location.href='https://www.paypal.com/https://paypal.me/DijaN976/nianekhadijadieng@gmail.com'">Acheter / Télécharger</button>
  </div>
  <!-- Ajoute plus de créations ici -->
</section>

<section id="contact" class="contact">
  <h2>Contactez-moi</h2>
  <form action="mailto:monemail@example.com" method="post" enctype="text/plain">
    <input type="text" name="nom" placeholder="Votre nom" required>
    <input type="email" name="email" placeholder="Votre email" required>
    <textarea name="message" rows="5" placeholder="Votre message" required></textarea>
    <button type="submit">Envoyer</button>
  </form>
</section>

<footer>
  <p>© 2026 Khadija Créations - Tous droits réservés</p>
</footer>

</body>
</html>
