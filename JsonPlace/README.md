# 🔌 Testes de API com Robot Framework

## 📌 Descrição

Projeto de automação de testes de API utilizando Robot Framework, com foco na validação de endpoints REST.

Os testes foram desenvolvidos consumindo a API pública JSONPlaceholder, simulando cenários reais de validação de requisições HTTP.

## 🌐 API utilizada

https://jsonplaceholder.typicode.com

## 🚀 Tecnologias utilizadas

* Robot Framework
* RequestsLibrary
* Python

## 🧪 Cenários automatizados

### ✅ Buscar usuário existente

* Requisição GET para um usuário válido
* Validação de status code 200

### ❌ Buscar usuário inexistente

* Requisição GET para um usuário inexistente
* Validação de status code 404

### 📝 Criar novo post

* Requisição POST enviando dados no corpo da requisição
* Validação de status code 201

## 📂 Estrutura do projeto

O projeto segue uma organização baseada em boas práticas:

* **resources/** → keywords e variáveis reutilizáveis
* **suites/** → cenários de teste
* **results/** → relatórios gerados após execução

## ▶️ Como executar o projeto

1. Instalar dependências:

```bash
pip install robotframework
pip install robotframework-requests
```

2. Executar os testes:

```bash
robot suites/
```

## 📊 Resultados

Após a execução, são gerados automaticamente:

* log.html
* report.html

Os arquivos ficam disponíveis na pasta **results/** com detalhes da execução dos testes.

## 🎯 Objetivo do projeto

Demonstrar conhecimentos em:

* Testes de API REST
* Métodos HTTP (GET e POST)
* Validação de status code
* Estruturação de testes automatizados
* Organização de projeto com Robot Framework

## 📌 Observações

Este projeto foi desenvolvido para fins educacionais, utilizando uma API pública para simulação de cenários reais de testes.

## 👨‍💻 Autor

Daniel Silveira Keide
📧 [ysilveira@yahoo.com.br](mailto:ysilveira@yahoo.com.br)
🔗 LinkedIn: https://www.linkedin.com/in/daniel-silveira-keide-32393611a
