<template>
    <div class="container">
        <div class="profile-image" :style="{ backgroundImage: `url(${imageUrl})` }">
        </div>
    </div>
</template>

<script>
    export default {
        name: 'ProfileImage',
        data() {
            return {
                imageUrl: require('@/assets/images/avatar-jessica.jpeg')
            }
        },
    }
</script>

<style scoped>
    .container {
        display: flex;
        justify-content: center;
    }
    .profile-image {
        border: 1px;
        border-radius: 50%;
        height: 100px;
        width: 100px;
        background-size: cover;
        background-position: center;
    }
</style>