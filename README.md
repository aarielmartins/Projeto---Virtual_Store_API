# 🛍️ Trama — Virtual Store API

API desenvolvida para fornecer os dados utilizados no e-commerce **Trama**, uma loja virtual fictícia de produtos de moda e decoração.

A API funciona como backend do projeto **Virtual Store**, disponibilizando os produtos das coleções **Vestir** e **Habitar** através de endpoints REST consumidos pela aplicação React.

## ✨ Funcionalidades

- Listagem de produtos
- Consulta de produtos por ID
- Filtragem de produtos por coleção
- Armazenamento dos dados dos produtos
- Disponibilização dos dados através de API REST
- Integração com o Front-End da aplicação Trama
- Deploy da API para acesso remoto

## 🚀 Tecnologias utilizadas

- Node.js
- JSON Server
- JavaScript
- JSON
- REST API
- Git
- GitHub
- Render

## 🔗 Endpoints

### Listar todos os produtos

```http
GET /products
```

### Buscar produto por ID

```http
GET /products/:id
```

Exemplo:

```http
GET /products/1
```

### Filtrar produtos por coleção

```http
GET /products?colecao=habitar
```

ou:

```http
GET /products?colecao=vestir
```

## 📦 Estrutura dos produtos

Os produtos disponibilizados pela API possuem informações como:

```json
{
  "id": 1,
  "titulo": "Nome do produto",
  "categoria": "Categoria",
  "colecao": "habitar",
  "imagem": "URL da imagem",
  "valor": 2999.9,
  "valorComDesconto": 2499.9,
  "dimensoes": {
    "altura": "00 cm",
    "largura": "00 cm",
    "profundidade": "00 cm"
  },
  "descricao": "Descrição do produto",
  "composicao": "Composição do produto",
  "feitoAMao": true,
  "origem": "Brasil",
  "entrega": "Informações sobre entrega"
}
```

## 📦 Como rodar o projeto

```bash
# Clone o repositório
git clone https://github.com/aarielmartins/Projeto---Virtual_Store_API.git

# Acesse a pasta
cd Projeto---Virtual_Store_API

# Instale as dependências
npm install

# Inicie a API
npm start
```

## 🌐 Integração com o Front-End

Esta API foi desenvolvida para ser consumida pelo projeto **Trama — Virtual Store**, desenvolvido com React e TypeScript.

Repositório do Front-End:

```text
https://github.com/aarielmartins/Projeto---Virtual_Store
```

A aplicação utiliza **RTK Query** para realizar as requisições e consumir os dados disponibilizados pela API.

## 💡 Sobre o projeto

O objetivo desta API é simular o backend de uma aplicação de e-commerce, permitindo trabalhar conceitos como:

- APIs REST
- Requisições HTTP
- Estruturação de dados em JSON
- Integração entre Front-End e Back-End
- Filtros através de query parameters
- Deploy de APIs
- Consumo de dados externos com React

## 👩‍💻 Autora

Desenvolvido por **Ariel Martins** como parte dos estudos em desenvolvimento Full Stack Python, complementando o projeto Front-End **Trama — Virtual Store**.
