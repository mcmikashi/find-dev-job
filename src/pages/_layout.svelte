<script>
    import Footer from "../UI/Footer.svelte";
    import Header from "../UI/Header.svelte";
</script>

<Header/>
<main class="min-h-screen">
    <slot />
</main>
<Footer/>