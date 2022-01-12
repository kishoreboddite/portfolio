<template>
<Navbar />
<div class="hero">
    <img :src="require('@/assets/icons/profile.jpg')"/>
    <p class="small">Hi, I'm Kishore👋</p> 
    <p class="x-large">Building Digital Products</p>
    <p class="txt">I’m a Frontend Web Developer based in Visakhapatnam, India. Even though I went for Electronics and Telecommunications Engineering degree, coding is my passion and my new professional career focus. Developing applications for the web has become my drive.</p>
</div>
</template>

<script>
import Navbar from './Navbar.vue'
export default {
    name: 'Hero',
    components: {
        Navbar
    }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@900&family=Poppins:wght@900&display=swap');

.hero {
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    background-color: #FFD4DB;
    align-items: center;
    text-align: center;
    color: black;
}


img {
    height: 150px;
    width: 150px;
    border: 6px solid lightblue;
    border-radius: 50%;
}
.small{
    font-size: 28px;
}
.x-large{
    font-size:56px;
    margin-top: -25px;
}
.txt{
    font-size: 20px;
    width: 65%;
    margin-top:-40px;
    
}


</style>
