<template>
  <div>
    <Header />
    <div class="app-container">
    <SideMenu />
    <Main />
    </div>
  </div>
</template>

<script>
import 'normalize.css';
import Header from './components/Header';
import SideMenu from './components/SideMenu';
import Main from './components/Main';

export default {
  components:{
    Header,
    SideMenu,
    Main
  }
}
</script>

<style scoped>
.app-container {
  display: flex;
  padding-top: 80px;
}
</style>
