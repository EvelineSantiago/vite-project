<script lang="js">
  import { Router, Route, Link } from "svelte-routing";
  import Home from "./Home.svelte";
  import plantLogo from "./assets/plant-logo.svg";

  export let url = "";
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
