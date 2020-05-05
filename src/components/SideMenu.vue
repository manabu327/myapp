<template>
  <aside class="menu">
    <ul class="menu-list">
      <li class="menu-list-title active">全体連絡</li>
      <li class="menu-list-title">雑談</li>
      <li class="menu-list-title">自己紹介</li>
    </ul>
  </aside>
</template>

<script>
export default {

}
</script>

<style scoped>
.menu {
  position: fixed;
  width: 199px;
  height: 100vh;
  background-color: #eee;
  border-right: 1px solid #000;
}

.menu-list {
  margin: 0;
  padding: 0;
  list-style: none;
  text-align: center;
}

.menu-list-title {
  height: 60px;
  line-height: 60px;
  border-bottom: 1px solid #000;
  font-size: 0.8em;
}

.menu-list-title:hover, .active {
  background-color: #555;
  font-size: 1em;
  color: #fff;
  font-weight: bold;
}
</style>