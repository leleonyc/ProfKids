# Prof Kids – Página de vendas

Página estática (HTML único), sem build.

## Subir no GitHub
```bash
cd prof-kids
git init
git add .
git commit -m "Página de vendas Prof Kids"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/prof-kids.git
git push -u origin main
```

## Publicar na Vercel
1. Acesse vercel.com > Add New > Project.
2. Importe o repositório `prof-kids`.
3. Framework Preset: **Other**. Deixe Build Command e Output Directory vazios.
4. Clique em **Deploy**.

Ou pela CLI: `npm i -g vercel && vercel --prod`

## Editar
- Link de checkout: procure `pay.cakto.com.br` no `index.html`.
- Preço e textos: edite direto no `index.html`.
