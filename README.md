# audiosubs-site — Página de vendas do AudioSubs

Landing page (PT/EN/ES) + política de privacidade, pronta para hospedar no **GitHub Pages** de graça.

## Como publicar (passo a passo)

1. **Crie um repositório novo** no GitHub (pode ser privado — o Pages funciona igual), ex.: `audiosubs-site`.
   - Clique em "Create repository". NÃO marque "Initialize with README".
2. Suba este conteúdo para o repositório (na raiz do repo):
   ```bash
   git init
   git add .
   git commit -m "Site de vendas AudioSubs (PT/EN/ES)"
   git branch -M main
   git remote add origin https://github.com/Roby87gyn/audiosubs-site.git
   git push -u origin main
   ```
3. Ative o GitHub Pages:
   - Repo → **Settings** → **Pages** (menu lateral)
   - Source: **Deploy from a branch** → branch `main` → pasta `/ (root)` → **Save**
   - Aguarde ~1 min. O site fica em `https://Roby87gyn.github.io/audiosubs-site/`

## Placeholders para substituir (ANTES de publicar)

Procure por `SEU_` em todos os arquivos e troque:

| Placeholder | Onde | Trocar por |
|---|---|---|
| `Roby87gyn` | links de download nos 3 `index.html` | seu usuário do GitHub |
| `SEU_LINK_GUMROAD` | botão "Comprar PRO" | o link do produto criado no Gumroad |
| `SEU_EMAIL@exemplo.com` | rodapé/privacidade/suporte | seu e-mail de contato/suporte |

## Preços atuais no site

- **Brasil (R$):** PRO R$ 119 vitalício (faixa sugerida R$ 99–149)
- **Global (US$):** PRO $39 vitalício (faixa sugerida US$ 29–49)

Ajuste os valores no `<div class="price">` se quiser outro ponto da faixa.

## Download do instalador

O botão "Baixar grátis" aponta para os **GitHub Releases** do repositório principal
(`https://github.com/Roby87gyn/audiosubs/releases`). Quando publicar a primeira
release do app (com `AudioSubs Setup 1.1.0.exe`), os links do site funcionam automaticamente.

Estrutura: `/` = PT (público principal), `/en/` e `/es/` = inglês e espanhol.
