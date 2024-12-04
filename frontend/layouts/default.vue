<template>
    <div class="">
        <header>
            <nav class="bg-[#007AFF] p-4 flex justify-between items-center text-white">
                <div class="text-3xl font-medium hover:cursor-pointer hover:text-slate-300 duration-300">
                    <NuxtLink to="/">Neural Nexus</NuxtLink>
                </div>
                <ul class="flex gap-3">
                    <li id="SearchButton" class="hover:cursor-pointer hover:text-slate-300 duration-300"><MdiIcon icon="mdiMagnify" /></li>
                    <li id="Menu" class="hover:cursor-pointer hover:text-slate-300 duration-300"><MdiIcon icon="mdiPencilOutline" /></li>
                    <li id="Account" class="hover:cursor-pointer hover:text-slate-300 duration-300"><MdiIcon icon="mdiAccountOutline" /></li>
                </ul>
            </nav>
        </header>
        <slot />
        <div id="popupMenu" class="popup-menu">
            <input type="text" id="searchBar" placeholder="Search...">
            <ul id="menuItems">
                <li>Item 1</li>
                <li>Item 2</li>
                <li>Item 3</li>
            </ul>
         </div>
    </div>
</template>

<script setup>
document.getElementById('menuButton').addEventListener('click', function() {
    const popupMenu = document.getElementById('popupMenu');
    if (popupMenu.style.display === 'block') {
        popupMenu.style.display = 'none';
    } else {
        popupMenu.style.display = 'block';
    }
});

// Optional: Close the popup menu when clicking outside of it
document.addEventListener('click', function(event) {
    const popupMenu = document.getElementById('popupMenu');
    const menuButton = document.getElementById('SearchButton');
    const Menu = document.getElementById('Menu');

    if (!popupMenu.contains(event.target) && !menuButton.contains(event.target) && !Menu.contains(event.target)) {
        popupMenu.style.display = 'none';
    }
});
</script>

<style scoped>
    body {
    font-family: Arial, sans-serif;
}
.popup-menu {
    display: none;
    position: absolute;
    top: 60px;
    left: 20px;
    border: 1px solid #ccc;
    background-color: white;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    width: 200px;
    padding: 10px;
}

.popup-menu input {
    width: 100%;
    padding: 8px;
    margin-bottom: 10px;
    box-sizing: border-box;
}

.popup-menu ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
}

.popup-menu li {
    padding: 8px;
    cursor: pointer;
}

.popup-menu li:hover {
    background-color: #f0f0f0;
}


</style>
