<script setup>

</script>
<template>
    <div class=" p-20">
        <div class=" text-darkGray">
            <h3 class=" text-5xl font-bold py-2">Stay updated!</h3>
            <p class="py-2 text-base font-bold">Join 60,000+ product managers receiving monthly updates on:</p>
        </div>
        <div class="features font-bold">
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
                <label class=" basis-1 grow-0 shrink-0 font-bold text-sm">Email Address</label>
                <input type="email" placeholder="email@company.com">
                <button class="basis-1 grow-0 shrink-0 text-center" @click.prevent="">Submit to monthly newsletter</button>
            </form>
        </div>
    </div>
</template>
<style>
</style>