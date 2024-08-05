<template>
    <div>
        <h1 class="name">{{ Name }}</h1>
        <p class="location">{{ Location }}</p>
        <p>{{ Description }}</p>
    </div>
</template>

<script>
    export default {
        name: 'UserInfo',
        data() {
            return {
                HelloWorld: 'Hello There World',
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
        margin-top: 10px;
    }
    .location {
        color:  var(--color-green);
        margin-bottom: 25px;
        margin-top: 0px;
    }
</style>