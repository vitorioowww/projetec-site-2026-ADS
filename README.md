# Projetec Montenegro — protótipo de site

Protótipo responsivo de página única (HTML, CSS e JavaScript puro), preparado para GitHub Pages.

## Visualizar localmente

Abra `index.html` no navegador. Não precisa instalar dependências.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (por exemplo, `projetec-site`).
2. Envie `index.html`, `README.md` e a pasta `assets/` para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione `main` e `/ (root)` e salve.
6. Aguarde o GitHub gerar o endereço público do site.

## Antes de publicar para a empresa

- Confira os textos institucionais e confirme a descrição de empresa familiar.
- Cadastre as fotos reais das garras e associe cada imagem a modelo, código, aplicação, material, dimensões e demais especificações aprovadas pela empresa.
- O catálogo está preparado para filtros por categoria, busca por texto e uso. Para acrescentar produtos, duplique o bloco `<article class="product-card">` e atualize `data-category`, `data-use`, `data-search`, imagem e texto.
- Substitua `WHATSAPP_NUMBER` no final de `index.html` pelo número oficial, apenas com DDI + DDD + número (somente dígitos).
- Substitua ou complete telefone e e-mail na seção de contato.

## Conteúdo usado neste protótipo

- Dados institucionais: Projeto fase 1 fornecido (fundação em 1998, Novo Hamburgo e cerca de 20 colaboradores).
- Imagens: logo, fachada e fotografia de equipamento extraídos do material fornecido. A fotografia do equipamento está identificada como referência visual; confirmar a identificação do produto antes de publicar.

O formulário só abre o WhatsApp depois que o número oficial for configurado. Até lá, ele mostra uma orientação e não envia dados a nenhum serviço.
