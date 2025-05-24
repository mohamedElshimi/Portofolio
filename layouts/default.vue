<template>
    <main class="flex flex-col min-h-screen justify-between">
        <NavBar></NavBar>
        <div class="bg-black text-gray-200 min-h-[calc(100vh-132px)] p-5">
            <div class="w-4/12 mx-auto">
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