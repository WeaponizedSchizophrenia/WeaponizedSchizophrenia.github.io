<script lang="ts">
	export var display = 'flex';
</script>

<div class="card" style="display: {display};">
	<slot />
</div>

<style>
	.card {
		background: #353535;
		margin: 2rem;
		padding: 3rem;
		border-radius: 5rem;
		justify-content: space-between;
		align-items: center;
	}
</style>
