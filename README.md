# Portfolio-freeCodeCamp-
(New) Responsive (Personal Portfolio Webpage)

index.html

<nav id="navbar">
  <ul>
    <li><a href="#welcome_section">Welcome section</a></li>
    <li><a href="#projects">Projects</a></li>
  </ul>
</nav>
<div id="welcome-section">
  <h1>Jessile Joyce Bonzo</h1>
</div>
<div id="projects">
  <div class="project-tile"><a href="https://codepen.io/jessilebonzo/details/gOeyXbN">Build a Technical Documentation Project</a></div>
</div>

<footer><a id="profile-link" target="_blank" href="https://www.freecodecamp.org/jessile_bonzo">Profile Page</a></footer>
<link rel="stylesheet" href="styles.css">

styles.css
#navbar {
  position: fixed;
  top: 0;
  display: flex;
}

#navbar ul {
  display: flex;
}

#navbar ul li {
  margin-right: 20px;
}
#welcome-section {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

@media (max-width; 768px) {
  body {
    background-color: brown;
  }
}
#navbar {
  position: fixed;
  top: 0;
  display: flex;
}

#navbar ul {
  display: flex;
}

#navbar ul li {
  margin-right: 20px;
}
#welcome-section {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

@media (max-width; 768px) {
  body {
    background-color: brown;
  }
}
