OldFlix – Aplicação de Busca de Filmes via API OMDb
Português (PT-BR)

OldFlix é um projeto simples e organizado desenvolvido em Java, cujo objetivo é realizar buscas de filmes utilizando a API pública OMDb.
O programa consulta títulos fornecidos pelo usuário, converte os dados retornados para objetos Java, exibe as informações formatadas e salva todas as buscas realizadas em um arquivo filmes.json.

Funcionalidades

Busca de filmes pelo título.

Consumo da API OMDb utilizando HttpClient.

Conversão automática do JSON usando Gson.

Tratamento de erros e exceções personalizadas.

Registro das buscas em um arquivo JSON.

Arquitetura organizada em:

controllers

services

models

utilitários

Tecnologias Utilizadas

Java 17+

Biblioteca Gson (Google)

API OMDb

IntelliJ IDEA

Estrutura do Projeto
src/
 ├── controllers/
 │    └── BuscaController.java
 ├── services/
 │    └── OmdbService.java
 ├── models/
 │    ├── Titulo.java
 │    ├── TituloOmdb.java
 │    └── ErroDeConversaoDeAnoException.java
 ├── utils/
 │    └── JsonWriter.java
 └── Main.java

Como Executar

Instale o Java 17 ou superior.

Baixe ou clone este repositório.

Instale a biblioteca Gson (via Maven, Gradle ou .jar).

Compile e execute o projeto pelo IntelliJ ou terminal.

Digite nomes de filmes quando solicitado.

O arquivo filmes.json será criado automaticamente com todos os títulos buscados.

OldFlix – Movie Search Application using OMDb API
English (EN)

OldFlix is a simple and well-structured Java project designed to search for movies using the OMDb public API.
The program retrieves movie information based on user input, converts the returned JSON into Java objects, displays formatted data, and stores all requested titles in a filmes.json file.

Features

Search movies by title.

HTTP requests using HttpClient.

JSON parsing through Gson.

Custom error handling.

Automatic generation of a JSON file containing all searches.

Clean architecture with:

controllers

services

models

utilities

Technologies Used

Java 17+

Gson Library

OMDb API

IntelliJ IDEA

Project Structure
src/
 ├── controllers/
 │    └── BuscaController.java
 ├── services/
 │    └── OmdbService.java
 ├── models/
 │    ├── Titulo.java
 │    ├── TituloOmdb.java
 │    └── ErroDeConversaoDeAnoException.java
 ├── utils/
 │    └── JsonWriter.java
 └── Main.java

How to Run

Install Java 17 or newer.

Download or clone this repository.

Add the Gson library to the project (Maven, Gradle, or .jar).

Build and run the project using IntelliJ or the terminal.

Type movie titles when requested.

The filmes.json file will be automatically generated.
