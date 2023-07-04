## Lojinha API Automação
**Esse software tem como propósito apenas à aplicação do que aprendi em um curso que implementa tecnologias para automatizar testes e validar a qualidade de um software.**

Repositório que contém algumas automações usando o API Rest em um software chamado Lojinha. Entenda abaixo as decisões tomadas para estruturar o projeto:

- **Tecnologias**

Java

JUnit

RestAssured

Maven


- **Testes Automatizados**
  Testes para validar as partições de equivalências relacionadas ao valor do produto na Lojinha que estão vinculados diretamente com a regra de negócios que diz que o valor do produto tem que estar entre R$ 0,01 e R$ 7.000,00.

**Observações**
1. O Before Each foi usado para capturar o token que será utilizado posteriormente em outras métodos do teste,
2. Foi usado a classe POJO para armazenar os dados que são enviados da API.
3. Dados iniciais são criados através da classe Data Factory que cria e controla o mesmo.
4. O projeto usou o JUnit 5, que possibilita o uso do DisplayName que descreve em português os testes. 
