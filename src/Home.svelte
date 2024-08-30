<script lang="js">
  import { Link } from "svelte-routing";
</script>

<header>
  <h2>Cultive Seu Jardim com Gerenciamento Inteligente de Recursos</h2>
  <p>Otimize sua experiência de jardinagem com nossa solução completa</p>
</header>

<section class="features box">
  <div class="feature">
    <h3>Acompanhe Recursos</h3>
    <p>Monitore o uso de água, saúde do solo e aplicação de fertilizantes</p>
  </div>
  <div class="feature">
    <h3>Calendário de Plantio</h3>
    <p>Cronogramas personalizados de plantio e colheita</p>
  </div>
  <div class="feature">
    <h3>Conselhos de Especialistas</h3>
    <p>Acesso a dicas de jardinagem e fóruns da comunidade</p>
  </div>
</section>

<section class="about box">
  <h2>Sobre o Kaáuni</h2>
  <p>
    Kaáuni é seu companheiro definitivo para jardinagem eficiente e sustentável.
    Nosso aplicativo ajuda você a gerenciar os recursos do seu jardim,
    acompanhar o crescimento das plantas e otimizar suas práticas de jardinagem.
  </p>

  <h3>Desafios que Resolvemos</h3>
  <p>
    O Kaáuni foi desenvolvido para abordar os principais desafios enfrentados
    pelos jardineiros modernos:
  </p>
  <ul>
    <li>Uso excessivo de água e fertilizantes</li>
    <li>Dificuldade em manter um cronograma de plantio e colheita eficiente</li>
    <li>
      Falta de conhecimento sobre cuidados específicos para diferentes plantas
    </li>
    <li>Detecção tardia de doenças e pragas</li>
    <li>Desperdício de recursos devido à falta de monitoramento preciso</li>
    <li>Isolamento e falta de suporte da comunidade de jardinagem</li>
  </ul>

  <h3>Nossos Objetivos</h3>
  <ul>
    <li>Promover práticas de jardinagem sustentáveis</li>
    <li>Simplificar o gerenciamento de recursos para jardineiros</li>
    <li>Construir uma comunidade de jardineiros experientes</li>
  </ul>
  <h3>Vantagens</h3>
  <ul>
    <li>Interface intuitiva para fácil acompanhamento de recursos</li>
    <li>
      Recomendações personalizadas baseadas nas necessidades do seu jardim
    </li>
    <li>
      Integração com dispositivos de jardim inteligentes para dados em tempo
      real
    </li>
  </ul>
  <h3>Modelo de Negócio</h3>
  <p>
    O Kaáuni oferece um modelo freemium. Recursos básicos estão disponíveis
    gratuitamente, enquanto recursos avançados como detecção de doenças em
    plantas com IA e conselhos premium de especialistas estão disponíveis
    através de uma assinatura mensal.
  </p>

  <h3>Nossos Diferenciais</h3>
  <p>
    Enquanto existem outras soluções de jardinagem no mercado, o Kaáuni se
    destaca por:
  </p>
  <ul>
    <li>Foco em sustentabilidade e eficiência de recursos</li>
    <li>Integração avançada com dispositivos IoT para jardins</li>
    <li>Comunidade ativa de jardineiros e especialistas</li>
    <li>Algoritmos de IA para detecção precoce de doenças em plantas</li>
    <li>
      Interface intuitiva e fácil de usar para todos os níveis de experiência
    </li>
  </ul>

  <h3>Lançamento no Mercado</h3>
  <p>
    O Kaáuni será introduzido no mercado através de uma estratégia multi-canal:
  </p>
  <ul>
    <li>
      Campanha de marketing digital focada em redes sociais e blogs de
      jardinagem
    </li>
    <li>
      Parcerias com influenciadores e especialistas em jardinagem para
      demonstrações e avaliações
    </li>
    <li>
      Período de teste gratuito para usuários iniciais, incentivando feedback e
      melhorias
    </li>
    <li>
      Participação em feiras e eventos de jardinagem para demonstrações ao vivo
    </li>
    <li>
      Programa de indicação para usuários existentes, recompensando-os por
      trazer novos jardineiros para a plataforma
    </li>
  </ul>
</section>

<style>
  .box {
    padding: 2rem;
    margin-bottom: 2rem;
    border-radius: 8px;
  }

  header {
    padding: 2rem;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  header > h2 {
    max-width: 20em;
  }

  .about.box {
    background-color: #fff5e6;
  }

  /* You may need to adjust these styles to fit your design preferences */
  h2,
  h3 {
    margin-top: 0;
  }

  ul {
    padding-left: 1.5rem;
  }
</style>
