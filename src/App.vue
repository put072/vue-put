<template>
  <div id="app">
    <h1>Hello PUT</h1>
    <p>Hi {{ text }}</p>
    <label for=""> <input v-model="text" placeholder="Your name"></label>
    <button type="submit">Sumit</button>
    <!-- <p>{{ message }}</p> -->
    <!-- <button v-on:click="reverseMessage">Reverse Message</button> -->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

// export default {
//   name: 'App',
//   components: {
//     HelloWorld
//   }
// }

export default {

  data: function() {
return {
   text: ''
  }
}

//   data: function() {
// return {
//     message: 'Hello Vue.js!'
//   };
// },
//   methods: {
//     reverseMessage: function () {
//       this.message = this.message.split('').reverse().join('')
//     }
//   }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
