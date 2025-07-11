<template>
    <section id="sobre" >
      
       <div id="texto">
        <h2>SOBRE <span>MIM</span></h2>
        <ul>
            <li>Graduando em Análise de Sistemas</li>
            <li>Apaixonado em Resolver Problemas Atráves da Programação</li>
            <li>Desenvolvedor Front-End</li>
            <li>Possuo alguns conhecimentos em NodeJs/Express, MySql, e consumo de APIs Rest</li>
            <li>Estou desenvolvendo meu inglês,já consigo comunicar o básico e ler documentação em inglês. </li>
            <li>Conhecimento em Scrumm. </li>
            <li>Em busca da primeira oportunidade</li>
        </ul>
      
       </div>
      
       <img src="../public/img/mexendo no pc.png" alt="foto pessoal">

      
    </section>
</template>

<script>

export default {
    name: 'sobre',
}
</script>

<style scoped>
#sobre{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 9%;
    flex-direction: row-reverse;


}

#texto{
    display: block;
    border: 3px rgb(5, 255, 255) solid;
    padding: 10px;
    border-top-left-radius: 50px;
    margin-bottom: 10%;
}


h2{
    margin-bottom: 7%;
    font-size: 3em;
    color: white;
    text-align: center;
    
}
span{
    color: aqua;
}

li{
    line-height: 50px;
    color: rgb(255, 255, 255);
    font-size: 1.5em;
   list-style: none;
   
}
li::before {
    content: "✔";
    color: aqua;
  padding-right: 4px;
  left: 0;
}

img{
    margin-bottom: 10%;
    border-radius: 30px;
    box-shadow: 10px 10px 15px aqua;
 margin-left: 5%;
    
}




/*responsivo max 450px*/
@media (max-width:450px){
    #sobre{
        display: flex;
        align-items: center;
        justify-content: center;
   flex-direction: column;
    gap: 5%;
    width: 100%;
  margin-top: 10%;
    
}

#texto{
    display: block;
    border: 3px rgb(5, 255, 255) solid;
    padding: 0;
    border-radius: 10px;
    width: 90%;
    
}


h2{
    margin-bottom: 4%;
    font-size: 1.8em;
    color: white;
    text-align: center;
    
}
span{
    color: aqua;
}

li{
    line-height: 50px;
    color: rgb(255, 255, 255);
    font-size: 1em;
   list-style: none;
   padding-left: 3px;
}
li::before {
    content: "✔";
    color: aqua;
  padding-right: 4px;
  padding-left: 3px;
  left: 0;
}

img{
    width: 300px;
    margin-bottom: 10%;
    border-radius: 30px;
    box-shadow: 10px 10px 15px aqua;
 
    
}
}

/*responsivo max 600px e min 450px*/
@media (max-width:600px) and (min-width:450px){
    #sobre{
        display: flex;
        align-items: center;
        justify-content: center;
   flex-direction: column;
    gap: 5%;
    width: 100%;
  margin-top: 10%;
    
}

#texto{
    display: block;
    border: 3px rgb(5, 255, 255) solid;
    padding: 0;
    border-radius: 10px;
    width: 90%;
    
}


h2{
    margin-bottom: 4%;
    font-size: 1.8em;
    color: white;
    text-align: center;
    
}
span{
    color: aqua;
}

li{
    line-height: 50px;
    color: rgb(255, 255, 255);
    font-size: 1.5em;
   list-style: none;
   padding-left: 3px;
}
li::before {
    content: "✔";
    color: aqua;
  padding-right: 4px;
  padding-left: 10px;
  left: 0;
}

img{
    width: 350px;
    margin-bottom: 10%;
    border-radius: 30px;
    box-shadow: 10px 10px 15px aqua;
 
    
}
}



/*responsivo max 800px e min 600px*/
@media (max-width:800px) and (min-width:600px){
    #sobre{
        display: flex;
        align-items: center;
        justify-content: center;
   flex-direction: column;
    gap: 5%;
    width: 100%;
  margin-top: 10%;
    
}

#texto{
    display: block;
    border: 3px rgb(5, 255, 255) solid;
    padding: 0;
    border-radius: 10px;
    width: 90%;
    
}


h2{
    margin-bottom: 4%;
    font-size: 1.8em;
    color: white;
    text-align: center;
    padding-top: 10px;
    
}
span{
    color: aqua;
}

li{
    line-height: 50px;
    color: rgb(255, 255, 255);
    font-size: 1.5em;
   list-style: none;
   padding-left: 3px;
}
li::before {
    content: "✔";
    color: aqua;
  padding-right: 4px;
  padding-left: 10px;
  left: 0;
}

img{
    width: 350px;
    margin-bottom: 10%;
    border-radius: 30px;
    box-shadow: 10px 10px 15px aqua;
 
    
}
}

</style>