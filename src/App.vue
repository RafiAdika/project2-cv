<template>
  <div id="app" class="container">
    <div class="row py-4">
      <CvDua />
      <CvSatu />
    </div>
  </div>
</template>

<script>
  import CvDua from './components/CvDua.vue'
  import CvSatu  from './components/CvSatu.vue'

  export default {
    name: 'app',
    components: {
      CvDua,
      CvSatu,
    }
  }
</script>
