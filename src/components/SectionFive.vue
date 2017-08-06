<template>
  <section id="SectionFive">
    <div class="container">
      <div class="row">
        <div class="col m12 s12 l4">
          <h1 class="header">Choose your perfect plan</h1>
          <p class="subtitile">YOU ARE</p>
          <div class="switched">
           <div class="company " v-bind:class="{ actived: isActive }" @click="changed">
             Company
           </div>
           <div class="individual" v-bind:class="{ actived: !isActive }" @click="changed">
             Individual
           </div>
         </div>
          <p class="paragraph">Thus much I thought proper to tell you in relation to yourself, and to the trust I reposed in you.</p>
          <p class="also">Have a bigger team? <a href="#">Let‘s talk</a></p>
        </div>
        <div class="col m12 prices l7 offset-l1 wow fadeInUp">

            <div class="table-price highlighted ">
              <h3>Starter</h3>
              <span>FREE</span>
              <p class="frase">Build your schedule every day</p>
              <ul>

                <li><i class="fa fa-check"></i> Unlimeted events</li>
                <li><i class="fa fa-check"></i> Connect Dropbox & Evernote</li>
              </ul>
              <a href="#" class="btn btnkostul">Get Started</a>
            </div>
            <div class="table-price ">
              <h3>Pro</h3>
              <span>$4.99</span>
              <p class="frase">Make your life better</p>
              <ul>

                <li><i class="fa fa-check"></i> Unlimeted events</li>
                <li><i class="fa fa-check"></i> Connect Dropbox & Evernote</li>
                <li><i class="fa fa-check"></i> Personal Assistant</li>

              </ul>
                <a href="#" class="btn probtn">Make me a pro</a>
            </div>



        </div>
      </div>



    </div>

  </section>
</template>
<script>
export default {
  name: "SectionFive",
  data: () => ({
    isActive: "true"

  }),
  methods: {
    changed() {
      this.isActive = !this.isActive;

    }
  }
}
</script>
<style lang="sass" scoped>
#SectionFive
  font-family: lato, sans-serif
  padding-top: 100px
  padding-bottom: 100px
  background-color: #f4f4f5
  box-sizing: border-box
  overflow: hidden
.frase
  margin-top: 30px
  padding: 0px 40px
  color: #8c8f94
  font-size: 20px
  line-height: 28px
  margin-bottom: 38px
.table-price
  width: 100%
  display: inline-block
  position: relative
  width: 340px
  max-width: 50%
  float: left
  background-color: #ebebed
  padding: 40px 15px 50px
  height: 500px
  .btn
    margin-top: 94px
    text-transform: none
    background-color: #267df4
    border-radius: 30px
    padding: 0px 50px
    width: 210px
    max-width: 100%
    // h-length, v-length, blur, spread, colour
    box-shadow: none
    &.probtn
      background-color: transparent
      border: 1px solid #267df4
      color: #267df4
      margin-top: 78px
    &:hover
      opacity: 0.9
      transition: all 0.5s



  i
    color: #6fc754
  li
    font-size: 16px
    line-height: 24px
    color: #26272d
    margin-bottom: 12px

  h3
    font-size: 32px
    line-height: 38px
    font-weight: 300
  span
    border: 1px solid rgba(38, 39, 45, 0.2)
    font-size: 11px
    font-weight: 700
    text-transform: uppercase
    letter-spacing: 0.1em
    color: #26272d
    padding: 9px 18px
    border-radius: 30px


.highlighted
  margin-top: -27px
  box-shadow: 15px 25px 50px 0px rgba(92, 95, 101, 0.2)
  background-color: #ffffff !important
  padding: 60px 15px 70px
  height: 550px !important
  z-index: 4
.header
  text-align: left
  font-size: 52px
  line-height: 52px
  margin-bottom: 64px
  font-family: VarelaRound, sans-serif
  font-weight: 400
.subtitile
  text-align: left
  line-height: 28px
  font-size: 12px
  letter-spacing: 0.1em
  font-weight: 700
  text-transform: uppercase
.paragraph
  font-size: 18px
  line-height: 28px
  color: #8c8f94
  text-align: left
.also
  text-align: left
  font-size: 14px
  margin-top: 24px
  line-height: 28px
  color: #8c8f94

.container
  width: 85%
.company
  display: inline-block
  position: relative
  width: 130px
  padding: 12px 10px
  text-align: center
  z-index: 2
  cursor: pointer
  font-family: lato, sans-serif
  font-size: 16px
  color: #8c8f94
  transition: all 0.3s cubic-bezier(0.545, 0, 0.05, 1)
  &.actived
    color: #26272d !important
    background-color: #fff !important
    width: 120px !important
    border-radius: 30px
    margin-top: 4px
    height: 40px
    padding-top: 8px
    box-shadow: 2.5px 4.33px 20px 0px rgba(61, 61, 62, 0.059)
    transition: all 0.3s cubic-bezier(0.545, 0, 0.05, 1)

.individual
  position: relative
  width: 130px
  float: left
  padding: 12px 10px
  text-align: center
  z-index: 2
  cursor: pointer
  font-size: 16px
  color: #8c8f94
  display: inline-block
  transition: all 0.3s cubic-bezier(0.545, 0, 0.05, 1)
  &.actived
    color: #26272d !important
    background-color: #fff !important
    width: 120px !important
    border-radius: 30px
    margin-top: 4px
    margin-left: 4px
    height: 40px
    padding-top: 8px
    box-shadow: 2.5px 4.33px 20px 0px rgba(61, 61, 62, 0.059)
    transition: all 0.3s cubic-bezier(0.545, 0, 0.05, 1)
.switched
  margin-bottom: 70px
  border: 1px solid rgba(38, 39, 45, 0.2)
  border-radius: 30px
  width: 262px
  height: 50px


@media screen and ( max-width: 1050px )
  .probtn
    margin-top: 60px !important
  .btnkostul
    margin-top: 75px  !important

@media screen and ( max-width: 995px )
  .prices
    margin: 100px auto !important


@media screen and ( max-width: 820px )
  .prices
    margin: 100px auto !important
@media screen and ( max-width: 620px )
  .table-price
    max-width: 100%
  .container
    width: 95%

  .prices

    margin:  80px 0% !important





</style>
