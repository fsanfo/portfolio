# Portfólio de BI — Fabiano Fonseca

Portfólio pessoal em HTML, CSS e JavaScript com foco em Business Intelligence, Data Visualization, Engenharia de Dados e Governança de Dados.

Site publicado em:
[fsanfo.github.io/portfolio](https://fsanfo.github.io/portfolio)

## Sobre

O projeto reúne:
- projetos reais de BI com foco em contexto executivo e profundidade técnica
- artigos técnicos publicados no LinkedIn
- currículo em português e inglês
- canais diretos de contato

A versão atual do site adota uma interface premium com navegação reativa, hero imersivo, animações com GSAP, cards de projetos com modal detalhada e layout responsivo.

## Estrutura

```text
portfolio/
├── index.html
├── index.html.bak
├── portfolio_cv.html
├── README.md
├── assets/
│   ├── css/
│   └── pbi/
├── cv/
├── prompts/
└── templates/
```

## Destaques da Interface

- Hero premium com tipografia expressiva e animações de entrada
- Navegação fixa com comportamento dinâmico no scroll
- Tooltip textual contextual no menu
- Seção de projetos com cards em blur e modal com detalhes completos
- Seção de artigos com curadoria visual e links externos
- Smooth scroll e animações progressivas respeitando `prefers-reduced-motion`

## Projetos Apresentados

O portfólio destaca entregas em áreas como:
- dashboard executivo
- indicadores comerciais
- controladoria e EBITDA
- segmentação RFM
- metas e vendas de e-commerce
- supply chain com OTD e SLA

## Stack

- HTML5
- CSS3
- JavaScript vanilla
- GSAP
- ScrollTrigger
- Lenis
- SplitType
- Google Fonts

## Execução Local

Como o projeto é estático, basta abrir o arquivo principal no navegador:

```bash
start index.html
```

Se preferir, use uma extensão como Live Server no VS Code.

## Currículos

- Português: `cv/FabianoFonsecaResume-pt-BR.pdf`
- Inglês: `cv/FabianoFonsecaResume-en-US.pdf`

## Contato

- Email: [fsanfo@gmail.com](mailto:fsanfo@gmail.com)
- LinkedIn: [linkedin.com/in/fsanfo](https://www.linkedin.com/in/fsanfo)
- WhatsApp: [+55 98 9 9202-3224](https://wa.me/5598992023224)

## Observação

`index.html` é a versão principal em produção. O arquivo experimental `index-b.html` foi removido após a migração definitiva do layout premium.
