<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy (Belated) Mother's Day!</title>
  <style>
    /* General body styling */
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      font-family: 'Segoe UI', Arial, sans-serif;
      color: #333;
    }

    /* Main heading styling */
    h1 {
      font-size: 3em;
      color: #ff6f61;
      text-shadow: 2px 2px 8px #fff7;
      margin-bottom: 0.5em;
    }

    /* Subheading styling */
    h2 {
      font-size: 1.5em;
      margin-bottom: 1em;
      color: #555;
    }

    /* Heart animation styling */
    .heart {
      font-size: 5em;
      color: #ff6f61;
      animation: beat 1s infinite;
    }

    /* Message styling */
    .message {
      font-size: 1.2em;
      text-align: center;
      margin-top: 1em;
      line-height: 1.5;
    }

    /* Signature styling */
    .signature {
      margin-top: 2em;
      font-size: 1em;
      color: #555;
      font-style: italic;
    }

    /* Apology styling */
    .apology {
      margin-top: 1.5em;
      font-size: 1em;
      color: #ff6f61;
      font-weight: bold;
    }

    /* Heartbeat animation */
    @keyframes beat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }
  </style>
</head>
<body>
  <!-- Main heading -->
  <h1>Happy (Belated) Mother's Day!</h1>

  <!-- Subheading -->
  <h2>To the Best Mom in the World, Deyse Resende Vieira</h2>

  <!-- Animated heart -->
  <div class="heart">❤️</div>

  <!-- Message content -->
  <div class="message">
    Thank you for your love and care for our family.<br>
    I wish you an amazing day filled with happiness and joy.<br>
    Sorry for saying this late, but know that I love you. ❤️
  </div>

  <!-- Signature -->
  <div class="signature">
    — With love, Leandro
  </div>
</body>
</html>
