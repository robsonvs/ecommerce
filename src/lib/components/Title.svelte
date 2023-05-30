<script lang="ts">
    export let title: string
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>

<h1>{title}</h1> <hr/>

<style>
    hr {
        padding-bottom: 5PX;
        border-radius: 10px;
        margin-bottom: 20px;
    }
</style>