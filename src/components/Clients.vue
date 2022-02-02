<template>
<section class="pic" id="clients">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="jump"><br>
              <span>C</span>
              <span>L</span>
              <span>I</span>
              <span>E</span>
              <span>N</span>
              <span>T</span>
              <span>S</span><br><br><br><br><br>
              </h2>
          </div>
        </div>
  <div>
 <ul class="slider">
      <li>
        <div class="content">
          <h2>Nationwide</h2>
          <p>
            The Man From Nationwide Is On Your Side.
          </p>
        </div>
      </li>
      <li>
        <div class="content">
         <h2>Allianz</h2>
          <p>
            You Can Trust Allianz.
          </p>
        </div>
      </li>
      <li>
        <div class="content">
          <h2>Capital Group | American Funds</h2>
          <p>
            Can I?
          </p>
        </div>
      </li>
      <li>
        <div class="content">
          <h2>Wilmington Trust</h2>
          <p>
            The Wilmington Trust Difference.
          </p>
        </div>
      </li>
      <li>
        <div class="content">
          <h2>CalPERS</h2>
          <p>
            Obtaining the highest return on our investment portfolio to survive, prosper, and grow in a safe and prudent manner.
          </p>
        </div>
      </li>
    </ul>
    </div>
  </section>
</template>

<style>
  .pic {
  margin: 0;
  padding-top: 100px;
  font-family: sans-serif;
}
.slider {
  position: relative;
  top: 0;
  left: 0;
  width: 100%;
  height: 70vh;
  background: #ccc;
  margin: 0;
  padding: 0;
}
.slider li {
  list-style: none;
  position: relative;
  width: 20%;
  height: 100%;
  border-right: 1px solid #000;
  float: left;
  box-sizing: border-box;
  transition: 0.5s;
  text-align: center;
  overflow: hidden;
}
.slider li:nth-child(1) {
  background: url(../assets/img/clients/1.jpg);
  background-size: cover;
  background-position: left;
}
.slider li:nth-child(2) {
  background: url(../assets/img/clients/2.jpg);
  background-size: cover;
  background-position: left;
}
.slider li:nth-child(3) {
  background: url(../assets/img/clients/3.jpg);
  background-size: cover;
  background-position: left;
}
.slider li:nth-child(4) {
  background: url(../assets/img/clients/4.jpg);
  background-size: cover;
  background-position: left;
}
.slider li:nth-child(5) {
  background: url(../assets/img/clients/5.jpg);
  background-size: cover;
  background-position: left;
}
.slider:hover li {
  width: 10%;
}
.slider li:hover {
  width: 60%;
}
.slider li .content {
  position: absolute;
  bottom: -100%;
  left: 0;
  width: 100%;
  background: rgba(0, 0, 0, 0.8);
  box-sizing: border-box;
  color: #fff;
  opacity: 0;
}
.slider li:hover .content {
  bottom: 0;
  transition: 0.5s;
  transition-delay: 0.5s;
  opacity: 1;
}


</style>


