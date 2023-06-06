<template>
  <div>
   <div class="flex justify-between items-center  bg-yellow-400 py-2">
    <a class="ml-8 lg:ml-12" href="/" aria-label="Module-House Homepage">
      <img class="w-32 hover:opacity-75" src="~/assets/img/house-svg.svg" alt="Module-House Logo">
    </a>
    <a class="flex items-center mr-16 lg:ml-12 hover:opacity-75" href="/" aria-label="Module-House Homepage">
      <img class="w-8" src="~/assets/img/ico_phone.svg" alt="Phone Icon">
      <h1 class="text-2xl font-bold ml-2">+38 (096) 057-74-85</h1>
    </a>
  </div>
    <div class="container mx-auto pb-8 px-8 pt-14 flex">
  <div class="w-1/2">
    <h1 class="text-2xl font-bold mb-4">Контакти</h1>

    <div class="mb-8">
      <h2 class="text-xl font-bold mb-2">Адреса:</h2>
      <p>Київ, с. Хотів, вул. Долина 11</p>
    </div>

    <div class="mb-8">
      <h2 class="text-xl font-bold mb-2">Номер телефону:</h2>
      <p>+38 (096) 0577485</p>
    </div>

    <div class="mb-8 mt-20">
      <h2 class="text-xl font-bold mb-2">Графік роботи:</h2>
      <p>Понеділок-П'ятниця: 9:00-18:00</p>
      <p>Неділя: Вихідний</p>
    </div>

    <div class="mb-8 mt-20">
      <h2 class="text-xl font-bold mb-6">Соціальні мережі:</h2>
      <ul class="flex space-x-4 hover:cursor-pointer">
        <li class="hover:opacity-75">
          <img class="w-12 mr-4" src="~/assets/img/insta.svg" alt="#">
        </li>
        <li class="hover:opacity-75">
          <img class="w-12 mr-4" src="~/assets/img/facebook.svg" alt="#">
        </li>
        <li class="hover:opacity-75">
          <img class="w-12" src="~/assets/img/youtube.svg" alt="#">
        </li>
      </ul>
    </div>
  </div>

  <div class="w-1/2">
      <iframe id="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2444.4696210906177!2d30.576550615970737!3d50.37011857947014!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x40d4d0f0ff9d4567%3A0x920d5422a876da8!2z0JrQvtC80L_RgNC-0LXQvNC90YvQuSDQv9C40YbQsCDQm9C10YHQutCw0Y8sIDEzLCDQktCw0L3QvtC_0YDQv9C-0LLRgdC60LDRjyDQvtCx0LvQsNGB0YLRjCwg0JTQvdC40LPQsNGPINC-0LHQu9Cw0YLRg3EsINCa0L7QstCw0LfQsCDQktC40L3RgdGC0LDQvSwg0J_QvtC70L7QttC00YAsINCU0LjRjw!5e0!3m2!1sen!2sua!4v1669017719870!5m2!1sen!2sua" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
  </div>

    </div>
    
  </div>
</template>

<style>
.fixed {
  position: fixed;
}

</style>