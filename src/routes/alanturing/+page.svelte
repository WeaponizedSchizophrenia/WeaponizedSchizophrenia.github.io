<script>
	import Card from '../../components/Card.svelte';
</script>

<Card>
	<img
		src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/40/Alan_Turing_%281912-1954%29_in_1936_at_Princeton_University_%28cropped%29.jpg/220px-Alan_Turing_%281912-1954%29_in_1936_at_Princeton_University_%28cropped%29.jpg"
		alt="Alano Tiuringo nuotrauka"
	/>
	<div>
		<p>
			<strong>Alanas Turingas</strong> buvo britų matematikas, kriptografas ir vienas iš moderniosios
			kompiuterijos pradininkų. Jis labiausiai žinomas dėl savo darbo Antrojo pasaulinio karo metu, kai
			padėjo iššifruoti nacių „Enigma“ kodus, tai labai prisidėjo prie karo baigties. Tačiau jo indėlis
			į informatiką ir dirbtinį intelektą yra ne mažiau reikšmingas.
		</p>
		<p>
			1940-ųjų pabaigoje Turingas pristatė teoriją apie „universaliąją mašiną“, kuri galėtų atlikti
			bet kokią skaičiavimo užduotį, jei jai būtų pateikta teisinga instrukcija. Ši idėja tapo
			kompiuterių mokslo pagrindu. Jo garsusis 1950 metų darbas „Skaičiavimo mašinos ir intelektas“
			(angl. "Computing Machinery and Intelligence") iškėlė klausimą, ar mašinos gali mąstyti, ir
			supažindino pasaulį su tuo, ką šiandien vadiname Turingo testu – eksperimentu, skirtu
			įvertinti dirbtinio intelekto gebėjimą imituoti žmogišką mąstymą.
		</p>
		<p>
			Turingas laikomas vienu iš dirbtinio intelekto mokslų pradininkų dėl savo įžvalgų apie tai,
			kaip mašinos galėtų imituoti žmogaus intelektą. Jo idėjos suformavo pagrindą, ant kurio
			šiandien kuriama dauguma DI sistemų.
		</p>
	</div>
</Card>

<style>
	img {
		border-radius: 100px;
	}
	div {
		margin: 2rem;
	}
	p {
		color: white;
	}
</style>
