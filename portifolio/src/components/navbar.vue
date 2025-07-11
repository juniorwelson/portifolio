<template>
<header>
  <nav>
    <h2 id="logo">   WelsonJunior</h2>
    <ul id="link">
      <li> <a href="#">Home</a></li>|
      <li> <a href="#sobre">Sobre Mim</a></li>|
      <li> <a href="#skiils">Skiils</a></li>|
      <li> <a href="#projetos">Projetos</a></li>
  </ul>
  

    <img src="../public/img/menulateral.png" alt="" id="menu" @click="AbrirMenu">
  </nav>
</header>


</template>

<script>
export default {
  name: 'navbar',
methods : {
    AbrirMenu() {
      let menu = document.getElementById('menu')
     let navbar= document.getElementById('link')
    menu.addEventListener('click', function () {
      if (navbar.style.display === "flex") {
        navbar.style.display='none'
      } else {
        navbar.style.display="flex"
      }
    } )
      
    }
  },
  mounted() {
    this.AbrirMenu()
  }
}
</script>

<style scoped>

nav{
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color:  rgb(49, 48, 64);
  height: 60px;
  width: 100%;
  position: fixed;
  
}
ul{
  display: flex;
  justify-content: space-around;
  align-items: center;
  gap: 60px;
}
li{
  list-style: none;
}
a{
  text-decoration: none;
  font-size: 1em;
 font-weight: bold;
  color: rgb(235, 223, 223);
  transition: 0.7s;
}
#logo{
  margin-left: 10%;
  color: aqua;
  font-weight: bold;
  font-size: 2em;
 
}
a:hover{
color: aqua;
text-decoration: underline;
}

img{
 position: fixed;
 left:90%;
 display: none
 
}
/*responsivo max 450px*/
@media (max-width:450px) {
  nav{
  display: flex;
  justify-content: flex-start;
  align-items: center;
  background-color:  rgb(49, 48, 64);
  height: 60px;
  width: 100%;
  position: relative;
  
}

  ul{
  display: none;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
  gap:0px;
  position: absolute;
  left: 75%;
  top: 90%;
  gap: 0px;
  background-color:  rgb(49, 48, 64);
  height: 50vh;
  width: 100px;
  padding-right: 10px;
}
#logo{
  margin-left: 10%;
  color: aqua;
  font-weight: bold;
  font-size: 2em;
 
}
a{
  text-decoration: none;
  font-size: 1em;
  font-weight: bold;
  color: rgb(248, 248, 248);
  transition: 0.7s;
}
a:hover{
color: aqua;
text-decoration: underline;
}

img{
 position: absolute;
 left:80%;
 display: inline
 
}
}
 /*responsivo max 600 min 450*/
@media (max-width:600px) and (min-width: 450px){
  nav{
  display: flex;
  justify-content: flex-start;
  align-items: center;
  background-color:  rgb(49, 48, 64);
  height: 60px;
  width: 100%;
  position: relative;
  
}

  ul{
  display: none;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
  padding-left: 5%;
  gap:0px;
  position: absolute;
  left: 80%;
  top: 95%;
  gap: 0px;
  
  height: 50vh;
  width: 70px;
  padding-right: 5%;
}
#logo{
  margin-left: 10%;
  color: aqua;
  font-weight: bold;
  font-size: 2em;
 
}
a{
  text-decoration: none;
  font-size: 18px;
  font-weight: bold;
  color: rgb(248, 248, 248);
  transition: 0.7s;
}
li{
  font-size: 20px;
}
a:hover{
color: aqua;
text-decoration: underline;
}

img{
  position: absolute;
 left:85%;
 display: inline
 
}
}
/*responsivo max 800 min 600*/
@media (max-width:800px) and (min-width: 600px){
  nav{
  display: flex;
  justify-content: flex-start;
  align-items: center;
  background-color:  rgb(49, 48, 64);
  height: 60px;
  width: 100%;
  position: relative;
  
}

  ul{
  display: none;
  flex-direction: column;
  justify-content: space-around;
  align-items: center;
  gap:0px;
  position: absolute;
  left: 80%;
  top: 95%;
  gap: 0px;
  background-color:  rgb(49, 48, 64);
  height: 50vh;
  width: 100px;
  padding-right: 10px;
  padding-left: 10%;
}
#logo{
  margin-left: 10%;
  color: aqua;
  font-weight: bold;
  font-size: 2em;
 
}
a{
  text-decoration: none;
  font-size:20px;
  font-weight: bold;
  color: rgb(248, 248, 248);
  transition: 0.7s;
}
a:hover{
color: aqua;
text-decoration: underline;
}

img{
  position: absolute;
 left:80%;
 display: inline
 
}
}


</style>

