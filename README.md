# Game translations / Traduções dos jogos

Translations for otaviols' audiogames, one folder per game. Anyone can contribute a language.

Traduções dos audiogames do otaviols, uma pasta por jogo. Qualquer pessoa pode contribuir com um
idioma.

| Game / Jogo | Folder / Pasta |
|---|---|
| Among Us Audiogame | [`among-us/`](among-us/) |

## How to contribute / Como contribuir

You do not need to know Git. Each game has a way to **send your translation from inside the game**
(see the game's folder). The maintainer reviews it and commits it here; it ships with the next
version of the game.

Não precisa saber Git. Cada jogo tem um jeito de **enviar a tradução de dentro do próprio jogo**
(veja a pasta do jogo). O mantenedor revisa e commita aqui; ela vai junto na versão seguinte.

If you do use GitHub, pull requests are welcome too: edit or add `lang/<code>.json` in the game's
folder. / Se você usa GitHub, pull request também serve: edite ou acrescente `lang/<código>.json`
na pasta do jogo.

## Rules that apply to every game / Regras que valem para todos os jogos

- Files are UTF-8 JSON, one flat object, `"key": "text"`. Keys never change; only translate the
  values. / Arquivos são JSON em UTF-8, um objeto só, `"chave": "texto"`. As chaves nunca mudam;
  traduza só os valores.
- `language.name` is the language's name **in that language** ("Español", not "Spanish"). It is
  what players hear in the language list. / `language.name` é o nome do idioma **no próprio idioma**.
- `language.translator` (optional) is your name, spoken next to the language: credit is deserved. /
  `language.translator` (opcional) é o seu nome, dito ao lado do idioma: crédito é merecido.
- Text inside `{braces}` is filled in by the game — keep it exactly as is. / O que está entre
  `{chaves}` é preenchido pelo jogo — mantenha igual.
- `en_US.json` in each game folder is the reference: it always has every key. Missing keys are not
  an error; the game falls back to English for them. / O `en_US.json` de cada jogo é a referência:
  sempre tem todas as chaves. Chave faltando não é erro; o jogo usa o inglês nela.
