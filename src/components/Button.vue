<template>
  <div class="button" @click="onClick">{{title}}</div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      default: 'ボタン'
    },
    onClick: {
      type: Function,
      required: true
    }
  }
};
</script>

<style scoped>
.button {
  background-color: red;
  display: inline-block;
  border-radius: 5px;
  cursor: pointer;
  padding: 8px;
  color: #fff;
}

.button:hover {
  background-color: rgb(182, 0, 0);
}

.button:active {
  background-color: rgb(138, 13, 13);
}
</style>