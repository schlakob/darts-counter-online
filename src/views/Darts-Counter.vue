<template>
  <div class="home">
    <Dartboard msg="Turn up"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Dartboard from '@/components/Dartboard.vue'

export default {
  name: 'Home',
  components: {
    Dartboard
  }
}
</script>