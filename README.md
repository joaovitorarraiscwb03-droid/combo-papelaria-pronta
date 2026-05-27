# Combo Papelaria Pronta no Canva — Static Export

Página de vendas estática pronta para publicar no GitHub + Vercel.

## Conteúdo
- `index.html` — página completa, auto-contida (HTML + CSS + JS inline)
- Facebook Pixel `1827075004936114` configurado (PageView + ViewContent)
- UTMify Pixel `6a176c76ff79882e807503af` configurado
- UTMify UTM tracker configurado
- Todos os botões apontam para `https://pay.wiapy.com/gcdazylzke`
- UTMs da URL atual são repassadas automaticamente para o checkout
- Eventos `CliqueCheckout` + `InitiateCheckout` no clique

## Como publicar no GitHub + Vercel

1. Crie um repositório novo no GitHub.
2. Suba o conteúdo desta pasta (apenas `index.html` e este `README.md`).
3. Em [vercel.com](https://vercel.com) clique em **Add New → Project** e importe o repositório.
4. Framework Preset: **Other** (Static). Não precisa configurar build.
5. Deploy.

Pronto — a página estará no ar com pixel e UTMs funcionando.

## Teste rápido
Abra a página com UTMs na URL, por exemplo:
```
https://seudominio.com/?utm_source=FB&utm_campaign=teste
```
Clique no botão de compra — o checkout abrirá com as UTMs preservadas.
