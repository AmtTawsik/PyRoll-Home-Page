<script setup>
import delivery from '../../assets/images/delivery.png'
</script>

<template>
    <div class="w-10/12 mx-auto mt-5 md:mt-10">
        <section class="grid md:grid-cols-2 bg-violet-800 items-center rounded-md">
            <div class="md:hidden flex">
                <img :src="delivery" alt="">
            </div>
            <div class="text-white pl-5 md:pl-10">
                <h5 class="text-2xl md:text-4xl font-semibold">Everything you need to</h5>
                <h5 class="text-2xl md:text-4xl font-semibold">confidently run your business</h5>
                <p class="text-lg my-3">Free Forever Unlimited No Credit Required</p>
                <button type="button"
                    class="text-gray-900 bg-white border border-gray-300 focus:outline-none hover:bg-gray-100 focus:ring-4 focus:ring-gray-200 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-gray-800 dark:text-white dark:border-gray-600 dark:hover:bg-gray-700 dark:hover:border-gray-600 dark:focus:ring-gray-700 mt-3">Sign
                    Up Now</button>
            </div>
            <div class="hidden md:flex justify-center">
                <img :src="delivery" alt="">
            </div>
        </section>
    </div>
</template>

