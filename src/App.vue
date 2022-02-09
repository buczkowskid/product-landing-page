<template>
	<div class="wrapper">
		<HeaderItem />
		<FeaturesItem />
		<SpecificationItem />
	</div>
</template>

<script>
import HeaderItem from "./components/HeaderItem.vue";
import FeaturesItem from "./components/FeaturesItem.vue";
import SpecificationItem from "./components/SpecificationItem.vue";

export default {
	name: "App",
	components: {
		HeaderItem,
		FeaturesItem,
		SpecificationItem,
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
