<template>
<header>
    <div class="logo">
    <img :src= "require('@/assets/icons/horns-sign.png')"/>
    <h2>KISHORE BODDITE</h2>
    </div>
    <nav class="mobile">
        <ul>
            <li><a href="#">PROJECTS</a></li>
            <li><a href="#">ABOUT</a></li>
            <li><a href="#">BLOG</a></li>
            <li><a href="#">SAY HI</a></li>
        </ul>
    </nav>
    <div class="hamburger"></div>
</header>



</template>

<script>
export default {
    name:'Navbar',
    data(){
        return{
       
        }
    }
}
</script>

<style scoped>

header {
	
	display: flex;
	align-items: center;
    justify-content:space-evenly;
    background-image: linear-gradient(to top, #fff1eb 0%, #ace0f9);
    position: fixed;
    opacity: 0;
    top: 0;
    width: 100%;
    filter:blur(-6px) ;
}
img{
    height: 60px;
    width: 60px;
}
a{
    text-decoration: none;
    color: black;
    font-size:18px;
}
li{
    list-style: none;
    margin-left: 60px;
}
ul,.logo{
    display: flex;
    flex-direction: row;
}

 

</style> 
