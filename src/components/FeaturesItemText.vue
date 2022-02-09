<template>
	<div class="features-container">
		<img
			v-if="featuresData.image"
			:src="featuresData.image.src"
			:alt="featuresData.alt"
			class="product-feature-img"
		/>
		<h2 class="features-heading">{{ featuresData.title }}</h2>
		<p class="features-text">
			{{ featuresData.text }}
		</p>
	</div>
</template>

<script>
export default {
	props: ["featuresData"],
};
</script>

<style>
.features-container {
	margin: 0 30rem;
}

.product-feature-img {
	display: flex;
	justify-content: center;
	align-items: center;
	margin: 0 auto;
	margin-top: 9rem;
	max-width: 100%;
}

.features-heading {
	margin: 4rem 0 2rem 0;
	font-size: 5rem;
	color: #000000;
	font-family: "Lato", sans-serif;
	font-weight: 300;
	text-align: left;
}

.features-text {
	font-size: 2rem;
	font-family: "Lato", sans-serif;
	font-weight: 300;
	line-height: 3rem;
	text-align: left;
}

/* MEDIA */

@media (max-width: 1500px) {
	.features-container {
		margin: 0 auto;
		padding: 0 2.5rem;
	}
}

@media (max-width: 768px) {
	.features-heading {
		margin-top: 2rem;
		font-size: 3rem;
	}
}
</style>
