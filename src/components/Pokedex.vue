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
        { name: 'Bulbasaur',
          image: 'http://ansipes.net/1-01.png',
          type: 'Grass',
          ability: 'Overgrow',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '50',
          attack: '45',
          defense: '55',
          speed: '35',
          sAttack: '60',
          sDefense: '75'
        },
        { name: 'Ivysaur',
          image: 'http://ansipes.net/2-01.png',
          type: 'Grass',
          ability: 'Overgrow',
          height: '1.5 m',
          weight: '17.5 kg',
          hitPoints: '75',
          attack: '55',
          defense: '65',
          speed: '45',
          sAttack: '75',
          sDefense: '90'
        },
        { name: 'Venusaur',
          image: 'http://ansipes.net/3-01.png',
          type: 'Grass',
          ability: 'Overgrow',
          height: '2.1 m',
          weight: '50.5 kg',
          hitPoints: '100',
          attack: '52',
          defense: '80',
          speed: '50',
          sAttack: '90',
          sDefense: '50'
        },
        { name: 'Charmander',
          image: 'http://ansipes.net/4-01.png',
          type: 'Fire',
          ability: 'Blaze',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '50',
          attack: '45',
          defense: '55',
          speed: '35',
          sAttack: '60',
          sDefense: '75'
        },
        { name: 'Charmeleon',
          image: 'http://ansipes.net/5-01.png',
          type: 'Fire',
          ability: 'Blaze',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '75',
          attack: '55',
          defense: '65',
          speed: '45',
          sAttack: '75',
          sDefense: '90'
        },
        { name: 'Charizard',
          image: 'http://ansipes.net/6-01.png',
          type: 'Fire',
          ability: 'Blaze',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '100',
          attack: '52',
          defense: '80',
          speed: '50',
          sAttack: '90',
          sDefense: '50'
        },
        { name: 'Squirtle',
          image: 'http://ansipes.net/7-01.png',
          type: 'Water',
          ability: 'Torrent',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '50',
          attack: '45',
          defense: '55',
          speed: '35',
          sAttack: '60',
          sDefense: '75'
        },
        { name: 'Wartortle',
          image: 'http://ansipes.net/8-01.png',
          type: 'Water',
          ability: 'Torrent',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '75',
          attack: '55',
          defense: '65',
          speed: '45',
          sAttack: '75',
          sDefense: '90'
        },
        { name: 'Blastoise',
          image: 'http://ansipes.net/9-01.png',
          type: 'Water',
          ability: 'Torrent',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '100',
          attack: '52',
          defense: '80',
          speed: '50',
          sAttack: '90',
          sDefense: '50'
        },
        { name: 'Caterpie',
          image: 'http://ansipes.net/10-01.png',
          type: 'Bug',
          ability: 'Shield',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '50',
          attack: '45',
          defense: '55',
          speed: '35',
          sAttack: '60',
          sDefense: '75'
        },
        { name: 'Metapod',
          image: 'http://ansipes.net/11-01.png',
          type: 'Bug',
          ability: 'Shed',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '75',
          attack: '55',
          defense: '65',
          speed: '45',
          sAttack: '75',
          sDefense: '90'
        },
        { name: 'Butterfree',
          image: 'http://ansipes.net/12-01.png',
          type: 'Bug',
          ability: 'Tinted',
          height: '0.7 m',
          weight: '7.9 kg',
          hitPoints: '100',
          attack: '52',
          defense: '80',
          speed: '50',
          sAttack: '90',
          sDefense: '50'
        }
      ]
    }
  }

}

</script>

<style>

</style>
