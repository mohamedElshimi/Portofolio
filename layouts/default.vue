<template>
    <main class="flex flex-col w-full min-h-screen justify-between">
        <NavBar></NavBar>
        <div class="bg-black text-gray-200 min-h-[calc(100vh-132px)] p-5">
            <div class="lg:w-4/12 md:w-8/12 w-10/12 mx-auto">
                <slot></slot>
            </div>
        </div>
        <Footer></Footer>
    </main>
</template>

<script setup>

</script>

<style scoped>

</style>