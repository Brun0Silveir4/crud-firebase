# Projeto Node.js CRUD com Firebase


Este projeto é uma aplicação **Node.js + Express** que realiza operações **CRUD (Create, Read, Update, Delete)** utilizando o **Firebase Firestore** como banco de dados. O sistema possui integração com **handlebars** para renderização de páginas, além de middlewares para parsing de requisições.


<br>

## ⚙️ Tecnologias Utilizadas

- Criar documentos no Firestore
- Listar documentos
- Editar e atualizar dados
- Deletar registros
- Interface com Handlebars (views simples)

<br>

## 🧩 Funcionalidades

- Node.js
- Express
- Firebase Admin SDK
- Handlebars (express-handlebars)
- Body-parser

<br>

## ⚙️ Pré-requisitos

- Placa ESP8266 (NodeMCU ou similar)
- Sensor DHT11
- Conta no [Firebase](https://firebase.google.com/)
- Arduino IDE com bibliotecas instaladas

<br>

## 🚀 Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/Brun0Silveir4/crud-firebase
cd crud-firebase
```

### 2. Instalar as dependências
```bash
npm install
```

### 3. Configure seu firebase
* Crie um projeto no [Firebase Console](https://console.firebase.google.com/)
* **Configurações do projeto** → **Contas de serviço** → clique em **Gerar nova chave privada**
* Salve o arquivo serviceAccountKey.json na raiz do projeto

### 4. Rode a aplicação
```bash
node app.js
```

<br>

## 🙋‍♂️ Autor

Desenvolvido por Bruno Silveira. Contato:  
• [LinkedIn](https://www.linkedin.com/in/bruno-silveira-dionisio/)  
• [GitHub](https://github.com/Brun0Silveir4)  
• bruno.silveira.dionisio@gmail.com