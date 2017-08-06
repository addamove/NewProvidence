<template>
  <div id="FooterSection">
    <div class="row">
      <div class="row">
        <div class="col s12  wow  zoomIn">
          <h2 class="header geth">Subscribe our newsletters</h2>
        </div>
      </div>
      <form class="col l8  offset-l2 m12 s12">
        <div class="row">
          <div class="input-field col l8  offset-l2 m8 offset-m2 s12">
            <input id="email" type="email" class="validate">
            <label for="email" data-error="wrong" data-success="right">Email</label>
            <a href="b" class="btn btngreen hide-on-small-only">Send invite</a>
            <p class="promise">We promise to never spam you.</p>
        </div>
        </div>
      </form>
    </div>


<footer>
  <div class="container">
    <div class="row">
      <div class="col l3 m4">
        <div class="logo">
          <img src="../assets/images/logo.png" alt="logo">
        </div>
        <p class="paragraph">It was some time before he obtained any answer, and the reply, when made, was unpropitious.</p>
        <a href="#"><img src="../assets/images/app-store-download.png" alt="appstore download" class="download"></a>
        <ul class="socials">
          <li><a href="#"><i class="fa fa-twitter"></i></a></li>
          <li><a href="#"><i class="fa fa-facebook"></i></a></li>
          <li><a href="#"><i class="fa fa-google-plus"></i></a></li>
          <li><a href="#"><i class="fa fa-tumblr"></i></a></li>
          <li><a href="#"><i class="fa fa-pinterest-p"></i></a></li>
          <li><a href="#"><i class="fa fa-linkedin"></i></a></li>
        </ul>


        </div>
      <div class="col l2 offset-l3 m4 s6 footer-links">
        <ul>
          <li>LEARN MORE</li>
          <li><a href="#">How it works?</a></li>
          <li><a href="#">Meeting tools</a></li>
          <li><a href="#">Live striming</a></li>
          <li><a href="#">Contat method</a></li>
        </ul>
      </div>
      <div class="col l2 m4 s6 footer-links">
        <ul>
          <li>ABOUT US</li>
          <li><a href="#">About us</a></li>
          <li><a href="#">Features</a></li>
          <li><a href="#">Privacy police</a></li>
          <li><a href="#">Terms & Conditions</a></li>
        </ul>
      </div>
      <div class="col l2 m4 s6 footer-links">
        <ul>
          <li>SUPPORT</li>
          <li><a href="#">F.A.Q.</a></li>
          <li><a href="#">Contact us</a></li>
          <li><a href="#">Live chat</a></li>
          <li><a href="#">Phone call</a></li>
        </ul>
      </div>

    </div>

  </div>





</footer>





  </div>
</template>
<script>
export default {
  name: "FooterSection",
  data: () => ({

  })
}
</script>
<style lang="sass" scoped>

#FooterSection
  padding-top: 100px
  font-family: Lato
  font-size: 16px
.container
  width: 85%
.logo
  text-align: left
  margin-bottom: 30px
footer
  padding-top: 200px
.footer-links
  text-align: left
  a
    color: #8c8f94
    text-decoration: none
    text-decoration-line: none
    text-decoration-style: initial
    text-decoration-color: initial
    line-height: 36px
    &:hover
      color: #26272d
  ul > li:nth-child(1)
    margin-top: -10px
    margin-bottom: 10px
    font-weight: 700
    text-transform: uppercase
    letter-spacing: 0.1em
    color: #26272d
    font-size: 12px
.header
  font-size: 52px
  line-height: 52px
  margin-bottom: 54px
  font-family: 'Varela Round', sans-serif
  color: #3a3d4b
.socials
  display: inline-block
  margin-top: 50px
  float: left
  li
    float: left
    margin-right: 20px
    font-size: 20px
    a
      color: #8c8f94
      &:hover
        color: #26272d
.promise
  font-size: 14px
  margin-top: 10px
  line-height: 28px
  color: #8c8f94
  text-align: center
.paragraph
  font-size: 14px
  line-height: 24px
  color: #8c8f94
  text-align: left
.download
  text-align: left
  margin-top: 10px
  float: left
.btn
  &.btngreen
  position: absolute
  top: 4px
  right: 10px
  box-shadow: none
  background-color: #6fc754
  text-transform: none
  width: 140px
  border-radius: 30px
  &:hover
    opacity: 0.8
    transition: all 0.75s
    background-color: #6fc754 !important
@media screen and ( max-width: 650px )
  .socials
    margin-left: -55%
    padding-top: 50px
    padding-bottom: 50px
    float: none
    li
      margin-right: 30px
@media screen and ( max-width: 992px )
  .footer-links
    margin-left: 50px

</style>
