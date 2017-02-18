<template>

  <div class="tile is-parent is-vertical">
        <article class="tile is-child notification is-primary">
          <p class="has-text-centered" style="padding-bottom: 10px;">Type</p>
          <p class="title has-text-centered">{{ type }}</p>
        </article>
        <article class="tile is-child notification is-info">
        <p class="has-text-centered" style="padding-bottom: 10px;">Ability</p>
        <p class="title has-text-centered">{{ ability }}</p>
        </article>
      </div>

</template>

<script>

export default {
  props: [
  'type',
  'ability'
  ]
}


</script>
