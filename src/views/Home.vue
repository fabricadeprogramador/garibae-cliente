<template>
  <div class="home">
    <h1>GARIBAÊ TELA INICIAL</h1>

    <div>  promoçẽs </div>
    <mais-proximos></mais-proximos>

  </div>
</template>

<script>
// @ is an alias to /src


import MaisProximos from "../components/MaisProximos";
export default {
  name: 'home',
  components: {
      MaisProximos
  }
}
</script>

<style>
    .v-content {
        background-color: grey;
    }
</style>
