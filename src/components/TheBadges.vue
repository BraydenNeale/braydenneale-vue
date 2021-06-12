<template>
    <ul>
        <li v-for="badge in badges" :key="badge.id">
            <img :src="badge.icon" :alt="badge.title">
        </li>
    </ul>
</template>

<script>
export default {
    data() {
        return {
            badges: [
                {
                    id: 'aws-solutions-architect-associate',
                    title: 'AWS Solutions Architect - Associate',
                    icon: require('@/assets/img/AWS-SolArchitect-Associate-2020.png')
                },
                {
                    id: 'kubernetes-application-developer',
                    title: 'Kubernetes Application Developer',
                    icon: require('@/assets/img/ckad_from_cncfsite.png')
                },
                {
                    id: 'dynatrace-professional',
                    title: 'Dynatrace Professional',
                    icon: require('@/assets/img/dynatrace_professional_badge.png')
                }
            ]
        }
    }
}
</script>

<style scoped>

</style>