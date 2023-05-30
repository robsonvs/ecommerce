<script lang="ts">
    import { page } from '$app/stores'
</script>

<nav>
    <a href="/" class:active={$page.url.pathname === '/'}>home</a>
    <a href="/about" class:active={$page.url.pathname === '/about'}>about</a>
</nav>

<style>

</style>