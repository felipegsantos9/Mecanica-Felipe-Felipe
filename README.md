# Documentação: Mecânica Felipe e Emanuelle

Descritivo:
O projeto pede o desenvolvimento de um software para informatizar uma oficina mecânica, substituindo o controle manual. O sistema deve organizar cadastros e agendamentos para evitar erros e perdas de reservas, proteger dados sensíveis (como o CPF) conforme a LGPD, exigir autenticação de usuários com tempo de expiração da sessão e incluir documentação técnica contendo os requisitos funcionais e o Diagrama Entidade-Relacionamento (DER).

## Front
- Cadastro
- Página de login
- Validação (JavaScript)
- Página principal
- Página agendamentos
- Gestão de informações 
- Página de registro

## Back end:
- Criação da API
- Pasta models com as classes de cada entidade
- Pasta data com o AppDbContext da API
- Pasta Controllers com o controller de cada classe
- link com o Banco de dados em SQL

## Banco de dados:
- Criação do banco de dados
- Tabelas de cada entidade (Veiculo, cliente, Serviços e etc...)
- Criptografia dos Dados dos clientes, como CPF e etc...
