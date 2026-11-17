# 🚀 API Testing — Postman & Newman

**Projeto de estudos em testes de API utilizando Postman, Collections e Newman.**

## 📌 Sobre o projeto

Este repositório reúne práticas de testes de API utilizando Postman, com uma coleção de requisições voltada à API ServeRest.

O projeto tem como objetivo desenvolver conhecimentos em validação de serviços, organização de requisições HTTP e execução de coleções de testes.

Também contempla o Newman, ferramenta utilizada para executar coleções do Postman por linha de comando, permitindo explorar possibilidades de integração dos testes em fluxos automatizados.

## 🎯 Objetivos

- Compreender os fundamentos de API Testing.
- Criar e organizar Collections no Postman.
- Executar requisições HTTP.
- Desenvolver práticas de validação de APIs REST.
- Explorar a execução de Collections utilizando Newman.
- Desenvolver conhecimentos aplicáveis à automação de testes de API.

## 🛠️ Tecnologias e ferramentas

| Tecnologia | Aplicação |
|---|---|
| Postman | Criação e execução de requisições HTTP |
| Newman | Execução de Collections via linha de comando |
| REST API | Contexto de testes de serviços |
| JSON | Formato utilizado para armazenar a Collection |

## 📂 Estrutura do repositório

```text
test-postman/
│
├── newman/
│
└── TesteServeRest.postman_collection.json
```

### Arquivos e diretórios

- **newman/**: diretório relacionado ao Newman e aos arquivos associados à execução das coleções.
- **TesteServeRest.postman_collection.json**: coleção de requisições do Postman utilizada no projeto.

## ⚙️ Executando os testes

### 1. Instalar o Newman

```bash
npm install -g newman
```

### 2. Executar a Collection

Na raiz do projeto, execute:

```bash
newman run TesteServeRest.postman_collection.json
```

Caso a coleção utilize variáveis de ambiente externas, será necessário fornecer o arquivo correspondente na execução.

## 🔍 Conhecimentos desenvolvidos

- API Testing
- REST API
- HTTP Requests
- Postman Collections
- JSON
- Newman CLI
- API Test Automation

## 🚀 Objetivo de aprendizado

Este projeto faz parte da minha jornada de desenvolvimento em Quality Assurance, ampliando meus conhecimentos de testes funcionais para o contexto de APIs.

A prática com Postman e Newman representa uma etapa importante na construção de competências em automação de testes, preparação para pipelines CI/CD e desenvolvimento de estratégias de validação de serviços.

---

**Autor:** Lucas Ferreira de Lima

**Área:** Quality Assurance | API Testing | Postman | Newman

*Test the endpoints. Validate the responses. Assure the quality.*
