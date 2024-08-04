<template>
  <HomePage />
</template>

<script>
import HomePage from './components/HomePage.vue'

export default {
  name: 'App',
  components: {
    HomePage,
  }
}
</script>

<style>
*{
  background-color: #1b1919;
}
/*custom scrollbar */

::-webkit-scrollbar {
  width: 12px;
}

::-webkit-scrollbar-track {
  background-color: white;
}

::-webkit-scrollbar-thumb {
  background-color: gray;
  border-radius: 10px;
  border: 3px solid transparent;
  background-clip: content-box;

}

::-webkit-scrollbar-thumb:hover {
  background-color: silver;

}

/* other */
* {
  padding: 0%;
  margin: 0%;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  color: #2c3e50;

}
</style>
