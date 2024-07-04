<template>
  <nav>
     <section class="nav-section">
         <a ><NuxtLink to="#home" class="nav-item">Home</NuxtLink></a>
         <a><NuxtLink to="#about" class="nav-item">About</NuxtLink></a>
         <a><NuxtLink to="#contact" class="nav-item">Contact</NuxtLink></a>
         <a><NuxtLink to="#project" class="nav-item">Project</NuxtLink></a>
         
     </section>
 </nav>
<div>
 <HeroSection />
 <AboutSection />
 <ContactSection />
 <ProjectsSection />
</div>

<footer class="footer">
     <p>&copy;2024 Build by YuwiDev</p>

 </footer>
</template>

<script>
import HeroSection from '~/components/HeroSection.vue';
import AboutSection from '~/components/AboutSection.vue';
import ProjectsSection from '~/components/ProjectsSection.vue';
import ContactSection from '~/components/ContactSection.vue';



export default {
components: {
 HeroSection,AboutSection,ContactSection,ProjectsSection
}
}
</script>./Index.vue
