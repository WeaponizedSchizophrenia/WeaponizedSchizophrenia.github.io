<script>
	import { base } from '$app/paths';
</script>

<div class="school">
	<img
		src="https://gruso.lt/wp-content/uploads/2021/11/mokyklos-logo-watermark-100.png"
		alt="Kauno Juozo Grušo meno gimnazijos logotipas"
		width="200"
		height="200"
	/>
	<div class="school-text">
		<p><strong>Laurynas Ramankevičius.</strong></p>
		<p>
			Aš mokausi
			<a href="https://gruso.lt/" class="school-link"> Kauno Juozo Grušo meno gimnazijoje </a>12B
			klasėje, kuri garsėja kūrybiškumo ir inovacijų skatinimu bei meno ir akademinių disciplinų
			derinimu.
		</p>
		<br />
		<p>
			Esu mokinys, kuris nuolat siekia gilinti savo žinias tiek menų, tiek technologijų srityse.
			Šiuo metu ypatingai domiuosi dirbtiniu intelektu ir jo galimybėmis spręsti realaus pasaulio
			problemas. Nuolatinis žinių gilinimas ir praktiniai projektai leidžia man ne tik tobulėti kaip
			asmenybei, bet ir prisidėti prie pažangesnės visuomenės kūrimo.
		</p>

		<p>
			Šią svetainę kuriu kaip mokyklinį projektą, kuriuo siekiu supažindinti lankytojus su <a
				href="{base}/di"
				class="school-link">dirbtinio intelekto pagrindais.</a
			> Mano tikslas yra paprastai ir suprantamai paaiškinti, kas yra dirbtinis intelektas, kaip jis
			veikia, bei kokios jo pritaikymo galimybės įvairiose gyvenimo srityse. Tai ne tik edukacinė, bet
			ir praktinė užduotis, leidžianti man pritaikyti savo žinias ir gilinti supratimą apie šią technologiją.
		</p>

		<p>
			Savo mokyklos veiklose dažnai taikau novatoriškus technologinius sprendimus, o dirbtinis
			intelektas man yra ne tik akademinis interesas, bet ir įrankis siekti geresnių rezultatų
			įvairiose gyvenimo srityse. Mokymasis šioje gimnazijoje suteikia galimybę kūrybiškai plėsti
			savo horizontus ir tyrinėti pažangiausius technologijų sprendimus.
		</p>
	</div>
</div>

<style>
	.school {
		background: #353535;
		margin: 2rem;
		padding: 1rem;
		border-radius: 5rem;
		display: flex;
		justify-content: space-between;
		align-items: center;
	}
	img {
		background: white;
		border-radius: 100px;
		margin: 0.5rem;
		flex-shrink: 0;
	}
	.school-text {
		margin: 0.5rem;
	}
	.school-text > p {
		color: white;
		text-wrap: balance;
	}
	.school-link {
		color: white;
	}
	.school-link:hover {
		color: lightskyblue;
	}
</style>
