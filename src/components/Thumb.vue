<template>

  <div class="tile is-parent is-vertical ">
  <article class="tile is-child notification">
    <p class="title has-text-centered">{{ name }}</p>
      <figure class="image">
        <img :src="image">
      </figure>
  </article>
</div>

</template>

<script>

export default {
  props: [
  'name',
  'image'
  ]
}

</script>
