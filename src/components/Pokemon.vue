<template>



  <div @click="activate" class="column is-one-quarter-desktop is-one-quarter-tablet is-half-mobile tileAdjust">
    <div class="notification">
      <figure class="image">
        <img :src="image" />
        <hr />
        <p class="subtitle has-text-centered">{{ name }}</p>
      </figure>
    </div>
    <modal
    @close="deactivate"
    :name="name"
    :image="image"
    :type="type"
    :ability="ability"
    :height="height"
    :weight="weight"
    :hitPoints="hitPoints"
    :attack="attack"
    :defense="defense"
    :speed="speed"
    :sAttack="sAttack"
    :sDefense="sDefense"
    :isActive="isActive"
    ></modal>
  </div>



</template>

<script>

import Modal from './Modal.vue';

export default {
  components: { Modal },
  props: [
  'name',
  'image',
  'type',
  'ability',
  'height',
  'weight',
  'hitPoints',
  'attack',
  'defense',
  'speed',
  'sAttack',
  'sDefense'
  ],
  data() {
    return {
      isActive: false
    }
  },
  methods: {
      activate: function() {
        this.isActive = true;
      },
      deactivate: function() {
        this.isActive = false;
      }


  }

}





</script>


<style>

</style>
