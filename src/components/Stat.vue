<template>

  <div class="tile is-parent">
      <article class="tile is-child notification is-danger">
        <div class="content">
          <div class="columns">
            <div class="column">
              <p>Hit Points</p>
              <progress class="progress is-success" :value="hitPoints" max="255"></progress>
              <p>Attack</p>
              <progress class="progress is-warning" :value="attack" max="255"></progress>
              <p>Defense</p>
              <progress class="progress is-info" :value="defense" max="255"></progress>
            </div>
            <div class="column">
              <p>Speed</p>
              <progress class="progress is-primary" :value="speed" max="255"></progress>
              <p>Special Attack</p>
              <progress class="progress is-warning" :value="sAttack" max="255"></progress>
              <p>Special Defense</p>
              <progress class="progress is-info" :value="sDefense" max="255"></progress>
            </div>
          </div>
        </div>
        <em>*Max of 255</em>
      </article>
    </div>

</template>


<script>

export default {
  props: [
  'hitPoints',
  'attack',
  'defense',
  'speed',
  'sAttack',
  'sDefense'
  ]
}


</script>
