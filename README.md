# QA Automation Challenge

##JSONPlaceholder API

O JsonPlaceholder é uma falsa API REST online para teste e prototipagem: https://jsonplaceholder.typicode.com/

### 🚀 Automação

Desenvolvimento de scripts de automação para validar as apis de cadastro e listagem de Posts.

### 📋 Pré-requisitos

* Postman
* Node.js
* Newman 

## 🔧 Executando os testes
 
#### Execução por linha de comando

Baixar o projeto e abrir o cmd no diretório "PostmanCollections".

##### Configuração

Para executar os casos de testes precisaremos realizar as instalações dos plugins abaixo:

```
npm install -g newman
npm install -g newman-reporter-html
npm install -g newman-reporter-htmlextra
```
Execução gerando relatório simples

```
newman run QA_Automation_Challenge.json -e QA_Automation_Challenge.postman_environment.json -r html
```
Execução gerando relatório detalhado
```
newman run QA_Automation_Challenge.json -e QA_Automation_Challenge.postman_environment.json -r htmlextra --reporter-htmlextra-title "QA Automation Challenge"
```

#### Execução no Postman

* Importar as collection "QA_Automation_Challenge.json" e "QA_Automation_Challenge.postman_environment.json" no Postman.
* Selecionar a coleção.
* Clicar no botão Run. 

### 🔩 Reports das execuções

Os reports são gerados no diretório "PostmanCollections\newman" do projeto. 
