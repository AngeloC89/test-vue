<template>
  <div>
    <TitleComponent />
    <JumpoComponent />
  </div>

</template>

<script>
  import TitleComponent from './components/TitleComponent.vue'
  import JumpoComponent from './components/JumpoComponent.vue'

  export default {
    name: 'app',
    components: {
      TitleComponent,
      JumpoComponent,

    },
    data() {
      return {
        // No data properties needed currently
      }
    },
  }
</script>

<style scoped>


</style>