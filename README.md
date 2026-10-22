# GladePay Compra Garantida

Página institucional de uma página, construída com React + Vite, preparada para GitHub e Vercel.

## Rodar localmente

```bash
npm install
npm run dev
```

## Gerar build

```bash
npm run build
```

## Publicar na Vercel

1. Envie os arquivos deste projeto para um repositório GitHub.
2. Na Vercel, importe esse repositório.
3. Use as configurações padrão do Vite: comando de build `npm run build` e diretório de saída `dist`.
4. Depois de publicar, edite `index.html` e substitua `https://gladepaygarantia.vercel.app/` pelo endereço público real do projeto nas metatags `og:url`, `og:image` e na tag `canonical`.
5. Publique novamente para atualizar as metatags.

## Importante sobre identidade e alegações

O tema inicial usa uma paleta escura com verde-menta como aproximação visual. Ajuste as variáveis CSS em `src/styles.css` após comparar com o site oficial, pois as cores oficiais não foram verificadas automaticamente.

O conteúdo não afirma que o Banco Central garante ou reembolsa compras, nem cria uma garantia comercial inexistente. Antes de anunciar condições específicas de Compra Garantida, confirme e publique os termos oficiais da empresa.

## Open Graph

A arte para compartilhamento fica em `public/og-gladepay.svg`. Após a publicação, confirme que a imagem abre publicamente e teste a prévia do WhatsApp. Alguns clientes mantêm o cache da prévia.
