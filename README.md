<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AdBooster | Crescimento Digital para Empresas</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}

body{background:#f5f8fc;color:#1a1a1a;line-height:1.6}

/* HEADER */
header{
  background:#ffffff;
  padding:20px 8%;
  display:flex;
  justify-content:space-between;
  align-items:center;
  box-shadow:0 4px 15px rgba(0,0,0,0.05);
  position:sticky;
  top:0;
  z-index:1000;
}

.logo{height:55px}

nav a{
  margin-left:30px;
  text-decoration:none;
  color:#003c8f;
  font-weight:600;
  transition:.3s;
}

nav a:hover{color:#ff6a00}

/* HERO */
.hero{
  background:linear-gradient(120deg,#003c8f,#007bff);
  color:white;
  padding:120px 8%;
  display:flex;
  flex-wrap:wrap;
  align-items:center;
  justify-content:space-between;
}

.hero-text{max-width:600px}
.hero h1{font-size:2.8rem;margin-bottom:20px}
.hero p{margin-bottom:30px;font-size:1.1rem}

.btn{
  background:#ff6a00;
  padding:14px 34px;
  border-radius:30px;
  color:white;
  text-decoration:none;
  font-weight:600;
  transition:.3s;
  display:inline-block;
}

.btn:hover{background:#e55d00;transform:scale(1.05)}

.hero img{
  width:420px;
  max-width:100%;
}

/* SEÇÕES */
section{padding:90px 8%}
h2{text-align:center;margin-bottom:50px;color:#003c8f;font-size:2.2rem}

/* SERVIÇOS */
.servicos{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
  gap:30px;
}

.card{
  background:#fff;
  border-radius:14px;
  padding:30px;
  text-align:center;
  box-shadow:0 10px 25px rgba(0,0,0,.05);
  transition:.3s;
}

.card:hover{transform:translateY(-10px)}

.card img{width:70px;margin-bottom:15px}

/* AUTORIDADE */
.autoridade{
  background:#ffffff;
  display:flex;
  flex-wrap:wrap;
  align-items:center;
  gap:40px;
}

.autoridade img{width:420px;max-width:100%;border-radius:12px}
.autoridade div{flex:1}

/* REDES */
.redes{
  display:flex;
  justify-content:center;
  gap:40px;
  flex-wrap:wrap;
}

.redes img{width:60px;transition:.3s}
.redes img:hover{transform:scale(1.2)}

/* CONTATO */
form{
  max-width:500px;
  margin:auto;
  display:grid;
  gap:15px;
}

form input, form textarea{
  padding:14px;
  border-radius:8px;
  border:1px solid #ddd;
}

form button{
  background:#ff6a00;
  color:white;
  border:none;
  padding:14px;
  border-radius:30px;
  font-weight:600;
  cursor:pointer;
}

footer{
  background:#001c3d;
  color:white;
  text-align:center;
  padding:40px;
  margin-top:40px;
}

@media(max-width:900px){
  .hero{flex-direction:column;text-align:center}
  nav{display:none}
}
</style>
</head>

<body>

<header>
  <img src="logo-adbooster.png" alt="Logo AdBooster" class="logo">
  <nav>
    <a href="#servicos">Serviços</a>
    <a href="#autoridade">Sobre</a>
    <a href="#contato">Contato</a>
  </nav>
</header>

<section class="hero">
  <div class="hero-text">
    <h1>Transformamos presença digital em vendas reais</h1>
    <p>A AdBooster ajuda empresas a crescer com estratégias de marketing, engajamento e tráfego pago de alta performance.</p>
    <a href="#contato" class="btn">Falar com um especialista</a>
  </div>
  <img src="https://images.unsplash.com/photo-1553877522-43269d4ea984" alt="">
</section>

<section id="servicos">
  <h2>Nossos Serviços</h2>
  <div class="servicos">
    <div class="card">
      <img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png">
      <h3>Gestão de Redes Sociais</h3>
      <p>Conteúdo estratégico, crescimento orgânico e autoridade digital.</p>
    </div>
    <div class="card">
      <img src="https://cdn-icons-png.flaticon.com/512/2920/2920277.png">
      <h3>Tráfego Pago</h3>
      <p>Campanhas lucrativas no Google, Instagram e Facebook.</p>
    </div>
    <div class="card">
      <img src="https://cdn-icons-png.flaticon.com/512/1828/1828884.png">
      <h3>Engajamento Digital</h3>
      <p>Aumente interações e fortaleça sua marca nas redes.</p>
    </div>
  </div>
</section>

<section id="autoridade" class="autoridade">
  <img src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d">
  <div>
    <h2>Marketing com foco em resultado</h2>
    <p>Não vendemos promessas. Criamos estratégias baseadas em dados, testes e otimizações constantes para garantir crescimento real e sustentável para sua empresa.</p>
    <a href="#contato" class="btn">Quero crescer</a>
  </div>
</section>

<section>
  <h2>Plataformas que impulsionamos</h2>
  <div class="redes">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733558.png">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733579.png">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733635.png">
  </div>
</section>

<section id="contato">
  <h2>Solicite uma análise gratuita</h2>
  <form>
    <input type="text" placeholder="Seu nome" required>
    <input type="email" placeholder="Seu e-mail" required>
    <textarea placeholder="Conte sobre sua empresa"></textarea>
    <button type="submit">Receber contato</button>
  </form>
</section>

<footer>
  © 2026 AdBooster — Especialistas em Crescimento Digital
</footer>

</body>
</html>
