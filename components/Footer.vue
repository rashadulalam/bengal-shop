<template>
    <footer class="">
        <div class="container mx-auto flex my-20">
            <div class="w-1/4 flex items-center">
                <div class="mr-2">
                    <img width="50" height="50" src="../assets/img/callcenter.svg" alt="Call Center">
                </div>
                <div>
                    <h3 class="font-medium text-xl capitalize">24 Customer Support</h3>
                    <p class="text-gray-400">Contact us 24 hours</p>
                </div>
            </div>

             <div class="w-1/4 flex items-center">
                <div class="mr-2">
                    <img width="50" height="50" src="../assets/img/t-shirt.svg" alt="Call Center">
                </div>
                <div>
                    <h3 class="font-medium text-xl capitalize">Authentic Products</h3>
                    <p class="text-gray-400">Contact us 24 hours</p>
                </div>
            </div>

            <div class="w-1/4 flex items-center">
                <div class="mr-2">
                    <img width="50" height="50" src="../assets/img/casback.png" alt="Call Center">
                </div>
                <div>
                    <h3 class="font-medium text-xl capitalize">Secure Payment</h3>
                    <p class="text-gray-400">Contact us 24 hours</p>
                </div>
            </div>

            <div class="w-1/4 flex items-center">
                <div class="mr-2">
                    <img width="50" height="50" src="../assets/img/callcenter.svg" alt="Call Center">
                </div>
                <div>
                    <h3 class="font-medium text-xl capitalize">Best Prices & Offers</h3>
                    <p class="text-gray-400">Contact us 24 hours</p>
                </div>
            </div>
        </div>
        <div class="bs-bg-gray py-6">
            <div class="container mx-auto flex mt-8">
                <div class="w-2/4">
                    <Logo />
                    <p class="mt-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla diam ornare nam est gravida. Netus viverra rhoncus sit magna sapien ac eget parturient id. Est luctus dapibus quam aliquam in nisl turpis. Elit et dictum lacus morbi nec accumsan a in.</p>
                    <div class="flex space-x-2 mt-4">
                        <img src="~/assets/img/play-store.svg" alt="">
                        <img src="~/assets/img/apple-store.svg" alt="">
                    </div>
                </div>
                <div class="w-1/4 pl-6">
                    <h2 class="font-medium text-black capitalize mb-6">About us</h2>
                    <div class="flex flex-col leading-loose">
                        <NuxtLink to="/">About Karte</NuxtLink>
                        <NuxtLink to="/">Contact</NuxtLink>
                        <NuxtLink to="/">Career</NuxtLink>
                        <NuxtLink to="/">Terms & Conditions</NuxtLink>
                        <NuxtLink to="/">Category</NuxtLink>
                    </div>
                </div>
                <div class="w-1/4">
                    <h2 class="font-medium text-black capitalize mb-6">Info</h2>
                    <div class="flex flex-col leading-loose">
                        <NuxtLink to="/">information</NuxtLink>
                        <NuxtLink to="/">Shipping</NuxtLink>
                        <NuxtLink to="/">Payment</NuxtLink>
                        <NuxtLink to="/">Return</NuxtLink>
                        <NuxtLink to="/">Blog</NuxtLink>
                    </div>
                </div>
            </div>
        </div>

        <!-- copyright -->
        <div class="container mx-auto flex items-center justify-between space-x-4 py-8">
            <div>
                <p>&copy; 2022 Copyright All Right Reserved by Bengal Shop</p>
            </div>
            <div class="flex items-center space-x-8">
                <NuxtLink to="/"><img src="~/assets/img/paypal.svg" alt=""></NuxtLink>
                <NuxtLink to="/"><img src="~/assets/img/visa.svg" alt=""></NuxtLink>
                <NuxtLink to="/"><img src="~/assets/img/play.svg" alt=""></NuxtLink>
                <NuxtLink to="/"><img src="~/assets/img/gplay.svg" alt=""></NuxtLink>
            </div>
        </div>
    </footer>
</template>
