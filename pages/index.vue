<template>
  <Tutorial />
</template>

<script lang="ts">
import { defineComponent } from '@vue/composition-api'
import { useRoute } from '@nuxtjs/composition-api'

export default defineComponent({
  setup() {
    const route = useRoute()
    console.log(route.value)
  },
})
</script>
