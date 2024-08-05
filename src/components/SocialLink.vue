<template>
    <a :href="link" class='social-link'>{{ name }}</a>
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
    color: white;
    font-weight: bold;
    padding: 8px;
    background-color: var(--color-grey-700);
    border: 1px;
    border-radius: 8px;
    text-decoration: none;
}
.social-link:hover {
    background-color: var(--color-green);
    color: black;
}
</style>