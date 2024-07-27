<script>
    import { afterNavigate } from "$app/navigation";
    import "../app.css";
    import Footer from "./layouts/Footer.svelte";
    import Navbar from "./layouts/Navbar.svelte";

    afterNavigate(() =>{
        window.HSStaticMethods.autoInit();
    })
</script>

<Navbar />

<slot />

<Footer />