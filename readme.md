# Flor de Pele — loja de beleza

Protótipo de uma loja virtual de beleza com páginas separadas para clientes e vendedores. O catálogo começa vazio, sem produtos de demonstração.

## Como abrir

Abra `index.html` no navegador. Ele leva ao catálogo da loja.

## Páginas

- `index.html` — entrada da loja.
- `cliente/catalogo.html` — vitrine, filtros por categoria e sacola.
- `cliente/cliente.html` — dados da conta do cliente e área de pedidos.
- `adm/vendedor.html` — painel do vendedor, cadastro e remoção de produtos.
- `adm/login.html` — reservado para a entrada do vendedor.

## Protótipo

Os produtos cadastrados pelo painel do vendedor e os dados da conta ficam no `localStorage` do navegador. A vitrine lê os produtos cadastrados neste mesmo navegador. Pedidos, pagamento, autenticação real e sincronização entre dispositivos ainda não estão conectados a um servidor.

## Personalização

Edite textos, cores e imagens diretamente nos arquivos HTML. O painel permite cadastrar nome, categoria, preço, estoque e URL opcional de imagem.
