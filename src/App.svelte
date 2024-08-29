<script lang="ts">
  import { Router, Route, Link } from 'svelte-routing';
  import Home from './Home.svelte';
  import GetStarted from './routes/GetStarted.svelte';
  import plantLogo from './assets/plant-logo.svg';

  export let url = '';
</script>

<Router {url}>
  <nav>
    <Link to="/"><img src={plantLogo} class="logo" alt="Logo Kaáuni" /></Link>
    <h1><Link to="/">Kaáuni</Link></h1>
  </nav>

  <main>
    <Route path="/" component={Home} />
    <Route path="/get-started" component={GetStarted} />
  </main>

  <footer>
    <p>&copy; 2023 Kaáuni. Todos os direitos reservados.</p>
  </footer>
</Router>

<style>
  nav {
    background-color: #4CAF50; /* Change this to your desired color */
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Add dropdown shadow */
    padding: 1rem;
  }

  nav :global(a) {
    color: white;
    text-decoration: none;
  }

  h1 {
    margin: 0;
  }

  .logo {
    height: 2rem;
    margin-right: 1rem;
  }
</style>
