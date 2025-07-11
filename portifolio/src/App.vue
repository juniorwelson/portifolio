<template>
  <div>
    <a href="https://w.app/rnbkif" target="_blank"><img id="what" src="./public/img/zap-aqua.svg" alt="logo zap"></a>
    <navbar/>
    <apresentacao/>
    <sobre/>
    <skiils/>
    <projetos/>
    <rodape/>
    </div>
</template>

<script>
import navbar from './components/navbar.vue'
import apresentacao from './components/apresentacao.vue';
import sobre from './components/sobre.vue';
import skiils from './components/skiils.vue';
import projetos from './components/projetos.vue';
import rodape from './components/rodape.vue';
export default {
  name: 'App',
  components: {
    navbar,
    apresentacao,
    sobre,
    skiils,
    projetos,
    rodape
  }
  
}
</script>
<style>
*{
  font-family: "Montserrat",sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  background-color:  rgb(49, 48, 64);
  
  scroll-behavior: smooth;

}

#what{
position: fixed;
top:80%;
margin-left:10px;
animation:piscar 0.9s linear  infinite ;
background-color:rgb(49, 48, 64); ;

}
@keyframes piscar {
   from {opacity: 0;}
   to {opacity: 1;}
}
</style>
