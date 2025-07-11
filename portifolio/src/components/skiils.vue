<template>
    <section id="skiils">
      <div id="titulo">
        <h2>Skills</h2>
      </div>
  
      <div id="hardskills">
        <div class="card">
          <img src="../public/img/html.gif" alt="html" />
          <p>Linguagem de marcação para desenvolvimento web</p>
        </div>
        <div class="card">
          <img src="../public/img/css.gif" alt="css" />
          <p>Linguagem de estilização</p>
        </div>
        <div class="card">
          <img src="../public/img/icons8-javascript.gif" alt="js" />
          <p>Linguagem que permite dar vida à web</p>
        </div>
        <div class="card">
          <img src="../public/img/icons8-vuejs-48.png" alt="vuejs" />
          <p>Framework para o desenvolvimento web</p>
        </div>
        <div class="card">
          <img src="../public/img/bootstrap.png" alt="bootstrap" />
          <p>Framework de estilização das páginas web</p>
        </div>
        <div class="card">
          <img src="../public/img/nodejs.png" alt="node" />
          <p>Ambiente para executar JS no backend</p>
        </div>
        <div class="card">
          <img src="../public/img/icons8-expresso-js-50.png" alt="express" />
          <p>Framework backend para Node.js</p>
        </div>
        <div class="card">
          <img src="../public/img/mysql.png" alt="mysql" />
          <p>Banco de dados relacional</p>
        </div>

        <div class="card">
          <img src="../public/img/icons8-git-48.png" alt="git" />
          <p>Controle de versionamento de projetos</p>
        </div>
      </div>
    </section>
  </template>
  


<script>
export default {
    name:'skills'
}
</script>

<style scoped>

#skiils {
  width: 100%;
  padding: 40px 5%;
}

#titulo {
  margin-bottom: 40px;
}

h2 {
  text-align: center;
  color: aqua;
  font-size: 3em;
}

#hardskills {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 40px;
}

.card {
  width: 220px;
  background-color: #0a0a23;
  border-radius: 15px;
  padding: 20px;
  text-align: center;
  box-shadow: 0 0 10px aqua;
  transition: transform 0.3s ease;
}

.card:hover {
  transform: scale(1.05);
  box-shadow: 0 0 15px aqua, 0 0 25px aqua;
}

.card img {
  width: 100%;
  height: auto;
  max-height: 150px;
  object-fit: contain;
}

.card p {
  font-size: 1em;
  color: rgb(255, 255, 255);
  font-weight: bold;
  margin-top: 10px;
}

/*responsivo max450px*/
@media (max-width:450px){
  #skiils {
  width: 100%;
  padding: 40px 5%;
}

#titulo {
  margin-bottom: 30px;
}

h2 {
  text-align: center;
  color: aqua;
  font-size: 2em;
}

#hardskills {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.card {
  width: 150px;
  background-color: #0a0a23;
  border-radius: 15px;
  padding: 20px;
  text-align: center;
  box-shadow: 0 0 10px aqua;
  transition: transform 0.3s ease;
}

.card:hover {
  transform: scale(1.05);
  box-shadow: 0 0 15px aqua, 0 0 25px aqua;
}

.card img {
  width: 100%;
  height: auto;
  max-height: 150px;
  object-fit: contain;
}

.card p {
  font-size: 10px;
  padding: 5px ;
  color: rgb(255, 255, 255);
  font-weight: bold;
  margin-top: 10px;
}

}

/*responsivo max600px a min450px*/
@media (max-width:600px) and (min-width:450px){
  #skiils {
  width: 100%;
  padding: 40px 5%;
}

#titulo {
  margin-bottom: 30px;
}

h2 {
  text-align: center;
  color: aqua;
  font-size: 2.2em;
}

#hardskills {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
}

.card {
  width: 150px;
  background-color: #0a0a23;
  border-radius: 15px;
  padding: 20px;
  text-align: center;
  box-shadow: 0 0 10px aqua;
  transition: transform 0.3s ease;
}

.card:hover {
  transform: scale(1.05);
  box-shadow: 0 0 15px aqua, 0 0 25px aqua;
}

.card img {
  width: 100%;
  height: auto;
  max-height: 150px;
  object-fit: contain;
}

.card p {
  font-size: 15px;
  padding: 5px ;
  color: rgb(255, 255, 255);
  font-weight: bold;
  margin-top: 10px;
}

}



</style>