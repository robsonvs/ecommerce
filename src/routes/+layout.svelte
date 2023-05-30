<script lang="ts">
	import '$lib/firestore/firebase.client'
    
    import Footer from "$lib/components/Footer.svelte";
    import Header from "$lib/components/Header.svelte";

</script>

<Header />

<main>
    <slot />
</main>

<Footer />

<style>

</style>