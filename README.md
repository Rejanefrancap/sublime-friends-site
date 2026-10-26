# Sublime Friends — site e-commerce

Site responsivo para apresentar primeiro os bordados para empresas e profissionais: jalecos, uniformes, bonés e patches táticos personalizados com a logo do cliente. Canecas, azulejos e camisetas estampadas ficam em uma seção complementar. O pedido começa pelo WhatsApp; preço, arte, produção e frete são confirmados no atendimento. O texto do frete já descreve o cálculo pelo Melhor Envio e a possibilidade de encaminhar clientes para Shopee ou Mercado Livre.

## Publicar no GitHub Pages (sem instalar programas)

1. Entre em https://github.com e crie uma conta ou entre na sua.
2. Clique em New repository. Use um nome simples, por exemplo sublime-friends, e marque Public. Não crie README, licença ou outros arquivos iniciais.
3. No repositório vazio, clique em Add file → Upload files.
4. Arraste os arquivos e pastas deste projeto para a janela. Inclua index.html, styles.css e a pasta public com sua logo. Clique Commit changes.
5. No repositório, abra Settings → Pages. Em Build and deployment, selecione Deploy from a branch. Escolha main e /(root) e clique Save.
6. Aguarde a publicação. A própria tela Pages mostrará o endereço gratuito, no formato https://seu-usuario.github.io/sublime-friends/.

A cada atualização futura, abra o arquivo no GitHub, envie os arquivos alterados e confirme em Commit changes; o Pages publica a nova versão automaticamente. O site e os arquivos do repositório ficam públicos.

## Conectar domínio próprio depois

Primeiro compre/registre o domínio que escolher. Depois, nas configurações Settings → Pages, adicione o domínio em Custom domain e salve. Em seguida, configure no painel da empresa onde comprou o domínio os registros DNS indicados pelo GitHub. Para um endereço www, o GitHub usa um registro CNAME que aponta para seu-usuario.github.io; para o domínio sem www, siga os registros A/AAAA exibidos pela documentação oficial. Quando o GitHub liberar a opção, ative Enforce HTTPS. A propagação de DNS pode levar até 24 horas. Consulte os links oficiais no fim deste guia antes de mudar o DNS.

## Atualizações necessárias para ficar completo

- O número informado já está ligado aos botões: +55 71 99317-5215.
- Envie os endereços da sua loja na Shopee e no Mercado Livre para acrescentar os atalhos correspondentes. Atualmente a página informa que o atendimento pode direcionar pedidos para esses canais, mas não inventa links.
- Revise os textos e substitua as ilustrações por fotos reais dos seus produtos quando tiver boas imagens. A página não anuncia preços, estoque, prazo fixo ou frete grátis porque essas condições não foram informadas.
- Para aparecer melhor em buscas, mantenha descrições verdadeiras e úteis, acrescente fotos próprias com texto alternativo e, quando quiser, informe cidade/região para incluir conteúdo local. O texto já inclui termos de busca como bordado para empresas, jaleco bordado com logo, boné personalizado bordado e patch tático bordado sem repetição artificial.

## Arquivos

- index.html: conteúdo, categorias e informações para mecanismos de busca.
- styles.css: visual adaptável para computador e celular.
- public/images/sublime-friends-logo.jpeg: logo enviada pela proprietária.

## Ajuda oficial do GitHub

- Escolher como o GitHub Pages publica o site: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- Configurar domínio próprio e DNS: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
- Proteger o site com HTTPS: https://docs.github.com/en/pages/getting-started-with-github-pages/securing-your-github-pages-site-with-https


