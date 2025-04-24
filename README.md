<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>OneTap Services</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #000;
      color: #fff;
    }
    header {
      background-color: #111;
      color: #0f0;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background-color: #111;
      padding: 10px;
    }
    nav a {
      color: #0f0;
      text-decoration: none;
    }
    .hero {
      padding: 40px;
      text-align: center;
      background-color: #111;
    }
    .section, .payment, .form-section {
      padding: 30px;
      text-align: center;
    }
    .cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 20px;
    }
    .card {
      background: #1a1a1a;
      border: 1px solid #444;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.4);
      width: 250px;
      padding: 20px;
      transition: 0.3s ease;
    }
    .card:hover {
      transform: translateY(-5px);
      border-color: #0f0;
    }
    .form-section form {
      max-width: 400px;
      margin: auto;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    input, select, textarea {
      padding: 10px;
      border: none;
      border-radius: 5px;
    }
    .form-section button {
      background: #0f0;
      color: black;
      padding: 12px;
      font-weight: bold;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .form-section button:hover {
      background: #0c0;
    }
    .payment p {
      color: #0f0;
      font-size: 18px;
      font-weight: bold;
    }
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #25D366;
      color: white;
      padding: 12px 16px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 0 10px #25D366;
    }
  </style>
</head>
<body>

  <header>
    <h1>OneTap Services</h1>
    <p>Top-up | TikTok Coins | Social Media</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Top-up</a>
    <a href="#">TikTok</a>
    <a href="#">Blue Tick</a>
    <a href="#">Contact</a>
  </nav>

  <div class="hero">
    <h2>Fast & Reliable Digital Services</h2>
    <p>Game Top-up, TikTok Coins, Social Media Boost – All in One Place</p>
  </div>

  <div class="section">
    <h3
