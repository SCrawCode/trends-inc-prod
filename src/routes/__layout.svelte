<script>
    import Footer from '../components/Footer.svelte';
    import Navbar from '../components/Navbar.svelte'
</script>

<div class="container">
    <div class="navbar">
        <Navbar />
    </div>
    <div class="content">
        <slot></slot>
    </div>
        <Footer />
</div>


<style>

    .container {
        overflow-x: hidden;
    }

</style>