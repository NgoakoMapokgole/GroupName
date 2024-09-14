<template>
    <div class="w-full">
        <div class="myTitle">SLA/OLA Management</div>
        <div class="mx-auto w-fit">
            <h4 class="text-[#007AFF] text-sm font-medium p-4 uppercase">BREAK DOWN DETAILS ON THE ALARMS SYSTEMS IN DATA FORMAT</h4>
            <div class="flex flex-row  gap-8 p-4">
                <div class="myCard">SLA DATA DETAILS PER CUSTOMER</div>
                <div class="myCard">OLA DATA DETAILS PER CUSTOMER</div>
                <div class="myCard">ALARM OCCURRENCES AND ANALYTICS</div>
            </div>

            <div class="flex flex-row  gap-8 p-4">
                <div class="myCard">Fault detection</div>
                <div class="myCard">SLA/OLA  REGULATIONS</div>
                <div class="myCard">Manual edit</div>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped>
    .myTitle {
        @apply text-[#007AFF] text-lg font-medium p-4 uppercase
    }

    .myCard {
        @apply border border-gray-300 rounded-md p-6 text-[#007AFF] 
        uppercase font-medium text-sm 
        hover:cursor-pointer hover:text-white hover:bg-[#007AFF] hover:border-0 duration-500
    }
</style>