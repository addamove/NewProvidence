<template>
  <div id="app">
  <MyHeader></MyHeader>
  <SectionOne></SectionOne>
  <SectionTwo></SectionTwo>
  <SectionThree></SectionThree>
  <SectionFour></SectionFour>
  <Carousele></Carousele>
  <SectionFive></SectionFive>
  <FooterSection></FooterSection>

  </div>
</template>

<script>
import MyHeader from './components/MyHeader'
import SectionOne from './components/SectionOne'
import SectionTwo from './components/SectionTwo'
import SectionThree from './components/SectionThree'
import SectionFour from './components/SectionFour'
import Carousele from './components/Carousele'
import SectionFive from './components/SectionFive'
import FooterSection from './components/FooterSection'

export default {
  name: 'app',
  components: {
    MyHeader,
    SectionOne,
    SectionTwo,
    SectionThree,
    SectionFour,
    Carousele,
    SectionFive,
    FooterSection
  }
}
</script>

<style>




h1 {
  font-family: MyWebFont;
}


#app {
  font-family: 'Lato', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;

}
</style>
