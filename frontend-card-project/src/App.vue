<template>
  <div id="app">
    <card-principal></card-principal>
  </div>
</template>

<script>

import CardPrincipal from './components/Card.vue'


export default {
  name: 'App',
  components: {
    CardPrincipal
  }
}
</script>

<style>

* {
  margin: 0px;
  border: 0px;
}


@import'~bootstrap/dist/css/bootstrap.css'

</style>
