<template>
  <div class="container-message">
    <h1 class="message-text">{{ message }}</h1>
  </div>
</template>

<script>
export default {
  name: 'Message',

  props: {
    message: { type: String, required: true }
  }
}
</script>

<style scoped>
  .container-message {
    background: #f8e6d4;
    border: 2px solid #CC5036;
    border-radius: 4px;
    width: 300px;
    height: 50px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    margin: auto;
  }

  .message-text {
    font-size: 16px;
  }
</style>