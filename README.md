# Proposta comercial — Produção audiovisual para imobiliárias

Site estático de uma página: `index.html` + pasta `videos/`.

## Publicar no GitHub Pages (grátis)

1. Crie um repositório **público** no GitHub (ex.: `proposta`).
2. Envie todo o conteúdo desta pasta (`index.html`, `README.md`, `.nojekyll` e a pasta `videos/`).
   - Pelo site: **Add file → Upload files**, arraste os arquivos e confirme em **Commit changes**.
3. Vá em **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)` e salve.
5. Em 1 a 2 minutos o site fica no ar em `https://SEU-USUARIO.github.io/proposta/`.

## Personalizar

Tudo fica no bloco de configuração no topo do segundo `<script>` do `index.html`:

- `SITE_CONFIG.brandName`: nome do estúdio.
- `SITE_CONFIG.whatsappNumber`: só dígitos, com DDI e DDD (ex.: `5531999999999`).
- `SITE_CONFIG.instagramUrl` e `SITE_CONFIG.email`.
- `PRICING_CONFIG`: preço por vídeo (em centavos) e faixas de desconto.
- `VIDEOS`: lista dos vídeos da seção Padrão de Vídeos. A `poster` de cada um também é a capa dos cards no carrossel do hero.

## Trocar ou adicionar vídeos

Coloque o MP4 e a capa (JPG, 9:16) em `videos/` e adicione uma linha em `VIDEOS`.
Para manter o site leve, exporte em H.264, 720×1280, por volta de 2,5 Mbps, com áudio AAC.
Pelo upload no navegador, o GitHub aceita no máximo 25 MB por arquivo (pelo Git ou GitHub Desktop, até 100 MB).

## Observação sobre os vídeos de referência

Os vídeos atuais são referências de estilo de outros produtores e estão creditados nos cards.
Como o repositório é público, o ideal é ter autorização dos autores ou substituí-los por produções próprias assim que houver portfólio.
