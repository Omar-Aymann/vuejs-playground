<script setup>

</script>
<template>
    <div class=" p-20 flex flex-col">
        <div class=" text-darkGray">
            <h3 class=" xl:text-6xl md:text-3xl font-bold py-2">Stay updated!</h3>
            <p class="py-2 text-base font-bold">Join 60,000+ product managers receiving monthly updates on:</p>
        </div>
        <div class="features font-medium">
            <div class="feature">
                <img src="../assets/icon-success.svg" alt="success">
                <p>Product discovery and building what matters</p>
            </div>
            <div class="feature">
                <img src="../assets/icon-success.svg" alt="success">
                <p>Measuring to ensure updates are a success</p>
            </div>
            <div class="feature">
                <img src="../assets/icon-success.svg" alt="success">
                <p>And much more!</p>
            </div>
        </div>
        <div class="lowerSection">
            <form class="flex flex-col items-start">
                <label class=" font-bold text-sm">Email Address</label>
                <input class="w-full my-3 p-3 px-4 border border-gray focus:border-black rounded-lg" type="email" placeholder="email@company.com">
                <button class=" text-center w-full p-4 bg-darkGray transition-all duration-500 text-white rounded-lg my-3" @click.prevent="">Submit to monthly newsletter</button>
            </form>
        </div>
    </div>
</template>
<style>
</style>