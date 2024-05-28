<template>
    <!-- Portfolio section start -->
	<section id="portfolio-section" class="px-4 lg:px-8 py-16  relative">
        <!-- Text wrapper start -->
        <div class="flex gap-8 flex-col md:flex-row">
            <!-- Main text start -->
            <h1 class="uppercase text-5xl mb-4 font-semibold ">
                A CLINICA
            </h1>
            <p class="capitalize xl:w-1/2 text-stone-500 mb-8">
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Reprehenderit dolores distinctio reiciendis obcaecati ea.
            </p>
            <!-- Main text end -->
        </div>
        <!-- Text wrapper end -->

        <!-- Images grid start -->
		<div class="grid-cols-2 md:grid-cols-5 grid mb-8 gap-4">
            <div class="grid grid-cols-1 md:hidden gap-4">
                <img src="@/assets/clinica/clinica1.png" alt="1" class="rounded-xl">
                <img src="@/assets/clinica/clinica2.png" alt="2" class="rounded-xl">
                <img src="@/assets/clinica/clinica3.png" alt="3" class="rounded-xl">
                <img src="@/assets/clinica/clinica4.png" alt="4" class="rounded-xl">
                <img src="@/assets/clinica/clinica5.png" alt="5" class="rounded-xl">
            </div>
            <div class="grid grid-cols-1 md:hidden gap-4">
                <img src="@/assets/clinica/clinica6.png" alt="6" class="rounded-xl">
                <img src="@/assets/clinica/clinica7.webp" alt="7" class="rounded-xl">
                <img src="@/assets/clinica/clinica8.webp" alt="8" class="rounded-xl">
                <img src="@/assets/clinica/clinica9.webp" alt="9" class="rounded-xl">
                <img src="@/assets/clinica/clinica10.webp" alt="10" class="rounded-xl">
            </div>

            <div class="hidden md:flex flex-col gap-4">
                <img src="@/assets/clinica/clinica1.png" alt="1" class="rounded-xl">
                <img src="@/assets/clinica/clinica2.png" alt="2" class="rounded-xl">
            </div>
            <div class="hidden md:flex flex-col gap-4">
                <img src="@/assets/clinica/clinica3.png" alt="1" class="rounded-xl">
                <img src="@/assets/clinica/clinica4.png" alt="2" class="rounded-xl">
            </div>
            <div class="hidden md:flex flex-col gap-4">
                <img src="@/assets/clinica/clinica8.webp" alt="2" class="rounded-xl">
                <img src="@/assets/clinica/clinica5.png" alt="2" class="rounded-xl">
            </div>
            <div class="hidden md:flex flex-col gap-4">
                <img src="@/assets/clinica/clinica7.webp" alt="1" class="rounded-xl">
                <img src="@/assets/clinica/clinica6.png" alt="2" class="rounded-xl">
            </div>
            <div class="hidden md:flex flex-col gap-4">
                <img src="@/assets/clinica/clinica9.webp" alt="1" class="rounded-xl">
                <img src="@/assets/clinica/clinica10.webp" alt="2" class="rounded-xl">
            </div>
        </div>
		<!-- Images grid end -->

        <!-- "More" link start -->
        <a href="https://www.instagram.com/niltonalves_terapia/" class="text-end">
            <p class="font-semibold text-lg group relative">
                <span>Veja mais no instagaram </span>
                <i class="fa-solid fa-arrow-right"></i>
            </p>
        </a>
        <!-- "More" link end -->

        <!-- Circle start -->
        <div class="bg-neutral-300 h-64 w-64 rounded-full absolute top-0 left-0 mt-16 -z-20"></div>
        <!-- Circle end -->
	</section>
	<!-- Portfolio section end -->
</template>

<script>
export default {

}
</script>

<style>

</style>