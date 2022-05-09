<h3 align="center">
Bootcamp Ignite Rocketseat - Finance API
</h3>

## :rocket: Sobre o desafio

A aplicação é um API para gestão de transações bancárias.

Requisitos, deve ser possível:
      - criar uma conta
      - buscar o extrato bancário do cliente
      - realizar um depósito
      - realizar um saque
      - buscar o extrato bancario do cliente por data
      - atualizar os dados da conta do cliente
      - deletar uma conta
      - retornar o balanço da conta

Regras de negócio, não deve ser possível:
      - cadastrar uma conta com CPF já existente
      - buscar extrato de uma conta não existente
      - fazer depósito em uma conta não existente
      - fazer daque em uma conta não existente
      - fazer saque quando o saldo for insuficiente
      - excluir uma conta não existente

## :wrench: Instalação e uso

```bash
# Abra um terminal e copie este repositório com o comando
git clone https://github.com/rodrigovellinho/Finance_API.git
# ou use a opção de download.

# Instale as dependências
yarn

# Rode a aplicação
yarn dev

# Acesse http://localhost:8080 no seu navagador
```

## 🔨 Tecnologias:

- **[Node.js](https://nodejs.org/en/)**
---

Feito por [Rodrigo Kloeckner](https://github.com/rodrigovellinho)
