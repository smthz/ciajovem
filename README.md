# Catálogo de Figurinos — Cia Jovem de Matão

Site estático (HTML, CSS e JS num arquivo só). Reservas pelo Onde Tá?.

## Estrutura

    index.html      página inteira
    vercel.json     cache das imagens
    img/            90 fotos
    logo-cia.png    logo completo
    marca-cia.png   bailarina e globo
    og-cover.jpg    preview ao compartilhar (1200x630)
    favicon.png     ícone da aba

## Publicar na Vercel

1. Importar este repositório em vercel.com/new
2. Framework Preset: **Other**. Build Command e Output Directory em branco.
3. Deploy.

## Editar

Preços, tamanhos e textos ficam no array `FIGURINOS`, no `<script>` no fim
do `index.html`. Cada commit na branch `main` publica sozinho.

## Endereço

Ao definir o domínio final, troque as 5 linhas do bloco "ENDERECO DO SITE"
no topo do `index.html` (canonical, og:url, og:image, twitter:image,
og:image:secure_url). Sem isso, o preview do WhatsApp aponta para o endereço antigo.
