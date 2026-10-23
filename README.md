# OptiFlow — Sistema de Gestão para Óticas

**Projeto pessoal de portfólio** desenvolvido por Bruna Martins, estudante de Análise e Desenvolvimento de Sistemas, inspirado em sua experiência profissional no setor óptico.

## Demonstração
[Ver OptiFlow online](https://brumartinss07.github.io/optiflow/) — é necessário ativar GitHub Pages em **Settings → Pages → Deploy from a branch → main → /(root)**.

## Funcionalidades
- Dashboard com indicadores, pedidos recentes e alertas de estoque baixo
- Produtos: cadastrar, consultar, editar e excluir armações, marcas, preços e quantidades
- Clientes: cadastrar, consultar, editar e excluir registros fictícios
- Pedidos: registrar cliente, descrição, valor e status; filtrar e pesquisar
- Relatórios: pedidos por status, unidades por marca e valor de pedidos entregues
- Persistência no navegador via `localStorage`
- Interface responsiva, sem dependências de frameworks

## Tecnologias
HTML5, CSS3 e JavaScript puro.

## Como testar
Abra o arquivo `index.html` no navegador. Os dados iniciais são **fictícios**. Para restaurá-los, acesse **Relatórios → Restaurar exemplos**.

## Limitações e próximos passos
Esta é uma aplicação **front-end demonstrativa**, sem autenticação, servidor ou banco de dados. Os registros ficam somente no navegador e não devem ser usados para dados reais de clientes. Como evolução, o projeto poderá receber API, SQL, autenticação, validação no servidor e testes automatizados.

## Autoria
**Bruna Martins** · [GitHub](https://github.com/brumartinss07) · [LinkedIn](https://www.linkedin.com/in/bruna-martinss7)
