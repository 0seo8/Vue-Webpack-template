<template>
  <button @click="handlerA(), handlerB()">
    Click1
  </button>
</template>

<script>
export default {
  methods: {
    handlerA(){
      console.log('A')
    },
    handlerB(){
      console.log('B')
    }
  }
}
</script>
