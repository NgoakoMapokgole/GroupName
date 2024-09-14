<template>
    <div class="">
        <header>
            <nav class="bg-[#007AFF] p-4 flex justify-between items-center text-white">
                <div class="text-3xl font-medium hover:cursor-pointer hover:text-slate-300 duration-300">
                    <NuxtLink to="/">Neural Nexus</NuxtLink>
                </div>
                <ul class="flex gap-3">
                    <li class="hover:cursor-pointer hover:text-slate-300 duration-300"><MdiIcon icon="mdiCog" /></li>
                    <li class="hover:cursor-pointer hover:text-slate-300 duration-300"><MdiIcon icon="mdiKeyboard" /></li>
                    <li class="hover:cursor-pointer hover:text-red-500 duration-300"><MdiIcon icon="mdiCloseCircleOutline" /></li>
                </ul>
            </nav>
        </header>
        <slot />
    </div>
</template>

<script setup>

</script>

<style scoped>

</style>