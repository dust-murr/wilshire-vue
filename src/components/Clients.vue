<template>
<section class="pic" id="clients">
        <div class="row">
          <div class="col-lg-12 text-center">
            <div class="threeD">
              Clients
            </div>
          </div>
        </div>
<div id="slider">
  <div class="slides">
    <div class="slider">
      <div class="legend"></div>
      <div class="content1">
        <div class="content-txt">
          <h1>Nationwide</h1>
          <h2>Insurance, investing & retirement.<br>Helping protect families, businesses and futures.</h2>
        </div>
      </div>
      <div class="image">
        <img src="../assets/img/clients/1.jpg">
      </div>
    </div>
    <div class="slider">
      <div class="legend"></div>
      <div class="content1">
        <div class="content-txt">
          <h1>Allianz</h1>
          <h2>Our innovative products give you and your family financial protection and guaranteed retirement income.</h2>
        </div>
      </div>
      <div class="image">
          <img src="../assets/img/clients/2.jpg">
      </div>
    </div>
    <div class="slider">
      <div class="legend"></div>
      <div class="content1">
        <div class="content-txt">
          <h1>Capital Group | <br>American Funds</h1>
          <h2>Since 1931, we've helped millions of investors worldwide pursue their real-life goals.</h2>
        </div>
      </div>
      <div class="image">
          <img src="../assets/img/clients/3.jpg">
      </div>
    </div>
    <div class="slider">
      <div class="legend"></div>
      <div class="content1">
        <div class="content-txt">
          <h1>CalPERS</h1>
          <h2>Obtaining the highest return on our investment portfolio to survive, prosper, and grow in a safe and prudent manner.</h2>
        </div>
      </div>
      <div class="image">
          <img src="../assets/img/clients/4.jpg">
      </div>
    </div>
  </div>
  <div class="switch">
    <ul>
      <li>
        <div class="on"></div>
      </li>
      <li></li>
      <li></li>
      <li></li>
    </ul>
  </div>
</div>
</section>
</template>

<style>

#slider{
  width:100%;
  height:500px;
  position:relative;
  overflow:hidden;
}
@keyframes load{
  from{left:-100%;}
  to{left:0;}
}
.slides{
  width:400%;
  height:100%;
  position:relative;
  -webkit-animation:slide 30s infinite;
  -moz-animation:slide 30s infinite;
  animation:slide 30s infinite;
}
.slider{
  width:25%;
  height:100%;
  float:left;
  position:relative;
  z-index:1;
  overflow:hidden;
}
.slide img{
  width:100%;
  height:100%;
}
.slide img{
  width:100%;
  height:100%;
}
.image{
  width:100%;
  height:100%;
}
.image img{
  width:100%;
  height:auto;
}

/* Legend */
.legend{
  border:500px solid transparent;
  border-left:800px solid rgba(52, 73, 94, .7);
  border-bottom:0;
  position:absolute;
  bottom:0;
}

/* Contents */
.content1{
  width:100%;
  height:100%;
  position:absolute;
  overflow:hidden;
}
.content-txt{
  width:400px;
  height:150px;
  float:left;
  position:relative;
  top:300px;
  -webkit-animation:content-s 7.5s infinite;
  -moz-animation:content-s 7.5s infinite;
  animation:content-s 7.5s infinite;
}
.content-txt h1{
  font-family:Arial;
  text-transform:uppercase;
  font-size:24px;
  color:#fff;
  text-align:left;
  margin-left:30px;
  padding-bottom:10px;
}
.content-txt h2{
  font-family:arial;
  font-weight:normal;
  font-size:14px;
  font-style:italic;
  color:#fff;
  text-align:left;
  margin-left:30px;
}

/* Switch */
.switch{
  width:120px;
  height:10px;
  position:absolute;
  bottom:50px;
  z-index:99;
  left:30px;
}
.switch > ul{
  list-style:none;
}
.switch > ul > li{
  width:10px;
  height:10px;
  border-radius:50%;
  background:#333;
  float:left;
  margin-right:5px;
  cursor:pointer;
}
.switch ul{
  overflow:hidden;
}
.on{
  width:100%;
  height:100%;
  border-radius:50%;
  background:#f39c12;
  position:relative;
  -webkit-animation:on 30s infinite;
  -moz-animation:on 30s infinite;
  animation:on 30s infinite;
}

/* Animation */
@-webkit-keyframes slide{
  0%,100%{
    margin-left:0%;
  }
  21%{
    margin-left:0%;
  }
  25%{
    margin-left:-100%;
  }
  46%{
    margin-left:-100%;
  }
  50%{
    margin-left:-200%;
  }
  71%{
    margin-left:-200%;
  }
  75%{
    margin-left:-300%;
  }
  96%{
    margin-left:-300%;
  }
}
@-moz-keyframes slide{
  0%,100%{
    margin-left:0%;
  }
  21%{
    margin-left:0%;
  }
  25%{
    margin-left:-100%;
  }
  46%{
    margin-left:-100%;
  }
  50%{
    margin-left:-200%;
  }
  71%{
    margin-left:-200%;
  }
  75%{
    margin-left:-300%;
  }
  96%{
    margin-left:-300%;
  }
}
@keyframes slide{
  0%,100%{
    margin-left:0%;
  }
  21%{
    margin-left:0%;
  }
  25%{
    margin-left:-100%;
  }
  46%{
    margin-left:-100%;
  }
  50%{
    margin-left:-200%;
  }
  71%{
    margin-left:-200%;
  }
  75%{
    margin-left:-300%;
  }
  96%{
    margin-left:-300%;
  }
}

@-webkit-keyframes content1-s{
  0%{left:-420px;}
  10%{left:0px;}
  30%{left:0px;}
  40%{left:0px;}
  50%{left:0px;}
  60%{left:0px;}
  70%{left:0;}
  80%{left:-420px;}
  90%{left:-420px;}
  100%{left:-420px;}
}
@-moz-keyframes content1-s{
  0%{left:-420px;}
  10%{left:0px;}
  30%{left:0px;}
  40%{left:0px;}
  50%{left:0px;}
  60%{left:0px;}
  70%{left:0;}
  80%{left:-420px;}
  90%{left:-420px;}
  100%{left:-420px;}
}
@keyframes content1-s{
  0%{left:-420px;}
  10%{left:20px;}
  15%{left:0px;}
  30%{left:0px;}
  40%{left:0px;}
  50%{left:0px;}
  60%{left:0px;}
  70%{left:0;}
  80%{left:-420px;}
  90%{left:-420px;}
  100%{left:-420px;}
}

@-webkit-keyframes on{
  0%,100%{
    margin-left:0%;
  }
  21%{
    margin-left:0%;
  }
  25%{
    margin-left:15px;
  }
  46%{
    margin-left:15px;
  }
  50%{
    margin-left:30px;
  }
  71%{
    margin-left:30px;
  }
  75%{
    margin-left:45px;
  }
  96%{
    margin-left:45px;
  }
}

@-moz-keyframes on{
  0%,100%{
    margin-left:0%;
  }
  21%{
    margin-left:0%;
  }
  25%{
    margin-left:15px;
  }
  46%{
    margin-left:15px;
  }
  50%{
    margin-left:30px;
  }
  71%{
    margin-left:30px;
  }
  75%{
    margin-left:45px;
  }
  96%{
    margin-left:45px;
  }
}

@keyframes on{
  0%,100%{
    margin-left:0%;
  }
  21%{
    margin-left:0%;
  }
  25%{
    margin-left:15px;
  }
  46%{
    margin-left:15px;
  }
  50%{
    margin-left:30px;
  }
  71%{
    margin-left:30px;
  }
  75%{
    margin-left:45px;
  }
  96%{
    margin-left:45px;
  }
}
</style>





