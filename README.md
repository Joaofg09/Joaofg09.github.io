# JPFG Apps — hub

Página: https://joaofg09.github.io/

- `index.html` monta os cartões a partir de `apps.json`.
- Para cadastrar um app, acrescente UM item no final de `apps.json` (campos: slug, nome, descricao,
  icone, site, privacidade, play, status). Quando o app for publicado, preencha `play` com o link
  da Play Store e troque `status` para `"disponível"`.
- Cada app tem o próprio repositório de site (`<slug>-site`) com a sua política de privacidade.
- Quando houver anúncios, o arquivo `app-ads.txt` do AdMob fica na raiz deste repositório.
- Campos opcionais para jogos: `"tipo": "jogo"` deixa o cartão com visual de jogo (selo 🎮 JOGO) e
  `"tema": {"de": "#RRGGBB", "para": "#RRGGBB", "acento": "#RRGGBB"}` escolhe as cores do degradê e do destaque.
