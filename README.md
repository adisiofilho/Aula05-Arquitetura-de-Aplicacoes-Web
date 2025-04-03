# Aula05-Arquitetura-de-Aplicacoes-Web


📋 Projeto: Gerenciamento de Tarefas - Spring Boot MVC

🎯 Objetivo

Este projeto tem como objetivo desenvolver uma aplicação web para gerenciamento de tarefas, seguindo o padrão arquitetural MVC (Model-View-Controller). A aplicação permite criar, listar, atualizar e excluir tarefas, com persistência de dados utilizando os bancos H2, MariaDB e MongoDB.

🧱 Estrutura do Projeto

O sistema é dividido em camadas bem definidas:

Model: Representa as entidades e atributos da aplicação.

Repository: Responsável pela comunicação com os bancos de dados.

Service: Contém a lógica de negócio.

Controller: Expõe os endpoints REST para o cliente.

⚒️ Tecnologias Utilizadas

Java 17+

Spring Boot

Spring Web

Spring Data JPA

Spring Data MongoDB

Lombok

Validation (Jakarta)

H2 Database

MariaDB Driver

MongoDB

Maven

VS Code com Spring Boot Extension Pack

⚙️ Configuração do Ambiente

O ambiente é configurado com o VS Code, utilizando extensões para desenvolvimento com Java e Spring Boot. O projeto é criado via Spring Initializr e inclui todas as dependências necessárias.

A configuração do application.properties permite alternar entre H2, MariaDB e MongoDB, conforme a necessidade.

🔄 Funcionalidades Implementadas

Listar todas as tarefas

Criar uma nova tarefa

Atualizar tarefa existente

Excluir tarefa

Persistência em múltiplos bancos (relacional e NoSQL)

