<template>
	<div class="wrapper">
		<Header />
		<Features />
		<Specification />
	</div>
</template>

<script>
import Header from "./components/Header.vue";
import Features from "./components/Features.vue";
import Specification from "./components/Specification.vue";

export default {
	name: "App",
	components: {
		Header,
		Features,
		Specification,
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
