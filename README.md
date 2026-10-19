# Portfólio — Anderson Akira Mekaru

Site estático (HTML, CSS e JavaScript puros, sem build).

## Estrutura
- `index.html` — página do portfólio
- `assets/anderson-akira-mekaru.jpg` — foto do perfil
- `favicon.svg` — ícone da aba
- `vercel.json` — configuração do Vercel

## Publicar no Vercel

**Pelo site (mais simples)**
1. Acesse vercel.com e entre com sua conta.
2. Clique em **Add New → Project**.
3. Envie esta pasta para um repositório no GitHub e importe-o, ou arraste a pasta na tela de deploy.
4. Em **Framework Preset**, escolha **Other**. Deixe Build Command e Output Directory vazios.
5. Clique em **Deploy**.

**Pela linha de comando**
```bash
npm i -g vercel
cd akira-portfolio
vercel        # pré-visualização
vercel --prod # produção
```

## Trocar a foto
Substitua `assets/anderson-akira-mekaru.jpg` por outra imagem com o mesmo nome.
