<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<title>NieMówŻeWiesz</title>

<style>
  html {
    scroll-behavior: smooth;
  }

  body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: black;
  }

  /* SEKCJA STARTOWA */
  .intro {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .intro-text {
    color: rgb(156, 8, 8);
    font-size: 18px;
    letter-spacing: 3px;
    cursor: pointer;
    transition: color 0.3s ease;
  }

  .intro-text:hover {
    color: white;
  }

  .content {
    min-height: 100vh;
    padding: 80px 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 60px;
  }

  .text-block {
    max-width: 600px;
    width: 100%;
    border: 1px solid white;
    padding: 20px;
    min-height: 150px;
  }

  .links {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
    justify-content: center;
  }

  .link-box {
    border: 1px solid white;
    padding: 20px 40px;
    text-decoration: none;
    color: white;
    transition: all 0.3s ease;
  }

  .link-box:hover {
    background: white;
    color: black;
  }

  .footer {
  border-top: 1px solid white;
  padding: 20px;
  text-align: center;
  font-size: 12px;
  opacity: 0.6;
  }

</style>
</head>

<body>

<!-- EKRAN STARTOWY -->
<div class="intro">
  <a href="#dalej" class="intro-text">obudź się ponownie</a>
</div>

<!-- ZAWARTOŚĆ -->
 <div id="dalej" class="content"></div>
 <div class="text-block">
    <p>cos tam cos tam dhdhbsdbsd</p>
  </div>
 <div class="footer">
  Emilia Ślusarska sXXXXX • upewnij sie że wróciłeś.
  </div>

 <div class="links">
    <a href="jak-powrócić.html" class="link-box">jak powrócić</a>
    <a href="album-z-wycieczki.html" class="link-box">album z wycieczki</a>
  </div>

</div>

</body>
</html>
