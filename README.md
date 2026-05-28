# Combo Papelaria Pronta — Static Export

Página de vendas estática pronta para deploy.

## Como subir

### GitHub + Vercel
1. Crie um repositório no GitHub e suba TODO o conteúdo desta pasta (`index.html` + `README.md`).
2. Na Vercel, clique em "Add New Project" → importe esse repo.
3. Framework Preset: **Other** (Static).
4. Build Command: deixe vazio.
5. Output Directory: deixe vazio (raiz).
6. Clique em **Deploy**.

### Drag & drop direto na Vercel
1. Acesse https://vercel.com/new
2. Arraste a pasta `static-export` inteira.
3. Deploy.

## O que está incluso
- Meta Pixel `1827075004936114` com `PageView`, `ViewContent` e `InitiateCheckout` no clique.
- UTMify Pixel `6a176c76ff79882e807503af`.
- UTMify UTMs script para captura/repasse.
- Checkout: `https://pay.wiapy.com/gcdazylzke` com repasse automático de todas as UTMs e `fbclid`.
- Layout 100% responsivo, otimizado para mobile.
