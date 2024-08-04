<template>
    <div>
        <h1>{{ Name }}</h1>
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
                Description: 'Front-end developer and avid reader'
            }
        }
    }
</script>

<style scoped>
    .name {
        font-weight: bold;
    }
    .location {
        color:  var(--color-green)
    }
</style>