<template>
  <section class="w-[1000px] m-auto">
    <div class="flex items-center gap-[62px]">

      <div class="flex">
        <div class="w-[265px]">
          <img src="../assents/person.png" alt="img">
          <p class="font-[500] text-[12px] text-[#000000A8] mt-[10px] mb-[5px]">Cotton T Shirt</p>
          <div class="flex items-center justify-between mb-[20px]">
            <p class="font-[500] text-[14px]">Full Sleeve Zipper</p>
            <p class="font-[500] text-[14px]">${{ price1 * count1 }}</p>
          </div>
        </div>
        <div class="w-[25px] ml-[10px]">
          <img class="ml-[6px]" src="../assents/cardsExit.png" alt="img">
          <p class="font-[500] text-[14px] ml-[6px] mt-[68px] mb-[16px]">L</p>
          <div class="bg-black w-[25px] h-[25px]"></div>

          <div class="border border-[#8A8A8A] mt-[15px] mb-[15px] select-none">
            <p @click="count1 < 10 ? count1++ : null" class="text-center cursor-pointer hover:bg-gray-200">+</p>
            <div class="bg-[#8A8A8A] w-[25px] border-[1px]"></div>

            <p class="text-center">{{ count1 }}</p>

            <div class="bg-[#8A8A8A] w-[25px] border-[1px]"></div>
            <p @click="count1 > 1 ? count1-- : null" class="text-center cursor-pointer hover:bg-gray-200">-</p>
          </div>

          <img src="../assents/reflesh.svg" alt="img">
        </div>
      </div>

      <div class="flex">
        <div class="w-[265px]">
          <img src="../assents/black-person.png" alt="img">
          <p class="font-[500] text-[12px] text-[#000000A8] mt-[10px] mb-[5px]">Cotton T Shirt</p>
          <div class="flex items-center justify-between">
            <p class="font-[500] text-[14px]">Full Sleeve Zipper</p>
            <p class="font-[500] text-[14px]">${{ price2 * count2 }}</p>
          </div>
        </div>
        <div class="w-[25px] ml-[10px]">
          <img class="ml-[6px]" src="../assents/cardsExit.png" alt="img">
          <p class="font-[500] text-[14px] ml-[6px] mt-[68px] mb-[16px]">L</p>
          <div class="bg-black w-[25px] h-[25px]"></div>

          <div class="border border-[#8A8A8A] mt-[15px] mb-[15px] select-none">
            <p @click="count2 < 10 ? count2++ : null" class="text-center cursor-pointer hover:bg-gray-200">+</p>
            <div class="bg-[#8A8A8A] w-[25px] border-[1px]"></div>

            <p class="text-center">{{ count2 }}</p>

            <div class="bg-[#8A8A8A] w-[25px] border-[1px]"></div>
            <p @click="count2 > 1 ? count2-- : null" class="text-center cursor-pointer hover:bg-gray-200">-</p>
          </div>

          <img src="../assents/reflesh.svg" alt="img">
        </div>
      </div>

    </div>
    <div class="bg-[#C9C9C9] w-[712px] border-[1px] mt-[15px]"></div>
  </section>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const price1 = ref(99);
const count1 = ref(1);

const price2 = ref(99);
const count2 = ref(1);
</script>