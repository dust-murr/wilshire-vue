<template>
    <header class="nav">
  <a href="" class="logo">Wilshire</a>
  <input class="menu-btn" type="checkbox" id="menu-btn" />
  <label class="menu-icon" for="menu-btn"><span class="navicon"></span></label>
  <ul class="menu">
    <li><a href="#team">Team</a></li>
    <li><a href="#clients">Clients</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#offices">Offices</a></li>
    <li><a href="#contact">Contact Us</a></li>
  </ul>
</header>
</template>

<style> 
 

.logo {
  color: yellow;
  font-family: "Helvetica script";
}

.logo:hover {
  color: #19ee60;
}

.nav {
  background-color: rgba(80, 69, 69, 0.479);
  position: fixed;
  width: 100%;
  z-index: 3;
}
.nav ul {
  margin: 0;
  list-style: none;
  overflow: hidden;
}
.nav li a {
  display: block;
  padding: 20px 20px;
  font-size: 18px;
  color: red;
  text-decoration: none;
}

.nav li a:hover,
.nav .menu-btn:hover {
  color: #19ee60;
}

.nav .logo {
  display: block;
  float: left;
  font-size: 2em;
  padding: 10px 20px;
  text-decoration: none;
}

/* menu */

.nav .menu {
  clear: both;
  max-height: 0;
  transition: max-height .2s ease-out;
}

/* menu icon */

.nav .menu-icon {
  cursor: pointer;
  display: block;
  float: right;
  padding: 28px 20px;
  position: relative;
  user-select: none;
}

.nav .menu-icon .navicon {
  background: #19ee60;
  display: block;
  height: 2px;
  position: relative;
  transition: background .2s ease-out;
  width: 18px;
}

.nav .menu-icon .navicon:before,
.nav .menu-icon .navicon:after {
  background: #19ee60;
  content: '';
  display: block;
  height: 150%;
  position: absolute;
  transition: all .2s ease-out;
  width: 100%;
}

.nav .menu-icon .navicon:before {
  top: 5px;
}

.nav .menu-icon .navicon:after {
  top: -5px;
}

/* menu btn */

.nav .menu-btn {
  display: none;
}

.nav .menu-btn:checked ~ .menu {
  max-height: 500px;
}

.nav .menu-btn:checked ~ .menu-icon .navicon {
  background: transparent;
}

.nav .menu-btn:checked ~ .menu-icon .navicon:before {
  transform: rotate(-45deg);
}

.nav .menu-btn:checked ~ .menu-icon .navicon:after {
  transform: rotate(45deg);
}

.nav .menu-btn:checked ~ .menu-icon:not(.steps) .navicon:before,
.nav .menu-btn:checked ~ .menu-icon:not(.steps) .navicon:after {
  top: 0;
}

@media (min-width: 50em) {
  .nav li {
    float: left;
  }
  .nav li a {
    padding: 20px 30px;
  }
  .nav .menu {
    clear: none;
    float: right;
    max-height: none;
  }
  .nav .menu-icon {
    display: none;
  }
}
</style>