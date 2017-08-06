<template>
  <section id="SectionOne">
    <div class="container">
    <div class="flexbox">
      <div class="flexitem wow fadeInUp">
        <i class="lnr lnr-lock"></i>
        <h4 class="header">Real-time all the time</h4>
        <p class="par">Thus much I thought proper to tell you in relation to yourself, and to the trust I reposed in you. Just then her head struck against the roof of the hall: in fact she was now more than nine feet high, and she at once took up the little golden key and hurried off to the garden door.</p>
      </div>
      <div class="flexitem clock wow fadeInUp">
        <i class="lnr lnr-clock"></i>
        <h4 class="header">Adopt without any obstacles</h4>
        <p class="par parl">This sounded a very good reason, and Alice was quite pleased to know it. 'I never thought of that before!' she said. This I have produced as a scantling of Jack’s great eloquence and the force of his reasoning upon such abstruse matters.</p>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "SectionOne",
  data: () => ({

  })
}
</script>
<style scoped lang="sass" >

#SectionOne
  padding: 120px 0




.lnr
  font-size: 42px
  color: #267df4


.flexbox
  display: flex
  flex-direction: column
.flexitem
  text-align: left
  flex: 1


.header
  padding-top: 30px
  font-size: 26px
  line-height: 34px
  font-weight: 300
  margin-bottom: 25px
  font-weight: 200
  font-family: Lato, sans-serif
  color: 26272d
.container
  width: 85%
.par
  font-size: 18px
  line-height: 28px
  color: #8c8f94

.clock
  padding-left: 150px


@media screen and ( min-width: 992px )
  .flexbox
    flex-direction: row

@media screen and ( max-width: 992px )
  .clock
    padding-top: 100px
    padding-left: 0px


</style>
