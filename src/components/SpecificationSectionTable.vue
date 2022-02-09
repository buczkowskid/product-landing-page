<template>
	<div>
		<table class="spec-table">
			<thead>
				<tr>
					<td><h2 class="spec-heading">Specyfikacja</h2></td>
				</tr>
			</thead>
			<tbody>
				<!-- Added space for first column -->
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
						mm
						<br />
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
							znacznie się różni w zależności od ustawień, sposobu wykorzystania
							i innych czynników.</span
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
	</div>
</template>

<script>
export default {};
</script>

<style>
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

.spec-table tr {
	border-bottom: 1px solid #979797;
}

.spec-table tr:last-child {
	border-bottom: none;
}

/* MEDIA */

@media (max-width: 768px) {
	.spec-heading {
		margin-top: 2rem;
		font-size: 3rem;
	}
}

@media (max-width: 320px) {
	.spec-table {
		font-size: 1.6rem;
	}
}
</style>
