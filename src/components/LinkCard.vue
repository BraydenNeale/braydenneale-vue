<template>
    <li>
        <h3>
            <a :href="url">{{title}}</a>
        </h3>
    </li>
</template>

<script>
export default {
    props: ['id', 'title', 'url'],
}
</script>

<style scoped>

</style>