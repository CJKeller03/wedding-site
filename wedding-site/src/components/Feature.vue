<script lang="ts">
  export default {
    props: {
      imageSrc: String
    }
  }
</script>

<template>
  <div class="col-4 col-6-medium col-12-small">
      <section>
        <a href="#" class="image featured"><img :src="imageSrc" alt="" /></a>
        <header>
          <h3><slot name="header"></slot></h3>
        </header>
        <p><slot name="content"></slot></p>
      </section>
  </div>
</template>


