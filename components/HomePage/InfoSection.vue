<template>
    <section class="mt-5">
        <div class="text-center flex px-5 justify-between items-center">
            <div v-for="(stat, index) in stats" :key="index" class="flex flex-col gap-1 items-center">
                <p>{{stat.value}}</p>
                <p>{{stat.label}}</p>
            </div>
        </div>
        <div class="mt-5 flex gap-3">
            <a href="/pdf/Mohamed Elshimi - Front-end Web Developer.pdf" download="Mohamed Elshimi - Front-end Web Developer.pdf" class="btn w-8/12 bg-blue-500 hover:bg-blue-600">DownLoad CV <Icon icon="hugeicons:download-05" width="24" height="24" /></a>
            <a href="https://www.linkedin.com/in/mohamedelshimi/" target="_blank" class="btn w-2/12 bg-slate-200 text-black"><Icon icon="ri:linkedin-fill" width="24" height="24" /></a>
            <a href="mailto:mohamed.a.elshimi@gmail.com" class="btn w-2/12 bg-slate-200 text-black"><Icon icon="mdi:email" width="24" height="24" /></a>
        </div>
    </section>
</template>

<script setup>
const stats = [
    { value: '2 +', label: 'Years of Experience' },
    { value: '10 +', label: 'Projects Completed' },
    { value: '5 +', label: 'Happy Clients' }
];
</script>

<style scoped>

</style>