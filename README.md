# Sistema de E-commerce

Bem-vindo ao Sistema de E-commerce! Este sistema é projetado utilizando a Arquitetura Limpa, garantindo uma separação clara das responsabilidades e facilitando a manutenção e evolução do projeto. Uma das funcionalidades principais é o cadastro de clientes, que inclui verificação por email utilizando códigos TOTP (Time-based One-Time Password) para validação da conta.


## Funcionalidades

- **Cadastro de Usuário :** Cadastro de Clientes com Verificação por Email: Permite que novos clientes criem contas no sistema. Após o cadastro, um código TOTP é enviado ao email do cliente para validação.
- **Gerenciamento de Produtos (feature em desenvolvimento) :** Adicione, edite ou remova produtos disponíveis para venda.
- **Carrinho de Compras (feature em desenvolvimento):** Funcionalidade para adicionar produtos ao carrinho e revisar antes de finalizar a compra.
- **Processamento de Pedidos (feature em desenvolvimento):** Finalize compras e acompanhe o status do pedido..

## Arquitetura
O sistema é desenvolvido utilizando a Arquitetura Limpa (Clean Architecture), garantindo:

- **Independência de frameworks :** As regras de negócios não dependem de frameworks específicos, facilitando futuras migrações ou mudanças.
- **Testabilidade :**  Separação clara das responsabilidades facilita a criação de testes unitários e de integração.
- **Independência da Interface de Usuário: :** O front-end pode ser substituído sem impactar a lógica de negócios.
- **Independência de Banco de Dados: :** A lógica de negócios não é acoplada ao banco de dados, permitindo mudanças sem grandes impactos.Nesse Projeto usei o SQLServer, porém pode ser alterado sem dificuldades e sem impactar a lógica do Sistema.

## Tecnologias Utilizadas

O sistema de E-commerce foi desenvolvido utilizando as seguintes tecnologias e ferramentas:
- **NET 8.0:** Framework utilizado para a construção da API, oferecendo suporte robusto para o desenvolvimento de aplicações web e serviços.
- **Entity Framework Core:** ORM (Object-Relational Mapper) utilizado para a interação com o banco de dados de forma simplificada e eficiente.
- **SQL Server :**


