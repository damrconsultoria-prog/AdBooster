<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AdBooster | Marketing Digital e Engajamento</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    *{margin:0;padding:0;box-sizing:border-box;font-family:'Montserrat',sans-serif}

    body{background:#f4f7fb;color:#1c1c1c;line-height:1.6}

    header{
      background:white;
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:20px 8%;
      box-shadow:0 2px 10px rgba(0,0,0,.05);
      position:sticky;
      top:0;
      z-index:1000;
    }

    .logo{height:55px}
    nav a{
      text-decoration:none;
      color:#1c1c1c;
      margin-left:30px;
      font-weight:600;
    }
    nav a:hover{color:#ff6a00}

    .hero{
      background:linear-gradient(120deg,#004aad,#007bff);
      color:white;
      padding:120px 8%;
      text-align:center;
    }

    .hero h1{font-size:2.8rem;margin-bottom:20px}
    .hero p{font-size:1.1rem;margin-bottom:30px}

    .btn{
      background:#ff6a00;
      padding:14px 32px;
      border-radius:30px;
      color:white;
      text-decoration:none;
      font-weight:600;
      display:inline-block;
    }

    section{padding:80px 8%}
    h2{text-align:center;margin-bottom:50px;font-size:2rem;color:#004aad}

    /* SERVIÇOS */
    .servicos{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
      gap:30px;
    }

    .servico{
      background:white;
      border-radius:12px;
      overflow:hidden;
      box-shadow:0 5px 20px rgba(0,0,0,.05);
      transition:.3s;
    }

    .servico img{width:100%;height:180px;object-fit:cover}
    .servico div{padding:20px}
    .servico:hover{transform:translateY(-8px)}

    /* REDES */
    .redes{
      display:flex;
      justify-content:center;
      gap:40px;
      flex-wrap:wrap;
    }

    .redes img{width:60px;height:60px;transition:.3s}
    .redes img:hover{transform:scale(1.15)}

    /* DIFERENCIAIS */
    .diferenciais{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
      gap:30px;
      text-align:center;
    }

    .diferenciais div{
      background:#ffffff;
      padding:25px;
      border-radius:12px;
      box-shadow:0 5px 20px rgba(0,0,0,.05);
    }

    /* CONTATO */
    form{
      display:grid;
      gap:15px;
      max-width:500px;
      margin:auto;
    }

    form input,form textarea{
      padding:12px;
      border-radius:8px;
      border:1px solid #ddd;
    }

    form button{
      background:#ff6a00;
      border:none;
      padding:14px;
      border-radius:30px;
      color:white;
      font-weight:600;
    }

    footer{
      background:#001c3d;
      color:white;
      text-align:center;
      padding:40px;
      margin-top:40px;
    }

    @media(max-width:768px){
      .hero h1{font-size:2rem}
      nav{display:none}
    }
  </style>
</head>
<body>

<header>
  <img src="logo-adbooster.png" class="logo">
  <nav>
    <a href="#servicos">Serviços</a>
    <a href="#redes">Redes</a>
    <a href="#contato">Contato</a>
  </nav>
</header>

<section class="hero">
  <h1>Impulsionamos marcas no mundo digital</h1>
  <p>Gestão de redes sociais, engajamento, tráfego pago e crescimento estratégico para empresas.</p>
  <a href="#contato" class="btn">Falar com especialista</a>
</section>

<section id="servicos">
  <h2>Nossos Serviços</h2>
  <div class="servicos">

    <div class="servico">
      <img src="https://images.unsplash.com/photo-1557838923-2985c318be48">
      <div>
        <h3>Gestão de Redes Sociais</h3>
        <p>Produção de conteúdo, planejamento e crescimento orgânico.</p>
      </div>
    </div>

    <div class="servico">
      <img src="https://images.unsplash.com/photo-1559028012-481c04fa702d">
      <div>
        <h3>Tráfego Pago</h3>
        <p>Anúncios estratégicos no Google, Facebook e Instagram.</p>
      </div>
    </div>

    <div class="servico">
      <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f">
      <div>
        <h3>Engajamento Digital</h3>
        <p>Aumente curtidas, comentários e alcance da sua marca.</p>
      </div>
    </div>

  </div>
</section>

<section id="redes">
  <h2>Trabalhamos com as principais plataformas</h2>
  <div class="redes">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733558.png">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733579.png">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733635.png">
  </div>
</section>

<section>
  <h2>Por que escolher a AdBooster?</h2>
  <div class="diferenciais">
    <div>📊 Estratégias baseadas em dados</div>
    <div>🚀 Crescimento rápido e sustentável</div>
    <div>🤝 Atendimento próximo e personalizado</div>
  </div>
</section>

<section id="contato">
  <h2>Vamos crescer sua empresa?</h2>
  <form>
    <input type="text" placeholder="Seu nome" required>
    <input type="email" placeholder="Seu e-mail" required>
    <textarea placeholder="Conte sobre seu negócio"></textarea>
    <button type="submit">Falar com especialista</button>
  </form>
</section>

<footer>
  © 2026 AdBooster — Marketing Digital e Engajamento
</footer>

</body>
</html>
