<template>
  <div>
    <a-scene background="color: #ECECEC">
      <a-assets>
        <a-asset-item id="cityModel" src="../assets/models/01.glb"></a-asset-item>
      </a-assets>
      <a-entity gltf-model="#cityModel" position="-1 0.5 -3"></a-entity>
    </a-scene>
  </div>
</template>

<script>
export default {
  name: 'test',
  methods: {
    test() {

    }
  }
}
</script>
<style scoped>

</style>