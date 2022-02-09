<template>
	<section class="header">
		<div class="header-container">
			<img
				src="../assets/images/logos/lenovo-logo-01.svg"
				alt="Logo firmy Lenovo"
				class="hero-logo"
			/>
			<div class="header-details">
				<HeaderItemText :hero="hero" />
				<img
					src="../assets/images/products/product-6.png"
					alt="Laptop Lenovo Yoga S740"
					class="hero-img"
				/>
			</div>
		</div>
	</section>
</template>

<script>
import HeaderItemText from "./HeaderItemText.vue";
export default {
	components: {
		HeaderItemText,
	},

	data() {
		return {
			hero: {
				title: "Yoga S740 (14)",
				subtitle: "Wyróżniająca inteligencja",
				text: "Z komputerem Yoga S740 możesz pracować i korzystać z rozrywki w eleganckim stylu. Ten imponujący laptop w całkowicie metalowej obudowie działa z pełną mocą procesora Intel® Core™ 10. generacji i oferuje inteligentne, przydatne na co dzień funkcje. Lekki, ale wydajny, zapewnia wysokiej klasy funkcje rozrywkowe dzięki baterii wystarczającej na nawet 15 godzin, efektownemu wyświetlaczowi 4K VESA400 HDR oraz fantastycznemu dźwiękowi z technologią Dolby Atmos®.",
			},
		};
	},
};
</script>

<style>
.header {
	background-color: #408ddc;
}

.header-container {
	display: flex;
	align-items: flex-start;
	flex-direction: row;
}

.header-details {
	display: flex;
	flex-wrap: wrap;
	margin-top: 14rem;
	margin-bottom: 14rem;
	max-width: 150rem;
}

.hero-img {
	display: flex;
	justify-content: center;
	align-items: center;
	/* max-width: 100%; */
}

/* MEDIA */

@media (max-width: 1700px) {
	.hero-img {
		margin: 0 auto;
		max-width: 100%;
	}
}

@media (max-width: 1400px) {
	.header-details {
		flex-direction: column;
		height: auto;
	}
}

@media (max-width: 1200px) {
	.header-details {
		margin: 2rem;
		padding: 0;
	}

	.hero-img {
		margin: 5rem auto;
		padding: 0;
		width: auto;
		height: 37rem;
		max-width: 100%;
	}

	@media (max-width: 768px) {
		.header-details {
			margin: 2rem auto;
		}

		.hero-img {
			margin: 0 1rem;
			width: 50rem;
			height: auto;
		}
	}

	@media (max-width: 576px) {
		.header {
			flex-direction: row;
		}

		.header-details {
			margin: 2rem auto;
		}

		.hero-img {
			padding: 0 2rem;
			max-width: 100%;
		}
	}
}
</style>
