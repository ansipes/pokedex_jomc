<template>

  <div class="tile is-parent is-vertical">
  <article class="tile is-child notification is-warning">
    <p class="has-text-centered" style="padding-bottom: 10px;">Height</p>
    <p class="title has-text-centered">{{ height }}</p>
  </article>
  <article class="tile is-child notification is-warning">
    <p class="has-text-centered" style="padding-bottom: 10px;">Weight</p>
    <p class="title has-text-centered">{{ weight }}</p>
  </article>
</div>

</template>


<script>

export default {
  props: [
  'height',
  'weight'
  ]
}

</script>
