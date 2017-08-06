<template>
  <section id="SectionThree">
    <div class="row">
      <div class="col l6 m12 s12">
        <div class="container">
          <h1 class="header">We are almost everywhere</h1>
          <p class="paragraph">Now the races of these two have been for some ages utterly extinct, and besides to discourse any further of them would not be at all to my purpose. </p>
          <p class="paragraph">Thus much I thought proper to tell you in relation to yourself, and to the trust I reposed in you.</p>
          <div class="partners" style="text-align: left">
            PARTNERS
            <div class="partnersImages">
              <img src="../assets/images/dropbox.png" alt="dropbox">
              <img src="../assets/images/evernote.png" alt="evernote">
            </div>
          </div>
        </div>
      </div>
    </div>


    <div class="container  wow fadeInRight">
      <img src="../assets/images/map.png" alt="map" class="responsive-image map">
    </div>





  </section>
</template>
<script>
export default {
  name: "SectionThree",
  data: () => ({

  })
}
</script>
<style lang="sass" scoped>

#SectionThree
  padding-top: 500px
  position: relative
  overflow-x: hidden
  overflow-y: hidden
  margin-bottom: 100px
.header
  text-align: left
  font-size: 52px
  line-height: 52px
  margin-bottom: 64px
  font-family: 'Varela Round', sans-serif
  color: #26272d
.paragraph
  text-align: left
  font-size: 18px
  line-height: 28px
  color: #8c8f94
.partners
  margin-top: 50px
  font-weight: 700
  letter-spacing: 0.1em
  text-transform: uppercase
  font-size: 12px
  font-family: Lato, sans-serif
  color: #26272d
  .partnersImages
    margin-top: 20px
    img
      margin-right: 25px

.map
  position: absolute
  left: 50%
  bottom: 0

@media screen and ( max-width: 600px )
  #SectionThree > div.row > div > div > div > div > img:nth-child(2)
    margin-top: 20px

@media screen and ( max-width: 992px )
  #SectionThree
    padding-top: 300px
  .map
    position: relative
    left: 0
    margin-top: 100px
    width: 100%


</style>
