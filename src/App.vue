<template>
 <Hero /> 

</template>

<script>
import Hero from './components/Hero.vue'
export default {
  name: 'App',
  components: {
   Hero
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@600&display=swap');
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Montserrat';
  opacity: 0;
  animation: 1s fadein 0.5s forwards;
}
@keyframes fadein {
	100% {
		opacity: 1;
	}
}
</style>
