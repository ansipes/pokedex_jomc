<template>

<div class="columns is-multiline is-mobile" style="margin: 0 10px 0 10px;">
  <pokemon v-for="pokemon in pokedex"
    :image="pokemon.image"
    :name="pokemon.name"
    :type="pokemon.type"
    :ability="pokemon.ability"
    :height="pokemon.height"
    :weight="pokemon.weight"
    :hitPoints="pokemon.hitPoints"
    :attack="pokemon.attack"
    :defense="pokemon.defense"
    :speed="pokemon.speed"
    :sAttack="pokemon.sAttack"
    :sDefense="pokemon.sDefense">
  </pokemon>
</div>

</template>

<script>

import Pokemon from './Pokemon.vue';


export default {
  name: 'pokedex',
  components: { Pokemon },

  data() {
    return {
      pokedex: [
        { name: 'One',
          image: 'http://static.giantbomb.com/uploads/scale_small/13/135472/1891758-001bulbasaur.png',
          type: 'Pooping',
          ability: 'Flying',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '50',
          attack: '50',
          defense: '50',
          speed: '50',
          sAttack: '50',
          sDefense: '50'
        },
        { name: 'One',
          image: 'http://static.giantbomb.com/uploads/scale_small/13/135472/1891758-001bulbasaur.png',
          type: 'Pooping',
          ability: 'Flying',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '50',
          attack: '50',
          defense: '50',
          speed: '50',
          sAttack: '50',
          sDefense: '50'
        },
        { name: 'One',
          image: 'http://static.giantbomb.com/uploads/scale_small/13/135472/1891758-001bulbasaur.png',
          type: 'Pooping',
          ability: 'Flying',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '50',
          attack: '50',
          defense: '50',
          speed: '50',
          sAttack: '50',
          sDefense: '50'
        },
        { name: 'One',
          image: 'http://static.giantbomb.com/uploads/scale_small/13/135472/1891758-001bulbasaur.png',
          type: 'Pooping',
          ability: 'Flying',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '50',
          attack: '50',
          defense: '50',
          speed: '50',
          sAttack: '50',
          sDefense: '50'
        },
        { name: 'One',
          image: 'http://static.giantbomb.com/uploads/scale_small/13/135472/1891758-001bulbasaur.png',
          type: 'Pooping',
          ability: 'Flying',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '50',
          attack: '50',
          defense: '50',
          speed: '50',
          sAttack: '50',
          sDefense: '50'
        },
        { name: 'One',
          image: 'http://static.giantbomb.com/uploads/scale_small/13/135472/1891758-001bulbasaur.png',
          type: 'Pooping',
          ability: 'Flying',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '50',
          attack: '50',
          defense: '50',
          speed: '50',
          sAttack: '50',
          sDefense: '50'
        },
        { name: 'One',
          image: 'http://static.giantbomb.com/uploads/scale_small/13/135472/1891758-001bulbasaur.png',
          type: 'Pooping',
          ability: 'Flying',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '50',
          attack: '50',
          defense: '50',
          speed: '50',
          sAttack: '50',
          sDefense: '50'
        },
        { name: 'One',
          image: 'http://static.giantbomb.com/uploads/scale_small/13/135472/1891758-001bulbasaur.png',
          type: 'Pooping',
          ability: 'Flying',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '50',
          attack: '50',
          defense: '50',
          speed: '50',
          sAttack: '50',
          sDefense: '50'
        }
      ]
    }
  }

}

</script>

<style>

</style>
