<template>
<div>
    <div class="bg-[#1d204e]">
        <div class="back fixed top-0 right-0 left-0 bottom-0 z-0 backdrop:blur opacity-20"></div>
        <div class="container mx-auto relative h-screen">
            <div class="flex justify-center items-center h-full">
                <div class="leading-[70px]">
                    <h1 class="text-7xl capitalize font-serif font-bold py-3 text-white">
                        Full stack web developer
                    </h1>
                    <p class="text-2xl text-white text-center">
                        Showcasing projects and skills with stunning animations
                    </p>
                    <div class="flex justify-center py-6">
                        <button class="bg-[#32a927] h-[50px] flex items-center px-6 text-white rounded-md">
                            View Projects
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- about section -->

    <div class="min-h-screen  z-10 bg-white relative">
        <div class="container mx-auto">
            <div class="grid grid-cols-2 gap-10 w-full h-full  items-center">
                <div class="w-[80%] ">
                    <div>
                        <h1 class="text-4xl font-bold font-serif">Passionate fullstack developer</h1>
                        <p class="text-2xl py-3 leading-9 text-[#595959]">
                            I am a dedicated fullstack developer based in Addis Ababa,
                            specializing in creating dynamic web applications. With expertise in
                            Nuxt 3 and Tailwind CSS, I craft responsive and engaging user
                            experiences that showcase my projects, skills, and professional
                            journey. My portfolio reflects my commitment to excellence and
                            innovation in every line of code I write.
                        </p>
                        <button>Get in touch</button>
                    </div>
                </div>
                <div class="flex h-full items-center">
                    <img src="@/assets/about.jpeg" alt="" class="h-[70%] object-cover rounded-md">
                </div>
            </div>
        </div>
    </div>
</div>
</template>

<script>
import image from "@/assets/pc.jpg";
</script>

<style scoped>
.back {
    background-image: url("@/assets/pc1.png");
    background-size: cover;
    /* Optional: Adjusts the background image size */
    height: 100vh;
}
</style>
