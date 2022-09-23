<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <a class="navbar-brand mt-2 mt-lg-0" href="#">
        <img
          src="https://www.sosfactory.com/wp-content/uploads/2016/12/restaurant-logo-mr-bolat.png"
          height="50"
          alt="Logo"
          loading="lazy"
        />
        <h5 class="text">Casa de anita</h5>
      </a>
      
      <br>
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link" href="#">Ensaladas</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Arroces</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Pescados</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Carnes</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Postres</a>
        </li>
      </ul>
    </div>
    <h5 class="text">David Zarate Ramirez  10° A DGS</h5>
</nav>
  <card url="https://www.paulinacocina.net/wp-content/uploads/2020/01/untitled-copy.jpg"  nombre="Tacos de asada" descripcion="simon es una pizza de peperoni" 
  precio="$766"/>
  <card url="https://www.cocinacaserayfacil.net/wp-content/uploads/2020/03/Platos-de-comida-que-pides-a-domicilio-y-puedes-hacer-en-casa.jpg" nombre="Pizza" descripcion="simon es una pizza de peperoni" 
  precio="$766"/>
  <card url="https://vivirmejor.mx/wp-content/uploads/2020/08/Comida-Tipica-Mexicana-Pozole-Portada.jpg" nombre="Pozole" descripcion="simon es una pizza de peperoni" 
  precio="$766"/>
  <card url="https://st2.depositphotos.com/1772367/7679/i/450/depositphotos_76797217-stock-photo-spaghetti-with-tomato-sauce.jpg" nombre="Spagueti" descripcion="simon es una pizza de peperoni"
  precio="$766"/>
  <card url="https://images.ecestaticos.com/_cg6AD-a8L0toabkQSJiN6frVY4=/0x118:2269x1393/1600x900/filters:fill(white):format(jpg)/f.elconfidencial.com%2Foriginal%2F8b5%2Fc1d%2F016%2F8b5c1d0163f7a26de81530b12e1e3a02.jpg" nombre="Donas"
  descripcion="simon es una pizza de peperoni" precio="$766"/>
  <card url="https://wrmx00.epimg.net/radio/imagenes/2021/06/23/sociedad/1624460359_840745_1624466631_miniatura_normal.jpg" nombre="Elotes" descripcion="simon es una pizza de peperoni"
  precio="$766"/>
  
  <MDBFooter :text="['center', 'lg-start']">
    <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2)">
      © 2020 Copyright:
      <a class="text-dark" href="https://mdbootstrap.com/">MDBootstrap.com</a>
    </div>
  </MDBFooter>
</template>

<script>
  import Card from "./components/Card.vue";
  import Contador from "./components/Contador.vue";
  import Modal from "./components/Modal.vue";
  export default{
    components: { Card, Contador, Modal,},
    
  };
</script>