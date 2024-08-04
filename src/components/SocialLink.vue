<template>
    <a href="link" class='social-link'>{{ name }}</a>
</template>

<script>
export default {
    name: 'SocialLink',
    props: {
        name : {
            type: String,
            required: true
        },
        link: {
            type: String,
            required: true
        } 
    }
}

</script>

<style scoped>
.social-link {
    color: red;
    background-color: var(--color-grey-700);
}
</style>