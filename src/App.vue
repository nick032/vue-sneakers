<script setup lang="ts">
import Header from "./components/Header.vue";
import "./assets/main.css";
</script>

<template>
  <div class="w-4/5 m-auto bg-white h-screen rounded-xl shadow-xl mt-14">
    <Header />

    <div class="">
      <div
        class="relative m-10 border shadow-md border-slate-100 rounded-4xl p-8 cursor-pointer hover:-translate-y-2 duration-200 ease-in"
      >
        <img class="absolute top-8 left-8" src="/like-1.svg" alt="Like" />
        <img src="/sneakers/sneakers-1.jpg" alt="Sneakers" />
        <p>Мужские кроссовки Nike Blazer Mid Suede</p>
        <div class="flex justify-between">
          <div class="flex flex-col">
            <span class="text-slate-400">Цена:</span>
            <b>12999 руб.</b>
          </div>
          <img src="/plus.svg" alt="Plus" />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
