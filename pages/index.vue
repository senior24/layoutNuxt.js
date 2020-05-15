<template>
	<div>
	 	<app-about />
		<app-skills /> 
		<app-quality />
		<app-works /> 
		<app-proces />
		<app-services />
		<app-testimonials />
		<app-contact />  
	</div>
</template>
 
<script>

import About from "~/components/About.vue";
import Skills from "~/components/Skills.vue";
import Quality from "~/components/Quality.vue";
import Works from "~/components/Works.vue";
import Proces from "~/components/Proces.vue";
import Services from "~/components/Services.vue";
import Reviews from "~/components/Reviews.vue";
import Testimonials from "~/components/Testimonials.vue";
import Contact from "~/components/Contact.vue";

  export default {
    components: {
		AppAbout: About,
		AppSkills: Skills,
		AppQuality: Quality,
		AppWorks: Works,
		AppProces: Proces,
		AppServices: Services,
		AppReviews: Reviews,
		AppTestimonials: Testimonials,
		AppContact: Contact
    }
  };

</script>

<style>
	 
</style>
