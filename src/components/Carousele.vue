<template>
  <section id="Carousele">
    <div class="row">
      <div class="col s11 m10  l6 offset-l3 offset-m1 kostul ">
        <carousel :perPage="1" :autoplayLoop="true" :loop="true" :autoplay="true" :autoplayHoverPause="true" :navigationEnabled="true" navigationNextLabel="<i class='fa fa-chevron-right hide-on-med-and-down'></i>" navigationPrevLabel="<i class='fa fa-chevron-left hide-on-med-and-down'></i>" >
              <slide>
                <h1 class="headerc">New Providence is the great UI kit</h1>
                <p class="paragraphc">“Just then her head struck against the roof of the hall: in fact she was now more than nine feet high, and she at once took up the little golden key and hurried off to the garden door.”</p>
                <i class="fa fa-star gold-star"></i>
                <i class="fa fa-star gold-star"></i>
                <i class="fa fa-star gold-star"></i>
                <i class="fa fa-star gold-star"></i>
                <i class="fa fa-star"></i>
                <p class="subtitlec">CAMERON DOWNMAN</p>
              </slide>
              <slide>
                <h1 class="headerc">New Providence is the great UI kit</h1>
                <p class="paragraphc">“Just then her head struck against the roof of the hall: in fact she was now more than nine feet high, and she at once took up the little golden key and hurried off to the garden door.”</p>
                <i class="fa fa-star gold-star"></i>
                <i class="fa fa-star gold-star"></i>
                <i class="fa fa-star gold-star"></i>
                <i class="fa fa-star gold-star"></i>
                <i class="fa fa-star"></i>
                <p class="subtitlec">CAMERON DOWNMAN</p>
              </slide>
              <slide>
                <h1 class="headerc">New Providence is the great UI kit</h1>
                <p class="paragraphc">“Just then her head struck against the roof of the hall: in fact she was now more than nine feet high, and she at once took up the little golden key and hurried off to the garden door.”</p>
                <i class="fa fa-star gold-star"></i>
                <i class="fa fa-star gold-star"></i>
                <i class="fa fa-star gold-star"></i>
                <i class="fa fa-star gold-star"></i>
                <i class="fa fa-star"></i>
                <p class="subtitlec">CAMERON DOWNMAN</p>
              </slide>

        </carousel>

      </div>
    </div>


  </section>
</template>
<script>
import { Carousel, Slide } from 'vue-carousel';


export default {
  name: "Carousele",
  data: () => ({

  }),
  components: {
   Carousel,
   Slide
 }
}
</script>
<style lang="sass" >
#Carousele
  margin-top: 300px
.headerc
  font-size: 32px
  line-height: 38px
  font-weight: 300
  margin-bottom: 46px
  font-family: lato, sans-serif
  text-transform: none
  text-decoration: none
  color: rgb(51, 51, 51)

.fa-star
  font-size: 22px
  color: #8c8f94
  &.gold-star
    color: #f2bc3b

.subtitlec
  margin-top: 56px
  font-size: 12px
  font-weight: 700
  text-transform: uppercase
  letter-spacing: 0.1em
  color: #26272d
.paragraphc
  font-size: 18px
  line-height: 28px
  color: #8c8f94
  font-family: Lato, sans-serif
  font-family: 400
.VueCarousel-dot--active
  opacity: 1 !important
  transform: scale(1.8)
  box-shadow: 10px 12px 30px 0px rgba(92, 95, 101, 0.18)
  transition: all 0.5s
#Carousele > div > div > div > div.VueCarousel-navigation > a.VueCarousel-navigation-button.VueCarousel-navigation-prev > i
  position: relative
  top: -260px
  color: #8c8f94
  font-size: 22px
#Carousele > div > div > div > div.VueCarousel-navigation > a.VueCarousel-navigation-button.VueCarousel-navigation-next > i
  position: relative
  top: -260px
  color: #8c8f94
  font-size: 22px
.VueCarousel-dot-inner
  display: none
.VueCarousel-dot

  position: relative
  top: -490px
  margin: 0 50px
  border-radius: 100%
  opacity: 0.4
  width: 75px
  height: 75px
  background-color: #fff
  background-image: url('../assets/images/user1.jpg')
  background-position: center
  background-size: cover
#Carousele > div > div > div > div.VueCarousel-pagination > div > div:nth-child(1)
 background-image: url('../assets/images/user2.jpg')
#Carousele > div > div > div > div.VueCarousel-pagination > div > div:nth-child(3)
 background-image: url('../assets/images/user3.jpg')


@media screen and ( max-width: 582px )
  .kostul
    margin-left: 27px !important
  .VueCarousel-dot
    margin: -20px 25px !important
    width: 45px
    height: 45px
@media screen and ( max-width: 1100px )
  .VueCarousel-dot
    margin: 0px 40px




</style>
