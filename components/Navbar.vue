<script setup lang="ts">
const rightMenu = [
  {
    name: "Новини",
    href: "news",
  },
  {
    name: "Команда",
    href: "komanda",
  },
];

const centerMenu = [
  {
    name: "Barn 30",
    href: "#Barn-30",
  },
  {
    name: "Nordi 65",
    href: "#Nordi-65",
  },
  {
    name: "Barn 25",
    href: "#Barn-25",
  },
  {
    name: "Nordi 42",
    href: "#Nordi-42",
  },
  {
    name: "Nordi 110",
    href: "#Nordi-110",
  },
  {
    name: "Nordi 81",
    href: "#Nordi-81",
  },
  {
    name: "Nordi 45",
    href: "#Nordi-45",
  },
];
</script>

<template>
  <div class="fixed top-0 z-20 w-screen">
    <div class="flex justify-between items-center pt-5">
      <a class="flex-1 ml-8 lg:ml-12" href="/" aria-label="Module-House Homepage">
        <img class="w-32" src="~/assets/img/house-svg.svg" alt="Module-House Logo">
      </a>

      <div class="grow">
        <ul class="flex-row justify-center flex font-Gotham text-sm">
          <li v-for="item in centerMenu" :key="item.name" class="mr-8 lg:block hidden select-none rounded">
            <a :href="item.href">{{ item.name }}</a>
          </li>
        </ul>
      </div>
      <div class="flex-1">
        <ul class="flex-row justify-end flex font-Gotham text-sm">
          <li v-for="item in rightMenu" :key="item.name" class="mr-8 lg:block hidden select-none">
            <a :href="item.href">{{ item.name }}</a>
          </li>
          <li class="mr-8 select-none" href="contacts"><a href="contacts">Контакти</a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>
li {
  padding: 8px;
  border-radius: 12px;
  transition: all 0.2s ease-in-out;
  cursor: pointer;
}

li:hover {
  background-color: rgba(255, 255, 255, 0.5);
}
</style>
