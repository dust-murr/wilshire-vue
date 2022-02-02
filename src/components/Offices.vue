<template>
<section id="offices">
    <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="jump">
              <span>O</span>
              <span>F</span>
              <span>F</span>
              <span>I</span>
              <span>C</span>
              <span>E</span>
              <span>S</span>
            </h2>
            <h3 class="section-subheading text-muted">Global & Affiliate Offices</h3>
          </div>
        </div>
    <div class="grid">
            <div class="box">
                <img src="../assets/img/offices/1.jpg" />
                <h2>Santa Monica</h2>
                <p>
                    1299 Ocean Avenue<br>
                    Suite 700<br>
                    Santa Monica, CA 90401                    
                </p>
            </div>
            <div class="box">
                <img src="../assets/img/offices/2.jpg" />
                <h2>New Jersey</h2>
                <p>
                    525 Washington Boulevard<br>
                    Suite 2410<br>
                    Jersey City, NJ 07310
                </p>
            </div>
            <div class="box">
                <img src="../assets/img/offices/3.jpg" />
                <h2>Pittsburgh</h2>
                <p>
                    210 Sixth Avenue<br>
                    Suite 3720<br>
                    Pittsburgh, PA 15222
                </p>
            </div>
            <div class="box">
              <img src="../assets/img/offices/4.jpg" />
                <h2>Chicago</h2>
                <p>
                    222 West Adams Street<br>
                    Suite 1880<br>
                    Chicago, IL 60606
                </p>
            </div>
            <div class="box">
                <img src="../assets/img/offices/5.jpg" />
                <h2>Denver</h2>
                <p>
                   370 Interlocken Boulevard<br>
                   Suite 620<br>
                   Broomfield, CO 80021
                </p>
            </div>
            <div class="box">
               <img src="../assets/img/offices/6.jpg" />
                <h2>Singapore</h2>
                <p>
                    3 Pickering Street<br>
                    02-39, Nankin Row,<br> 
                    China Square Central,<br> 
                    Singapore 048660
                </p>
            </div>
            <div class="box">
                <img src="../assets/img/offices/7.jpg" />
                <h2>London</h2>
                <p>
                    8th Floor<br>
                    20 Farringdon Street<br>
                    London EC4A 4AB<br>
                    United Kingdom
                </p>
            </div>
            <div class="box">
                <img src="../assets/img/offices/8.jpg" />      
                <h2>Wilshire Associates<br>Europe B.V.</h2>
                <p>
                    World Trade Center, 
                    25/F, Tower H<br>
                    Zuidplein 204<br>
                    1077 XV Amsterdam, Netherlands
                </p>
            </div>
            <div class="box">
                <img src="../assets/img/offices/9.jpg" />
                <h2>Wilshire<br>Hong Kong Ltd.</h2>
                <p>
                    37/F Jardine House<br>
                    Suite 3711<br>
                    1 Connaught Place<br>
                    Central, Hong Kong
                </p>
            </div>
            <div class="box">
                <img src="../assets/img/offices/10.jpg" />
                <h2>Suzhou Wilshire<br>Investment Services<br>Co., Ltd.</h2>
                <p>
                    苏州威尔希尔投资咨询有限公司<br>
                    Nison Plaza,<br>
                    205 Suzhou Ave. West,<br>
                    Suite 1902 Suzhou Industrial Park,<br>
                    Suzhou, Jiangsu,<br>
                    China 215021
                </p>
            </div>
        </div>
    </section>
</template>

<style>
    @import url('https://fonts.googleapis.com/css?family=Poppins');
.grid {
    width: 1200px;
    margin: 20px auto;
    columns: 4;
    column-gap: 40px;
}
.grid .box {
    width: 100%;
    margin: 0 0 20px;
    padding: 10px;
    background: #fff;
    overflow: hidden;
    break-inside: avoid;
}

.grid .box img {
    max-width: 100%;
    background-size: cover;
}
.grid .box h2 {
    margin: 10px 0 0;
    padding: 0;
    font-size: 24px;
}
.grid .box p {
    margin: 0;
    padding: 0 0 10px;
    font-size: 16px;
}
@media (max-width: 1200px) {
    .grid {
        columns: 3;
        width: calc(100% - 40px);
        box-sizing: border-box;
        padding: 20px 20px 20px 0;
    }
}
@media (max-width: 768px) {
    .grid {
        columns: 2;
    }
}
@media (max-width: 480px) {
    .grid {
        columns: 1;
    }
}
</style>


