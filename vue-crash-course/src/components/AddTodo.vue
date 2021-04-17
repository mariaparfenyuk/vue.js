<template>
  <form @submit.prevent="onSubmit">
    <input type="text">
    <button type="submit">Create</button>
  </form>
</template>

<script> 
export default {
  data(){
  //  return 
  // https://www.youtube.com/watch?v=OlnwgS-gk8Y 28:18
  },
  methods: {
    onSubmit() {
      console.log("Submit");
    }
  }
}

</script>

<style scoped>
  form {
    display: flex;
  }
  input {
    width: 400px;
  }
</style>