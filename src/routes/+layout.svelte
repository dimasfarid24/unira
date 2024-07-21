<script>
    import { afterNavigate } from "$app/navigation";
    import "../app.css";
  import Body from "./layouts/Body.svelte";
  import Footer from "./layouts/Footer.svelte";
  import Navbar from "./layouts/Navbar.svelte";

    afterNavigate(() =>{
        window.HSStaticMethods.autoInit();
    })
</script>

<Navbar />

<Body>
    <slot></slot>
</Body>

<Footer />