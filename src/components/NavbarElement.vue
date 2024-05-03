<template>
    <!-- Navbar start -->
    <nav class="w-screen fixed bg-opacity-90 bg-white p-4 lg:px-20 flex justify-between z-50">
		<!-- Logo start -->
		<div class="h-full flex flex-col justify-center">
    <div class="flex flex-row justify-center items-center">
		<img id="logo" :src="logo" alt="logo">
        <div class="flex flex-col paragrafos">
            <p class="tracking-widest font-semibolwd">Nilton</p>
            <p class="tracking-widest font-light">Alves</p>
        </div>
    </div>
</div>

		<!-- Logo end -->

		<!-- Toggler start -->
		<button role="menubar" class="md:hidden" @click="navToggle()">
			<i class="fa-solid fa-bars text-2xl"></i>
		</button>
		<!-- Toggler end -->

		<!-- Menu content start -->
		<div class="absolute left-0 right-0 translate-y-16 bg-opacity-90 bg-white md:bg-none md:bg-opacity-0 shadow hidden md:flex flex-col gap-4 items-center p-4 md:flex-row md:static md:shadow-none md:translate-y-0" role="menu" aria-expanded="false">
			<!-- Links start -->
			<a href="#" role="menuitem">
				<p class="mx-4">Home</p>
			</a>

			<a href="#" role="menuitem">
				<p class="mx-4">Sobre</p>
			</a>

			<a href="" @click="goTolink()" role="menuitem">
				<p class="mx-4">Localizção</p>
			</a>

			<button @click="goToContact()" class="btn" role="menuitem">
				Contato
			</button>
			<!-- Links end -->
		</div>
		<!-- Menu content end -->
	</nav>
    <!-- Navbar end -->
</template>

<script>
import logo from '@/assets/img/logo.png';

export default {
	data() {
		return {
			logo: logo,
		};
	},
    methods: {
		// Toogle navbar mode 
        navToggle() {
			let menu = document.querySelector("[role='menu']");
			let isExpanded = menu.getAttribute('aria-expanded');
			menu.setAttribute('aria-expanded', !isExpanded);
			menu.classList.toggle('hidden');
			menu.classList.toggle('flex');
		},
		goTolink() {
			window.open("https://maps.app.goo.gl/xb4vrTLd8Zp8DGvs8","_blank");	
		},
		goToContact() {
            const contactSection = document.getElementById('contact-section');
            if (contactSection) {
                contactSection.scrollIntoView({ behavior: 'smooth' });
            }
		},
    }
}
</script>

<style scoped>
#logo {
	width: 50px;
	height: 50px;
}
.flex.flex-col.paragrafos p {
	margin-left: 20px;
}
</style>