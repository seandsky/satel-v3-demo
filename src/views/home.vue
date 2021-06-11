<template>
  <div class="home w-full h-full">
    <jt-vue-cesium />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import jtVueCesium from '../components/jt-vue-cesium/index.vue'

export default defineComponent({
  name: 'Home',
  components: { jtVueCesium },
})
</script>
