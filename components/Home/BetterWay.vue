<script setup>
import hero from '../../assets/images/hero-3.png'
</script>

<template>
    <div class="bg-gray-50 md:py-8 py-3">
        <section class="w-11/12 mx-auto grid md:grid-cols-2 items-center">
            <div class="flex">
                <img :src="hero" alt="">
            </div>
            <div class="md:w-10/12 mx-auto">
                <h2 class="md:text-6xl text-3xl font-bold ">The better way to make, move and manage your money</h2>
                <p class="md:my-5 my-2 md:text-lg">Truly understand and manage your income and expenses. Track everything
                    and connect to other Wave products such as payroll, payments, and invoicing, Run payroll automatically
                    and easily make changes.</p>
                <div class="flex">
                    <button type="button"
                        class="py-2.5 px-5 mr-2 text-sm font-medium text-blue-600 focus:outline-none bg-none rounded-lg border border-blue-700 hover:bg-gray-100 hover:text-blue-700 focus:z-10 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-700 dark:bg-gray-800 dark:text-gray-400 dark:border-gray-600 dark:hover:text-white dark:hover:bg-gray-700">Try For Free</button>
                        <button type="button" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">Lats Know More</button>
                </div>
            </div>

        </section>
    </div>
</template>