<template>
    <sectiom id="projetos">
        <h2 id="title">Projetos</h2>


        <div id="preview">
       

        <div class="apresentacao">

<img src="../public/img/tela pleno.png" alt="preview do site">
<div class="apretexto">
<p class="textoapre">
  Desenvolvir este projeto front-end como freelaance. A ideia é ter um site institucional com algumas páginas de serviços ,contatos e links para as redes sociais. Usei as seguintes tecnologias:
</p> 
<div id="logos">
  <img class="logotec" src="../public/img/html.gif" alt="">
  <img class="logotec"  src="../public/img/icons8-javascript.gif" alt="">
  <img class="logotec"  src="../public/img/icons8-vuejs-48.png" alt="">
  <img class="logotec"  src="../public/img/css.gif" alt="">
  <img class="logotec"  src="../public/img/icons8-github-30.png" alt="">
 
</div>
<div class="link">
  <a class="linkpre" href="https://cheerful-lebkuchen-54756d.netlify.app/" target="_blank">VER PROJETO</a>
  <a  class="linkpre" href="https://github.com/juniorwelson/Site-Institucional" target="_blank">VER CODIGO NO GIT</a>
</div>
</div>





        </div>




        <div class="apresentacao2">
<img src="../public/img/tela pdv.png" alt="preview do site">
<div class="apretexto">
<p class="textoapre">
  Desenvolvir este projeto fullstack com a ideia de torná-lo uma aplicação desktop. Ainda precisa de algumas atualizações,mas acredito que já soluciona um problema do mundo real. Usei as seguintes tecnologias:
</p> 
<div id="logos">
  <img class="logotec" src="../public/img/html.gif" alt="">
  <img class="logotec"  src="../public/img/icons8-javascript.gif" alt="">
  <img class="logotec"  src="../public/img/icons8-vuejs-48.png" alt="">
  <img class="logotec"  src="../public/img/css.gif" alt="">
  <img class="logotec"  src="../public/img/icons8-github-30.png" alt="">
  <img class="logotec"  src="../public/img/bootstrap.png" alt="">
  <img class="logotec"  src="../public/img/mysql.png" alt="">
  <img class="logotec"  src="../public/img/nodejs.png" alt="">
  <img class="logotec"  src="../public/img/icons8-expresso-js-50.png" alt="">
</div>
<div class="link">
  <a class="linkpre" href="https://sistemacaixa.netlify.app/#/" target="_blank">VER PROJETO</a>
  <a  class="linkpre" href="https://github.com/juniorwelson/sistema-caixa" target="_blank">VER CODIGO NO GIT</a>
</div>
</div>





        </div>

      
        <div id="card">
   <div id="rodando"></div>
  <p id="textoroda">EM CONSTRUÇÃO</p>
        </div>


      </div>
    </sectiom>
</template>



<script>
export default {
    name:'projetos'
}
</script>

<style scoped>


#title{
    font-size: 3em;
    color: aqua;
    text-align: center;
}

#card {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 40px;
  border-radius: 15px;
  width: 520px;
  height: 600px;
  padding-top: 80px;
  background-color: #0a0a23;
  margin-left:10%;
}

#rodando {
    width: 400px;
      height: 400px;
      border: 10px dotted rgb(49, 48, 64);
      border-top: 10px solid aqua;
      border-bottom: 10px solid rgb(255, 255, 255);
      border-radius: 50%;
      animation: spin 1s linear infinite;
     
}
#textoroda{
    text-align: center;
    font-size: 1em;
    color: white;
    margin-bottom: 20px;
    padding: 10px;
    border-radius: 10px;
} 



@keyframes spin {
      0% {
        transform: rotate(0deg);
      }
      100% {
        transform: rotate(360deg);
      }
    }
#preview{
  display: flex;
  gap: 40px;
flex-wrap: wrap;
margin-top: 5%;
}

img{
  width: 400px;
  height: 300px;
  margin-left: 5%;
  border-radius: 10%;
}
.apresentacao{
  padding-left: 10px;
  border-radius: 15px;
  width: 520px;
  height: 650px;
  padding-top: 10px;
  background-color: #0a0a23;
  margin-left: 10%;
}
.textoapre{
  color: white;
  border-radius: 10px;
  margin-bottom: 10px;
  text-align: center;
  line-height: 30px;
}
.apresentacao2{
  padding-left: 10px;
  border-radius: 15px;
  width: 520px;
  height: 690px;
  padding-top: 10px;
  background-color: #0a0a23;
  
}

.apretexto{
  background-color: #0a0a23;
  margin-right: 10px;
  margin-top: 10px;
}
#logos{
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 40px;
  background-color: #0a0a23;
}

.logotec{
  width: 40px;
  height: 50px;
  background-color: #0a0a23;
  box-shadow: 0 0 10px aqua;
  transition: transform 0.3s ease;
}
.logotec:hover{
  transform: scale(1.05);
  box-shadow: 0 0 15px aqua, 0 0 25px aqua;
}
.link{
  background-color: #0a0a23;
  margin-top: 40px;
  gap: 10px;
  display: flex;
  justify-content: center;
  border-radius: 10px;
  
}

.linkpre{
  color: white;
    background-color: aqua;
    font-size: 1em;
    padding: 15px 10px;
    text-align:center ;
   height: 50px;
    border-radius:20px;
    text-decoration: none;
    transition: 0.5s;
    font-weight: bold;
}

.linkpre:hover{
background-color: white;
color: aqua;

}


/*responsivo max 450px*/
@media (max-width:450px){
  
#title{
    font-size: 2em;
   
}

#card {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 0px; 
  border-radius: 15px;
  width: 300px;
  height: 400px;
  padding-top: 10px;
  background-color: #0a0a23;
  margin-left:50px;
}

#rodando {
    width: 200px;
      height: 200px;
      border: 10px dotted rgb(49, 48, 64);
      border-top: 10px solid aqua;
      border-bottom: 10px solid rgb(255, 255, 255);
      border-radius: 50%;
      animation: spin 1s linear infinite;
     
}
#textoroda{
    text-align: center;
    font-size: 1em;
    color: white;
    margin-bottom: 5%;
    height: 50px;
    padding-top:5%;
    border-radius: 10px;
} 


@keyframes spin {
      0% {
        transform: rotate(0deg);
      }
      100% {
        transform: rotate(360deg);
      }
    }
#preview{
  display: flex;
  gap: 100px;
flex-wrap: wrap;
margin-top: 5%;
width: 100%;
}

img{
  width: 400px;
  height: 300px;
  margin-left: 0%;
  border-radius: 10%;
}
.apresentacao{
  padding-left: 5px;
  border-radius: 15px;
  width: 100%;
  height: 700px;
  padding-top: 10px;
  background-color: #0a0a23;
  margin-left: 0%;
}

.apresentacao2{
  padding-left: 5px;
  border-radius: 15px;
  width: 100%;
  height: 700px;
  padding-top: 10px;
  background-color: #0a0a23;
  
}

.apretexto{
  background-color: #0a0a23;
  margin-right:0px;
  margin-top: 10px;
}

.textoapre{
  color: white;
  border-radius: 10px;
  margin-bottom: 10px;
  text-align: center;
  font-size: 14px;
}
#logos{
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  background-color: #0a0a23;
}

.logotec{
  width: 30px;
  height: 50px;
  background-color: #0a0a23;
  box-shadow: 0 0 10px aqua;
  transition: transform 0.3s ease;
}
.logotec:hover{
  transform: scale(1.05);
  box-shadow: 0 0 15px aqua, 0 0 25px aqua;
}
.link{
  background-color: #0a0a23;
  margin-top: 40px;
  gap: 70px;
  display: flex;
  justify-content: center;
  border-radius: 10px;
  
}

.linkpre{
  color: white;
    background-color: aqua;
    font-size: 1em;
    padding: 15px 10px;
    text-align:center ;
   height: 50px;
    border-radius:20px;
    text-decoration: none;
    transition: 0.5s;
    font-weight: bold;
}

.linkpre:hover{
background-color: white;
color: aqua;

}
}

/*responsivo max 600px e min 450px */
@media (max-width:600px) and (min-width: 450px){
  #title{
    font-size: 2em;
   
}

#card {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 0px; 
  border-radius: 15px;
  width: 300px;
  height: 400px;
  padding-top: 10px;
  background-color: #0a0a23;
  margin-left:20%;
}

#rodando {
    width: 200px;
      height: 200px;
      border: 10px dotted rgb(49, 48, 64);
      border-top: 10px solid aqua;
      border-bottom: 10px solid rgb(255, 255, 255);
      border-radius: 50%;
      animation: spin 1s linear infinite;
     
}
#textoroda{
    text-align: center;
    font-size: 1em;
    color: white;
    margin-bottom: 5%;
    height: 50px;
    padding-top:5%;
    border-radius: 10px;
} 


@keyframes spin {
      0% {
        transform: rotate(0deg);
      }
      100% {
        transform: rotate(360deg);
      }
    }
#preview{
  display: flex;
  gap: 100px;
flex-wrap: wrap;
margin-top: 5%;
width: 100%;
}

img{
  width: 400px;
  height: 300px;
  margin-left: 5%;
  border-radius: 10%;
}
.apresentacao{
  padding-left: 5px;
  border-radius: 15px;
  width: 450px;
  height: 600px;
  padding-top: 10px;
  background-color: #0a0a23;
  margin-left: 7%;
  margin-right: 3%;
}

.apresentacao2{
  padding-left: 5px;
  border-radius: 15px;
  width: 500px;
  height: 700px;
  padding-top: 10px;
  background-color: #0a0a23;
  margin-left: 5%;
  margin-right: 3%;
}

.apretexto{
  background-color: #0a0a23;
  margin-right:0px;
  margin-top: 10px;
}

.textoapre{
  color: white;
  border-radius: 10px;
  margin-bottom: 10px;
  text-align: center;
}
#logos{
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  background-color: #0a0a23;
}

.logotec{
  width: 30px;
  height: 50px;
  background-color: #0a0a23;
  box-shadow: 0 0 10px aqua;
  transition: transform 0.3s ease;
}
.logotec:hover{
  transform: scale(1.05);
  box-shadow: 0 0 15px aqua, 0 0 25px aqua;
}
.link{
  background-color: #0a0a23;
  margin-top: 40px;
  gap: 70px;
  display: flex;
  justify-content: center;
  border-radius: 10px;
  
}

.linkpre{
  color: white;
    background-color: aqua;
    font-size: 1em;
    padding: 15px 10px;
    text-align:center ;
   height: 50px;
    border-radius:20px;
    text-decoration: none;
    transition: 0.5s;
    font-weight: bold;
}

.linkpre:hover{
background-color: white;
color: aqua;

}
}

/*responsivo max 600px e min 450px */
@media (max-width:800px) and (min-width: 600px){
  #title{
    font-size: 2em;
   
}

#card {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 0px; 
  border-radius: 15px;
  width: 300px;
  height: 400px;
  padding-top: 10px;
  background-color: #0a0a23;
  margin-left:25%;
}

#rodando {
    width: 200px;
      height: 200px;
      border: 10px dotted rgb(49, 48, 64);
      border-top: 10px solid aqua;
      border-bottom: 10px solid rgb(255, 255, 255);
      border-radius: 50%;
      animation: spin 1s linear infinite;
     
}
#textoroda{
    text-align: center;
    font-size: 1em;
    color: white;
    margin-bottom: 5%;
    height: 50px;
    padding-top:5%;
    border-radius: 10px;
} 


@keyframes spin {
      0% {
        transform: rotate(0deg);
      }
      100% {
        transform: rotate(360deg);
      }
    }
#preview{
  display: flex;
  gap: 100px;
flex-wrap: wrap;
margin-top: 5%;
width: 100%;
}

img{
  width: 400px;
  height: 300px;
  margin-left: 5%;
  border-radius: 10%;
}
.apresentacao{
  padding-left: 5px;
  border-radius: 15px;
  width: 450px;
  height: 600px;
  padding-top: 10px;
  background-color: #0a0a23;
  margin-left: 15%;
  margin-right: 3%;
}

.apresentacao2{
  padding-left: 5px;
  border-radius: 15px;
  width: 500px;
  height: 700px;
  padding-top: 10px;
  background-color: #0a0a23;
  margin-left: 12%;
  margin-right: 3%;
}

.apretexto{
  background-color: #0a0a23;
  margin-right:0px;
  margin-top: 10px;
}

.textoapre{
  color: white;
  border-radius: 10px;
  margin-bottom: 10px;
  text-align: center;
}
#logos{
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  background-color: #0a0a23;
}

.logotec{
  width: 30px;
  height: 50px;
  background-color: #0a0a23;
  box-shadow: 0 0 10px aqua;
  transition: transform 0.3s ease;
}
.logotec:hover{
  transform: scale(1.05);
  box-shadow: 0 0 15px aqua, 0 0 25px aqua;
}
.link{
  background-color: #0a0a23;
  margin-top: 40px;
  gap: 70px;
  display: flex;
  justify-content: center;
  border-radius: 10px;
  
}

.linkpre{
  color: white;
    background-color: aqua;
    font-size: 1em;
    padding: 15px 10px;
    text-align:center ;
   height: 50px;
    border-radius:20px;
    text-decoration: none;
    transition: 0.5s;
    font-weight: bold;
}

.linkpre:hover{
background-color: white;
color: aqua;

}
}
</style>