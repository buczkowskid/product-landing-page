<template>
	<div class="wrapper">
		<HeaderSection />
		<FeaturesSection />
		<SpecificationSection />
	</div>
</template>

<script>
import HeaderSection from "./components/HeaderSection.vue";
import FeaturesSection from "./components/FeaturesSection.vue";
import SpecificationSection from "./components/SpecificationSection.vue";

export default {
	name: "App",
	components: {
		HeaderSection,
		FeaturesSection,
		SpecificationSection,
	},
};
</script>

<style>
#app {
	font-family: "Lato", "Montserrat" sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
}

.wrapper {
	max-width: 1920px;
	margin: 0 auto;
	overflow: hidden;
}
@import url("https://fonts.googleapis.com/css2?family=Lato:wght@300&family=Montserrat:wght@300&display=swap");
</style>
