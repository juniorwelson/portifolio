<template>
    <section id="container">
<div id="texto">

    <div id="linha">
<h1>-Desenvolvedor <span>Front-End</span></h1><div id="barra"></div>
</div>
<div id="icones">
   <a href="https://github.com/juniorwelson" target="_blank"> <img id="git" src="../public/img/icons8-github-30.png" alt="logo github" ></a>
   <a href="https://www.linkedin.com/in/welson-junior-a587b72b8" target="_blank">  <img  id="linkdin" src="../public/img/icons8-linkedin-50.png" alt="logo linkdin"></a>
    <a href="mailto:eujuniorplus@gmail.com?subject=Olá&body=Quero%20falar%20sobre%20seu%20portfólio." target="_blank"> <img id="email" src="../public/img/icons8-nova-mensagem-30.png" alt="logo email"></a>
        <a href="https://wa.me/5575999431903?text=ol%C3%A1%20welson%2C%20vim%20do%20seu%20portifolio.%20Podemos%20marcar%20uma%20entrevista%3F" target="_blank">   <img id="zap" src="../public/img/icons8-whatsapp-50 (1).png" alt="logo zap"></a>

</div> 
<div id="acao">
    <a class="social"  target="_blank" href="https://drive.google.com/file/d/1xJFlSXqRQS0Xyvag4mBNdtbGUJ4CRv60/view?usp=sharing">Download CV</a>
    <a class="social" target="_blank" href="https://wa.me/5575999431903?text=ol%C3%A1%20welson%2C%20vim%20do%20seu%20portifolio.%20Podemos%20marcar%20uma%20entrevista%3F">Marcar uma Entrevista</a>
</div>
</div>


<img src="../public/img/ft de frente com pc.png" alt="" id="logo">

</section>



</template>


<script>
export default {
    name:'apresentacao'
}
</script>

<style scoped>
#container{
    display: flex;
  align-items: center;
  justify-content: center;
  background-color: rgb(49, 48, 64);
  gap: 50px;
  padding-top: 80px; /* adiciona espaço abaixo da navbar */
}
#texto{
    display: flex;
    flex-direction: column;
}
#linha{
    display: flex;
}

#logo{
    border-radius: 30px;
    box-shadow: 10px 10px 15px aqua;
    width: 500px;
    margin-bottom: 10%;
}

h1{
    font-size: 3.5em;
    color: white;
 
}
span{
    color: aqua;
}
#barra{
    background-color:aqua;
    width: 10px;
    height: 60px;
  
    animation:piscar 0.8s linear  infinite 
}

@keyframes piscar {
   from {opacity: 0;}
   to {opacity: 1;}
}

#icones{
   display: flex;
   gap: 50px;
   transform: scale(1.1);
   width: 370px;
   padding-left: 30px;
   border-radius: 10%;
}

#git,#zap,#linkdin,#email{
    height: 50px;
    padding: 10px;
    border-radius: 12px;
    background-color: aqua;
    transition: transform 0.3s ease, background-color 0.3s ease;
}

#git:hover{
    background-color: aqua;
    border-radius:10% ;
   
}
#linkdin:hover{
    background-color: #0061f2;
    border-radius:10% ;
}
#git:hover{
    background-color:#333;
    border-radius:10% ;
}
#email:hover{
    background-color: #cd1837;
    border-radius:10% ;
}

#zap:hover{
    background-color: #00ff37;
    border-radius:10% ;
}

#acao{
    margin-top: 15%;
 
   height: 100px;
   
}

.social{
    color: white;
    background-color: aqua;
    font-size: 2em;
    margin-left: 10px;
    height: 80px;
    padding: 20px;
    border-radius:20px;
    text-decoration: none;
    transition: 0.5s;
    font-weight: bold;
}

.social:hover{
background-color: white;
color: aqua;

}




/*responsivo max 450px*/
@media (max-width:450px){
    #container{
    flex-direction: column;
   gap:30px;
}
#texto{
    display: flex;
    flex-direction: column;margin-left: 20px;
}
#linha{
    display: flex;
}

#logo{
    border-radius: 30px;
    box-shadow: 10px 10px 15px aqua;
    width: 300px;
    margin-bottom: 5%;
}

h1{
    font-size:1.8em;
 
}

#barra{
    background-color:aqua;
    width: 8px;
    height: 30px;
  
    animation:piscar 0.8s linear  infinite 
}

@keyframes piscar {
   from {opacity: 0;}
   to {opacity: 1;}
}

#icones{
   display: flex;
   gap: 20px;
   margin-top: 5%;
  
   width: 250px;
   padding-left: 5px;
   border-radius: 10%;
}
#git,#zap,#linkdin,#email{
    height: 35px;
    transition: 0.7s;
  background-color: aqua;
  border-radius: 10%;
}
.social{
    color: white;
    background-color: aqua;
    font-size: 1em;
    margin-left: 5px;
    height: 80px;
    padding: 20px;
    border-radius:20px;
    text-decoration: none;
    transition: 0.5s;
    font-weight: bold;
}


}



/*responsivo max 600px e min 450px*/
@media (max-width:600px) and (min-width: 450px){
    #container{
    flex-direction: column;
   gap:30px;
}
#texto{
    display: flex;
    flex-direction: column;
    margin-left: 20px;
}
#linha{
    display: flex;
}

#logo{
    border-radius: 30px;
    box-shadow: 10px 10px 15px aqua;
    width: 300px;
    margin-bottom: 5%;
}

h1{
    font-size:1.9em;
 
}

#barra{
    background-color:aqua;
    width: 8px;
    height: 30px;
  
    animation:piscar 0.8s linear  infinite 
}

@keyframes piscar {
   from {opacity: 0;}
   to {opacity: 1;}
}

#icones{
   display: flex;
   gap: 20px;
   margin-top: 5%;
  
   width: 370px;
   padding-left: 5px;
   border-radius: 10%;
}
#git,#zap,#linkdin,#email{
    height:40px;
    transition: 0.7s;
  background-color: aqua;
  border-radius: 10%;
}
.social{
    color: white;
    background-color: aqua;
    font-size: 1.4em;
    margin-left: 5px;
    height: 80px;
    padding: 20px;
    border-radius:20px;
    text-decoration: none;
    transition: 0.5s;
    font-weight: bold;
}


}



/*responsivo max 800 min 600*/
    @media (max-width:800px) and (min-width: 600px){
        #container{
    flex-direction: column;
   gap:30px;
}
#texto{
    display: flex;
    flex-direction: column;
    margin-left: 20px;
}
#linha{
    display: flex;
}

#logo{
    border-radius: 30px;
    box-shadow: 10px 10px 15px aqua;
    width: 400px;
    margin-bottom: 5%;
}

h1{
    font-size:2em;
 
}

#barra{
    background-color:aqua;
    width: 8px;
    height: 30px;
  
    animation:piscar 0.8s linear  infinite 
}

@keyframes piscar {
   from {opacity: 0;}
   to {opacity: 1;}
}

#icones{
   display: flex;
   gap: 20px;
   margin-top: 5%;
  
   width: 370px;
   padding-left: 5px;
   border-radius: 10%;
}
#git,#zap,#linkdin,#email{
    height:50px;
    transition: 0.7s;
  background-color: aqua;
  border-radius: 10%;
}
.social{
    color: white;
    background-color: aqua;
    font-size: 1.5em;
    margin-left: 5px;
    height: 80px;
    padding: 20px;
    border-radius:20px;
    text-decoration: none;
    transition: 0.5s;
    font-weight: bold;
}
    }
</style>
