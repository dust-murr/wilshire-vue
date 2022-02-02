<template>
<section id="contact">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
             <h2 class="jump">
              <span>C</span>
              <span>O</span>
              <span>N</span>
              <span>T</span>
              <span>A</span>
              <span>C</span>
              <span>T&nbsp;</span>
              <span>U</span>
              <span>S</span>
              </h2>
            <h3 class="section-subheading text-muted">Whether you want to find out more about our solutions or speak to one of our experts, 
              <br>we're ready to connect you to the right team and answer any of your questions.</h3>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-12">
            <form id="contactForm" name="sentMessage" novalidate="novalidate">
              <div class="row">
                <div class="col-md-6">
                  <div class="form-group">
                    <input class="form-control" id="name" type="text" placeholder="Your Name *" required="required" data-validation-required-message="Please enter your name.">
                    <p class="help-block text-danger"></p>
                  </div>
                  <div class="form-group">
                    <input class="form-control" id="email" type="email" placeholder="Your Email *" required="required" data-validation-required-message="Please enter your email address.">
                    <p class="help-block text-danger"></p>
                  </div>
                  <div class="form-group">
                    <input class="form-control" id="phone" type="tel" placeholder="Your Phone *" required="required" data-validation-required-message="Please enter your phone number.">
                    <p class="help-block text-danger"></p>
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="form-group">
                    <textarea class="form-control" id="message" placeholder="Your Message *" required="required" data-validation-required-message="Please enter a message."></textarea>
                    <p class="help-block text-danger"></p>
                  </div>
                </div>
                <div class="clearfix"></div>
                <div class="col-lg-12 text-center">
                  <div id="success"></div>
                  <button id="sendMessageButton" class="btn btn-primary btn-xl text-uppercase" type="submit">Send Message</button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>
</template>

<style lang="css">
  
  section#contact{
    background-color:#212529;
    background-image:url(../assets/img/contact/1.jpg);
    background-repeat:no-repeat;
    background-position:center;
    }
  section#contact .section-heading{
    color:#fff;
    }
  section#contact .form-group{
    margin-bottom:25px;
    }
  section#contact .form-group input,section#contact .form-group textarea{
    padding:20px;
    }
  section#contact .form-group input.form-control{
    height:auto;
    }
  section#contact .form-group textarea.form-control{
    height:248px;
    }
  section#contact .form-control:focus{
    border-color:#19ee60;
    -webkit-box-shadow:none;
    box-shadow:none;
    }
  section#contact ::-webkit-input-placeholder{
    font-weight:700;
    color:#ced4da;
    font-family:Montserrat,-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,'Helvetica Neue',Arial,sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbol','Noto Color Emoji';
    }
  section#contact :-moz-placeholder{
    font-weight:700;
    color:#ced4da;
    font-family:Montserrat,-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,'Helvetica Neue',Arial,sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbol','Noto Color Emoji';
    }
  section#contact ::-moz-placeholder{
    font-weight:700;
    color:#ced4da;
    font-family:Montserrat,-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,'Helvetica Neue',Arial,sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbol','Noto Color Emoji';
    }
  section#contact :-ms-input-placeholder{
    font-weight:700;
    color:#ced4da;
    font-family:Montserrat,-apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,'Helvetica Neue',Arial,sans-serif,'Apple Color Emoji','Segoe UI Emoji','Segoe UI Symbol','Noto Color Emoji';
    }
  .btn-primary:active,.btn-primary:focus,.btn-primary:hover{
    background-color:#19ee60!important;
    border-color:#19ee60!important;
    color:#fff;
}
</style>