<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.2.0/css/all.css" integrity="sha384-hWVjflwFxL6sNzntih27bfxkr27PmbbK/iSvJ+a4+0owXq79v+lsFkW54bOGbiDQ"
    crossorigin="anonymous">
    <style>
    body{
      user-select: none;
      -moz-user-select: none;
      margin: 0;
    }
    *::selection{
      color: tomato;
    }
    .my_info{
      display: inline-block;
    }
    .my_info:hover{
      background-color: rgba(255,255,255,0.7);
      color: rgba(0,0,0,0.9);
      display: inline-block;
    }
    </style>
  <link rel="stylesheet" href="css/main.css">
  <title>Welcome To My Portfolio</title>
</head>

<body id="bg-img">
  <header>
    <div class="menu-btn">
      <div class="btn-line"></div>
      <div class="btn-line"></div>
      <div class="btn-line"></div>
    </div>

    <nav class="menu">
      <div class="menu-branding">
        <div class="portrait"></div>
      </div>
      <ul class="menu-nav">
        <li class="nav-item current">
          <a href="index.html" class="nav-link">
            Home
          </a>
        </li>
        <li class="nav-item">
          <a href="about.html" class="nav-link">
            About Me
          </a>
        </li>
        <li class="nav-item">
          <a href="work.html" class="nav-link">
            My Work
          </a>
        </li>
        <li class="nav-item">
          <a href="contact.html" class="nav-link">
            How To Reach Me
          </a>
        </li>
      </ul>
    </nav>
  </header>

  <main id="home">
    <h1 class="lg-heading name">
      Abdul
      <span class="text-secondary">Saboor</span>
      Hakimi
    </h1>
    <h2 class="sm-heading my_info">
      Web Developer, Competitive Programmer, Algorist & Online Freelancer
    </h2>
    <div class="icons">
      <a href="#!">
        <i class="fab fa-twitter fa-2x"></i>
      </a>
      <a href="#!">
        <i class="fab fa-facebook fa-2x"></i>
      </a>
      <a href="#!">
        <i class="fab fa-linkedin fa-2x"></i>
      </a>
      <a href="#!">
        <i class="fab fa-github fa-2x"></i>
      </a>
    </div>
  </main>

  <script src="js/main.js"></script>
</body>

</html>
