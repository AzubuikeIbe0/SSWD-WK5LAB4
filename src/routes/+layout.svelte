<div class="header">
  <div class="top">
    <div class="menuIcon">
      <i class='bx bx-menu'></i>
      <i class='bx bx-search'></i>
    </div>
    <div class="topMenu">
      <ul id="topMenu" class="topMenu">
        <li><a id="Biafra" href="/" data-sveltekit-prefetch>Biafra</a></li>
        <li><a id="International" href="/headlines" data-sveltekit-prefetch>International</a></li>
        <li><a id="Canada" href="/business" data-sveltekit-prefetch>Canada</a></li>
        <li><a id="Espanol" href="/sport" data-sveltekit-prefetch>Espanol</a></li>
        <li><a id="中文" href="/sport" data-sveltekit-prefetch>中文</a></li>
      </ul>
    </div>
    <div class="login">
      <button class="subscribe">Subscribe for €0.50/week</button>
      <button class="login">log in</button>
    </div>
  </div>
  <div class="midLogo">
    <div class="date">
      <h6>Sunday, November 27, 2022</h6>
      <small>Today's Paper</small>
    </div>
    <div class="logo">
      <img src="./assets/img/btimes.png" alt="Irish Times Logo">
    </div>
    <div class="weather">
     <div class="weather_details">
      <i class='bx bxs-sun'></i>
      <h4>9°C</h4>
      <small>11° 5°</small>
     </div>
     <div class="market">
      Nasdaq -0.52% <i class='bx bx-down-arrow-alt'></i>
    </div>
    </div>
  </div>
  <nav class="menu"> <!-- Navigation menu with news sections - see CSS for layout-->
 <!-- Each has a data-source attribute which contains the URI to be requested-->
    <ul id="newsLinks" class="topnav">
      <li><a id="Headlines" href="/" data-sveltekit-prefetch>World</a></li>
      <li><a id="Headlines" href="/headlines" data-sveltekit-prefetch>Biafra</a></li>
      <li><a id="Business" href="/business" data-sveltekit-prefetch>Politics</a></li>
      <li><a id="Sport" href="/sport" data-sveltekit-prefetch>Owerri</a></li>
      <li><a href="#">Business</a></li>
      <li><a href="#">Opinion</a></li>
      <li><a href="#">Science</a></li>
      <li><a href="#">Health</a></li>
      <li><a href="#">Sports</a></li>
      <li><a href="#">Arts</a></li>
      <li><a href="#">Books</a></li>
      <li><a href="#">Style</a></li>
      <li><a href="#">Food</a></li>
      <li><a href="#">Travel</a></li>
      <li><a href="#">Magazine</a></li>
      <li><a href="#">Cooking</a></li>
      <li><a href="#">Bight</a></li>
      <li><a href="#">Wirecutter</a></li>
      <li><a href="#">Games</a></li>
    </ul>
    </nav>
    <hr>
</div>


<slot />
