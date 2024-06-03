# Replicação de Banco de dados no PostgreSQL.
<br>

***O que é Replicação de Banco dados ?*** 

A replicação de banco de dados cria cópias idênticas do seu banco de dados, em diversos lugares ou servidores. Isso garante que os seus dados fiquem sempre acessíveis, mesmo em caso de falhas.

***Como funciona a replicação de banco de dados ?***

Em geral, a replicação envolve o banco de dados primário que é a fonte principal dos dados e uma ou mais réplicas que mantêm cópias do banco de dados primário. Quando ocorre uma alteração no banco de dados primário, os dados são copiados para as réplicas. Isso faz com que os dados nas réplicas sejam consistentes com o banco de dados primário.

- Banco de dados principal permite **leitura** e **escrita** de dados, ou seja, é possivel **criar**, **inserir**, **alterar** e **consultar dados**.
- Replicações permite apenas **leitura de dados**.
## Instruções para criar uma replicação de banco de dados utilizando o docker-compose.

- Defina um network para fazer a comunicação entre o banco principal e as replicações.
- Defina os volumes das replicações e do banco primário.
- Adicione usuário e senha para ter acesso ao banco de dados postgreSQL.
- Use portas entre sua máquina host e servidor para cada banco de dados. — Por exemplo: `5432:5432`

 Execute o comando `docker compose up -d` para iniciar e executar os containers em segundo plano.

- Entre na sua IDE defina as portas para cada banco de dados e conecte-se.
- Crie as tabelas e insira os dados.

Pronto! ***Replicação de banco de dados utilizando o PostgreSQL feita com sucesso!.***