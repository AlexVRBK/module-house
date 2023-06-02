<script setup lang="ts">
useHead(() => ({
  title: "Module House",
  meta: [
    {
      name: "description",
      content: "МОДУЛЬНІ БУДИНКИ ПІД КЛЮЧ - ОрганікБУД",
    },
  ],
  htmlAttrs: {
    lang: "en",
  },
}));

var products = [
  { Title: "Barn 30", Subtitle: "Замовити огляд", Background: "3", Href: "#" },
  { Title: "Nordi 65", Subtitle: "Замовити огляд", Background: "6_1", Href: "#" },
  { Title: "Barn 25", Subtitle: "Замовити огляд", Background: "2", Href: "#" },
  { Title: "Nordi 42", Subtitle: "Замовити огляд", Background: "7", Href: "#" },
  { Title: "Nordi 110", Subtitle: "Замовити огляд", Background: "8", Href: "#" },
  { Title: "Nordi 81", Subtitle: "Замовити огляд", Background: "5.1_1", Href: "#" },
  { Title: "Nordi 45", Subtitle: "Замовити огляд", Background: "1", Href: "#" },
];
</script>

<template>
  <div>
    <Navbar />
    <div id="Products" class="snap-y snap-mandatory h-screen w-screen overflow-y-scroll scroll-smooth">
      <LazyProduct v-for="product in products" :key="product.Title" :Title="product.Title" :Subtitle="product.Subtitle" :Background="product.Background" :Href="product.Href" />
    </div>
  </div>
</template>

<style scoped>
::-webkit-scrollbar {
  width: 0;
}
</style>