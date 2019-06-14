<template>
  <div id="app" class="position-relative m-0 bg-gradient">
    <HeaderComponent/>
    <navbar-component/>
    <Introduction/>
    <FirstComponent/>
    <SecondComponent/>
    <GetStartedComponent/>
    <FooterComponent/>

  </div>
</template>

<script>
import NavBarMenu from './components/NavBarMenu.vue'
import IntroductionComponent from './components/IntroductionComponent.vue'
import FirstComponent from './components/FirstComponent.vue'
import SecondComponent from './components/SecondComponent.vue'
import GetStartedComponent from './components/GetStartedComponent.vue'
import HeaderComponent from './components/HeaderComponent.vue'
import FooterComponent from './components/FooterComponent.vue'

export default {
  name: 'app',
  components: {
    'navbar-component': NavBarMenu,
    'Introduction': IntroductionComponent,
    'FirstComponent': FirstComponent,
    'SecondComponent': SecondComponent,
    'GetStartedComponent': GetStartedComponent,
    'HeaderComponent': HeaderComponent,
    'FooterComponent': FooterComponent
  }
}


</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.bg-gradient {
background: linear-gradient(#5f4d93, #e37682);
}

</style>
