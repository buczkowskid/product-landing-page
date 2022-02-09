<template>
	<div class="text-container">
		<div class="header-title">
			<h1>{{ hero.title }}</h1>
			<h2>{{ hero.subtitle }}</h2>
		</div>
		<p class="header-text">
			{{ hero.text }}
		</p>
	</div>
</template>

<script>
export default {
	props: ["hero"],
};
</script>

<style>
.text-container {
	display: flex;
	flex-direction: column;
	flex-wrap: wrap;
	flex: 1;
	margin: 9rem 3.5rem 0 22rem;
}

.header-title h1,
h2 {
	font-family: "Montserrat", sans-serif;
	font-size: 5rem;
	color: #ffffff;
	font-weight: 400;
	text-align: left;
}

.header-title h2 {
	font-size: 4rem;
}

.header-text {
	margin: 4rem 0;
	padding-right: 4.5rem;
	font-family: "Montserrat", sans-serif;
	font-size: 1.6rem;
	color: #ffffff;
	line-height: 2.6rem;
	max-width: 100%;
	text-align: left;
}

/* MEDIA */

@media (max-width: 1700px) {
	.text-container {
		margin: 9rem 3.5rem 0 5rem;
	}
}

@media (max-width: 1200px) {
	.text-container {
		margin: 0 auto;
	}
}

@media (max-width: 768px) {
	.text-container {
		margin: 0 auto;
		padding: 1rem;
	}
}

@media (max-width: 576px) {
	.text-container {
		margin: 0 auto;
		padding: 1rem;
	}

	.header-title h1 {
		font-size: 3rem;
	}

	.header-title h2 {
		font-size: 2.5rem;
	}

	.header-text {
		margin: 2rem 0;
		font-size: 1.5rem;
		line-height: 2rem;
		padding-right: 0;
	}
}
</style>
