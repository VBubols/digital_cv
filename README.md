# Currículo Digital

Currículo pessoal em HTML e CSS puro, pensado para leitura na web e para impressão em A4 sem ajuste manual.

Acesse o currículo aqui: https://vbubols.github.io/digital_cv/

Projeto desenvolvido como atividade do curso Técnico em Desenvolvimento de Sistemas (SENAI São José), com foco em HTML semântico, CSS moderno e fluxo de trabalho com Git e pull requests.

## O que foi construído

- Layout em duas colunas com trilho de rótulos, que colapsa para coluna única em telas menores que 720px
- Tipografia baseada na superfamília IBM Plex (Sans nos títulos, Serif no corpo, Mono nos metadados)
- Sistema de cores em variáveis CSS, permitindo trocar a identidade visual em um único ponto
- Folha de estilo de impressão com `@page` em A4 e controle de quebra de página
- HTML semântico com `header`, `section`, `dl` e listas, sem `div` genérica carregando significado
- Foco visível para navegação por teclado e suporte a `prefers-reduced-motion`

## Tecnologias

| Camada | Uso |
| --- | --- |
| HTML5 | Estrutura semântica do documento |
| CSS3 | Grid, Flexbox, variáveis customizadas, media queries |
| Google Fonts | IBM Plex Sans, Serif e Mono |

Sem dependências, sem build, sem framework. Abre direto no navegador.

## Estrutura

```
digital_cv/
├── index.html    # conteúdo e marcação do currículo
├── style.css     # tokens, layout, responsivo e regras de impressão
└── README.md
```

## Gerar o PDF

No navegador, use `Ctrl + P`. O CSS de impressão já define o formato A4, as margens e evita que blocos sejam cortados entre páginas. Em Destino, escolha "Salvar como PDF" e mantenha a opção de gráficos de plano de fundo ativada para preservar os detalhes coloridos.

## Fluxo de trabalho

A branch `main` é protegida e recebe apenas código revisado.

```
main            branch estável, exige pull request com aprovação
 └── dev        desenvolvimento e ajustes
```

## Autor

**Vitor Razia Bubols**

[LinkedIn](https://www.linkedin.com/in/vitor-bubols) · [GitHub](https://github.com/VBubols)