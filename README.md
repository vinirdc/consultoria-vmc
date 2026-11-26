# VMC Consultoria em Leilões — site

Site estático (HTML + CSS), pronto para publicar. Não precisa instalar nada nem rodar build.

## Ver no computador
Abra o `index.html` no navegador (duplo clique).

## Publicar com o Claude Code

1. Descompacte esta pasta no seu computador (ex.: `C:\Projetos\vmc-site`).
2. Abra o terminal nessa pasta e rode `claude`.
3. Cole o prompt abaixo, trocando o domínio:

```
Este é o site estático da VMC Consultoria em Leilões (leia o CLAUDE.md).
O domínio é: meudominio.com.br

1. Substitua SEU-DOMINIO.com.br pelo domínio real em index.html, robots.txt e sitemap.xml.
2. Inicialize um repositório git, faça o primeiro commit e crie um repositório
   privado no meu GitHub chamado vmc-site (use o gh CLI) e faça o push.
3. Publique na Vercel (use a Vercel CLI: npx vercel --prod), como site estático, sem build.
4. Adicione o domínio e o www ao projeto na Vercel e me diga exatamente quais
   registros DNS (tipo, nome e valor) eu preciso criar no painel onde o domínio foi registrado.
```

## Apontar o domínio (DNS)
A Vercel mostra os registros exatos depois que você adiciona o domínio. Normalmente são:

| Tipo  | Nome | Valor |
|-------|------|-------|
| A     | @    | 76.76.21.21 |
| CNAME | www  | cname.vercel-dns.com |

Se o domínio for `.com.br`, esses registros são criados no **Registro.br** (Painel › seu domínio › DNS › Editar zona). A propagação pode levar de alguns minutos a algumas horas. O HTTPS é ativado automaticamente pela Vercel.

## Antes de publicar
- [ ] Trocar `SEU-DOMINIO.com.br` pelo domínio real
- [ ] Conferir telefone, e-mail e LinkedIn na seção de contato
- [ ] (Opcional) Criar um e-mail no próprio domínio, ex.: contato@meudominio.com.br
