<template>
  <main class="main">
    <ProfileImage />
    <UserInfo/>
    <div class='links-container'>
      <SocialLink link="https://Github.com" name="GitHub"/>
      <SocialLink link="https://frontendmentor.io/" name="Frontend Mentor"/>
      <SocialLink link="https://linkedin.com" name="LinkedIn"/>
      <SocialLink link="https://twitter.com" name="Twitter"/>
      <SocialLink link="https://instagram.com" name="Instagram"/>
    </div>
  </main>
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
  display: flex;
  justify-content: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #FFFFFF;
}
.links-container {
  display: flex;
  flex-direction: column;
  gap: 12px;

}
.main {
  display: flex;
  flex-direction: column;
  margin-top: 60px;
  max-width: 40%;
  justify-content: center;
  justify-items: center;
  background-color: var(--color-grey-800);
  padding: 40px;
  border-radius: 8px;
}
</style>
