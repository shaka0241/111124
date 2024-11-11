<script>
import Alberto from './components/Alberto.vue'
import Diego from './components/Diego.vue'
import Horario from './components/Horario.vue'
export default {
  name: 'App',
  components: {
    Alberto,
    Diego,
    Horario
  }
}
</script>

<template>
  <Diego />
  <Horario />
</template>

<style scoped>
</style>
