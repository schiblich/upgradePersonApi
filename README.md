## AMDOCS - Projeto de SpringBoot - Dados Pessoais.
---

Roberto Schiblich

Spring Data JPA na Prática - Digital Innovation One.


Objetivo do Projeto
--

Os principais conceitos de mapeamento objeto relacional (ORM) usando o Spring Data JPA. Para isso, uma API RESTful foi focada na modelagem de suas entidades, no domínio de uma academia de ginástica.

### Pré-requistos
Fundamentos do Spring Boot, Noções de SQL

### Apresentação do Projeto Base

Configuração do banco de dados (SGBD PostgreSQL)
Aplicando as annotations
Execução do fluxo back-end: Controller - Service - Repository
Validação - Hibernate Validator
Consultas Avançadas - Derived Query - Native Query
IDE´s & Tecnologias Utilizadas
IDE IntelliJ
Java 17
Maven
Spring Web

Spring Data JPA
PostgreSQL Driver
Hibernate Validator
Lombok
Postman
Anotações de Map

### Curva de Aprendizado


- uso dos Beans @
- Model e  Repository
- implementação get
- post/ put
- uso do Postman para subir o aplicativo


@Entity demonstra a classe anotada ou seja representa um tipo de entidade. @Table demonstra a tabela principal da entidade recem anotada. @Id demonstra o identificador de uma entidade que sempre deve ter um atributo assinalado. @GeneratedValue demonstra o valor do identificador de entidade que é gerado. @Column demonstra como o mapeamento entre um atributo de entidade básica e a coluna da tabela de banco de dados. @JoinColumn demonstra a coluna FOREIGN KEY.demonstra a que a entidade se relaciona. @OneToMany demonstra o relacionamento de banco de dados de um-para-muitos. @OneToOne Usada para especificar um relacionamento de banco de dados um-para-um. @ManyToOne Usada para especificar um relacionamento de banco de dados muitos-para-um. cascade Realizar operações em cascata só faz sentido em relacionamentos Pai - Filho. mappedBy Indica qual é o lado inverso ou não dominante da relação.

O projeto foi passado de maneira empolgante e a curva de aprendizado foi bastante significante para o meu conhecimento. Espero ter a oportunidade de ter mais aprimoramento dentro deste método.
### git@github.com:schiblich/upgradePersonApi.git