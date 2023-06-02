<template>
  <div>
   <div class="flex justify-between items-center   bg-yellow-400 py-2">
    <a class="ml-8 lg:ml-12" href="/" aria-label="Module-House Homepage">
      <img class="w-32 hover:opacity-75" src="~/assets/img/house-svg.svg" alt="Module-House Logo">
    </a>
    <a class="flex items-center mr-16 lg:ml-12 hover:opacity-75" href="/" aria-label="Module-House Homepage">
      <img class="w-8" src="~/assets/img/ico_phone.svg" alt="Phone Icon">
      <h1 class="text-2xl font-bold ml-2">(096)057-74-85</h1>
    </a>
  </div>
    <div class="container mx-auto  pb-8 px-8 pt-28">
      <h1 class="text-2xl font-bold mb-4">Контакти</h1>

      <div class="mb-8">
        <h2 class="text-xl font-bold mb-2">Адреса:</h2>
        <p>Київ, с. Хотів, вул. Долина 11</p>
      </div>

      <div class="mb-8">
        <h2 class="text-xl font-bold mb-2">Номер телефону:</h2>
        <p>(096) 0577485</p>
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
      <div>
        <h2 class="text-xl mt-20 font-bold mb-2">Опис:</h2>
        <p class="text-xl">
          Наша компанія з виробництва модульних будинків завжди рада допомогти вам у створенні вашого ідеального житла.
          Для зв'язку з нами можна використовувати номер телефону або соціальні мережі. Наша команда експертів побудує
          для вас унікальний модульний будинок, який буде відповідати всім вашим вимогам та бажанням. Ми гарантуємо
          високу якість продукції та відмінний сервіс після продажу. Зв'яжіться з нами сьогодні, щоб розпочати роботу
          над вашим майбутнім будинком.
        </p>
      </div>
    </div>
    <div class="fixed bottom-0 mt-3 left-0 right-0 z-10 ">
      <Footer />
    </div>
  </div>
</template>

<style>
.fixed {
  position: fixed;
}

</style>