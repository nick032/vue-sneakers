<template>
  <header
    class="flex justify-between items-center px-10 py-8 border-b border-slate-300"
  >
    <div class="flex gap-4">
      <img src="/logo.png" alt="Logo" class="w-10" />
      <div>
        <h2 class="text-xl font-bold uppercase">Vue Sneakers</h2>
        <p class="text-slate-400">Магазин лучших кроссовок</p>
      </div>
    </div>

    <ul class="flex gap-10">
      <li
        class="flex items-center cursor-pointer gap-3 text-gray-500 hover:text-black duration-200 ease-in"
      >
        <img src="/cart.svg" alt="Cart" />
        <b>1205 руб.</b>
      </li>
      <li
        class="flex items-center cursor-pointer gap-3 text-gray-500 hover:text-black duration-200 ease-in"
      >
        <img src="/heart.svg" alt="Cart" />
        <span>Закладки</span>
      </li>
      <li
        class="flex items-center cursor-pointer gap-3 text-gray-500 hover:text-black duration-200 ease-in"
      >
        <img src="/profile.svg" alt="Cart" />
        <span>Профиль</span>
      </li>
    </ul>
  </header>
</template>
