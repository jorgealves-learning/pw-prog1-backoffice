# pw-prog1-backoffice
ETICEats Backoffice

## Requirements
- each Group element Must Fork this repo
- One PR per Group element
- Each PR MUST contains at least 15 commits
- Each commit MUST follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
- Each Group element MUST add proper documentation.


## Descrição
Este script implementa um sistema simples de gestão de utilizadores e pedidos. Permite criar novos utilizadores com email e password, realizando validações para garantir que os dados são inseridos corretamente.

## Funcionalidades principais:
Criação de novos utilizadores: Permite adicionar um novo utilizador, validando se o email já existe e se o formato do email e a password cumprem os requisitos mínimos.
Listagem de pedidos: Para cada utilizador, é possível listar os recibos de pagamento associados ao seu email, incluindo informações sobre o preço final, data do pagamento e o restaurante.
Validações incluídas:
Verificação se o email já está registado.
Validação básica do formato do email.
Verificação de requisitos de segurança para a password (mínimo de caracteres, complexidade, etc.).
Este sistema integra-se com um módulo de Billing (faturação), onde os pedidos são armazenados e podem ser acedidos com base no email do utilizador.
Este ficheiro faz parte do módulo backoffice.


