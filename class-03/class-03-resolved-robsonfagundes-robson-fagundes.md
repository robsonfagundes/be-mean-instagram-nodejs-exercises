# Node.js - Aula 03 - Exercício
**user:** [robsonfagundes](https://robsonfagundes.github.io)

**autor:** Robson Fagundes

## 1. Por que quando requisitamos ao nosso servidor de *Query String*, **com o Chrome**, ele executa 2 requisições, sendo a última "*vazia*"?


## 2. Qual a DIFERENÇA entre o GET e o POST?

- **GET:** Solicita algum recurso como um arquivo ou um script CGI (qualquer dado que estiver identificado pelo URI) por meio do protocolo HTTP. 
#####Exemplo: 
```
GET /index.html HTTP/1.1
Host: www.exemplo.com

```
- POST: Envia dados para serem processados (por exemplo, dados de um formulário HTML) para o recurso especificado. Os dados são incluídos no corpo do comando. Sua utilização em uma requisição ocorre quando é necessário enviar dados ao servidor para serem processados, geralmente por um programa script identificado no Request-URI. Uma requisição por meio desse método sempre requer que as informações submetidas sejam incluídas no corpo da mensagem e formatadas como uma **query string**, além de conter cabeçalhos adicionais especificando seu tamanho (Content-Length) e seu formato (Content-Type). Por isso, esse método oferece uma maior segurança em relação aos dados transferidos, ao contrário do método GET que os dados são anexados a URL, ficando visíveis ao usuário.
#####Exemplo: 
```
 POST /index.html HTTP/1.0
 Accept: text/html
 If-modified-since: Mon, 21 Dez 2015 15:37:31 GMT
 Content-Type: application/x-www-form-urlencoded
 Content-Length: 41
 
 Nome=NomePessoa&Idade=99&Curso=be-mean-instagram

```

## 3. Crie um Pokemon na nossa API com seu nome, depois modifique seu nome pelo seu User do Github.
```js

```

```js

```

## 4. **Depois faça o DELETE**, criando o script para tal, colocando aqui a resposta.
```js

```

## 5. Escolha uma **API externa** e crie um script para fazer um GET nela **mostrando o resultado com HTML**.
```html

```
