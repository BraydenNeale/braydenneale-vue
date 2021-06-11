<template>
    <header v-for="link in links" :key="link.id">
        <a :href="link.link">{{link.title}}</a>
    </header>
</template>

<script>
export default {
    data() {
        return {
            links: [
                {
                    id: 'github',
                    title: 'Github',
                    link: 'https://github.com/BraydenNeale'
                },
                {
                    id: 'linkedin',
                    title: 'LinkedIn',
                    link: 'https://www.linkedin.com/in/brayden-neale-135254102'
                }
            ]
        }
    }
}
</script>

<style scoped>

</style>
