<script>
    import '../app.css';
    import Navbar from '../components/Navbar.svelte';
    export const prerender = true;
</script>


<Navbar />
<slot></slot>

<style lang="postcss">

</style>