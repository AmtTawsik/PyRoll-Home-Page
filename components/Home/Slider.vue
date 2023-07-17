<template>
    <Carousel>
        <Slide v-for="(image, index) in images" :key="index">
            <div class="carousel__item">
                <img :src="image" alt="Carousel Image" />
            </div>
        </Slide>

        <template #addons>
            <Navigation />
        </template>
    </Carousel>
</template>
  
<script>
import { defineComponent } from 'vue'
import { Carousel, Navigation, Pagination, Slide } from 'vue3-carousel'

import 'vue3-carousel/dist/carousel.css'

const slides = [

]

export default defineComponent({
    name: 'Basic',
    components: {
        Carousel,
        Slide,
        Pagination,
        Navigation,
    },
    data() {
        return {
            images: [
                'https://i.ibb.co/v1YLJ82/s1.png',
                'https://i.ibb.co/v1YLJ82/s1.png',
                'https://i.ibb.co/v1YLJ82/s1.png',
                'https://i.ibb.co/v1YLJ82/s1.png',
            ]
        };
    }
})
</script>
  
<style>
.carousel__item {
    min-height: 200px;
    width: 100%;
    height: 100%;
    /* background-color: red; */
    color: var(--vc-clr-white);
    font-size: 20px;
    border-radius: 8px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.carousel__slide {
    padding: 10px;
}

.carousel__prev,
.carousel__next {
    box-sizing: content-box;
}
</style>
  