<template>
    <vue-slick-carousel :arrows="false" :dots="true" class="hero-slide">
       
        <div class="p-8">
            <div class="slide-bg rounded-2xl py-8">
                <div class="container mx-auto">
                    <div class="flex justify-center space-x-4">
                        <!-- slide content -->
                        <div class="self-center w-1/2 mr-6">
                            <p class="bs-text-green text-2xl font-medium mb-3">Save up 30% off</p>
                            <h2 class="text-4xl font-semibold leading-relaxed">Bengal Vegetable farm  Organic 100%</h2>
                            <p class="text-xl mb-6">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vehicula faucibus massa est elit maecenas.</p>
                            <NuxtLink to="/" class="bs-bg-green text-white rounded-full px-6 py-2 my-4 text-base">Shop Now</NuxtLink>
                        </div>
                        <!-- slide image -->
                        <div class="">
                            <img src="~/assets/img/slide1.png" width="400" class="" alt="Shop Now">
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="p-8">
            <div class="slide-bg rounded-2xl py-8">
                <div class="container mx-auto">
                    <div class="flex justify-center space-x-4">
                        <!-- slide content -->
                        <div class="self-center w-1/2 mr-6">
                            <p class="bs-text-green text-2xl font-medium mb-3">Black friday offer</p>
                            <h2 class="text-4xl font-semibold leading-relaxed">Super first delivary</h2>
                            <p class="text-xl mb-6">Lorem ipsum dolor sit amet.</p>
                            <NuxtLink to="/" class="bs-bg-green text-white rounded-full px-6 py-2 my-4 text-base">Go Now</NuxtLink>
                        </div>
                        <!-- slide image -->
                        <div class="">
                            <img src="~/assets/img/slide1.png" width="400" class="" alt="Shop Now">
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </vue-slick-carousel>
</template>

<script>
export default {
    name: "Slide"
}
</script>


