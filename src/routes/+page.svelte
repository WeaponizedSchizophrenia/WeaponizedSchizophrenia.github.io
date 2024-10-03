<script>
	import { base } from '$app/paths';
	import Card from '../components/Card.svelte';
</script>

<Card display="block">
	<h1>Sveiki atvykę į Dirbtinio Intelekto pasaulį!</h1>
	<p>
		Ši svetainė sukurta tam, kad padėtų jums geriau suprasti dirbtinio intelekto (DI) pagrindus, jo
		raidą, bei jo įtaką mūsų kasdieniam gyvenimui. Nors DI atrodo sudėtinga ir technologiškai
		pažangi sritis, mūsų tikslas yra paaiškinti šią technologiją paprastai ir suprantamai.
	</p>
</Card>

<Card display="block">
	<h2>Kodėl Dirbtinis Intelektas yra svarbus?</h2>
	<p>
		Dirbtinis intelektas keičia pasaulį taip, kaip kompiuteriai pakeitė žmonių gyvenimus praėjusio
		šimtmečio pabaigoje. Jis jau dabar yra plačiai naudojamas įvairiose srityse – nuo medicinos iki
		pramogų industrijos, nuo transporto iki kasdieninių namų asistentų. Šioje svetainėje mes
		išnagrinėsime, kaip veikia DI, kaip jis buvo sukurtas ir kokią ateitį mums gali atnešti.
	</p>
</Card>

<Card>
	<h2><a href="{base}/di">Kas yra Dirbtinis Intelektas?</a></h2>
</Card>

<style>
	* {
		color: white;
	}
</style>
