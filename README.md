# Tattoo JAD — propostas de website

Três propostas de site para **Jadson Felipe** ([@_tattoojad_](https://www.instagram.com/_tattoojad_/)), tatuador em Delmiro Gouveia - AL.

| Pasta | Proposta |
|---|---|
| `proposta-01/` | Tattoo JAD — dark premium |
| `proposta-02-black-label/` | Black Label — underground, preto e branco |
| `proposta-03-ink-atelier/` | Ink Atelier — galeria de arte em fundo claro |
| `img/` | Fotos reais dos trabalhos (compartilhadas pelos 3 sites) |

`index.html` na raiz é a página de apresentação com links para as três.

## Como ver no computador

Abra `index.html` no navegador (duplo clique).

## Ajustes rápidos

Cada site tem um bloco `CONFIG` no início do `<script>`:

- `whatsapp`: número com DDI + DDD, só dígitos (ex.: `5582900000000`). Vazio = botão do WhatsApp aguardando o número.
- Fotos: listas `PORTFOLIO` / `WORKS` apontam para arquivos em `img/`.

Feito em HTML, CSS e JavaScript puros: não precisa instalar nada nem compilar.

## Publicação no Cloudflare Pages

Site estático, sem etapa de build.

- Framework preset: **None**
- Build command: *(vazio)*
- Build output directory: **/** (raiz do repositório)

O arquivo `_headers` define cache longo para `img/`.
