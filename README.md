[angra_4_site.html](https://github.com/user-attachments/files/22682024/angra_4_site.html)
<!doctype html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Angra 4 — Energia Limpa para a Inclusão</title>
  <style>
    :root{
      --bg:#f6f8fb; --card:#ffffff; --accent:#0b6b63; --muted:#6b7280; --accent-2:#0b84a6;
      --glass: rgba(255,255,255,0.6);
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,#eef6f4 0%, #f6f8fb 100%);color:#0f1724;line-height:1.5}
    .container{max-width:1100px;margin:0 auto;padding:28px}

    header{display:flex;align-items:center;justify-content:space-between;padding:18px 0}
    .brand{display:flex;gap:12px;align-items:center}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent),var(--accent-2));display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;font-size:18px}
    h1{margin:0;font-size:20px}
    nav a{margin-left:16px;color:var(--muted);text-decoration:none;font-weight:600}

    .hero{display:grid;grid-template-columns:1fr 380px;gap:28px;align-items:center;padding:28px 0}
    .hero-card{background:var(--card);padding:26px;border-radius:14px;box-shadow:0 6px 18px rgba(8,15,20,0.06)}
    .hero h2{margin:0 0 10px 0;font-size:28px;color:var(--accent)}
    .lead{color:var(--muted);margin-bottom:18px}
    .cta{display:inline-block;background:var(--accent);color:#fff;padding:12px 18px;border-radius:10px;text-decoration:none;font-weight:700}

    .stats{display:flex;gap:12px;margin-top:14px}
    .stat{background:linear-gradient(180deg,#fff,#fbffff);padding:12px;border-radius:10px;flex:1;text-align:center}
    .stat strong{display:block;font-size:20px;color:var(--accent)}
    .section{margin:28px 0}
    .cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px}
    .card{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(8,15,20,0.04)}

    .impact-grid{display:grid;grid-template-columns:repeat(2,1fr);gap:12px}
    .impact-item{background:linear-gradient(180deg,#fff,#fbffff);padding:16px;border-radius:10px}
    .ods{display:flex;gap:10px;align-items:center}
    .ods .pill{background:var(--accent);color:#fff;padding:6px 10px;border-radius:999px;font-weight:700}

    footer{padding:18px 0;color:var(--muted);font-size:14px;border-top:1px solid rgba(15,23,36,0.04)}

    @media (max-width:880px){
      .hero{grid-template-columns:1fr}
      .impact-grid{grid-template-columns:1fr}
    }

    /* simple counter animation */
    .counter{font-size:22px;color:var(--accent);font-weight:800}
    .muted-small{color:var(--muted);font-size:14px}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">A4</div>
        <div>
          <h1>Angra 4</h1>
          <div class="muted-small">Energia Limpa para a Inclusão e Justiça Social</div>
        </div>
      </div>
      <nav>
        <a href="#objetivo">Objetivo</a>
        <a href="#acoes">Ações</a>
        <a href="#impactos">Impactos</a>
        <a href="#ods">ODS</a>
      </nav>
    </header>

    <main>
      <section class="hero-card hero">
        <div>
          <h2>Angra 4 — Energia limpa aliada à justiça social</h2>
          <p class="lead">Construir a usina nuclear Angra 4 como projeto que combate a pobreza (ODS 1) e reduz as desigualdades sociais e regionais (ODS 10), gerando emprego, capacitação e acesso à energia para comunidades vulneráveis.</p>
          <a class="cta" href="#acoes">Ver principais ações</a>

          <div class="stats">
            <div class="stat">
              <div class="counter" data-target="4000">0</div>
              <div class="muted-small">Empregos diretos (5 anos)</div>
            </div>
            <div class="stat">
              <div class="counter" data-target="2500">0</div>
              <div class="muted-small">Pessoas capacitadas</div>
            </div>
            <div class="stat">
              <div class="counter" data-target="50">0</div>
              <div class="muted-small">Comunidades beneficiadas</div>
            </div>
          </div>
        </div>

        <aside>
          <div style="padding:18px;border-radius:12px;background:linear-gradient(180deg,#f9ffff, #ffffff);box-shadow:0 8px 20px rgba(11,104,99,0.06)">
            <h3 style="margin-top:0;color:var(--accent)">Objetivo principal</h3>
            <p class="muted-small">Construir Angra 4 com foco em inclusão social, geração de renda e redução das desigualdades regionais — integrando mecanismos sociais à operação da usina.</p>
            <div style="margin-top:10px">
              <strong>Receita social prevista:</strong>
              <div class="muted-small">R$ 20 milhões/ano para projetos locais</div>
            </div>
          </div>
        </aside>
      </section>

      <section id="objetivo" class="section">
        <div class="hero-card">
          <h3>Objetivo</h3>
          <p class="muted-small">Construir a usina nuclear Angra 4 como iniciativa alinhada aos ODS da ONU, com foco em erradicação da pobreza e redução das desigualdades sociais e regionais.</p>
        </div>
      </section>

      <section id="acoes" class="section">
        <h3>Principais Ações</h3>
        <div class="cards">
          <div class="card">
            <h4>Geração de Empregos</h4>
            <p class="muted-small">Priorizar a contratação de moradores locais: <strong>70% das vagas</strong> reservadas para a comunidade de Angra dos Reis e região.</p>
          </div>

          <div class="card">
            <h4>Capacitação Técnica</h4>
            <p class="muted-small">Oferecer cursos gratuitos para jovens e adultos em áreas como operação industrial, segurança, elétrica e manutenção.</p>
          </div>

          <div class="card">
            <h4>Energia Acessível</h4>
            <p class="muted-small">Implementar tarifa social de energia para famílias de baixa renda e programas de acesso para comunidades rurais e periurbanas.</p>
          </div>

          <div class="card">
            <h4>Fundo Social</h4>
            <p class="muted-small">Destinar parte da receita da usina a projetos locais de educação, saúde e infraestrutura.</p>
          </div>

          <div class="card">
            <h4>Participação Popular</h4>
            <p class="muted-small">Criar um conselho com representantes da comunidade para monitorar e opinar sobre as ações sociais do projeto.</p>
          </div>
        </div>
      </section>

      <section id="impactos" class="section">
        <h3>Impactos Esperados (em 5 anos)</h3>
        <div class="impact-grid">
          <div class="impact-item">
            <strong>4.000</strong>
            <div class="muted-small">Empregos diretos</div>
          </div>
          <div class="impact-item">
            <strong>2.500</strong>
            <div class="muted-small">Pessoas capacitadas</div>
          </div>
          <div class="impact-item">
            <strong>50</strong>
            <div class="muted-small">Comunidades beneficiadas com energia acessível</div>
          </div>
          <div class="impact-item">
            <strong>40%</strong>
            <div class="muted-small">Redução na pobreza energética local</div>
          </div>
          <div class="impact-item">
            <strong>R$ 20M/ano</strong>
            <div class="muted-small">Investidos em projetos sociais</div>
          </div>
        </div>
      </section>

      <section id="ods" class="section">
        <h3>Alinhamento com os ODS</h3>
        <div class="cards">
          <div class="card">
            <h4>ODS 1 — Erradicação da Pobreza</h4>
            <p class="muted-small">Geração de renda, inclusão produtiva, capacitação técnica e acesso à energia como forma de reduzir a pobreza.</p>
          </div>
          <div class="card">
            <h4>ODS 10 — Redução das Desigualdades</h4>
            <p class="muted-small">Apoio a comunidades vulneráveis, contratação local e investimento em infraestrutura regional para reduzir desigualdades.</p>
          </div>
        </div>
      </section>

      <section class="section">
        <div class="hero-card">
          <h3>Como participar</h3>
          <p class="muted-small">Se você é morador(a) local, representante comunitário ou interessado(a) em colaborar, participe das consultas públicas e das ações de capacitação. O projeto prevê vagas e programas dedicados à comunidade local.</p>
          <p style="margin-top:10px" class="muted-small"><strong>Contato:</strong> projeto@angra4.social (exemplo)</p>
        </div>
      </section>

    </main>

    <footer>
      <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
        <div>© Angra 4 — Energia Limpa para a Inclusão</div>
        <div class="muted-small">Projeto alinhado aos ODS 1 e 10 • Dados projetados para 5 anos</div>
      </div>
    </footer>
  </div>

  <script>
    // contador simples animado
    const counters = document.querySelectorAll('.counter');
    counters.forEach(c => {
      const target = +c.getAttribute('data-target');
      let cur = 0;
      const step = Math.max(1, Math.floor(target / 120));
      const interval = setInterval(()=>{
        cur += step;
        if(cur >= target){ cur = target; clearInterval(interval); }
        c.textContent = cur.toLocaleString();
      },14);
    });
  </script>
</body>
</html>
