
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bubble Icons</title>
  <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      background-color: #f1efee;
      font-family: 'Quicksand', sans-serif;
      margin: 0;
      padding: 30px 10px; /* reduced padding */
      display: flex;
      justify-content: center;
      align-items: center;
      box-sizing: border-box;
      min-height: 100vh;
    }

    .bubble-container {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      max-width: 1000px;
      width: 100%;
    }

    .bubble {
      background: #ffffff;
      border-radius: 50%;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08);
      width: 110px;
      height: 110px;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 10px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .bubble:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
    }

    .icon {
      font-size: 24px;
      margin-bottom: 6px;
    }

    .label {
      font-size: 13px;
      color: #444;
      text-align: center;
    }

    @media (max-width: 500px) {
      .bubble {
        width: 90px;
        height: 90px;
      }

      .icon {
        font-size: 20px;
      }

      .label {
        font-size: 12px;
      }
    }
  </style>
</head>
<body>
  <div class="bubble-container">
    <div class="bubble"><div class="icon">🎨</div><div class="label">Creative Thinker</div></div>
    <div class="bubble"><div class="icon">💬</div><div class="label">Good Communicator</div></div>
    <div class="bubble"><div class="icon">🤝</div><div class="label">Team Player</div></div>
    <div class="bubble"><div class="icon">🧘‍♀️</div><div class="label">Calm & Focused</div></div>
    <div class="bubble"><div class="icon">🌱</div><div class="label">Always Learning</div></div>
  </div>
</body>
</html>
