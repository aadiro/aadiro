<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Watch & Earn</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f2f2f2;
      display: flex;
      flex-direction: column;
      height: 100vh;
    }
    header {
      background: #007bff;
      color: white;
      text-align: center;
      padding: 1rem;
      font-size: 1.5rem;
    }
    main {
      flex: 1;
      padding: 1rem;
      text-align: center;
    }
    .feature-button {
      display: block;
      width: 80%;
      margin: 1rem auto;
      padding: 1rem;
      font-size: 1.2rem;
      background: white;
      border: 1px solid #ccc;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    nav {
      background: #fff;
      display: flex;
      justify-content: space-around;
      padding: 0.5rem 0;
      border-top: 1px solid #ccc;
    }
    nav img {
      width: 30px;
      height: 30px;
    }
    footer {
      text-align: center;
      padding: 0.5rem;
      font-size: 0.8rem;
      color: #888;
    }
  </style>
</head>
<body>

  <header>Watch & Earn</header>

  <main>
    <button class="feature-button" onclick="watchAd()">Watch Ad</button>
    <button class="feature-button" onclick="dailyBonus()">Daily Bonus</button>
    <button class="feature-button" onclick="spinWheel()">Spin Wheel</button>
    <button class="feature-button" onclick="referEarn()">Refer & Earn</button>
  </main>

  <nav>
    <img src="https://cdn-icons-png.flaticon.com/512/633/633611.png" alt="Home" />
    <img src="https://cdn-icons-png.flaticon.com/512/709/709496.png" alt="Spin" />
    <img src="https://cdn-icons-png.flaticon.com/512/545/545674.png" alt="Bonus" />
    <img src="https://cdn-icons-png.flaticon.com/512/2989/2989988.png" alt="Refer" />
  </nav>

  <footer>&copy; 2025 Watch & Earn App</footer>

  <script>
    function watchAd() {
      alert("Ad watched! You earned 10 coins.");
    }

    function dailyBonus() {
      alert("Daily bonus claimed: 15 coins!");
    }

    function spinWheel() {
      const amount = Math.floor(Math.random() * 100);
      alert("You won " + amount + " coins from the spin wheel!");
    }

    function referEarn() {
      alert("Referral link copied. Share & earn!");
    }
  </script>
</body>
</html>
