# audiosubs-site — Página de vendas do AudioSubs

Landing page (PT/EN/ES) + política de privacidade, hospedada no **GitHub Pages**.

## Status (publicado)

- **Repo:** https://github.com/Roby87gyn/audiosubs-site
- **Site:** https://roby87gyn.github.io/audiosubs-site/
- **Pages:** branch `main`, pasta `/` (root), deploy automático no push.

Para atualizar o site: edite os arquivos, `git add -A && git commit && git push` — o Pages republica sozinho em ~1 min.

## Placeholders ainda pendentes (dependem das contas de venda)

| Placeholder | Onde | Trocar por |
|---|---|---|
| `SEU_LINK_GUMROAD` | botão "Comprar PRO" nos 3 `index.html` | o link do produto criado no Gumroad |
| `SEU_EMAIL@exemplo.com` | rodapé/privacidade/suporte | seu e-mail de contato/suporte |

(Os links de download já apontam para o repo e a release reais: `https://github.com/Roby87gyn/audiosubs/releases`.)

## Preços atuais no site

- **Brasil (R$):** PRO R$ 119 vitalício (faixa sugerida R$ 99–149)
- **Global (US$):** PRO $39 vitalício (faixa sugerida US$ 29–49)

Ajuste os valores no `<div class="price">` se quiser outro ponto da faixa.

## Download do instalador

O botão "Baixar grátis" aponta para os **GitHub Releases** do app:
`https://github.com/Roby87gyn/audiosubs/releases` (release **v1.1.0** já publicada com
`AudioSubs Setup 1.1.0.exe`).

Estrutura: `/` = PT (público principal), `/en/` e `/es/` = inglês e espanhol.
