# ☕ Triple Espresso — Landing Page de Cafeteria

Projeto de landing page desenvolvido como parte do **Sprint 4 do bootcamp de**
**Desenvolvimento Web da TripleTen Brasil**, com foco em **HTML e CSS avançados**,
organização de código com **BEM Flat** e fidelidade a layout profissional.

O projeto simula o site de um café fictício localizado em uma biblioteca, combinando
tipografia elegante, layout estruturado e boas práticas de desenvolvimento front-end.

> _A interface final da página inicial contém cabeçalho, seção de receitas, formulário
> de reserva e rodapé._

---

## 🔗 Visualização do Projeto

Está disponível via:

➡️ **GitHub Pages:** https://vanessayuriab.github.io/web_project_coffeeshop

---

## 🎯 Objetivo do Projeto

- Consolidar o uso de **HTML5 semântico**
- Criar layouts estruturados usando **Flexbox**
- Trabalhar **posicionamento relativo e absoluto**
- Aplicar **metodologia BEM Flat** na organização do CSS
- Estilizar **formulários HTML**
- Incorporar conteúdo externo usando `<iframe>`
- Seguir um **design profissional com requisitos rígidos de layout**

---

## ⚙️ Funcionalidades

- Navegação com âncoras funcionais
- Seção de receitas com vídeos incorporados do YouTube
- Formulário de reserva com validação nativa (`required`)
- Estados de hover e foco (`:hover`, `:focus`)
- Layout centralizado e adaptado para telas grandes (≥ 1100px)

> ⚠️ Observação: o formulário é visual e estrutural. A lógica de envio pode ser
> futuramente implementada com `JavaScript`.

---

## 🛠️ Tecnologias e Recursos Utilizados

- HTML5 semântico
- CSS3 (Flexbox, posicionamento, pseudoclasses e pseudoelementos)
- Google Fonts
- Metodologia BEM Flat (Block / Element / Modifier)
- Incorporação de conteúdo com `<iframe>`
- Formulários HTML
- Normalize.css
- Prettier
- Git & GitHub

---

## 🗂️ Estrutura do Projeto

```bash
web_project_coffeeshop/
├── .vscode/
├── blocks/
│   └── # Estilos CSS organizados por bloco (BEM Flat)
├── images/
│   ├── README/
│   └── # Imagens do projeto
├── pages/
│   └── index.css # Arquivo central de imports
├── vendor/
│   └── normalize.css
├── .editorconfig
├── .gitignore
├── .prettierignore
├── favicon.ico
├── index.html
└── README.md
```

---

## 🚀 Como executar o projeto localmente

```Shell
# Clone o repositório
git clone git@github.com:VanessaYuriAB/web_project_coffeeshop.git

# Acesse a pasta
cd web_project_coffeeshop
```

Depois:

- Abra o arquivo `index.html` diretamente no navegador

  ou

- Utilize uma extensão como o `Live Server` no `VS Code`

---

## 🔍 Destaques Técnicos

- Uso consistente de `HTML semântico` (`header`, `main`, `section`, `footer`, `nav`)
- `CSS` _modularizado_ por bloco conforme `BEM Flat`
- Nenhum estilo aplicado diretamente por seletores de tag
- Importação correta do `normalize.css`
- Fidelidade total ao layout fornecido no design (1440px)

---

## 📸 Implementação Técnica (Screenshots)

Esta seção reúne **evidências visuais da implementação técnica do projeto**,
demonstrando a aplicação prática dos conceitos utilizados durante o
desenvolvimento.

### HTML5 semântico:

<img
  src="./images/README/Semantica1_html.png"
  alt="HTML5 semântico 1"
  width="800"
/>
<img
  src="./images/README/Semântica2_head.png"
  alt="HTML5 semântico 2"
  width="800"
/>
<img
  src="./images/README/Semântica3_header.png"
  alt="HTML5 semântico 3"
  width="800"
/>
<img
  src="./images/README/Semântica4_main.png"
  alt="HTML5 semântico 4"
  width="800"
/>
<img
  src="./images/README/Semântica5_section-recipes.png"
  alt="HTML5 semântico 5"
  width="800"
/>
<img
  src="./images/README/Semântica6_section-reservation.png"
  alt="HTML5 semântico 6"
  width="800"
/>
<img
  src="./images/README/Semântica7_footer.png"
  alt="HTML5 semântico 7"
  width="800"
/>

---

### CSS3 - Flexbox:

<img
  src="./images/README/Flexbox1_justify-content.png"
  alt="Flexbox 1"
  width="800"
/>
<img
  src="./images/README/Flexbox2_flex-direction.png"
  alt="Flexbox 2"
  width="800"
/>
<img
  src="./images/README/Flexbox3_align-items.png"
  alt="Flexbox 3"
  width="800"
/>

---

### CSS3 - Posicionamento:

<img
  src="./images/README/Posicionamento1_relative.png"
  alt="Posicionamento 1"
  width="800"
/>
<img
  src="./images/README/Posicionamento2_absolute.png"
  alt="Posicionamento 2"
  width="800"
/>

---

### CSS3 - Pseudoclasses e Pseudoelementos:

<img
  src="./images/README/Pseudoclasses1_checkbox.png"
  alt="Pseudoclasses 1"
  width="800"
/>
<img
  src="./images/README/Pseudoclasses2_checked.png"
  alt="Pseudoclasses 2"
  width="800"
/>
<img
  src="./images/README/Pseudoclasses3_disabled.png"
  alt="Pseudoclasses 3"
  width="800"
/>
<img
  src="./images/README/Pseudoclasses4_focus.png"
  alt="Pseudoclasses 4"
  width="800"
/>
<img
  src="./images/README/Pseudoclasses5_disabled-checked.png"
  alt="Pseudoclasses 5"
  width="800"
/>

<img
  src="./images/README/Pseudoelementos1_placeholder.png"
  alt="Pseudoelementos 1"
  width="800"
/>
<img
  src="./images/README/Pseudoelementos2_placeholder.png"
  alt="Pseudoelementos 2"
  width="800"
/>

---

### Incorporação de conteúdo - `<iframe>`:

<img
  src="./images/README/Incorporação-de-conteúdo_iframe.png"
  alt="iframe"
  width="800"
/>

---

### Formulários HTML - `<form>`:

<img
  src="./images/README/Formulário.png"
  alt="Form"
  width="800"
/>

---

### Google Fonts:

<img
  src="./images/README/Google-fonts.png"
  alt="Google Fonts"
  width="800"
/>

---

### Organização CSS - BEM Flat:

<img
  src="./images/README/Bem-flat1_index-page-header.png"
  alt="BEM Flat 1"
  width="800"
/>
<img
  src="./images/README/Bem-flat2_index-nav-recipes.png"
  alt="BEM Flat 2"
  width="800"
/>
<img
  src="./images/README/Bem-flat3_index-reservation-form.png"
  alt="BEM Flat 3"
  width="800"
/>
<img
  src="./images/README/Bem-flat4_index-reservation-normalize.png"
  alt="BEM Flat 4"
  width="800"
/>

---

## 🔧 Possíveis Melhorias Futuras

- Adicionar **responsividade completa** para dispositivos móveis
- Implementar **interatividade com `JavaScript`** (envio real do formulário)
- Melhorar **acessibilidade** (`aria-labels`, contraste, navegação por teclado)
- Adicionar **animações** sutis com `CSS` ou `JS`
- Publicar versão otimizada para performance

---

## 👩‍💻 Autora

Vanessa Yuri A. Brito

Aplicativo _front-end_ desenvolvido durante a minha _formação em Desenvolvimento Web no
Bootcamp da Triple Ten Brasil_.
