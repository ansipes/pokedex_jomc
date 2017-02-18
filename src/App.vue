<template>

  <div id="app">

    <navbar></navbar>
    <pokedex></pokedex>

  </div>
</template>

<script>

import Navbar from './components/Navbar.vue';
import Pokedex from './components/Pokedex.vue';
import Modal from './components/Modal.vue';



export default {
  name: 'app',
  components: { Navbar, Pokedex, Modal },
  data () {
    return {

    }
  }
}

</script>

<style>

</style>
