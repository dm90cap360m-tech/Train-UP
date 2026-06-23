
<html>
<head>
  <title>Brain Hub</title>

  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500;700;900&display=swap" rel="stylesheet">

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
    }

    body{
      height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;

      background:linear-gradient(
        -45deg,
        #050000,
        #0a0000,
        #140000,
        #220000
      );

      background-size:400% 400%;
      animation:gradient 15s ease infinite;
    }

    @keyframes gradient{
      0%{background-position:0% 50%;}
      50%{background-position:100% 50%;}
      100%{background-position:0% 50%;}
    }

    .container{
      text-align:center;
      color:white;

      background:rgba(25,0,0,0.45);

      padding:60px;
      border-radius:25px;

      border:2px solid #660000;

      backdrop-filter:blur(12px);

      box-shadow:
        0 0 15px #330000,
        0 0 35px rgba(80,0,0,0.5);
    }
  .developer{
    position:fixed;
    bottom:15px;
    left:15px;

    color:#888;
   font-size:14px;
    font-family:'Orbitron', sans-serif;

    letter-spacing:1px;
  }

    h1{
      font-family:'Orbitron', sans-serif;
      font-size:100px;
      font-weight:900;

      letter-spacing:8px;

      color:#990000;

      margin-bottom:20px;

      text-shadow:
        0 0 5px #660000,
        0 0 15px #660000,
        0 0 30px #330000;
    }

    p{
      font-family:'Orbitron', sans-serif;
      font-size:22px;

      color:#cccccc;

      margin-bottom:40px;

      letter-spacing:2px;
    }

    .btn{
      display:inline-block;

      text-decoration:none;

      color:white;

      background:#660000;

      padding:16px 42px;

      border-radius:50px;

      font-size:22px;

      font-family:'Orbitron', sans-serif;

      transition:0.3s;

      box-shadow:0 0 10px #660000;
    }

    .btn:hover{
      transform:scale(1.08);

      background:#880000;

      box-shadow:0 0 20px #880000;
    }

    .footer{
      margin-top:30px;

      color:#888888;

      font-family:'Orbitron', sans-serif;

      letter-spacing:3px;

      font-size:14px;
    }
  </style>
</head>

<body>

  <div class="container">

    <h1>WELCOME</h1>

    <p>ENTER THE WORLD OF PUZZLES, LOGIC & GAMES</p>

    <a href="home.html" class="btn">
      LET'S GO
    </a>

    <div class="footer">
      PLAY • THINK • IMPROVE
    </div>

  </div>
  <div class="developer">
    Developer: Yunish Adhikari
</div>

</body>
</html>
