<script lang="ts">
	import Card from '../../components/Card.svelte';
	const images = [
		'https://cdn.midjourney.com/80179f60-de19-4cad-9e6e-d98ae3fe0751/0_0_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/8dc929de-3595-4b71-bf06-9569843580a9/0_2_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/e61957c1-5b78-4151-b31d-fe4fe6bd90f2/0_3_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/f7a371e0-29f4-40c8-bde9-ed494ea872d4/0_2_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/b7059f37-b980-458e-9933-5da1ac1f60b0/0_3_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/8075669f-7113-4098-8bc9-8ed1246a5405/0_0_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/6950d30c-1dd4-4c7b-bed3-6c788d31cc47/0_0_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/017b91d2-12c9-488d-be40-362870b30937/0_0_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/9588d5df-1bc8-4bf4-921c-b7c1e1851bad/0_0_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/ebb1ba96-9dab-45fc-996b-6ddd014d7714/0_2_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/190403b8-9d88-4030-a5e7-c135b404faef/0_1_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/83f0680b-f5da-4d92-be9d-b637447767dd/0_0_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/9bad7571-8cf2-4a58-9ecf-0478a303edb0/0_2_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/d286cad4-e0a8-426d-afad-d1b50a9dd0fe/0_1_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/7a2064de-adb3-453f-a627-d860d5216433/0_0_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/b61fe7d0-b594-45b9-8ac0-6bbdb60953aa/0_2_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/f0a4cb1a-7c95-4a46-91b7-0ccf268dcbb4/0_1_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/13e7b183-4bf4-446d-b20c-46e588179302/0_3_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/55727bf2-fb55-4761-959d-f07d29a43356/0_0_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/73d1b707-ac8e-4b7e-a1fe-07b5a7a81595/0_0_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/0178ec6a-6596-48b1-9bbd-65fda6f45fcc/0_0_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/eaebf9e3-9786-409d-85cd-a79b662336a3/0_0_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/c9ae76e6-dcc7-4670-8704-5b58bdc82479/0_1_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/1755a029-0d61-4c54-805e-cffb70ef203c/0_3_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/f0a4cb1a-7c95-4a46-91b7-0ccf268dcbb4/0_1_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/b8799b6c-de36-41c1-bc79-1c88806c3cc5/0_2_384_N.webp?method=shortest&qst=6&quality=15',
		'https://cdn.midjourney.com/5d178c93-7281-432d-ad39-6230d95c8b2c/0_0_384_N.webp?method=shortest&qst=6&quality=15'
	];
</script>

<Card display="block">
	<h1>Kas yra Generatyvusis Dirbtinis Intelektas?</h1>
	<p>
		Generatyvusis dirbtinis intelektas (DI) – tai DI technologija, galinti kurti naują turinį,
		remiantis esamais duomenimis. Skirtingai nuo kitų DI tipų, kurie analizuoja arba prognozuoja,
		generatyvusis DI kuria tekstą, vaizdus, muziką ir netgi vaizdo įrašus, imituodamas žmogiškąjį
		kūrybingumą.
	</p>
</Card>

<Card display="block">
	<h2>Kaip veikia Generatyvusis DI?</h2>
	<p>
		Generatyvusis DI naudoja pažangius modelius, tokius kaip neuroniniai tinklai ir gilusis
		mokymasis, kad išmokytų sistemas atpažinti šablonus didžiuliuose duomenų rinkiniuose. Vienas
		žymiausių generatyvaus DI modelių yra „Generative Adversarial Network“ (GAN), kur du neuroniniai
		tinklai varžosi tarpusavyje: vienas kuria naują turinį, o kitas bando įvertinti jo autentiškumą.
		Tokiu būdu sistema nuolat tobulėja ir mokosi kurti tikrovišką, naują turinį.
	</p>
</Card>

<Card display="block">
	<h2>Kur naudojamas Generatyvusis DI?</h2>
	<p>Generatyvusis DI jau dabar turi platų pritaikymą įvairiose srityse:</p>
	<ul>
		<li>
			<strong>Vaizdo ir grafikos kūrimas:</strong> Kuria vaizdus, meno kūrinius arba animacijas, naudodamas
			algoritmus.
		</li>
		<li>
			<strong>Teksto generavimas:</strong> Kuria naujas istorijas, straipsnius arba netgi poeziją.
		</li>
		<li>
			<strong>Muzikos kūrimas:</strong> Modeliai gali kurti naujas melodijas ar netgi imituoti garsaus
			kompozitoriaus stilių.
		</li>
		<li>
			<strong>Filmų ir vaizdo kūrimas:</strong> Galima sukurti filmų scenarijus arba generuoti vaizdo
			klipus remiantis esamais duomenimis.
		</li>
	</ul>

	<p>
		Generatyvusis DI ne tik palengvina kūrybinių procesų automatizavimą, bet ir sukuria visiškai
		naujas galimybes žmonėms dirbti kartu su technologijomis. Galerijoje galite pamatyti pavyzdžius,
		kaip ši technologija pritaikoma meno, dizaino ir kitose kūrybinėse srityse.
	</p>
</Card>

<Card display="block">
	<h1>Generatyvaus intelekto sukurtos nuotraukos</h1>
	<br />
	<p>Naudota: <a href="https://www.midjourney.com/home">MidJourney</a></p>
	<br />
	<div class="gallery">
		{#each images as image}
			<img src={image} alt="Dirbtinio intelekto sukurta nuotrauka" />
		{/each}
	</div>
</Card>

<style>
	* {
		color: white;
	}
	.gallery {
		display: flex;
		flex-wrap: wrap;
		justify-content: flex-start;
		gap: 1rem;
	}
	img {
		flex: none;
		object-fit: cover;
		align-self: center;
		border-radius: 1rem;
		border: solid 0.3rem #20202f;
	}
</style>
