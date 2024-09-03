<script lang="js">
  import { Router, Route, Link } from "svelte-routing";
  import Home from "./Home.svelte";
  import plantLogo from "./assets/plant-logo.svg";
  import { onMount } from "svelte";

  export let url = "";

  const html = /** @type {HTMLElement}*/ (document.children[0]);
  let h2 = null;
  html.style.backgroundPositionY = `${Math.sin((0 - 1) * 0.05 + 1) * 100}px`;

  document.addEventListener("scroll", (e) => {
    let scrollY = html.scrollTop;
    html.style.backgroundPositionY = `${Math.pow((scrollY - 5.0) * 0.02 + 5.0, 0.3) * 1000.0}px`;
    let value = 1 - scrollY / 200;
    h2.style.filter = `drop-shadow(0px ${5 * value}px 0px hsl(50, 70%, 60%, 60%))
      drop-shadow(0px ${value * 10}px 0px hsl(100, 70%, 60%, 60%))`;
  });
  onMount(() => {
    h2 = document.querySelector("header");
  });
</script>

<Router {url}>
  <nav>
    <Link to="/"><img src={plantLogo} class="logo" alt="Logo Kaáuni" /></Link>
    <Link to="/">Kaáuni</Link>
  </nav>

  <main>
    <Route path="/" component={Home} />
  </main>

  <footer>
    <p>&copy; 2024 Kaáuni. Todos os direitos reservados.</p>
  </footer>
</Router>

<style>
  nav {
    /* background-color: #4caf50; */
    /* box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); */
    padding: 1rem;
    position: absolute;
    /* width: 100%; */
    height: fit-content;
    border-radius: 0 10px 10px 0;
    background: hsl(0, 0%, 100%);
    margin-top: 20px;
  }

  nav :global(a) {
    color: hsl(0, 0%, 20%);
    text-decoration: none;
    display: flex;
    font-size: 1em;
  }

  .logo {
    height: 2rem;
    margin-right: 0.5rem;
  }
</style>
