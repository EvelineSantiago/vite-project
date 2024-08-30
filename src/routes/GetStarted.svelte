<script>
  import { Link } from "svelte-routing";
</script>

<main>
  <h1>Comece com o GardenSmart</h1>
  <p>
    Bem-vindo ao GardenSmart! Siga estes passos para iniciar sua jornada de
    jardinagem inteligente:
  </p>

  <ol>
    <li>Crie uma conta</li>
    <li>Configure o perfil do seu jardim</li>
    <li>Adicione suas plantas</li>
    <li>Comece a acompanhar seus recursos</li>
  </ol>

  <button>Criar Conta</button>

  <p>Já tem uma conta? <Link to="/login">Entrar</Link></p>
</main>

<style>
  main {
    max-width: 800px;
    margin: 0 auto;
    padding: 2rem;
  }

  h1 {
    color: var(--primary-color);
  }

  ol {
    margin-bottom: 2rem;
  }

  button {
    margin-bottom: 1rem;
  }
</style>
