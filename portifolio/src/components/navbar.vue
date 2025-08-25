<template>
  <header>
    <nav class="navbar navbar-expand-lg fixed-top bg-dark">
      <div class="container-fluid">
        <a class="navbar-brand text-warning fw-bold" href="#">Welson Júnior</a>
        <button 
          class="navbar-toggler" 
          type="button" 
          data-bs-toggle="collapse" 
          data-bs-target="#navbarSupportedContent" 
          aria-controls="navbarSupportedContent" 
          aria-expanded="false" 
          aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active text-light" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-light" href="#sobre">Sobre Mim</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-light" href="#skiils">Skills</a>
            </li>
            <li class="nav-item">
              <a class="nav-link text-light" href="#projeto">Projetos</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'navbar'
}
</script>

<style scoped>

.navbar {
  background-color: #111 !important;
  box-shadow: 0px 2px 5px rgba(0,0,0,0.5);
}
.navbar-brand{
  color: aqua !important;
}

/* Links do menu */
.nav-link {
  margin: 0 10px;
  transition: color 0.3s ease, transform 0.2s ease;
}


.nav-link:hover {
  color: aqua !important;
  transform: scale(1.1);
}

/* Marca o link ativo */
.nav-link.active {
  color: aqua !important;
  font-weight: bold;
  
}
</style>
