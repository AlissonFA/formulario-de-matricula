<h1 align="center">📋 Estrelas do Amanhã</h1>

<p align="center">
  <a href="#-o-projeto">O Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>
</p>

<p align="center">
  <img src="./assets/images/Preview.png" width="100%" alt="Preview do projeto Estrelas do Amanhã">
</p>

---

## 💻 O Projeto

**Estrelas do Amanhã** é um formulário de matrícula para uma escola de educação infantil, desenvolvido com foco em acessibilidade, usabilidade e boas práticas de marcação HTML5 e CSS3. A página permite que responsáveis preencham informações da criança, endereço residencial, dados do responsável e opções de matrícula — tudo em uma interface dividida em dois painéis: o formulário à esquerda e uma ilustração institucional à direita.

Os principais destaques do desenvolvimento incluem:

1. **CSS Modular com `@import`:** os estilos foram organizados em arquivos separados por responsabilidade (`input.css`, `radio.css`, `checkbox.css`, `droparea.css`, `buttons.css`), todos importados por um `index.css` central — facilitando manutenção e escalabilidade.
2. **Inputs completamente customizados:** radio buttons, checkboxes e a área de drag-and-drop foram reconstruídos visualmente com CSS puro, preservando a funcionalidade nativa e a acessibilidade por teclado com `:focus-within` e `:has()`.
3. **Layout Grid de dois painéis:** a estrutura principal usa `display: grid` com colunas proporcionais (`51.25% / 48.75%`) para criar o split entre formulário e aside, com `overflow: auto` apenas no `<main>` para o aside permanecer fixo.
4. **Validação visual com CSS:** campos `required` com estado `:invalid` exibem mensagem de erro customizada; campos `disabled` recebem opacidade reduzida via `:has([disabled])` no wrapper pai.

---

## 🚀 Tecnologias

* **HTML5:** estrutura semântica do formulário com uso correto de `<fieldset>`, `<legend>`, `<label>` e atributos nativos (`required`, `disabled`, `enctype`).
* **CSS3:** responsável por toda a estilização, incluindo CSS Nesting, pseudo-classes modernas (`:has()`, `:focus-within`, `:invalid`, `:checked`) e variáveis CSS (`--brand-dark`, `--stroke-highlight`, etc.).
* **CSS Grid & Flexbox:** Grid para o layout de dois painéis e para os radio buttons responsivos com `auto-fit`; Flexbox para alinhamentos internos nos campos de endereço e botões.
* **SVG inline:** ícone de upload na dropzone em SVG inline para permitir troca de cor via `stroke` no CSS, sem substituição de imagem.
* **Git & GitHub:** versionamento e deploy da aplicação.
* **Figma**

---

## 🔖 Layout

Você pode visualizar e interagir com o projeto através dos links abaixo:

* 📲 **[Acesse o layout original do projeto aqui](https://www.figma.com/community/file/1365016793556649696/)**
* 👉 **[Acesse o site funcionando aqui](https://alissonfa.github.io/formulario-de-matricula/)**

**Para rodar no seu computador (Local):**
1. Faça o download ou clone o repositório.
2. Certifique-se de que a estrutura de pastas está correta.
3. Dê um duplo clique no arquivo `index.html` ou abra através da extensão *Live Server* no seu editor de código.

---

Feito com 💜 por **[AlissonFA](https://www.linkedin.com/in/alissonfa/)**