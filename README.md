# my-website<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rhythm Game</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background-color: #222;
      color: #fff;
    }
    .note {
      width: 50px;
      height: 50px;
      background-color: red;
      position: absolute;
      animation: moveDown 2s linear infinite;
    }
    @keyframes moveDown {
      from { top: 0; }
      to { top: 100%; }
    }
  </style>
</head>
<body>
  <h1>Friday Night Funkin' Inspired Game</h1>
  <div id="game-area" style="position: relative; height: 500px; border: 2px solid white;">
    <div class="note" style="left: 50px;"></div>
  </div>
  <script>
    // Basic game logic can be added here
    console.log("Game initialized!");
  </script>
</body>
</html>
