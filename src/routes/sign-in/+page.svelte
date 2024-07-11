<script lang="ts">
	import SignIn from 'clerk-sveltekit/client/SignIn.svelte';
</script>

<div>
	<SignIn
		redirectUrl="/admin"
		appearance={{
			variables: {
				colorPrimary: '#ff3e00'
			}
		}}
	/>
</div>
