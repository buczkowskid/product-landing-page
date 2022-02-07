<template>
	<section class="header">
		<div class="header">
			<img
				src="../assets/lenovo-logo-01.svg"
				alt="Logo firmy Lenovo"
				class="hero-logo"
			/>
			<div class="container">
				<div class="text-container">
					<div class="header-heading">
						<h1>Yoga S740 (14)</h1>
						<h2>Wyróżniająca inteligencja</h2>
					</div>
					<p class="header-text">
						Z komputerem Yoga S740 możesz pracować i korzystać z rozrywki w
						eleganckim stylu. Ten imponujący laptop w całkowicie metalowej
						obudowie działa z pełną mocą procesora Intel® Core™ 10. generacji i
						oferuje inteligentne, przydatne na co dzień funkcje. Lekki, ale
						wydajny, zapewnia wysokiej klasy funkcje rozrywkowe dzięki baterii
						wystarczającej na nawet 15 godzin, efektownemu wyświetlaczowi 4K
						VESA400 HDR oraz fantastycznemu dźwiękowi z technologią Dolby
						Atmos®.
					</p>
				</div>
				<img
					src="../assets/product-6.png"
					alt="Laptop Lenovo Yoga S740"
					class="hero-img"
					sizes="(max-width: 725px)"
				/>
			</div>
		</div>
	</section>
</template>

<script>
export default {};
</script>

<style>
.header {
	display: flex;
	align-items: flex-start;
	flex-direction: row;
	background-color: #408ddc;
}

.container {
	display: flex;
	flex-wrap: wrap;
	margin-top: 14rem;
	margin-right: 24rem;
	margin-bottom: 14rem;
}

.text-container {
	display: flex;
	flex-direction: column;
	flex-wrap: wrap;
	flex: 1;
	margin: 9rem 3.5rem 0 22rem;
}

.header-heading h1,
h2 {
	font-family: "Montserrat", sans-serif;
	font-size: 5rem;
	color: #ffffff;
	font-weight: 400;
	text-align: left;
}

.header-heading h2 {
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

.hero-img {
	display: flex;
	justify-content: center;
	align-items: center;
	width: 72.5rem;
	height: 51.5rem;
	max-width: 100%;
}

/* MEDIA */

@media (max-width: 1400px) {
	.header {
		flex-direction: column;
		height: auto;
	}

	.container {
		margin: 2rem auto;
	}

	.text-container {
		margin-left: 10rem;
	}

	.hero-img {
		margin: 2rem;
		padding-left: 8rem;
	}
}

@media (max-width: 1200px) {
	.text-container {
		margin-top: 0;
	}
}

@media (max-width: 576px) {
	.header {
		flex-direction: row;
	}

	.text-container {
		margin: 0 auto;
		padding: 0 2.5rem;
	}

	.header-heading h1 {
		font-size: 4rem;
	}

	.header-heading h2 {
		font-size: 3rem;
	}

	.header-text {
		margin: 2rem 0;
		font-size: 1.5rem;
		line-height: 2rem;
		padding-right: 0;
	}

	.hero-img {
		width: 200px;
		height: auto;
		padding-left: 0;
	}
}
</style>
