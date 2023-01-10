<script>
	import Navbar from '../components/Navbar.svelte'
    import MainBody from '../components/MainBody.svelte'
    import '../app.css'
    
</script>
<div class="mx-auto">
<Navbar />
<MainBody />
</div>
<style global>
    :global(body) {
        background:#E5E5E5;
        
    }
    :global(*)
    {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
</style>