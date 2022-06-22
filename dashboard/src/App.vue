<template>
  <modal-factory/>
  <router-view/>
</template>

<script>
import ModalFactory from './components/ModalFactory/indexComponent.vue'

export default {
  components: { ModalFactory }
}
</script>
