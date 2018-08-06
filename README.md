# Repositório: Workshop - Criando uma Web App RESTFUL API em MEAN (Angular 5/6) by Glaucia Lemos

<p align="center">
  <img src="https://i.imgsafe.org/86/861db1e830.jpeg"/>  
</p>

Repositório responsável pelo códigos desenvolvidos durante o workshop: **Criando uma Web App RESTFUL API em MEAN (Angular 5/6)**
O curso será feito de maneira online e as aulas serão gravadas e enviadas para os alunos(as).

- **VAGAS LIMITADAS**: 250 alunos(as)
- **LINK INSCRIÇÃO WORKSHOP**: [LINK](https://www.sympla.com.br/workshop-criando-uma-web-app-restful-api-em-mean__335756)
- **PREÇO**: R$ 50,00
- **APOSTILA**
- **AULAS GRAVADAS E ENVIADAS PARA OS PARTICIPANTES**
- **CERTIFICADO DE CONCLUSÃO**


## ⚡️Recursos Utilizados no Workshop:

- Visual Studio Code - [DOWNLOAD AQUI](https://code.visualstudio.com/)
- Node.JS - [DOWNLOAD AQUI](https://nodejs.org/en/) 
- Express.Js;
- MongoDb Community - [DOWNLOAD AQUI](https://www.mongodb.com/download-center?jmp=homepage#community)
- Angular 5/6;
- Typescript 2.x
- Deploy da Aplicação;
- Code Metrics; (análise de desenvolvimento do codigo)
- Json data (para retornar os dados)
- PostMan (testar a API criada) - [DOWNLOAD AQUI](https://www.getpostman.com/)

## :fire: Pré-Requisitos para realização do Workshop:

* **Ter noções de JavaScript:**
    - Desvendando a linguagem JavaScript (Rodrigo Branas): [AQUI](https://www.youtube.com/playlist?list=PLQCmSnNFVYnT1-oeDOSBnt164802rkegc)
    
* **Ter noções de Node.Js & MongoDb:**

    - Se possível realizar o workshop de Node.Js: [AQUI](https://www.sympla.com.br/criando-uma-app-rest-api-com-nodejs--mongodb__332860)
    - **(Caso não tenha feito o workshop)** Tutorial CRUD API RESTful com: Node + Express + MongoDB: [AQUI](https://www.udemy.com/tutorial-crud-api-restful-com-node-express-mongodb)
    
* **Ter noções de Typescript:**
    - Curso TypeScript: Básico à Intermediário: [AQUI](https://www.udemy.com/curso-typescript-para-desenvolvedores-c)


## :rocket: Testando a Aplicação no Postman: 

Caso queira testar as API's criadas no projeto, primeiro baixe o [Postman](https://chrome.google.com/webstore/detail/postman/fhbjgbiflinjbdggehcddcbncdddomop).
Depois de realizar o download do Postman, basta agora realizar os passos abaiaxo para 
poder testar cada API criada!

## 🔥 Executando Código Localmente:

Caso você deseja executar o projeto na sua máquina local, basta seguir os passos abaixo:

### Começando...

Para começar, você deve simplesmente clonar o repositório do projeto na sua máquina e instalar as dependências. 😝

### Pré-Requisitos de Instalação:

Antes de instalar as dependências no projeto, você precisa já ter instalado na sua máquina:

* **Node.Js**: Caso não tenha, basta realizar o download [Aqui](https://nodejs.org/en/)
* **MongoDb**: Caso também não tenha, basta realizar o download [Aqui](https://www.mongodb.com/download-center#community)
* **Typescript**: Caso também não tenha, basta abrir o prompt comando e dgitar o comando abaixo:

```

> npm install -g typescript

```

* **Angular**: Caso também não tenham instalado em suas máquinas, basta abrir o prompt de comando e digitar o comando abaixo:

```

> npm install -g @angular/cli

```


### Instalando as Dependências (via Windows):

Abre o cmd (caso esteja utilizando o Windows) e digite a path do seu projeto

```
cd "C:\Users\NomeDoComputador\Documents\..."
```

Depois, quando estiver na pasta do projeto, basta digitar no cmd a seguinte instrução: **(dentro do src)**

```
npm install
```

Ao digitar a instrução acima, automaticamente ele irá baixar todas as dependências listadas e definidas no arquivo package.json:

* `node_modules` - que contêm os packages do npm que precisará para o projeto.

### Instalação dos Programas via Linux:

Estarei disponibilizando os links onde explicam como baixar:

- Node.Js: [AQUI](https://nodejs.org/en/download/package-manager/)
- MongoDb: [AQUI](https://docs.mongodb.com/v3.0/administration/install-on-linux/)

## 💥 Padrão das Rotas Criadas: 

Procurando seguir o padrão e design das API's, segue abaixo as URI's das rotas a serem desenvolvidas:

obs.: api de exemplo através do site: https://jsonplaceholder.typicode.com


### Executando a Aplicação: 

Bom, agora na mesma tela do cmd, basta iniciar o server para o projeto ser executado localmente.

```
node server.js
```

Depois, você precisará abrir um outro terminal na sua máquina e iniciar o MongoDb. Basta digitar na tela do cmd o seguinte comando:

```
mongod
```

Caso o MongoDb esteja devidamente instalado em sua máquina, ele iniciará o serviço mostrando que a port 27017 foi iniciada.


Agora, abre a página da aplicação em `http://localhost:4000/v1`. E pronto a aplicação será executada de maneira local na sua máquina.        

**(documentação em desenvolvimento)**

