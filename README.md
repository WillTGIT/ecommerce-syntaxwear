# SyntaxWear E-commerce

Este é um projeto de front-end para um site de e-commerce de calçados chamado SyntaxWear. O layout é moderno, responsivo e focado em apresentar os produtos de forma atraente.

## 🚀 Visão Geral

O projeto consiste em uma única página (landing page) que demonstra a interface de uma loja virtual de tênis, com um design limpo e focado na experiência do usuário.

## ✨ Funcionalidades

- **Header Fixo e Responsivo:** Menu de navegação que se adapta a diferentes tamanhos de tela, com um menu hambúrguer para dispositivos móveis.
- **Seção Hero:** Banner principal com imagem de fundo, título e botões de chamada para ação (CTA).
- **Categorias de Produtos:** Seção que exibe as principais categorias de calçados (Casual, Esporte, Moderno, Futurista) com imagens e links.
- **Grid de Produtos:** Uma grade de layout CSS Grid que destaca produtos de forma visualmente interessante.
- **Rodapé Completo:** Inclui:
  - Formulário de inscrição para newsletter.
  - Links para redes sociais.
  - Menus de navegação adicionais.
  - Informações de copyright.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Para a estrutura semântica do conteúdo.
- **CSS3:** Para estilização, utilizando:
  - **Variáveis CSS:** Para um tema consistente e fácil de manter.
  - **Arquitetura BEM (Bloco, Elemento, Modificador):** Sugerida pela estrutura de classes.
  - **Design Responsivo:** Media queries para adaptar o layout a telas de desktop, tablets e celulares.
  - **CSS Grid e Flexbox:** Para layouts complexos e alinhamento de itens.

## 📂 Estrutura do Projeto

O projeto está organizado da seguinte forma:

```
ecommerce-syntaxwear/
├── css/
│   ├── base.css               # Estilos base (body, botões, etc.)
│   ├── reset.css              # Reset de estilos padrão do navegador
│   ├── styles.css             # Arquivo principal de estilos (atualmente vazio)
│   ├── variables.css          # Definição de variáveis CSS (cores, fontes)
│   └── components/
│       ├── footer.css         # Estilos do rodapé
│       ├── header.css         # Estilos do cabeçalho
│       ├── hero.css           # Estilos da seção hero
│       ├── product-category.css # Estilos das categorias
│       └── product-grid.css   # Estilos da grade de produtos
├── images/
│   ├── banners/               # Imagens para banners (hero)
│   ├── icons/                 # Ícones (redes sociais, menu, etc.)
│   ├── logo/                  # Logo do site
│   └── products/              # Imagens dos produtos
├── index.html                 # Arquivo principal da página
└── README.md                  # Este arquivo
```

## 🏁 Como Executar

Como este é um projeto de front-end estático, não há necessidade de um servidor ou processo de build.

1.  Clone este repositório:
    ```sh
    git clone <URL_DO_REPOSITORIO>
    ```
2.  Navegue até o diretório do projeto:
    ```sh
    cd ecommerce-syntaxwear
    ```
3.  Abra o arquivo `index.html` diretamente no seu navegador de preferência (Google Chrome, Firefox, etc.).

E pronto! A página será exibida.
