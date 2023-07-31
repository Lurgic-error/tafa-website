<template>
    <!-- <header>
        <nav class="container flex items-start py-4 mt-4 sm:mt-12">
            <div class="flex"></div>
        </nav>
    </header> -->
    <main class="">
        <!-- Hero -->
        <section class="relative">
            <div class="container flex flex-col-reverse lg:flex-row items-center gap-12 mt-14 lg:mt-28">
                <!-- Content -->
                <div class="flex-1 flex flex-col items-center lg:items-start">
                    <h2 class="text-3xl md:text-4xl lg:text-5xl text-center lg:text-left mb-6">
                        A Simple Bookmark Manager
                    </h2>
                    <p class="text-lg text-center lg:text-left mb-6">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Eaque facere debitis labore mollitia
                        veniam! Cupiditate, fuga reiciendis minus et assumenda aperiam qui soluta dolorum nostrum omnis
                        possimus expedita.
                    </p>
                    <div class="flex justify-center flex-wrap gap-6">
                        <button class="button button-primary hover:bg-gray-400 hover:text-black">Buy Some</button>

                        <button class="button button-secondary hover:bg-indigo-900 hover:text-white">Get Some</button>
                    </div>
                </div>

                <!-- Image -->
                <div class="flex-1 flex justify-center z-10  mb-10 md:mb-16 lg:mb-0">
                    <img class="w-5/6 h-5/6 sm:w-3/4 sm:h-3/4 md:w-full md:h-full" src="../assets/hero-1.jpg"
                        alt="Hero">
                </div>
            </div>
            <!-- Rounded Rectangle -->
            <div
                class="hidden md:block overflow-hidden bg-indigo-900 rounded-l-full absolute h-80 w-2/4 top-32 right-0 lg:-button-28 lg:-right-36 ">
            </div>
        </section>

        <!-- Features -->
        <section class="bg-gray-200 py-20 mt-20 lg:mt-60">
            <!-- Section Heading -->
            <div class="sm:w-3/4 lg:w-5/12 mx-auto px-2">
                <h1 class="text-3xl text-center ">Features</h1>
                <p class="text-center mt-4">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus, ipsum alias necessitatibus
                    dolorem officiis dolores sapiente?
                </p>
            </div>

            <!-- Feature 1 -->
            <div class="relative mt-20 lg:mt-24">
                <div class="container flex flex-col lg:flex-row items-center justify-center gap-x-24">
                    <!-- Image -->
                    <div class="flex-1 flex justify-center z-10 mb-10 lg:mb-0">
                        <img src="../assets/feature-1.jpg" alt="Feature 1"
                            class="w-5/6 h-5/6 sm:w-3/4 sm:h-3/4 md:w-full md:h-full">
                    </div>
                    <!-- Content -->
                    <div class="flex-1 flex flex-col items-center lg:items-start">
                        <h1 class="text-3xl">Feature Name</h1>
                        <p class="my-4 text-center lg:text-left sm:w-3/4 lg:w-w-full">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam ut nihil labore minima beatae
                            temporibus est iste? Nihil, cum laboriosam!
                        </p>
                        <button class="button button-primary hover:bg-gray-400 hover:text-black">Learn More</button>
                    </div>
                </div>
                <!-- Rounded Rectangle -->
                <div
                    class="hidden lg:block overflow-hidden bg-indigo-900 rounded-r-full absolute h-80 w-2/4 top-24 -left-36 ">
                </div>
            </div>

            <!-- Feature 2 -->
            <div class="relative mt-20 lg:mt-52">
                <div class="container flex flex-col lg:flex-row-reverse items-center justify-center gap-x-24">
                    <!-- Image -->
                    <div class="flex-1 flex justify-center z-10 mb-10 lg:mb-0">
                        <img src="../assets/feature-2.jpg" alt="Feature 1"
                            class="w-5/6 h-5/6 sm:w-3/4 sm:h-3/4 md:w-full md:h-full">
                    </div>
                    <!-- Content -->
                    <div class="flex-1 flex flex-col items-center lg:items-start">
                        <h1 class="text-3xl">Feature Name</h1>
                        <p class="my-4 text-center lg:text-left sm:w-3/4 lg:w-w-full">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam ut nihil labore minima beatae
                            temporibus est iste? Nihil, cum laboriosam!
                        </p>
                        <button class="button button-primary hover:bg-gray-400 hover:text-black">Learn More</button>
                    </div>
                </div>
                <!-- Rounded Rectangle -->
                <div
                    class="hidden lg:block overflow-hidden bg-indigo-900 rounded-l-full absolute h-80 w-2/4 top-24 -right-36 ">
                </div>
            </div>

            <!-- Feature 3 -->
            <div class="relative mt-20 lg:mt-52">
                <div class="container flex flex-col lg:flex-row items-center justify-center gap-x-24">
                    <!-- Image -->
                    <div class="flex-1 flex justify-center z-10 mb-10 lg:mb-0">
                        <img src="../assets/feature-3.jpg" alt="Feature 1"
                            class="w-5/6 h-5/6 sm:w-3/4 sm:h-3/4 md:w-full md:h-full">
                    </div>
                    <!-- Content -->
                    <div class="flex-1 flex flex-col items-center lg:items-start">
                        <h1 class="text-3xl">Feature Name</h1>
                        <p class="my-4 text-center lg:text-left sm:w-3/4 lg:w-w-full">
                            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam ut nihil labore minima beatae
                            temporibus est iste? Nihil, cum laboriosam!
                        </p>
                        <button class="button button-primary hover:bg-gray-400 hover:text-black">Learn More</button>
                    </div>
                </div>
                <!-- Rounded Rectangle -->
                <div
                    class="hidden lg:block overflow-hidden bg-indigo-900 rounded-r-full absolute h-80 w-2/4 top-24 -left-36 ">
                </div>
            </div>
        </section>

        <!-- Download -->
        <section class="py-20">
            <!-- Section Heading -->
            <div class="sm:w-3/4 lg:w-5/12 mx-auto px-2">
                <h1 class="text-3xl text-center ">Download the extension</h1>
                <p class="text-center mt-4">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus, ipsum alias necessitatibus
                    dolorem officiis dolores sapiente?
                </p>
            </div>

            <!-- Cards -->
            <div class="container grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-16 max-w-screen-lg mt-16">
                <!-- Card 1 -->
                <div class="flex flex-col rounded-md shadow  lg:mb-16">
                    <div class="p-6 flex flex-col items-center">
                        <div class="h-32 w-32 rounded-full bg-indigo-900"></div>
                        <h3 class="mt-5 mb-2 text-lg">Card Name</h3>
                        <p class="mb-2 font-light text-center">
                            Lorem ipsum dolor sit amet consectetur.
                        </p>
                    </div>
                    <hr class="border-b border-indigo-900">
                    <div class="flex p-6">
                        <button class="button button-primary hover:bg-gray-400 hover:text-black flex-1">Add To
                            Wishlist</button>
                    </div>
                </div>
                <!-- Card 2-->
                <div class="flex flex-col rounded-md shadow lg:my-8">
                    <div class="p-6 flex flex-col items-center">
                        <div class="h-32 w-32 rounded-full bg-indigo-900"></div>
                        <h3 class="mt-5 mb-2 text-lg">Card Name</h3>
                        <p class="mb-2 font-light text-center">
                            Lorem ipsum dolor sit amet consectetur.
                        </p>
                    </div>
                    <hr class="border-b border-indigo-900">
                    <div class="flex p-6">
                        <button class="button button-primary hover:bg-gray-400 hover:text-black flex-1">Add To
                            Wishlist</button>
                    </div>
                </div>
                <!-- Card 3 -->
                <div class="flex flex-col rounded-md shadow lg:mt-16">
                    <div class="p-6 flex flex-col items-center">
                        <div class="h-32 w-32 rounded-full bg-indigo-900"></div>
                        <h3 class="mt-5 mb-2 text-lg">Card Name</h3>
                        <p class="mb-2 font-light text-center">
                            Lorem ipsum dolor sit amet consectetur.
                        </p>
                    </div>
                    <hr class="border-b border-indigo-900">
                    <div class="flex p-6">
                        <button class="button button-primary hover:bg-gray-400 hover:text-black flex-1">Add To
                            Wishlist</button>
                    </div>
                </div>
            </div>
        </section>

        <!-- FAQ -->
        <section class="bg-gray-100 py-20 ">
            <div class="container">
                <!-- Section Heading -->
                <div class="sm:w-3/4 lg:w-5/12 mx-auto px-2">
                    <h1 class="text-3xl text-center ">Frequently Asked Questions</h1>
                    <p class="text-center mt-4">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Possimus, ipsum alias necessitatibus
                    dolorem officiis dolores sapiente?
                    </p>
                </div>
                <!-- FAQ Items -->
                <div class="flex flex-col sm:w-3/4 lg:w-5/12 mt-12 mx-auto ">
                    <div class="flex items-center py-4 border-b">
                        <span class="flex-1">What is item?</span>
                    </div>
                    <div class="flex items-center py-4 border-b">
                        <span class="flex-1">What is item?</span>
                    </div>
                    <div class="flex items-center py-4 border-b">
                        <span class="flex-1">What is item?</span>
                    </div>
                    <div class="flex items-center py-4 border-b">
                        <span class="flex-1">What is item?</span>
                    </div>
                    <div class="flex items-center py-4 border-b">
                        <span class="flex-1">What is item?</span>
                    </div>
                    <button class="button button-primary hover:bg-gray-400 hover:text-black flex self-center mt-8">See More</button>
                </div>
            </div>
        </section>
    </main>
</template>

<script setup></script>