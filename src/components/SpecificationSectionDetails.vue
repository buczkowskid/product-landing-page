<template>
	<div class="spec-region-info">Dane techniczne mogą zależeć od regionu</div>
	<div class="spec-info-img">
		<h2 class="spec-heading">Specyfikacja</h2>
		<img
			src="../assets/images/products/product-5.png"
			alt="Zdjęcie pokazujące wszystkie złącza w laptopie Lenovo YogaS740"
			class="spec-img"
		/>
		<ol class="spec-list">
			<li>Zasilanie</li>
			<li>USB 3.1 (Gen 2, zawsze aktywny)</li>
			<li>USB-C (USB + DisplayPort + zasilanie + Thunderbolt™ 3)</li>
			<li>Gniazdo słuchawek/mikrofonu</li>
			<li>USB 3.1 (Gen 2)</li>
		</ol>
	</div>
</template>

<script>
export default {};
</script>

<style>
.spec-region-info {
	display: flex;
	justify-content: flex-end;
	font-size: 1rem;
}

.spec-img {
	display: flex;
	justify-content: center;
	align-items: center;
	margin: 7rem auto 0 auto;
	max-width: 100%;
}

.spec-list {
	margin-bottom: 12.5rem;
	padding-left: 2rem;
	font-family: "Lato", sans-serif;
	font-size: 2rem;
	font-weight: 300;
}

/* MEDIA */
@media (max-width: 1200px) {
	.spec-list {
		margin-left: 2rem;
	}
}

@media (max-width: 768px) {
	.spec-heading {
		margin-top: 2rem;
		font-size: 3rem;
	}

	.spec-img {
		margin-top: 3rem;
	}
}
</style>
