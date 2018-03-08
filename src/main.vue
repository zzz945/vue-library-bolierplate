<template lang="pug">
  .library-example {{content}}
</template>

<script>
  export default {
    name: 'library-example',

		components: {
		},

    props: {
    },

    data () {
      return {
        content: "Hello vue library boilerplate!"
      }
    },

		watch: {
    },

    computed: {
    },

    methods: {
    },

    mounted() {
    },
  }
</script>

<style lang="stylus" scoped>
  .library-example
    font-size: 20px
</style>
