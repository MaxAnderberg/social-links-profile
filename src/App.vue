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
  align-items: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #FFFFFF;
  height: 100vh;
}
.links-container {
  display: flex;
  flex-direction: column;
  gap: 16px;
}
.main {
  display: flex;
  flex-direction: column;
    @media (max-width: 768px) {
    min-width: 225px;
    /* margin-bottom: 60px; */
  }
  min-width: 300px;  
  background-color: var(--color-grey-800);
  padding: 40px;
  border-radius: 8px;
}
</style>
