<template>
  <div>
    <NavbarHome />
    <Nuxt />
  </div>
</template>

<script>
  import NavbarHome from '~/components/NavbarHome.vue'

  export default {
    components: {
      NavbarHome
    }
  }
</script>