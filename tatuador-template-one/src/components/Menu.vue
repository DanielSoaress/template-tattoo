<template>
  <header class="menu">
    <div class="container">
      <a href="#home" @click="closeMenu" class="logo"
        ><img src="../assets/img/logo.png" alt="Logo"
      /></a>
      <nav class="menu-nav">
        <ul>
          <li><a class="nav-link" @click="closeMenu" href="#sobre">Sobre</a></li>
          <li><a class="nav-link" @click="closeMenu" href="#galeria">Galeria</a></li>
          <li><a class="nav-link" @click="closeMenu" href="#depoimentos">Depoimentos</a></li>
          <li><a class="nav-link" @click="closeMenu" href="#contato">Contato</a></li>
        </ul>
      </nav>
      <div class="menu-hamburguer">
        <a @click="active = !active">
            <img v-show="!active" src="../assets/img/menu-button.png" alt="Menu Open"/>
            <img v-show="active" width="25" height="25" src="../assets/img/close.png" alt="Menu Close"/>
        </a>
      </div>
    </div>
    <nav class="menu-bar" v-show="active">
      <ul>
        <li><a class="nav-link" @click="active = !active" href="#sobre">Sobre</a></li>
        <li><a class="nav-link" @click="active = !active" href="#galeria">Galeria</a></li>
        <li><a class="nav-link" @click="active = !active" href="#depoimentos">Depoimentos</a></li>
        <li><a class="nav-link" @click="active = !active" href="#contato">Contato</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  data: function () {
    return {
      active: false,
    };
  },
  methods: {
      closeMenu() {
          if(this.active){
              this.active = !this.active
          }
      }
  }
};
</script>

<style scoped>
.container {
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.menu {
  width: 100vw;
  background-color: #0b0c0c;
  position: fixed;
}

.container ul li {
  display: inline-block;
}

.logo {
  margin: 10px 20px;
}

.menu-bar .nav-link {
  display: block;
  padding: 10px 0;
}

.nav-link {
  text-decoration: none;
  text-transform: uppercase;
  color: white;
  padding: 10px;
  font-weight: 300;
  font-family: "Roboto", Helvetica, Arial, sans-serif;
  letter-spacing: 2px;
  font-size: 0.875em;
}

.nav-link:hover {
  color: #ca9e67;
  text-decoration: underline #ca9e67;
}

.menu-hamburguer {
  display: none;
  margin-right: 20px;
}

.menu-hamburguer a{
    cursor: pointer;
}

.menu-bar {
    margin-bottom: 10px;
}

@media (max-width: 700px) {
  .menu-nav {
    display: none;
  }
  .menu-hamburguer {
    display: block;
  }
}

@media (min-width: 701px) {
  .menu-bar {
    display: none;
  }
}
</style>