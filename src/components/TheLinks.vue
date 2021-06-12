<template>
<ul>
    <link-card v-for="link in links"
        :key="link.id"
        :title="link.title"
        :url="link.url"
    ></link-card>
</ul>
</template>

<script>
import LinkCard from './LinkCard.vue'
export default {
    components: {
        LinkCard,
    },
    data() {
        return {
            links: [
                {
                    id: 'github',
                    title: 'Github',
                    url: 'https://github.com/BraydenNeale'
                },
                {
                    id: 'linkedin',
                    title: 'LinkedIn',
                    url: 'https://www.linkedin.com/in/brayden-neale-135254102'
                },
                {
                    id: 'dynatrace-plugins-youtube',
                    title: 'Webinar: Extending Dynatrace - Custom Plugins',
                    url: 'https://www.youtube.com/watch?v=GafO-GtYD5g'
                },
                {
                    id: 'dynatrace-snmp-github',
                    title: 'Project: Dynatrace SNMP Monitoring',
                    url: 'https://github.com/BraydenNeale/DT-SNMP'
                },
                {
                    id: 'tutorial-academy',
                    title: 'Project: Tutorial Academy Rails App',
                    url: 'https://tutorial-academy.herokuapp.com/'
                }
            ]
        }
    }
}
</script>

<style scoped>
ul {
  list-style: none;
  margin: 0;
  padding: 0;
  margin: auto;
}
</style>
