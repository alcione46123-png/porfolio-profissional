const projetos = [
  {
    nome: "Loja Online",
    descricao: "E-commerce com carrinho de compras.",
    link: "https://github.com/alcione46123-png/fksports"
  },
  {
    nome: "Sistema de Pedidos",
    descricao: "Sistema com integração WhatsApp.",
    link: "https://github.com/alcione46123-png/fksports"
  }
];

const container = document.getElementById("lista-projetos");

projetos.forEach(projeto => {
  const article = document.createElement("article");

  article.innerHTML = `
    <h3>${projeto.nome}</h3>
    <p>${projeto.descricao}</p>
    <a href="${projeto.link}" target="_blank">Ver no GitHub</a>
  `;

  container.appendChild(article);
});

/* ANIMAÇÃO */
const elementos = document.querySelectorAll(".fade");

function mostrarElementos() {
  elementos.forEach(el => {
    const posicao = el.getBoundingClientRect().top;
    const tela = window.innerHeight;

    if (posicao < tela - 100) {
      el.classList.add("show");
    }
  });
}

window.addEventListener("scroll", mostrarElementos);
mostrarElementos();
