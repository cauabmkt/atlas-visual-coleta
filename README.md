# Atlas Visual da Coleta — Página de Vendas

Site estático (HTML único, sem build). Deploy via GitHub + Vercel.

## Estrutura
- `index.html` — página completa (CSS, JS e imagens WebP embutidos)
- `vercel.json` — URLs limpas e headers de segurança

## Deploy
1. Suba esta pasta para um repositório no GitHub.
2. Na Vercel: Add New → Project → importe o repositório.
3. Framework Preset: **Other**. Build Command e Output Directory: vazios.
4. Deploy. Cada `git push` na branch `main` publica automaticamente.
