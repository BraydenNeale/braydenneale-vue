<template>
    <h1>{{content.name}}</h1>
    <h2>{{content.role}}</h2>
    <h2>{{content.location}}</h2>
</template>

<script>
export default {
    data() {
        return {
            content: {
                name: 'Brayden Neale',
                role: 'Consultant, Developer',
                location: "Melbourne, Australia"
            }
        }
    }
}
</script>

<style scoped>
h2 {
    margin: 0;
}

h1 {
    margin: 0;
    color: black;
}
</style>