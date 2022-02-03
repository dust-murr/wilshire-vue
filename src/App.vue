<template>
  <div id="app">

    <!-- Navigation -->
    <Navigation></Navigation>

    <!-- Header -->
    <Header></Header>

    <!-- Team -->
    <Team></Team>

    <!-- Clients -->
    <Clients></Clients>

    <!-- About -->
    <About></About>

    <!-- Offices -->
    <Offices></Offices>

    <!-- Contact -->
    <Contact></Contact>

    <!-- Footer -->
    <Footer></Footer>
    
  </div>
</template>

<script>

import Navigation from './components/Navigation'
import Header from './components/Header'
import Team from './components/Team'
import Clients from './components/Clients'
import About from './components/About'
import Offices from './components/Offices'
import Contact from './components/Contact'
import Footer from './components/Footer'

export default {
  name: 'app',
  components: {
    Navigation,
    Header,
    Team,
    Clients,
    About,
    Offices,
    Contact,
    Footer,
  },
  
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
section h3.section-subheading{
    font-size:16px;
    font-weight:400;
    font-style:italic;
    margin-bottom:75px;
    text-transform:none;
    font-family:'Droid Serif',-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,'Helvetica Neue',Arial,sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbol','Noto Color Emoji';
}
@media (min-width:768px){
    section{
        padding:150px 0;
    }
}
::-webkit-scrollbar {
  width: 12px;
}
::-webkit-scrollbar-thumb {
  background: linear-gradient(#000, #359c71);
  border-radius: 6px;
}

/* Titles */

.threeD {
  color: black;
  white-space: nowrap;
  position: absolute;
  bottom: 100%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-size: 3em;
  font-family: sans-serif;
  font-weight: bold;
  letter-spacing: 0.1em;
  transition: 0.3s;
  text-shadow: 1px 1px 0 grey, 1px 2px 0 grey, 1px 3px 0 grey, 1px 4px 0 grey,
    1px 5px 0 grey, 1px 6px 0 grey, 1px 7px 0 grey, 1px 8px 0 grey,
    5px 13px 15px black;
}

.threeD:hover {
  transition: 0.3s;
  transform: scale(1.1)translate(-50%, -50%);
  text-shadow: 1px -1px 0 grey, 1px -2px 0 grey, 1px -3px 0 grey,
    1px -4px 0 grey, 1px -5px 0 grey, 1px -6px 0 grey, 1px -7px 0 grey,
    1px -8px 0 grey, 5px -13px 15px black, 5px -13px 25px #808080;
}
</style>
