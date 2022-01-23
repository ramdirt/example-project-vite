<script setup>
import { computed } from 'vue'
import { useStore } from 'vuex'

const store = useStore()
const user = ''
const stack = computed(() => {
    return store.state.stack
})
</script>

<template lang="pug">
router-view.p-24
</template>

<style lang="scss">

</style>
