<template>
</template>

<script>
export default {
  name: 'RuoYiDoc',
  data() {
    return {
      url: 'https://github.com/oddfar/campus-imaotai/wiki/'
    }
  },
  methods: {
    goto() {
      window.open(this.url)
    }
  }
}
</script>
