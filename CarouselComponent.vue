<script setup>
import { Carousel } from 'flowbite-vue'

const props = defineProps({
    pictures: {
        type: Array,
        default() {
            return [
                {
                    'src': 'https://caliclecups.com/cdn/shop/articles/melting_ice_cream.jpg?v=1647644764',
                    'alt': 'Picture 1',
                }
            ]
        },
    },
})

</script>
<template>
    <Carousel :pictures="pictures" :indicators="false"></Carousel>
  </template>