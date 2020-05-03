<template>
  <div>
    <Header />
    <div class="app-container">
    <SideMenu />
    </div>
  </div>
</template>

<script>
import 'normalize.css';
import Header from './components/Header';
import SideMenu from './components/SideMenu';

export default {
  components:{
    Header,
    SideMenu,
  }
}
</script>

<style>
.app-container {
  padding-top: 80px;
}
</style>
