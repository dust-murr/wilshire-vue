<template>
 <section class="head">
   <div class="container">
    <div class="row">
      <video src="../assets/video/world.mp4" muted loop autoplay></video>
    <div class="overlay"></div>
      <div class="text">
        <h2 class="animate__animated animate__backInLeft">Invest Now </h2> 
        <h3 class="animate__animated animate__backInLeft animate__delay-1s">In Your Future</h3>
        <p class= "animate__animated animate__backInLeft animate__delay-2s">We provide a holistic service that brings together market-leading indexes, robust financial analytics and end-to-end investment services and solutions for institutional investors, financial advisors and intermediaries.</p>
        <a href="#team" class="animate__animated animate__backInLeft animate__delay-2s"><b>Explore</b></a>
      </div>
    <ul class="social">
      <li><a href="#"><img src="https://i.ibb.co/Wnxq2Nq/twitter.png"></a></li>
      <li><a href="#"><img src="https://i.ibb.co/x7P24fL/facebook.png"></a></li>
      <li><a href="#"><img src="https://i.ibb.co/ySwtH4B/instagram.png"></a></li>
    </ul>
    </div>
  </div>
  </section>
</template>


<style>
*
{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}
.head
{
  position: relative;
  right: 0;
  width: 100%;
  min-height: 100vh;
  padding: 100px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #111;
  transition: 0.5s;
  z-index: 2;
}
.head.active
{
  right: 300px;
}

.head video
{
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  opacity: 0.8;
}
.overlay
{
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: #03a9f4;
  mix-blend-mode: overlay;
}
.text
{
  position: relative;
  z-index: 10;
}

.text h2
{
  font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-size: 90px;
  font-weight: 800;
  color: rgb(209, 74, 148);
  line-height: 1em;
  text-transform: uppercase;
  text-align: left;
}
.text h3
{
  font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  font-size: 50px;
  font-weight: 700;
  color: #19ee60;
  line-height: 1em;
  text-transform: uppercase;
  text-align: left;
}
.text p
{
  font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; 
  font-size: 18px;
  color: #fff;
  margin: 20px 0;
  font-weight: 400;
  max-width: 700px;
  text-align: left;
  padding-right: 175px;
}
.text a
{
  display: inline-block;
  border-radius: 20px;
  margin-right: 200px;
  font-size: 20px;
  background: #19ee60;
  padding: 10px;
  text-transform: uppercase;
  text-decoration: none;
  font-weight: 500;

  color: #111;
  letter-spacing: 2px;
  transition: 0.2s;
}
.text a:hover
{
  letter-spacing: 3px;
  text-decoration: none;
}
.social
{
  position: absolute;
  z-index: 10;
  bottom: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.social li
{
  list-style: none;
}
.social li a
{
  display: inline-block;
  margin-right: 20px;
  filter: invert(1);
  transform: scale(0.5);
  transition: 0.5s;
}
.social li a:hover
{
  transform: scale(0.5) translateY(-15px);
}
</style>