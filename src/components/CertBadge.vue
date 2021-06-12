<template>
    <li>
        <img :src="icon" :alt="title">
    </li>
</template>

<script>
export default {
    props: ['icon', 'title']
}
</script>

<style scoped>
li {
    display: inline-block;
    max-width: 40rem;
}

img {
    max-width: 12rem;
}
</style>