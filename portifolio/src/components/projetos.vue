<template>
<section id="projeto" class="mt-5">
  <h2 id="title" class="pb-5">Projetos</h2>
  <div id="projetos" class="d-flex justify-center flex-wrap ">
    
    <div class="card bg- ms-5" style="width: 20rem">
      <img
        src="../public/img/tela-law.png"
        style="width: 20rem; height: 300px"
        class="card-img-top"
        alt="preview do site"
      />
      <div class="card-body">
        <h5 class="card-title" style="color: aqua;">Site de advocacia</h5>
        <p class="card-text text-white">
          Desenvolvi este site no intuito de colocar em práticas as habilidades
          em bootstrap e Vue Js. Usei as seguintes tecnologias:
        </p>
        <div class="tecnologia">
          <img
            src="../public/img/bootstrap.png"
            alt="logo de bootsrap"
            class="tecno"
          />
          <img src="../public/img/css.gif" alt="logo css" class="tecno" />
          <img src="../public/img/html.gif" alt="logo html" class="tecno" />
          <img
            src="../public/img/icons8-javascript.gif"
            alt="logo js"
            class="tecno"
          />
          <img
            src="../public/img/icons8-vuejs-48.png"
            alt="logo vuejs"
            class="tecno"
          />
        </div>

        <div class="btnAction">
          <a href="https://github.com/juniorwelson/advocacia_prime" target=" _blank">Ver Código</a>
          <a href="https://advocacia-prime.netlify.app/" target=" _blank">Ver Projeto</a>
        </div>
      </div>
    </div>

    <!--segundo card-->
     <div class="card bg- ms-5" style="width: 20rem">
      <img
        src="../public/img/tela pdv.png"
        style="width: 20rem; height: 300px"
        class="card-img-top"
        alt="preview do site"
      />
      <div class="card-body">
        <h5 class="card-title" style="color: aqua;">Sistema de caixa financeiro</h5>
        <p class="card-text text-white">
          Desenvolvi este site no intuito de colocar em práticas as habilidades
          tanto no front quanro no backend. Esse sistema pode fechar venda e visualizar relatório de todas as vendas no dia. Para isso usei as seguintes tecnologias:
        </p>
        <div class="tecnologia">
          <img
            src="../public/img/bootstrap.png"
            alt="logo de bootsrap"
            class="tecno"
          />
          <img src="../public/img/css.gif" alt="logo css" class="tecno" />
          <img src="../public/img/html.gif" alt="logo html" class="tecno" />
          <img
            src="../public/img/icons8-javascript.gif"
            alt="logo js"
            class="tecno"
          />
          <img
            src="../public/img/icons8-vuejs-48.png"
            alt="logo vuejs"
            class="tecno"
          />
          
          <img
            src="../public/img/icons8-expresso-js-50.png"
            alt="logo exprees js"
            class="tecno"
          />
          <img
            src="../public/img/mysql.png"
            alt="logo mysql"
            class="tecno"
          />

          <img
            src="../public/img/nodejs.png"
            alt="logo node js"
            class="tecno"
          />
        </div>

        <div class="btnAction">
          <a href="https://github.com/juniorwelson/sistema-caixa" target=" _blank">Ver Código</a>
          <a href="https://sistemacaixa.netlify.app/#/" target=" _blank">Ver Projeto</a>
        </div>
      </div>
    </div>

    <!--terceiro card-->
     <div class="card bg- ms-5" style="width: 20rem">
      <img
        src="../public/img/tela pleno.png"
        style="width: 20rem; height: 300px"
        class="card-img-top"
        alt="preview do site"
      />
      <div class="card-body">
        <h5 class="card-title" style="color: aqua;">Site Pleno Bank</h5>
        <p class="card-text text-white">
          Desenvolvi este site para uma empresa que desejava um site institucional.Para isso usei as seguintes tecnologias:
        </p>
        <div class="tecnologia">
          <img
            src="../public/img/bootstrap.png"
            alt="logo de bootsrap"
            class="tecno"
          />
          <img src="../public/img/css.gif" alt="logo css" class="tecno" />
          <img src="../public/img/html.gif" alt="logo html" class="tecno" />
          <img
            src="../public/img/icons8-javascript.gif"
            alt="logo js"
            class="tecno"
          />
          <img
            src="../public/img/icons8-vuejs-48.png"
            alt="logo vuejs"
            class="tecno"
          />
        </div>

        <div class="btnAction">
          <a href="https://github.com/juniorwelson/Site-Institucional" target=" _blank">Ver Código</a>
          <a href="https://cheerful-lebkuchen-54756d.netlify.app/" target=" _blank">Ver Projeto</a>
        </div>
      </div>


    </div>


  </div>

  </section>
</template>

<script>
export default {
  name: "projetos",
};
</script>

<style scoped>
#projetos{
margin-left:10%;
}
.tecnologia {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
}
.tecno {
  width: 50px;
  height: 30px;
}
.btnAction {
  display: flex;
  justify-content: center;
  gap: 10px;
  margin-top: 10px;
}
.btnAction a {
  padding: 10px;
  color: #fff;
  background-color: aqua;
  text-decoration: none;
  border-radius: 10px;
  margin-left: 5px;
  transition: 0.5s;
  font-weight: bold;
}
.btnAction a:hover {
  color: aqua;
  background-color: #fff;
}
#title{
    font-size: 3em;
    color: aqua;
    text-align: center;
   
}
/*responsivo max 450px*/
@media (max-width:450px){
  #projetos{
margin-left:3%;
}
.card{
  margin-bottom: 5%;
}
}

/*responsivo max 600px e min 450px*/
@media (max-width:600px) and (min-width:450px){
  #projetos{
margin-left:14%;
}
.card{
  margin-bottom: 5%;
}
}


/*responsivo max 800px e min 600px*/
@media (max-width:800px) and (min-width:600px){
  #projetos{
margin-left:20%;
}
.card{
  margin-bottom: 5%;
}
}
</style>
