<template>
    <div class="job-list">
        <div v-for="job of jobs" :key="job.job_title" class="jobs-container" > 
            <SingleJob :job=job />
        </div>
    </div>
</template>
<script>
import SingleJob from './SingleJob.vue'

export default {
    name: 'JobList',
    props:{
        jobs: Array
    },
    components:{
        SingleJob
    }
    
}
</script>
<style scoped>
    .job-list{
        display: flex;
        flex-wrap: wrap;
        gap: 1rem;
        padding: 1rem;
        width: 65%;
        margin: auto;
    }
    .jobs-container{
       width:100%;
    }
</style>
