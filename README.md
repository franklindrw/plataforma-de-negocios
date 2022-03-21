<br />
<h1 align="center"> Plataforma de Negócios B3</h1>
<h4 align="center">Aplicação Web para armazenar movimentações de ações na B3, feita para estudo Typescript com base das aulas da Alura.</h4>
<br />

<div id="statusProject" align="center">
<img src="https://img.shields.io/github/license/franklindrw/plataforma-de-negocios.svg?style=for-the-badge" />
<img src="https://img.shields.io/github/stars/franklindrw/plataforma-de-negocios.svg?style=for-the-badge" />
<img src="https://img.shields.io/github/forks/franklindrw/plataforma-de-negocios.svg?style=for-the-badge" />
<img src="https://img.shields.io/github/issues/franklindrw/plataforma-de-negocios.svg?style=for-the-badge" />
<img src="http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=green&style=for-the-badge"/>
</div>

<br /><br />

## Índice
* [Sobre o Projeto](#-sobre-o-projeto)
* [Validação de Dados](#validação-de-dados)
* [Inclusão e Listagem de Dados](#inclusão-e-listagem-de-dados)
* [Importação de Dados da API](#importação-de-dados-da-api)
* [Console Log](#console-log)
* [Linguagens Usadas](#-construindo-com)
* [Instalação](#-instalação)
* [Como Usar](#%EF%B8%8F-como-usar)
* [Autor](#-autor)
* [Licença](#-licença)

<br /><br />

## 🔎 Sobre o Projeto

Esta aplicação foi criada para colocar em prática os conhecimentos adquiridos na formação Typescript da Alura em um projeto Front-end Web. O objetivo do projeto foi criar uma interface de histórico de negociação, onde o usuário pode enviar as informações para uma web service.

Com Typescript é possível ter uma experiência mais fluida ao lidar com arquitetura MVC e Orientações a objetos, e como é baseado em JavaScript é possivel combinar com diferentes frameworks e deixar que seja copilado para várias versões diferentes do ECMAScript.

<br /><br />

<h3>Validação de Dados</h3>

É validado para que o usuário não consiga fazer negociações em finais de semana, e usando getDay() para verificar se é maior que Domingo(0) e menor que sábado(6)
<br />
<div align="center">
<img height="600px" src="https://user-images.githubusercontent.com/81038899/159193148-e277acdb-47bd-4383-8601-1d65281f8772.gif" />
</div>

<br />

<h3>Inclusão e Listagem de Dados</h3>
Para o preenchimento dos dados foi usado o preventDefault para não recarregar a página ao enviar o formulário, e ao clicar em incluir é chamado o método que recebe os dados do formulário e insere em uma lista, e em seguida é atualizado o método de View que imprime na tabela todos os dados da lista.
<br /><br />
<div align="center">
<img height="600px" src="https://user-images.githubusercontent.com/81038899/159195423-999c4f4c-f48f-4ec5-bc8d-f85be5954dc2.gif" />
</div>

<br />

<h3>Importação de Dados da API</h3>
Para o tratamento dos dados da API foi usado Fetch para receber os dados em JSON para retornar na promisse os dados e, ao usar o map, ele insere cada objeto na lista usando o método Negociação.
<br /><br />
<div align="center">
<img height="600px" src="https://user-images.githubusercontent.com/81038899/159196360-eefb7922-7065-41a5-bcd4-c1c2c1e78426.gif" />
</div>

<br /><br />
<h3>Console Log</h3>
Também foi usado Decorators para validar a performance da aplicação imprimindo o tempo de execução no console log, assim é possível avaliar e velocidade e esforço do servidor ao inserir e imprimir dados. E foi feito um método de impressão dos dados para imprimir de forma mais legível no console log sempre que o usuário insere os dados.
<br /><br />
<div align="center">
<img height="600px" src="https://user-images.githubusercontent.com/81038899/159197105-8278850d-e3fa-4ecc-ba6e-8059028ad4c2.png" />
</div>


<br /><br />

### 🔨 Construindo com
<div id="statusProject" align="left">
 <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
 <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
 <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
</div>

<br /><br />

## 📥 Instalação

### Instalar a aplicação Web

 1. Clone o repositório

 2. Navegue até a pasta clonada

 3. Abra o painel de comandos dentro da pasta e rode a instalação de dependencias do Node com npm
 ```
 npm install
 ```
 4. Após a instalação rode o comando abaixo para iniciar o compilador de Typescript e o Node server. Ao iniciar irá abrir a página no navegador padrão da sua máquina
 ```
 npm run start
 ```
 
 ### Instalar a API
 1. com outro CMD navegue até a pasta servidor-API dentro da pasta clonada
 
 2. Abra o painel de comandos dentro da pasta e rode a instalação de dependencias do Node com npm
 ```
 npm install
 ```
 
 3. Após a instalação rode o comando abaixo para iniciar o servidor da API
 ```
 npm start
 ```
 
 
## ▶️ Como Usar

1. Preencha os dados do formulário

2. Clique em Incluir

3. Para trazer os dados da API clique em importar os dados
 

### 🖊 Autor

<a href="https://github.com/franklindrw">
<img style="border-radius: 50%; width: 100px" src="https://github.com/franklindrw.png" alt="Foto do Autor"/>
<br />
<sub><b>Franklin Campos</b></sub>
</a>
</br>
<p>Feito por <strong>Franklin Campos</strong> 👋🏻 </br>
Entre em contato!</p>

<div>
<a href="https://www.linkedin.com/in/franklindrw" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
<a href="mailto:franklindrw@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
<a href="https://www.instagram.com/franklindrw" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
</div>

<br /><br />

### 📋 Licença

<p> Copyright 2022 © Franklin Campos </br>
This project is MIT licensed.</p>
