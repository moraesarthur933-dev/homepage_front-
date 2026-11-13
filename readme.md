# Loja de beleza

Projeto de protótipo de e-commerce de beleza e autocuidado, com foco em uma experiência visual premium para clientes que desejam explorar produtos, adicionar itens à sacola e manter dados pessoais no navegador.

## Visão geral

A loja foi desenvolvida como uma interface estática em HTML/CSS/JS, sem backend ou banco de dados. O objetivo principal é demonstrar a navegação e os fluxos de compra de um catálogo de beleza em um ambiente leve, rápido e fácil de executar localmente.

## Funcionalidades

- Catálogo de produtos com layout editorial e visual elegante
- Filtros por categoria da vitrine
- Adição de itens à sacola com controle de quantidade
- Página de conta do cliente com dados pessoais
- Armazenamento local em `localStorage` para simular persistência do navegador
- Interface responsiva para visualização em desktop e mobile

## Estrutura do projeto

```text
.
├── index.html                # Redireciona para a vitrine da loja
├── cliente/
│   ├── catalogo.html         # Página principal da loja
│   └── cliente.html          # Perfil do cliente e dados da conta
├── LICENSE                   # Licença do projeto
├── readme.md                 # Documentação do projeto
└── (outros arquivos locais) # Possíveis arquivos temporários ou de configuração do ambiente
```

## Como executar

### Opção 1: abrir diretamente no navegador

1. Abra a pasta do projeto no seu computador.
2. Clique duas vezes em `index.html`.
3. O navegador abrirá a vitrine da loja.

### Opção 2: servir localmente

Se preferir uma abordagem mais próxima de um ambiente web, execute:

```bash
cd "C:\Users\morae\Desktop\homepege_ front"
python -m http.server 8000
```

Depois, acesse:

```text
http://localhost:8000/
```

## Observações importantes

Este projeto é um protótipo front-end e não inclui:

- autenticação real de usuários
- checkout com pagamento integrado
- backend ou API
- sincronização entre dispositivos
- persistência em banco de dados

Todos os dados criados no navegador ficam armazenados no `localStorage` do próprio cliente, o que é suficiente para simular o comportamento de uma loja estática em demonstrações locais.

## Personalização

Você pode alterar facilmente:

- textos e slogans
- cores e estilos visuais
- imagens de destaque
- nomes, preços e categorias dos produtos

Os ajustes podem ser feitos diretamente nos arquivos HTML/CSS do projeto.

## Licença

Este projeto está licenciado sob a Apache License 2.0. Consulte o arquivo [LICENSE](./LICENSE) para mais detalhes.

## Status do projeto

Prototype front-end de e-commerce de beleza, pronto para uso local e demonstração visual. Ainda não representa um sistema completo de vendas online.
