<template>
    <div>
        <h1 class="name">{{ Name }}</h1>
        <p class="location">{{ Location }}</p>
        <p class="description">{{ Description }}</p>
    </div>
</template>

<script>
    export default {
        name: 'UserInfo',
        data() {
            return {
                Name: 'Jessica Randall',
                Location: 'London, United Kingdom',
                Description: `"Front-end developer and avid reader"`
            }
        }
    }
</script>

<style scoped>
    .name {
        font-weight: bold;
        margin-bottom: 8px;
        margin-top: 40px;
        font-size: 24px;
    }
    .location {
        color:  var(--color-green);
        margin-bottom: 25px;
        font-size: 14px;
        margin-top: 0px;
        font-weight: bold;
    }
    .description {
        font-size: 14px;
        margin-bottom: 24px;
    }
</style> 