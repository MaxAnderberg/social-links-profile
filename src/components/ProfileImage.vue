<template>
    <div class="component">
        <h1>{{ title }}</h1>
        <p>{{ message }}</p>
    </div>
</template>

<script>
    export default {
        name: 'ProfileImage',
        data() {
            return {
                title: 'Hello Vue',
                message: 'This is a basic vue component'
            }
        },
    }
</script>

<style scoped>
    .component {
        background-color: aqua;
    }
</style>