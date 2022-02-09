<template>
	<section class="features">
		<div v-for="features of featuresData" :key="features.id">
			<FeaturesSectionText :featuresData="features" />
		</div>
	</section>
</template>

<script>
import FeaturesSectionText from "./FeaturesSectionText.vue";

export default {
	components: {
		FeaturesSectionText,
	},
	data() {
		return {
			featuresData: [
				{
					id: 1,
					image: {
						src: require("../assets/images/products/product-1.png"),
						alt: "Laptop Lenovo Yoga S740",
					},
					title: "Pomysłowe technologie dla wszystkich",
					text: "Lenovo poszerza zakres możliwości w nowych laptopach Yoga opracowanych wspólnie z firmą Intel® i wyposażonych w funkcje sztucznej inteligencji. Teraz możesz mówić do urządzenia i nim sterować z drugiego końca pokoju. Oglądać wideo o podwyższonej jakości w programie Windows Media Player. Unikać zmęczenia oczu dzięki wyświetlaczowi, który automatycznie zmniejsza natężenie światła niebieskiego odpowiednio do pory dnia. A to jeszcze nie wszystko.",
				},
				{
					id: 2,
					image: null,
					title: "Sztuczna inteligencja i zdrowy rozsądek",
					text: "Zaawansowany procesor Intel® Core™ 10. generacji do urządzeń mobilnych i utraprzenośny laptop Yoga S740 dostosowują się do Twoich potrzeb i stylu użytkowania. Razem tworzą rozwiązanie bardziej intuicyjne i osobiste, którego sztuczna inteligencja dynamicznie reaguje na Twoje działania i optymalizuje żywotność baterii.",
				},
				{
					id: 3,
					image: {
						src: require("../assets/images/products/product-7.png"),
						alt: "Zdjęcie laptopa Lenovo Yoga S740 na stole w mieszkaniu",
					},
					title: "Potrzebujesz czegoś? Wystarczy poprosić.",
					text: "Yoga S740 ma mikrofony dalekiego zasięgu i inteligentne asystentki głosowe Alexę oraz Cortanę. Pomogą Ci złożyć zamówienie, ustawić przypomnienie czy odtworzyć muzykę — wystarczy poprosić z odległości do 4 metrów. To kolejny przykład przewagi, jaką daje Ci Yoga S740. Aby uzyskać więcej informacji o Cortanie, kliknij tutaj , a w celu uzyskania dodatkowych informacji o Alexie, kliknij tutaj.",
				},
				{
					id: 4,
					image: null,
					title: "Mobilne kino",
					text: "Wyświetlacz o przekątnej 14 cali w wąskiej jak brzytwa ramce prezentuje imponującą gamę kolorów i szczegółów. Ekran do poziomu 4K VESA400 HDR z jasnością 500 nitów i spektakularną technologią Dolby Vision™ oraz bogaty, wielowarstwowy dźwięk 3D z głośników z Dolby Atmos® oferują niezwykle realistyczną i wciągającą rozrywkę.",
				},
				{
					id: 5,
					image: {
						src: require("../assets/images/products/product-2.png"),
						alt: "Zdjęcie osoby pracującej na laptopie Lenovo Yoga S740",
					},
					title: "Nie ma gniazdka? Nie ma problemu.",
					text: "Niezależnie od tego, czy pracujesz w terenie, czy też urządzasz sobie serialową noc na sofie, bateria eleganckiego i smukłego Yoga S740 ma w sobie wystarczająco dużo energii — na nawet 15 godzin działania.",
				},
				{
					id: 6,
					image: null,
					title: "Nowy poziom wydajności",
					text: "Opcjonalna dedykowana karta graficzna NVIDIA® GeForce® MX250 zwiększa dodatkowo możliwości laptopa w zastosowaniach służbowych i rozrywkowych. Korzystaj z nawet 3,5-krotnie większej wydajności w porównaniu ze zintegrowaną kartą graficzną w aplikacjach do edycji zdjęć i wideo, a także z szybszej i płynniejszej gry.",
				},
				{
					id: 7,
					image: {
						src: require("../assets/images/products/product-3.png"),
						alt: "Zdjęcie osoby pijącej kawę przy laptopie Lenovo Yoga S740",
					},
					title: "Intuicyjnie i interaktywnie",
					text: "Kamera na podczerwień ułatwia życie. Wystarczy, że się oddalisz, a oglądany film zostanie automatycznie wstrzymany. Zawartość wyświetlacza laptopa możesz przenieść na dodatkowy monitor ruchem głowy. A to jeszcze nie wszystko. Laptop Yoga S740 reaguje na Twój styl użytkowania, dlatego możesz skupić się na tym, co ważne.",
				},
				{
					id: 8,
					image: null,
					title: "Zna Cię lepiej",
					text: "Możesz na przykład logować się do niego samym uśmiechem. Dzięki kamerze na podczerwień i funkcji rozpoznawania twarzy Windows Hello możesz zacząć pracę trzy razy szybciej niż wpisując hasło. Jest też świetnie zabezpieczony.",
				},
				{
					id: 9,
					image: {
						src: require("../assets/images/products/product-4.png"),
						alt: "Zdjęcie dwóch laptopów Lenovo Yoga S740 w różnych kolorach",
					},
					title: "Elegancki styl i mobilność",
					text: "Yoga S740 ma obudowę z piaskowanego aluminium z wykończeniem wysokiej klasy i łączy w sobie wysoką wydajność z wygodną mobilnością. Ma jedynie 14,9 mm grubości, a waży zaledwie 1,4 kg i jest dostępny w kolorze żelaznoszarym lub z ciepłym, metalicznym mikowym wykończeniem.",
				},
				{
					id: 10,
					image: null,
					title: "Szybki i elastyczny",
					text: "Yoga S740 ma port Thunderbolt™ 3. Pod względem szybkości przewyższa on port USB 3.0 aż 8 razy, dlatego stanowi najszybszy i najbardziej uniwersalny sposób łączenia z monitorami, stacjami dokującymi i pamięcią masową. Co więcej, służy też jako źródło zasilania. Laptop ma też szybką łączność Wi-Fi 6, dlatego możesz teraz wyświetlać strumieniowe wideo i przeglądać strony internetowe bez porównania płynniej.",
				},
			],
		};
	},
};
</script>

<style>
.features {
	padding-top: 1rem;
	background-color: #ffffff;
}
</style>
