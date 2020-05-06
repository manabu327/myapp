<template>
  <div class="message">
    <div class="message-date">{{ date }}</div>
    <p class="message-text">{{ body }}</p>
  </div>
</template>

<script>
export default {
  props: {
    body: {
      type: String,
      required: true
    },
    date: {
      type: String,
      required: true
    },
  }
}
</script>

<style scoped>
.message {
  border: 1px solid #000;
  min-height: 80px;
  padding: 10px;
}

.message:hover {
  background-color: #eee;
}

.message-date {
  font-size: 0.8em;
  color: #777;
  text-align: right;
}

.message-text {
  margin: 0;
  margin-top: 5px;
  white-space: pre-line;
  font-size: 1.5em;
}
</style>