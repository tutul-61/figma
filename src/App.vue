<template>
  <div id="app">
    <TopUp/><br>
    <NavBar/><br>
    <HomeItem/><br>
    <AboutItem/><br>
    <FootItem/>
  </div>
</template>

<script>
import  TopUp from './components/TopUp'
import  NavBar from './components/NavBar'
import  HomeItem from './components/HomeItem'
import AboutItem from './components/AboutItem'
import FootItem from './components/FootItem'

export default {
  name: 'App',
  components: {
    TopUp,
    NavBar,
    HomeItem,
    AboutItem,
    FootItem
  }
}
</script>

<style>

</style>
