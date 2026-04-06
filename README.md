# Banco API Tests

## 📌 Descrição
Este projeto contém testes automatizados para a API REST disponível em:
https://github.com/rodrigoelias97/banco-api

Os testes colaboram com o correto funcionamento dos endpoints da API, validando regras de negócio e respostas HTTP.

---

## 🎯 Objetivo
Automatizar testes de integração da API REST utilizando boas práticas, garantindo:
- Confiabilidade da API
- Validação de contratos
- Facilidade de manutenção
- Geração de relatórios de execução

---

## 🛠️ Stack utilizada
- Node.js
- JavaScript
- Mocha (Framework de testes)
- Chai (Assertions)
- Supertest (Requisições HTTP)
- Mochawesome (Relatórios)

---

## 📁 Estrutura de diretórios

```
banco-api-tests/
│
├── test/               # Arquivos de teste
├── node_modules/      # Dependências
├── mochawesome-report/ # Relatórios gerados
├── package.json       # Configurações do projeto
├── .env               # Variáveis de ambiente (não versionado)
└── README.md
```

---

## ⚙️ Configuração do ambiente

Crie um arquivo `.env` na raiz do projeto com o seguinte formato:

```
BASE_URL=http://localhost:3000
```

> Ajuste a URL conforme o ambiente onde a API estiver rodando.

---

## ▶️ Como executar o projeto

### 1. Instalar dependências
```
npm install
```

### 2. Executar os testes
```
npm test
```

---

## 📊 Relatórios

Após a execução dos testes, um relatório HTML será gerado automaticamente utilizando o Mochawesome:

```
/mochawesome-report/index.html
```

Abra este arquivo no navegador para visualizar os resultados.

---

## 📚 Documentação das dependências

- Mocha: https://mochajs.org/
- Chai: https://www.chaijs.com/
- Supertest: https://github.com/visionmedia/supertest
- Mochawesome: https://github.com/adamgruber/mochawesome

---

## 👨‍💻 Autor
Rodrigo Elias
