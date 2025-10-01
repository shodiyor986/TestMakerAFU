<!DOCTYPE html>
<html lang="uz">
<head>
  <meta charset="UTF-8">
  <title>Bosh sahifa - Test sayt</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)),
                  url('https://images.unsplash.com/photo-1501785888041-af3ef285b470?ixlib=rb-4.0.3&auto=format&fit=crop&w=1600&q=80') no-repeat center center fixed;
      background-size: cover;
      color: white;
    }

    header {
      background: rgba(0, 0, 0, 0.6);
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #ffd700; /* oltin rang */
    }

    header h1 {
      margin: 0;
      font-size: 36px;
      color: #00ffcc;
      text-shadow: 2px 2px 4px black;
    }

    header p {
      margin: 5px 0 0;
      font-size: 18px;
      color: #ffd700;
    }

    nav {
      background: rgba(255, 255, 255, 0.2);
      padding: 15px;
      text-align: center;
      backdrop-filter: blur(6px);
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover {
      color: #ffd700;
      text-shadow: 1px 1px 5px #000;
    }

    .content {
      max-width: 800px;
      margin: 50px auto;
      background: rgba(255, 255, 255, 0.1);
      padding: 30px;
      border-radius: 15px;
      backdrop-filter: blur(8px);
      box-shadow: 0 0 15px rgba(0,0,0,0.6);
    }

    .content h2 {
      color: #00ffcc;
      text-align: center;
    }

    .content p {
      line-height: 1.6;
      font-size: 18px;
      color: #f1f1f1;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: rgba(0, 0, 0, 0.7);
      border-top: 2px solid #ffd700;
      margin-top: 50px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Test Sayt</h1>
    <p>Uzbekona zamonaviy dizayn</p>
  </header>

  <nav>
    <a href="index.html">Bosh sahifa</a>
    <a href="page2.html">2-sahifa</a>
    <a href="page3.html">3-sahifa</a>
  </nav>

  <div class="content">
    <h2>Bosh sahifa</h2>
    <p>
      Bu test qilish uchun mo‘ljallangan saytning bosh sahifasi. 
      Bu sahifada zamonaviy, shafof panel va rang-barang dizayn ishlatilgan. 
      O‘zbekona ohangda yashil, ko‘k va oltin ranglar uyg‘unligi saytingizga chiroy beradi.
    </p>
  </div>

  <footer>
    © 2025 TestMakerAFU. Barcha huquqlar himoyalangan.
  </footer>
</body>
</html>
