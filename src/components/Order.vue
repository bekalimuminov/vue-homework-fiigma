<template>
  <div class="w-[400px] px-[40px] border p-[30px] font-sans">
    <h2 class="text-[18px] font-bold tracking-tight mb-[30px]">ORDER SUMMARY</h2>

    <div class="space-y-[15px]">
      <div class="flex justify-between items-center">
        <p class="text-[16px] font-[500]">Subtotal</p>
        <p class="text-[16px] font-[500]">$180</p>
      </div>

      <div class="flex justify-between items-center">
        <p class="text-[16px] font-[500]">Shipping</p>
        <p class="text-[16px] font-[500]">$10</p>
      </div>
    </div>

    <div class="border-t border-[#D1D1D1] mt-[25px] mb-[25px]"></div>

    <div class="flex justify-between items-center mb-[40px]">
      <div class="flex items-baseline gap-[5px]">
        <p class="text-[20px] font-bold">TOTAL</p>
        <span class="text-[12px] text-[#8A8A8A]">(TAX INCL.)</span>
      </div>
      <p class="text-[22px] font-bold">{{priceTotal}}</p>
    </div>

    <div class="flex items-center gap-[10px] mb-[25px]">
      <input type="checkbox" class="w-[20px] h-[20px] border border-[#8A8A8A]">
      <label for="terms" class="text-[13px] text-[#4A4A4A] leading-tight">
        I agree to the Terms and Conditions
      </label>
    </div>

    <button class="w-full bg-[#D9D9D9] py-[15px] text-[16px] font-bold uppercase cursor-pointer hover:bg-black hover:text-white">Continue</button>
  </div>
</template>

<script setup>
import {ref} from "vue";

let priceTotal = ref(0)
</script>