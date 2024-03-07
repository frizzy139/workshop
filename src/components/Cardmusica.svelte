<script>
	export let disco;
	export let artista;
	export let anno;
	export let durata;
	export let cope;
</script>

<div class="music">
	<img class="foto" src={cope} alt="copesfera" />

	<div>
		<div class="riga">
			<p class="stile">{artista}</p>
			<p>{anno}</p>
		</div>

		<div class="riga">
			<p>{disco}</p>
			<p>{durata}</p>
		</div>
	</div>
</div>

<style>
	.stile {
		font-size: 25px;
	}

	.music {
		background-color: rgb(215, 4, 215);
		width: 300px;
		border-radius: 20px;
		padding: 15px;
	}

	.foto {
		border-radius: 20px;
		width: 100%;
	}
	.riga {
		display: flex;
		flex-direction: row;
		justify-content: space-between;
		padding-right: 5px;
		padding-left: 5px;
		align-items: end;
	}
</style>
