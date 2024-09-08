<template>
    <div class="">
        <header>
            <nav class="bg-[#007AFF] p-4 flex justify-between items-center text-white">
                <div class="text-3xl font-medium">
                    <NuxtLink to="/">Neural Nexus</NuxtLink>
                </div>
                <ul class="flex gap-2">
                    <li class="text">1</li>
                    <li class="text">2</li>
                    <li class="text">3</li>
                    <li class="text">4</li>
                    <li class="text">5</li>
                </ul>
            </nav>
        </header>
        <div class="text-lg font-semibold text-left p-4">Faults</div>
        <slot />
    </div>
</template>

<script setup>

</script>

<style scoped>

</style>