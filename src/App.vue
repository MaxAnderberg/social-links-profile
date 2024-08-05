<template>
  <ProfileImage />
  <UserInfo/>
  <div class='links-container'>
    <SocialLink link="https://google.se" name="Google"/>
    <SocialLink link="https://google.se" name="Google"/>
    <SocialLink link="https://google.se" name="Google"/>
    <SocialLink link="https://google.se" name="Google"/>
  </div>
</template>

<script>
import ProfileImage from './components/ProfileImage'
import SocialLink from './components/SocialLink.vue';
import UserInfo from './components/UserInfo'

export default {
  name: 'App',
  components: {
    ProfileImage,
    UserInfo,
    SocialLink,
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
.links-container {
  display: flex;
  flex-direction: column;
  gap: 12px;
}
</style>
