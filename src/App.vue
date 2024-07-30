<template>
  <ProfileImage />
</template>

<script>
import ProfileImage from './components/ProfileImage'

export default {
  name: 'App',
  components: {
    ProfileImage
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #FFFFFF;
  margin-top: 60px;
}
</style>
