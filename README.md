<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Povos Indígenas da Região Norte</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background-color: #f0f8f0;
      color: #333;
    }
    header {
      background-color: #006400;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #228B22;
      padding: 15px;
      text-align: center;
    }
    nav button {
      background-color: white;
      color: #228B22;
      border: 2px solid #228B22;
      padding: 10px 20px;
      margin: 5px;
      cursor: pointer;
      border-radius: 5px;
      font-weight: bold;
      transition: 0.3s;
    }
    nav button:hover {
      background-color: #228B22;
      color: white;
    }
    main {
      padding: 20px;
      max-width: 1000px;
      margin: auto;
    }
    section {
      margin-bottom: 40px;
    }
    h2 {
      color: #006400;
    }
    footer {
      background-color: #ccc;
      padding: 10px;
      text-align: center;
    }
  </style>
  <script>
    function scrollToSection(id) {
      document.getElementById(id).scrollIntoView({ behavior: 'smooth' });
    }
  </script>
</head>
<body>

  <header>
    <h1>Povos Indígenas da Região Norte</h1>
    <p>Explore a diversidade, história e cultura dos povos originários da Amazônia brasileira.</p>
  </header>

  <nav>
    <button onclick="scrollToSection('quem-sao')">Quem São</button>
    <button onclick="scrollToSection('principais-povos')">Etnias</button>
    <button onclick="scrollToSection('cultura')">Cultura</button>
    <button onclick="scrollToSection('meio-ambiente')">Natureza</button>
    <button onclick="scrollToSection('direitos')">Direitos</button>
    <button onclick="scrollToSection('educacao-saude')">Educação e Saúde</button>
  </nav>

  <main>
    <section id="quem-sao">
      <h2>Quem são os Povos Indígenas do Norte</h2>
      <p>Os povos indígenas da Região Norte do Brasil são os habitantes originários da Floresta Amazônica. Estão presentes nos estados do Acre, Amazonas, Roraima, Pará, Rondônia, Amapá e Tocantins. São diversos, com línguas próprias, culturas únicas e formas de vida ligadas à terra e à floresta.</p>
    </section>

    <section id="principais-povos">
      <h2>Principais Povos e Etnias</h2>
      <ul>
        <li><strong>Yanomami</strong> – Vivem entre Brasil e Venezuela. Conhecidos por sua forte conexão espiritual e defesa do território.</li>
        <li><strong>Tikuna</strong> – Falam a língua tikuna, são pescadores e têm rituais marcantes de passagem para a vida adulta.</li>
        <li><strong>Macuxi</strong> – Habitam Roraima e vivem da agricultura, caça e pesca. Lutam pela demarcação de suas terras.</li>
        <li><strong>Baniwa</strong> e <strong>Tukano</strong> – Povos do Alto Rio Negro, com vasta mitologia e práticas agrícolas tradicionais.</li>
        <li><strong>Munduruku</strong> – Fortemente organizados, lutam contra projetos de barragens e mineração na Amazônia.</li>
        <li><strong>Waiãpi</strong> – Mantêm viva sua língua e espiritualidade. Valorizam a preservação de suas florestas e saberes.</li>
      </ul>
    </section>

    <section id="cultura">
      <h2>Cultura e Tradições</h2>
      <p>A cultura indígena é rica e diversa. Cada povo possui línguas, músicas, danças, pinturas corporais e rituais próprios. A oralidade é fundamental: histórias, lendas e conhecimentos são passados de geração em geração. O artesanato com sementes, penas, barro e fibras vegetais expressa identidade e resistência cultural.</p>
    </section>

    <section id="meio-ambiente">
      <h2>Relação com o Meio Ambiente</h2>
      <p>Vivem em equilíbrio com a natureza, utilizando técnicas sustentáveis para plantar, colher, pescar e caçar. A floresta é vista como sagrada, sendo fonte de alimento, medicina e espiritualidade. Os povos indígenas são os maiores protetores da biodiversidade amazônica.</p>
    </section>

    <section id="direitos">
      <h2>Direitos e Lutas</h2>
      <p>Desde a Constituição de 1988, os povos indígenas têm direito às suas terras, culturas e formas de organização. No entanto, ainda enfrentam ameaças como desmatamento ilegal, garimpo, violência e falta de políticas públicas adequadas. Organizações e lideranças indígenas continuam lutando por justiça e respeito.</p>
    </section>

    <section id="educacao-saude">
      <h2>Educação e Saúde</h2>
      <p>Há avanços na educação indígena bilíngue e na valorização dos saberes tradicionais. No entanto, o acesso à educação de qualidade e à saúde ainda é limitado em muitas aldeias. Programas de apoio precisam respeitar as tradições e a autonomia dos povos indígenas.</p>
    </section>
  </main>

  <footer>
    <p>Site educativo criado para fins escolares – Todos os direitos reservados © 2025</p>
  </footer>

</body>
</html>
