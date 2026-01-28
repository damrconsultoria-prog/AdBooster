<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AdBooster | Marketing Digital</title>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Montserrat',sans-serif}

body{background:#f4f7fb;color:#222;line-height:1.6}

/* HEADER */
header{
  background:#fff;
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:18px 8%;
  box-shadow:0 2px 12px rgba(0,0,0,.06);
  position:sticky;
  top:0;
  z-index:1000;
}

.logo{height:55px}

nav a{
  text-decoration:none;
  color:#003c8f;
  margin-left:30px;
  font-weight:600;
  transition:.3s;
}

nav a:hover{color:#ff6a00}

/* HERO */
.hero{
  background:linear-gradient(120deg,#003c8f,#007bff);
  color:#fff;
  padding:120px 8%;
  text-align:center;
}

.hero h1{font-size:2.6rem;margin-bottom:20px}
.hero p{font-size:1.1rem;margin-bottom:30px}

.btn{
  background:#ff6a00;
  padding:14px 34px;
  border-radius:30px;
  color:white;
  text-decoration:none;
  font-weight:600;
  display:inline-block;
  transition:.3s;
}

.btn:hover{background:#e55d00;transform:scale(1.05)}

/* SEÇÕES */
section{padding:80px 8%}
h2{text-align:center;margin-bottom:50px;font-size:2rem;color:#003c8f}

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

.servico img{
  width:100%;
  height:180px;
  object-fit:cover;
}

.servico div{padding:20px}
.servico:hover{transform:translateY(-8px)}

/* REDES SOCIAIS */
.redes{
  display:flex;
  justify-content:center;
  gap:40px;
  flex-wrap:wrap;
}

.redes img{
  width:60px;
  height:60px;
  transition:.3s;
}

.redes img:hover{transform:scale(1.15)}

/* DIFERENCIAIS */
.diferenciais{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
  gap:30px;
  text-align:center;
}

.diferenciais div{
  background:#fff;
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

form input, form textarea{
  padding:12px;
  border-radius:8px;
  border:1px solid #ddd;
}

form textarea{min-height:120px}

form button{
  background:#ff6a00;
  border:none;
  padding:14px;
  border-radius:30px;
  color:white;
  font-weight:600;
  cursor:pointer;
  transition:.3s;
}

form button:hover{background:#e55d00}

/* FOOTER */
footer{
  background:#001c3d;
  color:white;
  text-align:center;
  padding:40px;
  margin-top:40px;
}

/* RESPONSIVO */
@media(max-width:768px){
  nav{display:none}
  .hero h1{font-size:2rem}
}
</style>
</head>

<body>

<header>
  <img src="logo-adbooster.png" alt="Logo AdBooster" class="logo">
  <nav>
    <a href="#servicos">Serviços</a>
    <a href="#redes">Redes</a>
    <a href="#contato">Contato</a>
  </nav>
</header>

<section class="hero">
  <h1>Impulsionamos empresas no digital</h1>
  <p>Gestão de redes sociais, engajamento real e campanhas que geram vendas.</p>
  <a href="#contato" class="btn">Falar com especialista</a>
</section>

<section id="servicos">
  <h2>Nossos Serviços</h2>
  <div class="servicos">

    <div class="servico">
      <img src="https://images.unsplash.com/photo-1557838923-2985c318be48" alt="">
      <div>
        <h3>Gestão de Redes Sociais</h3>
        <p>Crescimento, conteúdo profissional e autoridade digital.</p>
      </div>
    </div>

    <div class="servico">
      <img src="https://images.unsplash.com/photo-1559028012-481c04fa702d" alt="">
      <div>
        <h3>Tráfego Pago</h3>
        <p>Anúncios estratégicos no Google, Instagram e Facebook.</p>
      </div>
    </div>

    <div class="servico">
      <img src="https://images.unsplash.com/photo-1522202176988-66273c2fd55f" alt="">
      <div>
        <h3>Engajamento Digital</h3>
        <p>Mais curtidas, comentários e alcance para sua marca.</p>
      </div>
    </div>

  </div>
</section>

<section id="redes">
  <h2>Plataformas que impulsionamos</h2>
  <div class="redes">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733558.png" alt="Instagram">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733579.png" alt="Twitter">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733635.png" alt="LinkedIn">
  </div>
</section>

<section>
  <h2>Por que escolher a AdBooster?</h2>
  <div class="diferenciais">
    <div>📊 Estratégias baseadas em dados reais</div>
    <div>🚀 Crescimento rápido e sustentável</div>
    <div>🤝 Suporte próximo e personalizado</div>
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
