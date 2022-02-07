<template>
	<section class="spec">
		<div class="spec-container">
			<table class="spec-table">
				<!-- Added space for first column -->
				<thead>
					<tr>
						<td><h2 class="spec-heading">Specyfikacja</h2></td>
					</tr>
				</thead>
				<tbody>
					<col class="spec-col-one" />
					<tr>
						<td>Procesor</td>
						<td>Do Intel® Core™ i7 10. generacji</td>
					</tr>
					<tr>
						<td>System operacyjny</td>
						<td>Windows 10 Home</td>
					</tr>
					<tr>
						<td>Wyświetlacz</td>
						<td>
							14” UHD (3840 x 2160) HDR IPS, 500 nitów z Dolby Vision‡ <br />
							14” FHD (1920 x 1080) IPS, 400 nitów z Dolby Vision <br />
							Wąskie ramki ekranu: lewa/prawa: 3,4 mm, górna 6,7 mm, dolna: 11,8
							mm <br />
							‡ Spodziewana dostępność w modelu HDR z końcem 2019 r.
						</td>
					</tr>
					<tr>
						<td>Pamięć</td>
						<td>Do 16 GB pamięci LPDDR4X</td>
					</tr>
					<tr>
						<td>Bateria</td>
						<td>
							Do 15 godzin z wyświetlaczem FHD <br />
							Do 10 godzin z wyświetlaczem UHD <br />
							<span>
								* Na podstawie testu MobileMark 2014. Czas działania baterii
								znacznie się różni w zależności od ustawień, sposobu
								wykorzystania i innych czynników.</span
							>
						</td>
					</tr>
					<tr>
						<td>Pamięć masowa</td>
						<td>Do 1 TB PCIe SSD</td>
					</tr>
					<tr>
						<td>Grafika</td>
						<td>
							Intel® HD Iris <br />
							Opcjonalnie: NVIDIA® GeForce® MX250 2GB
						</td>
					</tr>
					<tr>
						<td>Zabezpieczenia</td>
						<td>Kamera na podczerwień do logowania się bez użycia rąk</td>
					</tr>
					<tr>
						<td>Dźwięk</td>
						<td>
							Dolby Atmos® Speaker System <br />
							Mikrofony dalekiego zasięgu
						</td>
					</tr>
					<tr>
						<td>Asystenci cyfrowi</td>
						<td>
							Cortana <br />
							Alexa <br />† † Spodziewana dostępność z końcem 2019 r. Tylko na
							wybranych rynkach.
						</td>
					</tr>
					<tr>
						<td>Kamera</td>
						<td>720p</td>
					</tr>
					<tr>
						<td>Wymiary (szer. x wys. x głęb.)</td>
						<td>
							322,3 mm x 212 x 14,9 mm krawędź przednia i 18,1 mm krawędź tylna
						</td>
					</tr>
					<tr>
						<td>Waga</td>
						<td>Od 1,4 kg</td>
					</tr>
					<tr>
						<td>Opcje kolorystyczne</td>
						<td>
							Iron Grey (żelaznoszary) <br />
							Mika
						</td>
					</tr>
					<tr>
						<td>Łączność</td>
						<td>
							Intel® Wireless-AC 2x2 <br />
							Wi-Fi 6 (dostępność z końcem 2019 r.)
						</td>
					</tr>
					<tr>
						<td>Klawiatura</td>
						<td>Podświetlana klawiatura</td>
					</tr>
					<tr>
						<td>Gniazda</td>
						<td>
							USB-C (USB + DisplayPort + zasilanie + Thunderbolt™ 3) <br />
							2 x USB 3.1 (2. generacji, jedno zawsze aktywne) <br />
							Gniazdo słuchawek/mikrofonu <br />
							Zasilanie <br />
						</td>
					</tr>
				</tbody>
			</table>
			<div class="spec-region-info">
				Dane techniczne mogą zależeć od regionu
			</div>
			<div class="spec-info-img">
				<h2 class="spec-heading">Specyfikacja</h2>
				<img
					src="../assets/product-5.png"
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
		</div>
	</section>
</template>

<script>
export default {};
</script>

<style>
.spec {
	background-color: #ffffff;
}
.spec-container {
	display: flex;
	flex-direction: column;
	margin: 0 30rem;
	overflow-x: auto;
}

.spec-heading {
	margin-top: 6rem;
	font-family: "Lato", sans-serif;
	font-size: 5rem;
	color: #000000;
	font-weight: 300;
	line-height: 6rem;
}
.spec-table {
	border-collapse: collapse;
	width: 100%;
	font-family: "Lato", sans-serif;
	font-size: 2rem;
	font-weight: 300;
	line-height: 3rem;
}

/* First column space */
.spec-col-one {
	width: 30%;
}

.spec-table td {
	padding: 1.2rem 0;
	vertical-align: top;
	color: #000000;
}

.spec-table span {
	font-size: 1rem;
}

.spec-region-info {
	display: flex;
	justify-content: flex-end;
	font-size: 1rem;
}

.spec-table tr {
	border-bottom: 1px solid #979797;
}

.spec-table tr:last-child {
	border-bottom: none;
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
	.spec-container {
		margin: 0 auto;
		padding: 0 2.5rem;
	}

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
