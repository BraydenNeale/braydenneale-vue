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

</style>