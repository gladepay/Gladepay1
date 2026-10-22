# GladePay Compra Garantida — projeto completo

Projeto de página institucional em React + Vite, preparado para GitHub e Vercel.

## Estrutura obrigatória do repositório

Estes arquivos precisam estar na **raiz** do repositório GitHub (não dentro de outra pasta):

- `index.html`
- `package.json`
- `vite.config.js`
- `vercel.json`
- `.gitignore`
- `src/main.jsx`
- `src/styles.css`
- `public/favicon.svg`
- `public/og-gladepay.svg`

## Publicar ou corrigir na Vercel

1. Abra o repositório no GitHub.
2. Confira se `index.html`, `package.json` e `vite.config.js` aparecem na primeira página do repositório.
3. Se estiverem dentro de uma pasta `gladepay-compra-garantida/`, mova o conteúdo dessa pasta para a raiz do repositório, ou ajuste o **Root Directory** da Vercel para essa pasta.
4. Na Vercel, abra o projeto e vá a **Settings → Build and Deployment**.
5. Configure:
   - Framework Preset: `Vite`
   - Build Command: `npm run build`
   - Output Directory: `dist`
   - Install Command: `npm install`
   - Root Directory: `./` se os arquivos estiverem na raiz.
6. Abra **Deployments**, selecione **Redeploy** no último deploy e aguarde terminar.
7. Se continuar branco, abra **Deployments → último deploy → Build Logs** e confira o erro.

## Executar localmente

Requer Node.js instalado.

```bash
npm install
npm run dev
```

## Gerar build

```bash
npm install
npm run build
npm run preview
```

## URL e prévia de compartilhamento

A URL configurada no `index.html` é `https://gladepaygarantia.vercel.app/`.
Se o endereço público real for diferente, atualize `og:url`, `og:image`, a tag `canonical` e `twitter:image`, depois publique novamente.
A imagem Open Graph está em `public/og-gladepay.svg`.

## Importante sobre identidade e alegações

O conteúdo não afirma que o Banco Central garante ou reembolsa compras. O site tem caráter informativo; confirme os termos oficiais antes de anunciar condições específicas de uma garantia comercial.
A paleta escura e verde-menta é uma aproximação visual, não uma confirmação das cores oficiais da GladePay.
