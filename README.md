<!DOCTYPE html>
<html>
<head>
  <title>Welcome Page</title>

  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #1e3c72, #2a5298);
      color: white;
    }

    h1 {
      font-size: 90px;
      margin: 0;
      letter-spacing: 5px;
      animation: glow 2s infinite alternate;
    }

    @keyframes glow {
      from {
        text-shadow: 0 0 10px #fff;
      }
      to {
        text-shadow: 0 0 25px #00ffcc;
      }
    }

    p {
      font-size: 20px;
      margin-top: 10px;
      opacity: 0.8;
    }

    .btn {
      margin-top: 40px;
      padding: 15px 40px;
      font-size: 22px;
      color: white;
      background: #00c6ff;
      border: none;
      border-radius: 50px;
      text-decoration: none;
      transition: 0.3s;
      box-shadow: 0 0 15px rgba(0, 198, 255, 0.6);
    }

    .btn:hover {
      transform: scale(1.1);
      box-shadow: 0 0 30px rgba(0, 198, 255, 1);
    }
  </style>
</head>

<body>

  <h1>WELCOME</h1>
  <p>Start your journey now</p>

  <a href="home.html" class="btn">Let's Go</a>

</body>
</html>
