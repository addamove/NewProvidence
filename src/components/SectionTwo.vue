<template>
  <section id="SectionTwo">



        <img src="../assets/images/iphone-feature.png" class="phone responsive-img wow fadeInLeft data-wow-delay='1s' " alt="phone">






    <div class="row">
      <div class="col l6 m12 s12 offset-l6 ">
        <div class="container wow fadeInUp">
          <h1 class="header">Your day<br> is protected</h1>
          <p class="paragraph">There have not been any since we have lived here, said my mother. </p>
          <p class="paragraph">We thought - Mr. Copperfield thought - it was quite a large rookery; but the nests were very old ones, and the birds have deserted them a long while.</p>
          <div class="rowb">
            <a href="#" class="btn btn-first ">Try to hack us</a>
            <a href="#" class="btn btn-watch">Learn more</a>
          </div>
        </div>
      </div>
    </div>




  </section>
</template>
<script>
export default {
  name: "SectionTwo",
  data: () => ({

  })
}
</script>
<style lang="sass" scoped>


#SectionTwo
  padding-top: 100px



.header
  font-family: 'Varela Round', sans-serif
  line-height: 52px
  font-size: 52px
  color: #26272d
  text-align: left
  margin-bottom: 64px

.paragraph
  text-align: left
  font-size: 18px
  line-height: 28px
  color: #8c8f94
.btn-watch
  border: 1px solid rgba(38, 39, 45, 0.1)
  text-transform: none
  box-shadow: none
  background-color: #ffffff
  color: #26272d
  border-radius: 30px
  padding: 1px 20px
  height: 40px
  position: absolute
  left: 50%
  &:hover
    background-color: #ffffff !important

.btn-first
  box-shadow: none
  white-space: nowrap
  font-family: Lato
  background-color: #267df4
  color: white
  border: 1px solid rgba(38, 39, 45, 0.1)
  border-radius: 30px
  font-family: lato, sans-serif
  font-size: 16px
  font-weight: 400
  text-decoration: none
  text-transform: none
  padding-right: 20px
  padding-left: 15px
  padding-bottom: 10px
  position: absolute
  left: 0px
  height: 40px
  width: 200px

  &::after
    content: ' \f061'
    font-family: fontawesome
    padding-left: 20px
  &:hover
    opacity: 0.9 !important
    transition: all 0.5s !important

    background-color: #267df4 !important

.phone
  display: block
  position: absolute
  left: -25%
  margin-top: -75px



.rowb
  margin-top: 75px
  position: relative



@media screen and ( max-width: 1200px )
  .btn-first
    position: absolute
    left: 0
  .btn-watch
    left: 63%
    position: absolute
  .phone
    left: -35%

@media screen and ( max-width: 992px )
  .btn-first
    position: absolute
    left: 0
  .btn-watch
    left: 30%
    position: absolute
  .phone
    position: relative
    left: 0
    margin-top: 10px
    width: 100%

@media screen and ( max-width: 830px )
  .btn-watch
    left: 60%
    position: absolute
  #SectionTwo
    padding-top: 0px

@media screen and ( max-width: 530px )
  .btn-first
    width: 170px


</style>
