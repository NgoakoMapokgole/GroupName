<template>
    <div class="mx-auto my-32 max-w-80">
        <div class="relative my-6 w-full">
            <input type="text" id="employeeId" 
                class="border-b-2 py-1 w-full focus:outline-none focus:border-[#007AFF] focus:border-b-2 transition-colors duration-500 peer" autocomplete="off">
            <label for="employeeId" 
                class="absolute left-0 top-1 text-gray-600 cursor-text peer-focus:text-xs peer-focus:-top-4 peer-focus:text-[#007AFF] transition-all">Employee ID</label>
  </div>

  <div class="relative my-6 w-full">
    <input type="password" id="password" 
        class="border-b-2 py-1 w-full focus:outline-none focus:border-[#007AFF] focus:border-b-2 transition-colors duration-500 peer" autocomplete="off">
    <label for="password" 
        class="absolute left-0 top-1 text-gray-600 cursor-text peer-focus:text-xs peer-focus:-top-4 peer-focus:text-[#007AFF] transition-all">Password</label>
  </div>

  <button class="my-3 px-4 py-2 w-full bg-[#007AFF] text-white rounded-full">Login</button>
    </div>
</template>

<script setup>
    definePageMeta({
        layout: 'login'
    })

</script>

<style scoped>

</style>