<script>
	import { base } from '$app/paths';
	import Card from '../../components/Card.svelte';
</script>

<Card display="block">
	<h3>Kas yra Dirbtinis Intelektas?</h3>
	<p>
		Dirbtinis intelektas (DI) – tai kompiuterių mokslų sritis, kuri siekia sukurti sistemas,
		gebančias atlikti užduotis, reikalaujančias žmogiško intelekto. DI apima užduotis, tokias kaip
		mokymasis, problemų sprendimas, sprendimų priėmimas, kalbos atpažinimas ir vaizdų apdorojimas.
	</p>
</Card>

<Card display="block">
	<h3>Dirbtinio Intelekto Istorija</h3>
	<p>
		Dirbtinio intelekto idėjos atsirado XX amžiaus viduryje, kai mokslininkai, tokie kaip <a
			href="{base}/alanturing">Alanas Tiuringas</a
		>, pradėjo kelti klausimus apie mašinų gebėjimą mąstyti. 1956 metais Darthmouto konferencijoje
		DI buvo pripažinta atskira mokslo sritimi, o nuo tada mokslininkai ėmė kurti algoritmus, kurie
		galėtų imituoti žmogaus mąstymo procesus.
	</p>
	<p>
		Viena iš pirmųjų sėkmių buvo kompiuterių programų sukūrimas, galinčių žaisti šachmatais. Nors
		pirmieji DI metodai buvo riboti, tobulėjant kompiuterinei įrangai ir duomenų analizei, DI
		galimybės pradėjo sparčiai plėstis.
	</p>
</Card>

<Card display="block">
	<h3>Kaip veikia Dirbtinis Intelektas?</h3>
	<p>
		Šiuolaikiniai DI algoritmai yra pagrįsti <a
			href="https://lt.wikipedia.org/wiki/Ma%C5%A1ininis_mokymasis">mašininiu mokymusi</a
		>, tai yra procesu, kai sistema mokosi iš duomenų ir patirties, o ne yra tiesiogiai
		programuojama atlikti specifines užduotis. Viena iš populiariausių technologijų, kuri leidžia DI
		pasiekti aukštą našumą, yra
		<a href="https://www.unite.ai/lt/what-is-deep-learning/">gilusis mokymasis</a>, kuris naudoja
		<a href="https://lt.wikipedia.org/wiki/Dirbtinis_neuroninis_tinklas">neuroninius tinklus</a>,
		panašius į žmogaus smegenų struktūrą.
	</p>
	<p>
		Mašininiam mokymuisi reikalingi dideli duomenų kiekiai, kurie padeda DI sistemoms atpažinti
		šablonus ir daryti prognozes. Pavyzdžiui, norint sukurti DI, kuris gali atpažinti objektus
		nuotraukose, algoritmas mokomas tūkstančiais vaizdų, kuriuose objektai yra žymėti. Per tam tikrą
		laiką sistema išmoksta atpažinti objektus, kurių ji anksčiau nematė.
	</p>
</Card>

<Card display="block">
	<h3>Dirbtinio Intelekto Tipai</h3>
	<p>Dirbtinis intelektas skirstomas į kelis tipus, priklausomai nuo jo gebėjimų:</p>
	<ul>
		<li>
			<a href="https://en.wikipedia.org/wiki/Weak_artificial_intelligence"
				>Siaurasis DI (angl. Narrow AI)</a
			> – tai DI, sukurtas atlikti vieną specifinę užduotį, pvz., balsų atpažinimą ar rekomendacijas
			filmuose. Dauguma šiandien naudojamų DI sistemų yra siaurojo tipo.
		</li>
		<li>
			<a href="https://en.wikipedia.org/wiki/Artificial_general_intelligence"
				>Bendrasis DI (angl. General AI)</a
			> – tai teorinė DI forma, kuri galėtų atlikti bet kokią intelektinę užduotį, kurią gali atlikti
			žmogus. Toks DI dar neegzistuoja, bet tai yra vienas iš pagrindinių DI tyrimų tikslų.
		</li>
	</ul>
</Card>

<Card display="block">
	<h3>Kur naudojamas Dirbtinis Intelektas?</h3>
	<p>Dirbtinis intelektas jau dabar plačiai naudojamas įvairiose srityse:</p>
	<ul>
		<li><strong>Medicinoje</strong> – diagnozuoti ligas ir analizuoti medicininius duomenis.</li>
		<li>
			<strong>Versle</strong> – pagerinti klientų aptarnavimą, optimizuoti gamybą ir analizuoti rinkos
			tendencijas.
		</li>
		<li><strong>Transporte</strong> – autonominiai automobiliai ir logistikos optimizavimas.</li>
		<li>
			<strong>Kasdieniniame gyvenime</strong> – balso asistentai, tokie kaip „Siri“ ir „Google Assistant“,
			bei rekomendacijų sistemos „Netflix“ ar „YouTube“ platformose.
		</li>
	</ul>

	<p>
		Dirbtinio intelekto pažanga per pastaruosius dešimtmečius atvėrė daugybę galimybių spręsti
		sudėtingas problemas ir padaryti mūsų gyvenimą patogesnį, tačiau kartu ji kelia ir etinius
		klausimus, kaip atsakingai naudoti šią technologiją.
	</p>
</Card>

<style>
	* {
		color: white;
		font-size: 1.1rem;
	}
</style>
