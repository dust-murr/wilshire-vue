<template>
    <footer>
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <span class="copyright">Copyright &copy; Dustin Murry 2022</span>
          </div>
          <div class="col-md-4">
            <ul class="list-inline social-buttons">
              <li class="list-inline-item">
                <a href="#">
                  <i class="fab fa-twitter"></i>
                </a>
              </li>
              <li class="list-inline-item">
                <a href="#">
                  <i class="fab fa-facebook-f"></i>
                </a>
              </li>
              <li class="list-inline-item">
                <a href="#">
                  <i class="fab fa-linkedin-in"></i>
                </a>
              </li>
            </ul>
          </div>
          <div class="col-md-4">
            <ul class="list-inline quicklinks">
              <li class="list-inline-item">
                <a href="#">Privacy Policy</a>
              </li>
              <li class="list-inline-item">
                <a href="#">Terms of Use</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </footer>
</template>

<style lang="css">
  footer{
    padding:25px 0;
    text-align:center;
    }
  footer span.copyright{
    font-size:90%;
    line-height:40px;
    text-transform:none;
    font-family:Montserrat,-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,'Helvetica Neue',Arial,sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbol','Noto Color Emoji';
    }
  footer ul.quicklinks{
    font-size:90%;
    line-height:40px;
    margin-bottom:0;
    text-transform:none;
    font-family:Montserrat,-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,'Helvetica Neue',Arial,sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbol','Noto Color Emoji';
    }
  ul.social-buttons{
    margin-bottom:0;
    }
  ul.social-buttons li a{
    font-size:20px;
    line-height:50px;
    display:block;
    width:50px;
    height:50px;
    -webkit-transition:all .3s;
    transition:all .3s;
    color:#fff;
    border-radius:100%;
    outline:0;
    background-color:#212529;
    }
  ul.social-buttons li a:active,ul.social-buttons li a:focus,ul.social-buttons li a:hover{
    background-color:#19ee60;
    }
</style>