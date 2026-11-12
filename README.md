# Reinald Mendes — Soluções em Gestão e Tecnologia

Landing page / portfólio, feita em HTML, CSS e JavaScript puros (sem build). Usa só as fontes do Google Fonts como dependência externa.

## Estrutura
```
index.html          página inteira (CSS e JS embutidos)
foto.jpg            foto da seção "Sobre"
assets/
  favicon.svg, favicon-32.png, apple-touch-icon.png, favicon-192.png, icon-512.png
  og-image.png                   imagem exibida ao compartilhar o link (1200 x 630)
  logo-mark-claro.svg / .png     selo RM para fundos claros
  logo-mark-escuro.svg / .png    selo RM para fundos escuros
```

## O que a página tem
- Logo RM (selo com a curva de crescimento) no cabeçalho, no "Sobre", no contato e no rodapé
- Tema claro/escuro automático, com alternância manual
- Hero com curva animada, painel de demonstração e indicadores
- Segmentos atendidos, serviços, seção "Para lojas" com chamada para demonstração
- Portfólio com filtros (Trilhas da Infância, Maxx Confort, Reflorescer, Rose Monteiro, Jogos Escolares e Apps Script)
- Processo de trabalho, "Sobre" com dados da empresa (CNPJ), contato com WhatsApp e botão "Copiar número"
- Botão flutuante de WhatsApp, barra de progresso de leitura, animações suaves (respeitam "reduzir movimento")
- Metadados de compartilhamento (Open Graph) e dados estruturados para buscadores

## Publicar no GitHub Pages
1. Envie todos os arquivos para o repositório, mantendo `index.html` na raiz e a pasta `assets/`.
2. Em **Settings → Pages**, escolha a branch principal e a pasta `/ (root)`.
3. Abra `index.html` e confirme o endereço da constante usada em `og:url` e `og:image`
   (`https://reinaldmendes.github.io/portfolio-reinald-mendes/`). Se o seu endereço for outro, troque nessas duas linhas.

## Editar conteúdo
As seções estão marcadas por comentários HTML (`<!-- HERO -->`, `<!-- SERVIÇOS -->`, `<!-- PARA LOJAS -->`, `<!-- PORTFÓLIO -->`, `<!-- PROCESSO -->`, `<!-- SOBRE -->`, `<!-- CONTATO -->`).
O WhatsApp aparece em `wa.me/5542991562593`; para trocar o número, substitua nos links e no texto da seção de contato.
