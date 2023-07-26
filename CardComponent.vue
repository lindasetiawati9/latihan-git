<script setup>
import { TheCard } from 'flowbite-vue'
import { Rating } from 'flowbite-vue'
</script>
<template>
    <center>
        <h1 style="color: rgb(243, 93, 118);" class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Beranda</h1>
    </center><hr><br>
    <center>
  <div class="flex flex-row">
    <div class="basis-1/3">
    <the-card variant="image" img-src="https://theheirloompantry.co/wp-content/uploads/2023/04/fruit-sando-japanese-fruit-sandwich-the-heirloom-pantry-04.jpg" img-alt="1">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Sandwich Fruit</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Fruit sando atau fruit sandwich adalah makanan dari Jepang yang bentuknya seperti sandwich atau roti tangkup.
    </p><br>
    <Rating :rating="4">
      <template #besideText>
          <p class="ml-2 text-sm font-medium text-gray-500 dark:text-gray-400">4.95 out of 5</p>
        </template>
    </Rating>
    </the-card>
    </div>

    <div class="basis-1/3">
    <the-card variant="image" img-src="https://goukm.id/wp-content/uploads/2020/12/dessert-kekinian.jpeg" img-alt="2">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">dessert box</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Dessert box merupakan makanan berupa cake dengan beraneka topping yang disajikan dalam sebuah kotak plastik.
    </p><br>
    <Rating :rating="4">
      <template #besideText>
          <p class="ml-2 text-sm font-medium text-gray-500 dark:text-gray-400">4.95 out of 5</p>
        </template>
    </Rating>
    </the-card>
    </div>

    <div class="basis-1/3">
    <the-card variant="image" img-src="https://media.istockphoto.com/id/1271274108/photo/dessert-of-belgian-waffle-and-fresh-berries-isolated-on-white.jpg?s=612x612&w=0&k=20&c=dr1KZtRU4A7ekn5b250Zr5b_T08vm_Iv0mHOwQihCuU=" img-alt="3">
    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">waffle ice cream</h5>
    <p class="font-normal text-gray-700 dark:text-gray-400">
        Waffle selama ini dikenal sebagai dessert yang dihidangkan saat sarapan dengan sirup maple, madu, atau pasta coklat sebagai topping-nya.
    </p><br>
    <Rating :rating="4">
      <template #besideText>
          <p class="ml-2 text-sm font-medium text-gray-500 dark:text-gray-400">4.95 out of 5</p>
        </template>
    </Rating>
    </the-card>
    </div>
  </div>
</center>
</template>
