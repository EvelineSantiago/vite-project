<script lang="js">
  import { Link } from "svelte-routing";
  import Snap from "snapsvg";

  let d =
    "M199.636 78.750 C 192.987 79.450,186.234 82.321,181.285 86.551 C 179.874 87.757,179.994 87.792,178.829 85.834 C 176.096 81.240,173.237 79.235,169.688 79.423 C 162.148 79.823,162.310 88.924,169.992 96.558 C 172.097 98.650,172.117 98.708,171.354 100.586 C 171.067 101.291,170.573 102.877,170.254 104.111 L 169.676 106.354 167.655 107.334 C 160.714 110.698,160.844 117.708,167.848 117.708 C 169.638 117.708,169.446 117.457,170.269 120.877 C 175.341 141.964,199.441 152.717,218.929 142.588 C 220.345 141.852,221.595 141.250,221.707 141.250 C 222.470 141.250,229.539 134.176,231.080 131.870 C 247.241 107.688,228.321 75.727,199.636 78.750 M172.504 80.399 C 176.240 81.818,180.311 88.033,181.938 94.800 C 182.408 96.754,183.827 103.051,184.094 104.371 C 184.340 105.586,192.499 113.016,195.104 114.398 C 196.759 115.275,196.575 114.784,194.048 111.563 C 189.848 106.210,187.593 97.735,188.953 92.416 C 190.847 85.013,198.024 82.929,199.898 89.238 C 200.636 91.723,200.276 94.248,198.379 99.896 L 197.190 103.438 197.189 108.944 L 197.188 114.450 198.149 115.715 C 199.347 117.290,199.440 117.369,201.960 118.945 C 203.095 119.655,205.129 121.082,206.480 122.117 C 209.434 124.380,209.519 124.359,208.640 121.590 C 204.884 109.753,208.936 97.650,216.897 96.928 C 222.680 96.404,223.230 103.200,217.929 109.688 C 213.694 114.871,213.376 115.414,212.091 119.680 C 211.609 121.280,211.082 122.846,210.920 123.159 C 210.185 124.580,210.579 125.387,213.602 128.655 C 217.982 133.388,223.106 140.862,221.636 140.372 C 221.505 140.328,220.842 139.406,220.163 138.323 C 216.582 132.610,211.380 126.935,208.750 125.872 C 205.434 124.532,204.144 124.261,202.886 124.641 C 202.273 124.827,200.224 125.168,198.333 125.399 C 194.355 125.886,193.861 126.054,188.957 128.575 C 184.763 130.732,182.736 131.352,180.402 131.193 C 173.455 130.721,173.732 123.372,180.823 120.021 C 186.306 117.429,195.726 118.562,202.405 122.616 C 203.880 123.512,206.693 124.418,207.010 124.101 C 207.383 123.728,203.954 121.080,199.271 118.125 C 197.781 117.185,195.605 115.719,194.434 114.866 C 190.906 112.297,188.212 111.283,186.198 111.766 C 185.482 111.937,183.733 112.222,182.311 112.399 C 179.403 112.761,178.230 113.166,174.680 115.030 C 167.123 119.000,161.005 117.018,163.764 111.496 C 166.666 105.689,176.462 104.933,185.760 109.799 C 189.924 111.978,189.992 111.467,186.038 107.705 C 183.948 105.716,182.689 104.694,181.611 104.110 C 169.778 97.701,163.297 89.643,164.974 83.426 C 165.734 80.613,169.296 79.180,172.504 80.399 ";
  // let abspathstring = "";
  let rel = Snap.path.toRelative(d);
  console.log(rel);
</script>

<header class="box">
  <h2>Cultive Seu Jardim com Gerenciamento Inteligente de Recursos</h2>
  <p>Otimize sua experiência de jardinagem com nossa solução completa</p>
</header>

<section class="features box">
  <div class="feature">
    <svg
      id="svg"
      version="1.1"
      xmlns="http://www.w3.org/2000/svg"
      xmlns:xlink="http://www.w3.org/1999/xlink"
      width="400"
      height="225"
      viewBox="0, 0, 400,225"
      ><g id="svgg"
        ><path
          id="path0"
          d="M199.636 78.750 C 192.987 79.450,186.234 82.321,181.285 86.551 C 179.874 87.757,179.994 87.792,178.829 85.834 C 176.096 81.240,173.237 79.235,169.688 79.423 C 162.148 79.823,162.310 88.924,169.992 96.558 C 172.097 98.650,172.117 98.708,171.354 100.586 C 171.067 101.291,170.573 102.877,170.254 104.111 L 169.676 106.354 167.655 107.334 C 160.714 110.698,160.844 117.708,167.848 117.708 C 169.638 117.708,169.446 117.457,170.269 120.877 C 175.341 141.964,199.441 152.717,218.929 142.588 C 220.345 141.852,221.595 141.250,221.707 141.250 C 222.470 141.250,229.539 134.176,231.080 131.870 C 247.241 107.688,228.321 75.727,199.636 78.750 M172.504 80.399 C 176.240 81.818,180.311 88.033,181.938 94.800 C 182.408 96.754,183.827 103.051,184.094 104.371 C 184.340 105.586,192.499 113.016,195.104 114.398 C 196.759 115.275,196.575 114.784,194.048 111.563 C 189.848 106.210,187.593 97.735,188.953 92.416 C 190.847 85.013,198.024 82.929,199.898 89.238 C 200.636 91.723,200.276 94.248,198.379 99.896 L 197.190 103.438 197.189 108.944 L 197.188 114.450 198.149 115.715 C 199.347 117.290,199.440 117.369,201.960 118.945 C 203.095 119.655,205.129 121.082,206.480 122.117 C 209.434 124.380,209.519 124.359,208.640 121.590 C 204.884 109.753,208.936 97.650,216.897 96.928 C 222.680 96.404,223.230 103.200,217.929 109.688 C 213.694 114.871,213.376 115.414,212.091 119.680 C 211.609 121.280,211.082 122.846,210.920 123.159 C 210.185 124.580,210.579 125.387,213.602 128.655 C 217.982 133.388,223.106 140.862,221.636 140.372 C 221.505 140.328,220.842 139.406,220.163 138.323 C 216.582 132.610,211.380 126.935,208.750 125.872 C 205.434 124.532,204.144 124.261,202.886 124.641 C 202.273 124.827,200.224 125.168,198.333 125.399 C 194.355 125.886,193.861 126.054,188.957 128.575 C 184.763 130.732,182.736 131.352,180.402 131.193 C 173.455 130.721,173.732 123.372,180.823 120.021 C 186.306 117.429,195.726 118.562,202.405 122.616 C 203.880 123.512,206.693 124.418,207.010 124.101 C 207.383 123.728,203.954 121.080,199.271 118.125 C 197.781 117.185,195.605 115.719,194.434 114.866 C 190.906 112.297,188.212 111.283,186.198 111.766 C 185.482 111.937,183.733 112.222,182.311 112.399 C 179.403 112.761,178.230 113.166,174.680 115.030 C 167.123 119.000,161.005 117.018,163.764 111.496 C 166.666 105.689,176.462 104.933,185.760 109.799 C 189.924 111.978,189.992 111.467,186.038 107.705 C 183.948 105.716,182.689 104.694,181.611 104.110 C 169.778 97.701,163.297 89.643,164.974 83.426 C 165.734 80.613,169.296 79.180,172.504 80.399 "
          stroke="none"
          fill="#f3ecdb"
          fill-rule="evenodd"
        ></path><path
          id="path1"
          d="M167.593 80.393 C 165.595 81.300,164.687 83.164,164.841 86.042 C 165.156 91.931,171.253 98.500,181.611 104.110 C 182.689 104.694,183.948 105.716,186.038 107.705 C 189.992 111.467,189.924 111.978,185.760 109.799 C 176.462 104.933,166.666 105.689,163.764 111.496 C 161.005 117.018,167.123 119.000,174.680 115.030 C 178.230 113.166,179.403 112.761,182.311 112.399 C 183.733 112.222,185.482 111.937,186.198 111.766 C 188.212 111.283,190.906 112.297,194.434 114.866 C 195.605 115.719,197.781 117.185,199.271 118.125 C 203.954 121.080,207.383 123.728,207.010 124.101 C 206.693 124.418,203.880 123.512,202.405 122.616 C 195.726 118.562,186.306 117.429,180.823 120.021 C 173.732 123.372,173.455 130.721,180.402 131.193 C 182.736 131.352,184.763 130.732,188.957 128.575 C 193.861 126.054,194.355 125.886,198.333 125.399 C 200.224 125.168,202.273 124.827,202.886 124.641 C 204.144 124.261,205.434 124.532,208.750 125.872 C 211.380 126.935,216.582 132.610,220.163 138.323 C 220.842 139.406,221.505 140.328,221.636 140.372 C 223.106 140.862,217.982 133.388,213.602 128.655 C 210.579 125.387,210.185 124.580,210.920 123.159 C 211.082 122.846,211.609 121.280,212.091 119.680 C 213.376 115.414,213.694 114.871,217.929 109.688 C 223.230 103.200,222.680 96.404,216.897 96.928 C 208.936 97.650,204.884 109.753,208.640 121.590 C 209.519 124.359,209.434 124.380,206.480 122.117 C 205.129 121.082,203.095 119.655,201.960 118.945 C 199.440 117.369,199.347 117.290,198.149 115.715 L 197.188 114.450 197.189 108.944 L 197.190 103.438 198.379 99.896 C 200.276 94.248,200.636 91.723,199.898 89.238 C 198.024 82.929,190.847 85.013,188.953 92.416 C 187.593 97.735,189.848 106.210,194.048 111.563 C 196.575 114.784,196.759 115.275,195.104 114.398 C 192.499 113.016,184.340 105.586,184.094 104.371 C 183.827 103.051,182.408 96.754,181.938 94.800 C 179.491 84.622,172.886 77.989,167.593 80.393 "
          stroke="none"
          fill="#adbe5d"
          fill-rule="evenodd"
        ></path></g
      ></svg
    >
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

  header.box {
    background-color: #e6f7ff;
  }

  .features.box {
    background-color: #f0f5ea;
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
