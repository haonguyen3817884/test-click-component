<template>
  <div>
    place
    <button @click="onCustomerClicked">place</button>
    <test :test="test" />
  </div>
</template>

<script setup lang="ts">
  
  
  
  
  
  
  import { ref } from "vue";

  import Test from "./components/Test.vue";


  const test = ref("place");

  
  const onCustomerClicked = () => {
    test.value = "place place place place place";
  };
</script>


<style scoped>

</style>