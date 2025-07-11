<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>🎲 Game Lounge 🎲</title>
  <style>
    body {
      background: linear-gradient(135deg, #0b0b0b, #1c1c1c);
      color: #fff;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      padding: 30px;
      line-height: 1.6;
    }

    h1, h2, h3 {
      color: gold;
      text-shadow: 0 0 6px #ff0000aa;
    }

    section {
      background-color: #121212;
      border: 1px solid #333;
      border-radius: 10px;
      padding: 25px;
      margin-bottom: 40px;
      box-shadow: 0 0 10px #0008;
    }

    ul {
      padding-left: 20px;
    }

    li::marker {
      color: #00bfff;
    }

    form {
      margin-top: 15px;
    }

    input, select, button {
      margin: 5px 0;
      padding: 10px;
      font-size: 16px;
      border-radius: 6px;
      border: none;
      width: 100%;
      box-sizing: border-box;
    }

    input::placeholder {
      color: #aaa;
    }

    button {
      background-color: red;
      color: white;
      cursor: pointer;
    }

    button:hover {
      background-color: #cc0000;
    }

    header {
      position: relative;
      text-align: center;
    }

    .logo {
      max-width: 160px;
      margin: 0 auto 20px;
      display: block;
    }

    .social-top {
      position: absolute;
      top: 10px;
      width: 100%;
      display: flex;
      justify-content: space-between;
      padding: 0 20px;
      box-sizing: border-box;
    }

    .social-top a img {
      width: 32px;
      height: 32px;
      transition: transform 0.2s ease;
    }

    .social-top a img:hover {
      transform: scale(1.1);
    }

    .banner {
      width: 100%;
      max-width: 1000px;
      margin: 20px auto;
      display: block;
      border-radius: 8px;
    }

    .social-buttons a {
      display: inline-block;
      margin: 10px 15px 0 0;
      padding: 12px 20px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      color: white;
    }

    .twitter-button {
      background-color: #1DA1F2;
    }

    .twitch-button {
      background-color: #9146FF;
    }
  </style>
</head>
<body>
  <header>
    <div class="social-top">
      <a href="https://x.com/GameLoungeRNG" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/53/X_logo_2023.svg" alt="X logo">
      </a>
      <a href="https://www.twitch.tv/gameloungerng" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/2/26/Twitch_logo.svg" alt="Twitch logo">
      </a>
    </div>

    <img src="https://i.imgur.com/pFsQD1q.png" alt="24/7 Live Games Logo" class="logo">
    <img src="https://i.imgur.com/iYZFd8B.png" alt="Live Games Banner" class="banner">
  </header>

  <section>
    <h2>🎯 Reserve Your Number</h2>
    <p>Pick a number (1–6) for the current live game and enter your Solana wallet address and username. Donations are required to participate. Once all numbers are reserved and entries sent, the game begins. Good luck! Once your reservation is confirmed by the host, you can send your entry to the Game Lounge Pot Wallet: <strong>DZ3CArZt7pAynMkE3ah2i9mpP5iYAo4x4zfm1FGE1rSz</strong></p>
    
    <form action="https://formsubmit.co/gmaeloungerng@gmail.com" method="POST">
      <input type="hidden" name="_captcha" value="false">
      <input type="hidden" name="_next" value="https://gameloungedev.github.io/GameLoungeRNG/">
      <input type="text" name="username" placeholder="Your Username" required>
      <input type="text" name="wallet" placeholder="Your Solana Wallet Address" required>
      <select name="number" required>
        <option value="">Pick a Number</option>
        <option value="1">1</option>
        <option value="2">2</option>
        <option value="3">3</option>
        <option value="4">4</option>
        <option value="5">5</option>
        <option value="6">6</option>
      </select>
      <button type="submit">Reserve Number</button>
    </form>
  </section>

  <section>
    <h2>🧠 About Us</h2>
    <p>Game Lounge is an unpredictable, high-energy livestream games platform built for entertainment, community, and deflationary crypto economics. This isn’t just a game — it’s an experiment in building something real, raw, and rewarding from the ground up.</p>
    <p>We’re not launching with studio lighting and million-dollar sets. We’re starting this in a room, with makeshift props, DIY games, and a big vision. Over time, with the community’s support, we’ll grow this into a full-blown livestreaming production — with custom game setups, studio-grade streaming, and a vibrant ecosystem that gives back.</p>
    <p>Whether you’re watching, playing, or just vibing, you’re part of something we’re building together — from scratch.</p>
  </section>

  <section>
    <h2>🎡 How to Play</h2>
    <ol>
      <li>🌀 Spin the Wheel - The host spins a digital wheel to randomly select the game or host challenge.</li>
      <li>🔢 Reserve Your Number (1–6) - Players reserve numbers and send entry to the community pot. Once all six are taken, confirmed, and paid, the game starts.</li>
      <li>🎮 Game is Played Live - Performed on stream. No edits. No retakes.</li>
      <li>🏆 1st wins 2.5x entry, 2nd wins 1.5x entry, 3rd wins 1x entry - Three unique numbers are picked by gameplay outcome. Prizes are paid as the winners are announced.</li>
    </ol>
  </section>

  <section>
    <h2>🎮 Available Games</h2>
    <h3>🎲 Dice Roll – How It Works</h3>
    <p>Each game starts with a mix of colorful dice, but there's only one that matters — the red die. All the dice go into the cup, are shaken live on stream, and rolled onto the board. We keep rolling until we get three unique numbers from the red die. These become the 1st, 2nd, and 3rd place winners — in the order they appear.</p>

    <h3>🃏 Card Draw – How It Works</h3>
    <p>A standard deck is shown on camera, shuffled three times using an automatic shuffler, and given one clean cut. Cards are drawn one at a time. We only care about Ace through 6. Once we draw three unique numbers from that range, they become the 1st, 2nd, and 3rd place winners.</p>

    <h3>🎁 Mystery Box – How It Works</h3>
    <p>Six mystery boxes are numbered 1 through 6. Three of them contain Bitcoin tokens. A random number generator decides which box is opened next. We continue opening boxes until three Bitcoin boxes are revealed. Those become our 1st, 2nd, and 3rd place winners.</p>

    <p>🔄 New games will be added to the wheel. Once we reach 5 games, we'll rotate weekly. Suggestions welcome. Chaos guaranteed.</p>
  </section>

  <section>
    <h2>💎 Tokenomics</h2>
    <p>Every week, 100% of the show's earnings are used to buy back tokens from the market. At the end of each month, 50% of those tokens are burned — until the target supply of 100,000,000 is reached.</p>
    <p>Once the target is met, weekly buybacks are reduced to 50% of house earnings, and burning stops. The remaining 50% supports the show's treasury.</p>
    <p>The treasury fuels:</p>
    <ul>
      <li>🎥 Production & Streaming Upgrades</li>
      <li>📢 Marketing & Promotions</li>
      <li>🌍 Platform Expansion</li>
      <li>🎉 Weekly Community Jackpot Payouts</li>
    </ul>
  </section>

  <section>
    <h2>📈 Token Utility (Evolving)</h2>
    <ul>
      <li>In-game advantages</li>
      <li>Entry to premium prize pools</li>
      <li>Vote on new games</li>
      <li>Future staking, rewards, and tiers</li>
    </ul>
    <h3>🤝 Community Growth</h3>
    <p>This is built for everyone. As we grow, so do your tokens.</p>
  </section>
</body>
</html>
