# SyntaxWear

Projeto estático de uma vitrine virtual de tênis e sneakers, desenvolvido como parte dos estudos do curso **DEV EM DOBRO**. O repositório também reúne páginas de estudo independentes para praticar HTML e CSS.

## Sobre a vitrine

A página principal está em [`index.html`](./index.html) e apresenta:

- cabeçalho com navegação e menu adaptado para telas menores;
- banner principal com chamadas para ação;
- categorias de produtos: casual, esporte, moderno e futurista;
- grade visual de produtos;
- rodapé com formulário de newsletter, redes sociais e links de navegação.

O conteúdo é uma demonstração visual. Os links estão como `#` e não há carrinho funcional, fluxo de compra, integração com serviços ou backend.

## Tecnologias

- HTML5
- CSS3, incluindo Flexbox, Grid e media queries
- Imagens e ícones SVG locais
- Fonte Ubuntu carregada do Google Fonts

Não há dependências de JavaScript, gerenciador de pacotes ou etapa de build.

## Como visualizar

Abra `index.html` diretamente no navegador. Se preferir servir o projeto localmente, execute na pasta raiz:

```bash
python -m http.server 8000
```

Depois, acesse <http://localhost:8000>.

## Estrutura do repositório

```text
.
├── index.html                  # Página principal da SyntaxWear
├── images/
│   ├── banners/                # Banners desktop e mobile
│   ├── icons/                  # Ícones de navegação e redes sociais
│   ├── logo/                   # Logo da marca
│   └── products/               # Imagens de categorias e produtos
└── css/
    ├── reset.css               # Reset de estilos
    ├── variables.css           # Fonte e variáveis globais
    ├── base.css                # Estilos base e botões da vitrine
    ├── components/             # Estilos do cabeçalho, hero, categorias,
    │                           # grade de produtos e rodapé
    └── ...                     # Exercícios HTML/CSS independentes
```

### Página principal

Os estilos da vitrine estão separados por responsabilidade:

- `css/reset.css`, `css/variables.css` e `css/base.css`: estilos globais;
- `css/components/header.css`: cabeçalho e navegação responsiva;
- `css/components/hero.css`: banner principal;
- `css/components/product-category.css`: cartões de categorias;
- `css/components/product-grid.css`: grade de imagens de produtos;
- `css/components/footer.css`: rodapé e newsletter.

Os arquivos de imagem da página ficam em `images/banners/`, `images/icons/`, `images/logo/` e `images/products/`.

### Exercícios em `css/`

Cada pasta de exercício contém uma página HTML e seus estilos, podendo ser aberta individualmente no navegador.

**Flexbox:** `01-flex-direction`, `02-justify-content`, `03-align-items`, `04-flex-wrap-flex-flow`, `05-align-content`, `06-gap`, `07-grow`, `08-basis`, `09-shrink`, `10-flex`, `11-order`, `12-align-self` e `align-itens final`.

**Grid:** `grid`, `grid-auto-fit-auto-fill`, `grid-ocupando-espacos` e `grid-template-area`. A pasta `grid/` também contém o exemplo `minmax`.

**Fundamentos e responsividade:** `cores-fontes`, `css-inline-externo-interno`, `display`, `responsivo-com-media-queries`, `seletores` e `tecnicas-responsividade`.

Alguns exercícios incluem PDFs de apoio com explicações sobre propriedades de Flexbox.

## Licença

Este projeto está licenciado sob os termos da [MIT License](./LICENSE).
