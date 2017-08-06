<template>

  <header class="MyHeader" @scroll="handleScroll">

       <ul id="slide-out" class="side-nav">
            <li>
              <div class="logo">
                <img src="../assets/images/logo-white.png" alt="logo">
              </div>
            </li>
            <li>Tour</li>
            <li>Features</li>
            <li>Pricing</li>
            <li><span>Help</span></li>
            <li>Contacts</li>

            <a class="waves-effect waves-light btn sidebtn">Get App</a>
            <div class="sidefooter">


            <ul class="sidenavul">
              <li><i class="fa fa-twitter"></i></li>
              <li><i class="fa fa-facebook"></i></li>
              <li><i class="fa fa-pinterest"></i></li>
              <li><i class="fa fa-google-plus"></i></li>
              <li><i class="fa fa-linkedin"></i></li>
            </ul>
            </div>
            </ul>


      <div  class="TopLine" v-bind:class="[{ styleObjectScrolled: scrolled, styleObject: notscrolled}]">
        <div class="container">

        <a href="#" data-activates="slide-out" class="button-collapse hide-on-med-only"> <i class="fa fa-bars fac"></i></a>


        <div class="row ">

           <div class="col l4 hide-on-med-and-down">

                <ul class="left-nav">
                  <li>Tour</li>
                  <li>Features</li>
                  <li>Pricing</li>
                </ul>
              </div>


            <div class="col l4 m4 offset-m4 s4 offset-s4">
              <div class="logo">
                <img src="../assets/images/logo.png" alt="logo">
              </div>
            </div>


         <div class="col l4 hide-on-med-and-down">
             <ul class="right-nav">
                  <li><span>Help</span></li>
                  <li>Contacts</li>
              </ul>
              <a class="waves-effect waves-light btn mybtn">Get App</a>
            </div>
        </div>

    </div>
</div>

        <div class="flex-container ">

            <div class="box ">
              <h1 class="wellcome-h1 center-align wow fadeInUp animated">What happens tomorrow?</h1>
              <p class="wellcome-p center-align wow fadeInUp animated">The sight of the tumblers restored Bob Sawyer to a degree of equanimity which he had not possessed since his interview with his landlady. His face brightened up, and he began to feel quite convivial.</p>
              <div class="">
                <a href="#" class="watch btn wow fadeInUp   ">Watch Video</a>
              </div>
          </div>


                  </div>



        <div class="box ">
          <img src="../assets/images/header_iphone.png" alt="logo" class="phone ">
        </div>


  </header>
</template>

<script>
import Vue from 'vue'
Vue.use(require('vue-touch'))


export default {
  name: 'MyHeader',
  data () {
    return {
      opened:true,
      scrolled: false,
      notscrolled: true
    }
  },
  methods: {
handleScroll () {
  this.scrolled = window.scrollY > 0;
  this.notscrolled = !this.scrolled;
}
  },
  created () {
  window.addEventListener('scroll', this.handleScroll);
  },
  destroyed () {
  window.removeEventListener('scroll', this.handleScroll);
},

}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="sass">

html, body
	height: 100%

#app > header > div.flex-container > div > p
  width: 70%
  margin-left: 15%

.flex-container

  height: 100%
  margin: 0
  display: -webkit-box
  display: -moz-box
  display: -ms-flexbox
  display: -webkit-flex
  display: flex
  align-items: center
  justify-content: center
  overflow: hidden
  position: relative



.container
  width: 90%


.styleObjectScrolled
  background-color: #ffffff
  box-shadow: 0 10px 20px rgba(0,0,0,0.19)
    position: absolute
    top: 60px
    left: 3%
  transition: all  0.5s
  padding-top: 30px !important
  z-index: 100
.styleObject
  background-color: transparent
  // h-length, v-length, blur, spread, colour
  box-shadow: none
  padding-top: 40px !important
  transition: all  0.5s
  z-index: 99



.box
  width: 75%
  margin-top: 75px

.wellcome-h1
  padding-top: 100px
  font-family: 'Varela Round', sans-serif
  font-size: 62px
  color: #39393F

.wellcome-p
  font-family: 'Lato', sans-serif
  font-size: 20px
  color: #8c8f94



.MyHeader
  background-image: url('../assets/images/banner_background.jpg')
  background-color: #cccccc
  background-size: cover
  background-repeat: no-repeat
  min-height: 100%
  padding-bottom: 28%
  width: 100%
  font-size: 16px
  min-width: 320px
  line-height: 1.5
  overflow-x: hidden
  opacity: 1
  font-family: Lato, sans-serif
  overflow-y: hidden
  position: relative


.left-nav
  text-align: left
  margin-left: 15px

.side-nav
  li
    display: block


//button watch video
.watch

  margin-top: 40px
  color: #26272d
  border: 1px solid rgba(38, 39, 45, 0.1)
  box-shadow: none
  text-transform: none
  line-height: 1.3333333
  font-family: Lato, sans-serif
  border-radius: 30px
  height: 49px
  width: 216px
  background-color: transparent
  padding: 14px
  &::before
    font-family: fontawesome
    content: '\f04b'
    margin-right: 16px
  &:hover
    color: rgba(38, 39, 45, 0.8) !important
    transition: color 0.3s !important



.box
  width


.phone

  overflow-y: hidden
  overflow-x: hidden
  position: absolute

  bottom: -400px
  left: 50%
  margin-left: -185px
  clip: rect(0px 10000px 363px 5px)






//-------------------------------------------
.TopLine
  .fac
    font-size: 16px
    display: block
    position: absolute
    margin-left: -20px
    margin-top: 21px
  position: fixed
  width: 100%
  height: 110px
  font-family: Lato
  padding-top: 40px
  font-size: 16px
  font-weight: 400
  .left-nav
  .right-nav
    position: relative
    left: -30px
    span
      color: rgba(38, 39, 45, 0.4)
      &:hover
        color: #267df4



  .logo
    margin: 16px
    img
      vertical-align: middle
  // h-length, v-length, blur, spread, colour


  a
    color: #26272d
  li
    &:hover
      color: #267df4
      cursor: pointer



//-------------------------------------------


.btn
  &.mybtn
   position: relative
   height: 40px
   top: -50px
   left: 150px
   background-color: #267df4
   border: 1px solid #267df4
   border-radius: 30px
   color: #fff
   padding: 0px 15px


   text-transform: none
   font-family: lato
   box-shadow: none
   &::before
     font-family: fontawesome
     content: '\f179'
     padding-right: 5px

.sidefooter
  margin-top: 10px
  padding: 10px
#slide-out > li:nth-child(1) > div > img
  padding-top: 55px
  padding-bottom: 15px
.side-nav
  background-color: rgb(38, 39, 45)
  color: #fff
  text-align: left


  .sidenavul
    position: absolute
    display: block
    width: 100%
    left: 0
    bottom: 0
    margin-top: 10px
    padding: 10px


    li
      display: inline
      margin: 0 20px
      i
        font-size: 16px


  .sidebtn
    height: 40px
    margin-left: 50px
    margin-top: 30px
    background-color: #267df4
    border: 1px solid #267df4
    border-radius: 25px
    color: #fff
    padding: 0px 15px
    text-transform: none
    font-family: lato
    box-shadow: none

    &::before
      font-family: fontawesome
      content: '\f179'
      padding-right: 5px


  li
    font-size: 16px
    margin-bottom: -15px
    margin-left: 50px






ul
  list-style-type: none



li
  display: inline-block
  margin: 0 15px

@font-face
    font-family: Myriad
    src: url('../assets/fonts/MyriadPro-Regular.otf')





@media screen and (max-width: 1080px)
  .MyHeader
    padding-bottom: 340px
  .TopLine
    padding-top: 5px !important
    height: 80px


@media screen and ( max-width: 992px )
  .container
    width: 90%

@media screen and ( max-width: 720px )
  .TopLine
    padding-top: 5px !important
    height: 70px
  .wellcome-h1
    font-size: 50px

  .fac
    margin-left: 2px !important
  .logo
    margin: 16px -10px !important



</style>
