<!DOCTYPE html>
<html>
<head>
  <title>TrainUP</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:Arial, sans-serif;
    }

    body{
      height:100vh;
      display:flex;
      justify-content:center;
      align-items:center;
      background:linear-gradient(
        -45deg,
        #1e3c72,
        #2a5298,
        #00c6ff,
        #0072ff
      );
      background-size:400% 400%;
      animation:gradient 10s ease infinite;
    }

    @keyframes gradient{
      0%{background-position:0% 50%;}
      50%{background-position:100% 50%;}
      100%{background-position:0% 50%;}
    }

    .container{
      text-align:center;
      color:white;
      background:rgba(255,255,255,0.12);
      padding:50px;
      border-radius:25px;
      backdrop-filter:blur(10px);
      box-shadow:0 0 25px rgba(0,0,0,0.3);
    }

    h1{
      font-size:80px;
      letter-spacing:5px;
      margin-bottom:15px;
      text-shadow:0 0 20px rgba(255,255,255,0.8);
    }

    p{
      font-size:22px;
      margin-bottom:35px;
      opacity:0.9;
    }

    .btn{
      display:inline-block;
      text-decoration:none;
      color:white;
      background:#00c6ff;
      padding:15px 40px;
      font-size:22px;
      border-radius:50px;
      transition:0.3s;
      box-shadow:0 0 15px rgba(0,198,255,0.7);
    }

    .btn:hover{
      transform:scale(1.1);
      box-shadow:0 0 30px rgba(0,198,255,1);
    }

    .footer{
      margin-top:25px;
      font-size:14px;
      opacity:0.7;
    }
  </style>
</head>

<body>

  <div class="container">
    <h1>WELCOME</h1>

    <p>Welcome to TrainUP 🚀</p>

    <a href="home.html" class="btn">
      Let's Go
    </a>

    <div class="footer">
      Learn • Create • Grow
    </div>
  </div>

</body>
</html>
