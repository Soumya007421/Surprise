<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Funny Code Roast 😂</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #111;
      color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
    }
    button {
      background-color: #ff0055;
      border: none;
      color: white;
      padding: 12px 25px;
      font-size: 18px;
      border-radius: 10px;
      cursor: pointer;
      transition: 0.2s;
    }
    button:hover {
      background-color: #ff3388;
    }
    h1 {
      font-size: 26px;
      margin-bottom: 30px;
    }
  </style>
</head>
<body>
  <h1>Here's Your Special Diwali Gift 💌</h1>
  <button onclick="showRoast()">🔥 Show Me 🔥</button>

  <script>
    const roasts = [
    
      "Congratulations! Tumhe chutiya banaya gaya hai 🎉"
  
    ];

    function showRoast() {
      const randomRoast = roasts[Math.floor(Math.random() * roasts.length)];
      alert(randomRoast);
    }
  </script>
</body>
</html>
