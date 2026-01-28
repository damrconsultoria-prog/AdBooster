// ===== SCROLL SUAVE PARA CONTATO =====
function scrollToContato() {
  const contato = document.getElementById("contato");
  if (contato) {
    contato.scrollIntoView({ behavior: "smooth" });
  }
}

// ===== SIMULADOR DE RESULTADOS =====
function simular() {
  const investimentoInput = document.getElementById("investimento");
  const resultadoTexto = document.getElementById("resultado");

  if (!investimentoInput || !resultadoTexto) return;

  const valor = parseFloat(investimentoInput.value);

  if (isNaN(valor) || valor <= 0) {
    resultadoTexto.innerText = "Digite um valor válido para simular.";
    return;
  }

  // Projeção fictícia de retorno
  const retorno = valor * 5;

  resultadoTexto.innerText =
    "Com esse investimento, seu faturamento potencial pode chegar a R$ " +
    retorno.toLocaleString("pt-BR");
}

// ===== MENU MOBILE =====
function toggleMenu() {
  const menu = document.getElementById("menu");
  if (!menu) return;

  if (menu.style.display === "flex") {
    menu.style.display = "none";
  } else {
    menu.style.display = "flex";
    menu.style.flexDirection = "column";
  }
}

// Fecha o menu ao clicar em um link (mobile)
document.querySelectorAll("#menu a").forEach(link => {
  link.addEventListener("click", () => {
    if (window.innerWidth <= 768) {
      document.getElementById("menu").style.display = "none";
    }
  });
});

// ===== ANIMAÇÃO AO ROLAR A PÁGINA =====
const observer = new IntersectionObserver(entries => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add("active");
    }
  });
}, { threshold: 0.15 });

document.querySelectorAll("section").forEach(sec => {
  sec.classList.add("reveal");
  observer.observe(sec);
});

// ===== EFEITO HEADER AO ROLAR =====
window.addEventListener("scroll", () => {
  const header = document.querySelector("header");
  if (!header) return;

  if (window.scrollY > 50) {
    header.style.background = "rgba(10,15,44,0.85)";
    header.style.boxShadow = "0 5px 20px rgba(0,0,0,0.3)";
  } else {
    header.style.background = "rgba(255,255,255,0.05)";
    header.style.boxShadow = "none";
  }
});
