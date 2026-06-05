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
    color: white;
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
    font-size: 36px;
    letter-spacing: 3px;
    cursor: pointer;
    transition: color 0.5s ease;
    text-decoration: none;
  }

  .intro-text:hover {
    color: white;
  }

  /* CONTENT */
  .content {
    min-height: 100vh;
    padding: 80px 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 60px;
  }

  /* BLOK TEKSTOWY */
  .text-block {
    max-width: 600px;
    width: 100%;
    border: 1px solid white;
    padding: 20px;
    min-height: 150px;
  }

  /* LINKI */
  .links {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
    justify-content: center;
  }

  .link-box {
    border: 3px solid rgb(206, 151, 255);
    padding: 20px 40px;
    text-decoration: none;
    color: white;
    transition: all 0.3s ease;
  }

  .link-box:hover {
    background: rgba(255, 255, 255, 0.5);
    color: black;
  }

  /* FOOTER */
  .footer {
    border-top: 1px solid white;
    padding: 20px;
    text-align: center;
    font-size: 16px;
    opacity: 0.3;
    margin-top: 20px;
  }

</style>
</head>

<body>

<!-- EKRAN STARTOWY -->
<div class="intro">
  <a href="#dalej" class="intro-text">obudź się ponownie</a>
</div>

<!-- ZAWARTOŚĆ -->
<div id="dalej" class="content">

  <div class="text-block">
    <p>
8, 9, 10, 11 raz… chwila, czy znowu mnie cofnie, czy może już jestem dalej.

Ktoś stoi na klatce. 
Nie widzę ale wiem. 

Wstaje, za wolno… za późno.

Drzwi są otwarte, ktoś w nich stoi. Podbiegam by jak najszybciej je zamknąć, zdążyć, przed nim. 

Znowu zbyt wolno, znowu nie mam tyle siły.

Wbiega, przenika przeze mnie, ale wszystko znów się cofa. Aha znowu leżę.

Mogę się ruszyć? Nie? Super, dziękuję. 

Najprościej: Twój mózg już się obudził, ale ciało jeszcze nie.  
Czyli, w jaki sposób działa paraliż senny.

Normalnie, kiedy śpisz (zwłaszcza w fazie REM), Twoje ciało jest praktycznie sparaliżowane. To się nazywa atonia. I wbrew temu, co się wydaje, to jest bardzo potrzebne — dzięki temu nie wykonujesz ruchów ze snu i nie robisz sobie krzywdy.

Problem zaczyna się wtedy, kiedy coś się rozjedzie.  
Budzi się głowa… ale ciało nadal jest „wyłączone”.

Jesteś świadomy, wiesz gdzie jesteś, próbujesz się ruszyć — i nic. Jakby ktoś odciął połączenie. To właśnie moment, w którym mózg nie przechodzi płynnie ze snu do pełnego czuwania.

I to nie dzieje się bez powodu.

Różne rzeczy mogą to wywoływać — problemy ze snem (np. niespokojne nogi), niektóre zaburzenia psychiczne albo nawet leki, szczególnie te na lęk.

Ale mimo wszystko twoja głowa, podświadomość, wyobraźnia — kto w co wierzy — postanawia pisać ci dziwne scenariusze, w których jesteś zmuszony grać.
    </p>
  </div>

  <div class="links">
    <a href="jak-wrócić.html" class="link-box">jak wrócić</a>
    <a href="album-z-wycieczki.html" class="link-box">album z wycieczki</a>
  </div>

  <div class="footer">
    Emilia Ślusarska sXXXXX <br>
    <b>upewnij się że wróciłeś.</b>
  </div>

</div>

</body>
</html>
