<template>
    <MainSection></MainSection>
    <AboutSection></AboutSection>
    <ServiceSection></ServiceSection>
    <PortfolioSection></PortfolioSection>
    <ContactSection></ContactSection>

</template>
<script>
import MainSection from '@/sections/MainSection.vue';
import AboutSection from '@/sections/AboutSection.vue';
import ServiceSection from '@/sections/ServiceSection.vue';
import PortfolioSection from '@/sections/PortfolioSection.vue';
import ContactSection from '@/sections/ContactSection.vue';
export default {
    components: {
        MainSection,
        AboutSection,
        ServiceSection,
        PortfolioSection,
        ContactSection
    }
}
</script>
<style>
    
</style>