<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Sam | Professor de Inglês</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    :root {
      --primary: #0a2540;
      --secondary: #425466;
      --accent: #1f8ef1;
      --bg: #f5f7fa;
      --white: #ffffff;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen;
    }

    body {
      background: var(--bg);
      color: var(--secondary);
      line-height: 1.6;
    }

    header {
      background: var(--primary);
      color: var(--white);
      padding: 80px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.8rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    section {
      max-width: 1000px;
      margin: 60px auto;
      padding: 0 20px;
    }

    h2 {
      color: var(--primary);
      margin-bottom: 20px;
      font-size: 2rem;
    }

    .card {
      background: var(--white);
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.05);
      margin-bottom: 30px;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .service {
      border-left: 4px solid var(--accent);
    }

    .cta {
      background: var(--accent);
      color: var(--white);
      text-align: center;
      padding: 50px 20px;
      border-radius: 16px;
    }

    .cta a {
      display: inline-block;
      margin-top: 20px;
      background: var(--white);
      color: var(--accent);
      padding: 12px 25px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    .cta a:hover {
      transform: scale(1.05);
    }

    footer {
      text-align: center;
      padding: 30px;
      font-size: 0.9rem;
      color: #777;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2.2rem;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>Sam</h1>
    <p>Professor de Inglês | Aulas práticas e focadas na comunicação</p>
  </header>

  <section>
    <div class="card">
      <h2>Sobre mim</h2>
      <p>
        Sou professor de inglês com foco em comunicação real, fluência e confiança.
        Trabalho com alunos iniciantes e intermediários, utilizando métodos práticos
        e objetivos. Atualmente estou em processo de certificação TEFL, ampliando
        minha atuação no ensino internacional.
      </p>
    </div>
  </section>

  <section>
    <h2>O que eu ofereço</h2>
    <div class="services">
      <div class="card service">
        <h3>Aulas Online</h3>
        <p>Aulas individuais ou em pequenos grupos, 100% online.</p>
      </div>
      <div class="card service">
        <h3>Inglês para Viagem</h3>
        <p>Comunicação prática para aeroportos, hotéis e situações reais.</p>
      </div>
      <div class="card service">
        <h3>Inglês para Iniciantes</h3>
        <p>Do zero ao básico funcional, com explicações claras.</p>
      </div>
      <div class="card service">
        <h3>Conversação</h3>
        <p>Desenvolvimento de fluência, pronúncia e segurança ao falar.</p>
      </div>
    </div>
  </section>

  <section>
    <div class="cta">
      <h2>Vamos conversar?</h2>
      <p>Entre em contato e agende uma aula experimental.</p>
      <a href="mailto:seuemail@email.com">Entrar em contato</a>
    </div>
  </section>

  <footer>
    © 2025 Sam • Professor de Inglês
  </footer>

</body>
</html>
