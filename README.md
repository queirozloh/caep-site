# CAEP — Centro Acadêmico de Engenharia de Produção

Site institucional estático do Centro Acadêmico de Engenharia de Produção da UFMS.

## Tecnologias

- HTML5
- CSS3 responsivo
- JavaScript sem dependências

## Executar localmente

Abra `index.html` em um navegador moderno. Não há instalação de dependências nem etapa de build.

Para simular a publicação, sirva esta pasta com um servidor estático local, por exemplo usando a extensão Live Server do VS Code.

## Publicação

O projeto está pronto para ser publicado como site estático na Vercel. A Vercel detecta `index.html` automaticamente; não há comando de build ou diretório de saída configurado.

## Estrutura

- `index.html` — estrutura e metadados da página
- `styles.css` — identidade visual, responsividade e animações
- `app.js` — rotas por hash, dados mockados e interações
- `assets/caep/` — logos, mascote e capacete oficiais

Os dados demonstrativos estão centralizados em `app.js`. O formulário é visual e não envia dados a um servidor nesta versão.
