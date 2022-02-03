<template>
  <div id="app">
    <v-header />
    <router-view/>
    <v-footer />
  </div>
</template>

<script>
import VHeader from '@/components/v-header'
import VFooter from '@/components/v-footer'

export default {
  name: 'App',
  components: {
    VHeader,
    VFooter,
  },
}
</script>

<style lang="sass">

*
  margin: 0
  padding: 0

a
  text-decoration: none
  font-family: Montserrat, sans-serif

li
  list-style-type: none

body
  font-family: Montserrat, sans-serif
</style>
