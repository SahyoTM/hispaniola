<template>
  <div>
    <b-navbar toggleable="md" fixed="top" type="light" align="center">

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item class="test"><NuxtLink to="/">ACCUEIL</NuxtLink></b-nav-item>
          <b-nav-item ><NuxtLink to="/">SERVICES</NuxtLink></b-nav-item>
          <b-nav-item ><NuxtLink to="/">FAQ</NuxtLink></b-nav-item>
          <b-nav-item ><NuxtLink to="/">NOUS REJOINDRE</NuxtLink></b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
}
</script>

<style  >
nav a{
  color:white;
  font-weight: 400;
  margin-left:1.5rem;
  margin-right:1.5rem;

  font-family: 'Bebas Neue', cursive !important;

  font-size:1.5rem;

  transition : all 0.5s;
}

@media only screen and (max-width : 1224px) {
    nav li.test{
      margin-left: 0;
  }
}

nav a:hover,nav a:focus{
  color:#090409;
  font-weight: 900;
  text-decoration: none;

  transition : all 0.5s;
}

nav ul{
    margin:auto;
}
</style>