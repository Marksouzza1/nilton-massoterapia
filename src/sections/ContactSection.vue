<template>
    <!-- Contact section start -->
	<section id="contact-section" class="px-12 lg:px-32 py-16 relative">
        <!-- Main text start -->
		<h1 class="uppercase text-5xl mb-4 font-semibold ">
			Agende um atentimendo
		</h1>
		<!-- Main text end -->

        <!-- Form start -->
        <div class="grid grid-cols-1 md:grid-cols-2 w-full">
            <div class="hidden md:flex justify-center items-center">
                <img src="@/assets/camera.png" alt="">
            </div>
            <div class="flex flex-col w-full items-center">
                <label for="user_whatsapp" class="text-stone-500 text-left">WhatsApp</label>
                <p type="text" name="user_whatsapp" id="user_whatsapp" class="text-stone-500 text-left">+55 (XX) XXXXX-XXXX</p>
                
                <label class="text-stone-500 text-left">Endereço da Clínica</label>
                <p class="text-stone-500 text-left">Rua Exemplo, 123, Bairro, Cidade, Estado, CEP 12345-678</p>
            </div>  
        </div>
        <!-- Form end -->

        <!-- Circle start -->
        <div class="bg-neutral-200 h-44 w-44 md:h-52 md:w-52 rounded-full absolute -top-20 left-0 mt-16 -z-20"></div>
        <!-- Circle end -->
	</section>
	<!-- Contact section end -->
</template>

<script>
export default {

}
</script>

<style>

</style>