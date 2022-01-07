# QA Automation Challenge

##JSONPlaceholder API

O JsonPlaceholder é uma falsa API REST online para teste e prototipagem: https://jsonplaceholder.typicode.com/

### 🚀 Automação

Desenvolvimento de scripts de automação para validar as apis de cadastro e listagem de Posts.

### 📋 Pré-requisitos

* Postman
* Node.js
* Newman (Para executar via linha de comando)

## 🔧 Executando os testes
 
#### Execução por linha de comando

##### Configuração

Com o Node.js instalado, abrir o cmd e executar o comando os comandos abaixo para configurar a execução e geração de relatório:

```
npm install -g newman
npm install -g newman-reporter-html
```
##### Execução do teste

```
newman run QA_Automation_Challenge.json -e QA_Automation_Challenge.postman_environment.json
```
##### Gerar relatório
```
newman run QA_Automation_Challenge.json -e QA_Automation_Challenge.postman_environment.json
```


#### Execução no Postman

* Importar as collection "QA_Automation_Challenge.json" e "QA_Automation_Challenge.postman_environment.json" no Postman.
* Selecionar a coleção.
* Clicar no botão Run. 

