<template>
    <footer id="rodape">
      <a id="voltar-inicio" href="#">Voltar ao Início</a>
  
      <div id="icones-contato">
        <a href="https://github.com/juniorwelson" target="_blank" aria-label="GitHub">
          <img src="../public/img/icons8-github-30.png" alt="GitHub" class="icone-social" />
        </a>
        <a href="https://www.linkedin.com/in/welson-junior-a587b72b8" target="_blank"  aria-label="LinkedIn">
          <img src="../public/img/icons8-linkedin-50.png" alt="LinkedIn" class="icone-social" />
        </a>
        <a href="mailto:eujuniorplus@gmail.com?subject=Olá&body=Quero%20falar%20sobre%20seu%20portfólio." target="_blank" aria-label="Email">
          <img src="../public/img/icons8-nova-mensagem-30.png" alt="Email" class="icone-social" />
        </a>
        <a href="https://w.app/rnbkif" target="_blank" aria-label="WhatsApp">
          <img src="../public/img/icons8-whatsapp-50 (1).png" alt="WhatsApp" class="icone-social" />
        </a>
      </div>
  
      <p id="autor">Desenvolvido por <span>Welson Junior</span></p>
    </footer>
  </template>
  
  <script>
  export default {
    name: 'Rodape',
  }
  </script>
  
  <style scoped>
  #rodape {
    width: 100%;
    height: 350px;
    margin-top: 5%;
    padding: 30px 0;
    background-color: #222229;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
  }
  
  #voltar-inicio {
    color: white;
    background-color: aqua;
    font-size: 1.5em;
    padding: 15px 30px;
    border-radius: 20px;
    text-decoration: none;
    font-weight: bold;
    transition: all 0.3s ease;
  }
  
  #voltar-inicio:hover {
    background-color: white;
    color: aqua;
  }
  
  #icones-contato {
    display: flex;
    gap: 40px;
    margin: 20px 0;
  }
  
  .icone-social {
    height: 50px;
    padding: 10px;
    border-radius: 12px;
    background-color: aqua;
    transition: transform 0.3s ease, background-color 0.3s ease;
  }
  
  .icone-social:hover {
    transform: scale(1.1);
  }
  
  .icone-social[alt="GitHub"]:hover {
    background-color: #333;
  }
  
  .icone-social[alt="LinkedIn"]:hover {
    background-color: #0061f2;
  }
  
  .icone-social[alt="Email"]:hover {
    background-color: #cd1837;
  }
  
  .icone-social[alt="WhatsApp"]:hover {
    background-color: #00ff37;
  }
  
  #autor {
    font-size: 1.2em;
    color: white;
    font-weight: bold;
  }
  
  #autor span {
    color: aqua;
  }
  </style>
  