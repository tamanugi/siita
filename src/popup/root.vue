<template lang="pug">
  v-app
    div
      v-btn(color="info" @click="onClick()") Success

</template>
<script>
  export default {
    data: () => ({
      text: ''
    }),
    computed: { },
    created () { },
    mounted () { },
    methods: {
      onClick () {
        this.text = 'CLICKED!!!!'
      }
    }
  }
</script>

<style lang="stylus">
</style>
