<template>
  <section id="SectionFour">
    <h1 class="header">Beautiful Interface</h1>
    <hr>
    <p class="subtitle">LANDING SCREEN</p>
    <div class="flex-container">
      <img src="../assets/images/interface/img-1.png" alt="main" class="image im1 hoverable">
      <img src="../assets/images/interface/img-2.png" alt="main" class="image im2 hoverable">
      <img src="../assets/images/interface/main-img.png" alt="main" class="image imm ">
      <img src="../assets/images/interface/img-3.png" alt="main" class="image im4 hoverable">
      <img src="../assets/images/interface/img-4.png" alt="main" class="image im5 hoverable">
    </div>


    <div class="logo">
      <span>new</span>providence
    </div>
    <div class="row">
      <div class="col s12">
        <h2 class="header geth">Get it to your smartphone</h2>
      </div>
    </div>
    <div class="row">
      <form class="col l8  offset-l2 m12 s12">
        <div class="row">
          <div class="input-field col l8 offset-l2 m8 offset-m2  s12">
            <input id="email" type="email" class="validate">
            <label for="email" data-error="wrong" data-success="right">Email</label>
            <a href="b" class="btn btngreen hide-on-small-only">Send invite</a>
            <p class="downloadsub">OR DOWNLOAD FROM</p>
        </div>
        </div>
      </form>
    </div>
    <a href="#" class="btn btnblack"><i class="fa fa-apple"></i><span>Download on the<br><b>App Store</b></span></a>

  </section>
</template>
<script>
export default {
  name: "SectionFour",
  data: () => ({

  })
}
</script>
<style lang="sass" scoped>
#SectionFour
  padding-top: 150px
  background-color: #F6F5F9
  position: relative
  overflow: hidden
  padding-bottom: 100px
hr
  width: 50px
  height: 2px
  margin: 30px auto
  background-color: #267df4
  border: 0
.header
  font-size: 52px
  line-height: 52px
  margin-bottom: 64px
  font-family: 'Varela Round', sans-serif
  color: #3a3d4b

  &.geth
    margin-bottom: 48px
.subtitle
  line-height: 28px
  color: #8c8f94
  text-align: center
  font-size: 12px
  letter-spacing: 0.1em
  font-weight: 700
  text-transform: uppercase
  font-family: lato, sans-serif
.downloadsub
  text-align: center
  color: #8c8f94
  font-size: 12px
  font-family: lato, sans-serif
  font-weight: 700
  margin-top: 70px
.flex-container
  display: flex
  width: auto
  flex-wrap: nowrap
  justify-content: center
  height: 800px
  margin-bottom: 100px
.image
  flex: 1
.im1
  margin: 130px 1%  145px 1%
.im2
  margin: 130px 1% 145px 1%
.imm
  margin: 30px
.im4
  margin: 130px 1%  145px 1%

.im5
  margin: 130px 1%  145px 1%

.input-field
  position: relative
.logo
  font-weight: 400
  font-size: 12px
  letter-spacing: 0.1em
  text-transform: uppercase
  color: #8c8f94
  span
    font-weight: bold
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
  &.btnblack
    line-height: 1.3em
    padding-right: 10px

    padding-top: 14px
    position: relative
    right: 1px
    color: #fff
    box-shadow: none
    background-color: #131315
    text-transform: none
    width: 180px
    height: 60px
    border-radius: 30px
    font-size: 12px
    text-align: left
    span
      position: absolute
      top: 15
      right: 20px
    i
      position: absolute
      top: 26px
      font-size: 32px
      left: 20px

    b
      font-size: 22px




  </style>
