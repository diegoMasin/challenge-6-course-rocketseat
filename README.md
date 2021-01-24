# Desafio 6 - Curso GoStack Rocketseat

```Seguindo o template proposto, criar as seguintes rotas:```
- POST /transactions: A rota deve receber title, value, type, e category dentro do corpo da requisição, sendo o type o tipo da transação, que deve ser income para entradas (depósitos) e outcome para saídas (retiradas). Ao cadastrar uma nova transação, ela deve ser armazenada dentro do seu banco de dados, possuindo os campos id, title, value, type, category_id, created_at, updated_at.
**Dica:** Para a categoria, você deve criar uma nova tabela, que terá os campos id, title, created_at, updated_at.
**Dica 2:** Antes de criar uma nova categoria, sempre verifique se já existe uma categoria com o mesmo título. Caso ela exista, use o id já existente no banco de dados.

##### Executar **_yarn test_** para avaliar as diretrizes passadas.
