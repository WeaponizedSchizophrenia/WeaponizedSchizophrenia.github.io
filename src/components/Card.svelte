<script lang="ts">
	export var display = 'flex';
	export var style = '';
</script>

<div class="card" style="display: {display}; {style}">
	<slot />
</div>

<style>
	.card {
		background: #353535;
		margin: 2rem;
		padding: 1rem;
		border-radius: 5rem;
		justify-content: space-between;
		align-items: center;
	}
</style>
