<script setup>
import hero from '../../assets/images/hero-1.png'
</script>

<template>
    <div class="bg-[#F5FAFF] md:py-8 py-3">
        <section class="w-11/12 mx-auto grid md:grid-cols-2 items-center">
            <div class="md:hidden flex">
                <img :src="hero" alt="">
            </div>
            <div class="md:w-10/12 mx-auto">
                <h2 class="md:text-6xl text-3xl font-bold ">Payroll and HR that move you to the next level</h2>
                <p class="md:my-5 my-2 md:text-lg">Payroll is a big job-but that doesn't mean it needs to be a big job. for you. Our online payroll is easy to set up if your people are more engaged than your competitors' workforce.</p>

                <form class="">
                    <label for="default-search"
                        class="mb-2 text-sm font-medium text-gray-900 sr-only dark:text-white">Search</label>
                    <div class="relative">
                        <div class="absolute inset-y-0 left-0 flex items-center pl-3 pointer-events-none">
                            <svg class="w-4 h-4 text-gray-500 dark:text-gray-400" aria-hidden="true"
                                xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 20 20">
                                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                    d="m19 19-4-4m0-7A7 7 0 1 1 1 8a7 7 0 0 1 14 0Z" />
                            </svg>
                        </div>
                        <input type="search" id="default-search"
                            class="block w-full p-4 pl-10 text-sm text-gray-900 border border-gray-300 rounded-lg bg-gray-50 focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                            placeholder="Enter Email Address" required>
                        <button type="submit"
                            class="text-white absolute right-2.5 bottom-2.5 bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm px-4 py-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Get Start Free</button>
                    </div>
                </form>

        </div>
        <div class="hidden md:flex justify-center">
            <img :src="hero" alt="">
        </div>
    </section>
</div></template>