<template>
    <li>
        <base-card>
            <a :href="url">
                <h3>{{title}}</h3>
            </a>
        </base-card>
    </li>
</template>

<script>
export default {
    props: ['id', 'title', 'url'],
}
</script>

<style scoped>
    a,h3 {
        text-decoration: none;
        color: black;
    }

    li {
        margin: auto;
    }
</style>