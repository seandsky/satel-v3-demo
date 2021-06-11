<template>
  <div
    ref="jtVueCesium"
    class="jt-vue-cesium"
    style="height: 100vh; width: 100vw"
  ></div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import * as Cesium from 'cesium'
import 'cesium/Build/Cesium/Widgets/widgets.css'

export default defineComponent({
  name: 'jt-vue-cesium',
  mounted() {
    const container = this.$refs.jtVueCesium as HTMLElement
    new Cesium.Viewer(container)
  },
})
</script>
