# VMC Consultoria em Leilões — site institucional

Landing page estática (HTML + CSS puro, sem build) da VMC Consultoria em Leilões, consultoria de Vinicius M. Carvalho para leiloeiros oficiais.

## Estrutura
- `index.html` — página única, em português (pt-BR)
- `assets/css/styles.css` — todos os estilos (variáveis de cor em `:root`)
- `assets/img/` — foto (jpg + webp) e favicon
- `robots.txt`, `sitemap.xml` — SEO básico

## Regras do conteúdo
- É uma **prestação de serviços e consultoria**: em algumas frentes o Vinicius executa, em outras orienta o leiloeiro e a equipe dele. Nunca escrever que ele "faz tudo" ou "substitui a equipe".
- **Não** oferecer modelo de edital: edital é sempre "elaborado em parceria com advogados especializados".
- As 4 etapas (Setup Inicial, Montagem do Evento, Operação de Pregão, Growth & Atendimento) têm o **mesmo peso visual** — nenhuma destacada como plano principal.
- Ordem das seções: problemas → soluções (4 etapas) → quem sou (formação e experiência) → contato.

## Identidade visual
- Azul-marinho `#16294A`, ouro `#D4A72C`, cinza escuro `#2A2D33`, azul aço `#3E6A9E`
- Fontes (Google Fonts): Sora (títulos), Inter (texto), Manrope (logo)
- Logo: "vmc" minúsculo + losango dourado + linha de batida + "consultoria em leilões"

## Domínio
`consultoriavmc.com.br` — usado em `index.html` (canonical, og:url, og:image, JSON-LD), `robots.txt` e `sitemap.xml`. Se mudar, trocar nesses três arquivos.

## Deploy
Site estático: publicar a pasta raiz como está (Vercel, Netlify ou Cloudflare Pages). Não há etapa de build.
