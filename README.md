<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/Matheus-Chaves/desafio-ignite-react-01.svg)](https://github.com/Matheus-Chaves/desafio-ignite-react-01)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/Matheus-Chaves/desafio-ignite-react-01.svg)](https://github.com/Matheus-Chaves/desafio-ignite-react-01/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center">
  to.do - Primeiro desafio das aulas de ReactJS do curso Ignite, da <a href="https://rocketseat.com.br/">Rocketseat</a>.
  <p align="center">
    <img  src="/.github/banner.png" alt="Project logo">
  </p>
</p>

## 📝 Sumário

- [Sobre](#sobre)
- [Iniciando o projeto](#getting_started)
- [Rodando os testes](#tests)
- [Utilização](#utilizacao)
- [Construído com](#construido_com)
- [Autores](#autores)

## 🧐 Sobre <a name = "sobre"></a>

O :sparkles: to.do :sparkles: é um aplicativo de 'To-do list'. Ele consiste em uma página única, onde é possível cadastrar, marcar, desmarcar e remover suas tarefas a serem feitas.

É um desafio inteiramente Front-End, que foi desenvolvido através das aulas de ReactJS do curso Ignite, da [Rocketseat](https://rocketseat.com.br/).

Passar no desafio significa que todos os testes foram concluídos corretamente.

## 🏁 Iniciando o projeto <a name = "getting_started"></a>

As instruções abaixo irão servir para que o projeto seja corretamente instalado e utilizado em seu dispositivo.

### Pré-requisitos

É necessário ter as tecnologias abaixo instaladas em sua máquina para poder seguir os próximos passos.

- Um navegador para que o sistema rode (Google Chrome, Firefox, Edge, etc.)
- [Node.js](https://nodejs.org/pt-br/)
- [Git](https://git-scm.com/download/windows)
- (Opcional) - Editor de código para edição e visualização do script. Recomendado: [Visual Studio Code](https://code.visualstudio.com/download)

### ⚙️ Instalação e uso

Siga o passo a passo abaixo para instalar corretamente o aplicativo e rodá-lo no seu próprio dispositivo.

Para seguir as instruções abaixo corretamente, abra o terminal do seu sistema operacional e execute os seguintes comandos:

```bash
# Clone o repositório deste projeto
$ git clone https://github.com/Matheus-Chaves/desafio-ignite-react-01.git

# Acesse a pasta do projeto pelo terminal
$ cd desafio-ignite-react-01

# Instale as dependências
$ yarn

# Execute a aplicação no modo de desenvolvimento
$ yarn dev

# O servidor rodará na porta:8080 - acesse <http://localhost:8080>
```

Após as instruções acima, o sistema já poderá ser utilizado.
Caso deseje encerrar/parar a aplicação, basta fechar o terminal ou encerrar o comando utilizando `Ctrl + C`.

## 🔧 Rodando os testes <a name = "tests"></a>

Para a conclusão do desafio, todos os testes precisaram passar.
Para rodá-los, basta executar o comando abaixo:

```bash
yarn test
```

### 🎯 Imagem ao passar nos testes

<img  src="/.github/tests.png" alt="Project logo">

#### 1 - Teste 'should be able to add a task'

Esse teste verifica se na aplicação é possível adicionar uma nova tarefa (novo item na To-do list).

#### 2 - Teste 'should not be able to add a task with a empty title'

Esse teste verifica se a aplicação impede que uma nova tarefa seja adicionada caso não tenha um título.

#### 3 - Teste 'should be able to remove a task'

Esse teste verifica se na aplicação é possível remover uma tarefa.

#### 4 - Teste 'should be able to check a task'

Esse teste verifica se na aplicação é possível marcar uma tarefa.

## 🎈 Utilização <a name="utilizacao"></a>

A utilização do sistema é simples e a interface é bem intuitiva.

### Cadastrando um novo item (tarefa) na lista

- Clique na caixa com o texto "Adicionar novo todo"
- Escreva o título da sua tarefa
- Clique no botão verde para inserir o item na lista

### Marcando um item da lista

- Localize a tarefa que você deseja marcar
- Clique na checkbox (à esquerda do título do item) e o item será marcado
- Clique novamente para desmarcar

### Removendo um item da lista

- Localize a tarefa que você deseja remover
- Clique no símbolo de lixeira 🗑️ e o item será removido

<div align="center">
  <img src="/.github/home.png" alt="Tela inicial"/>
  <img src="/.github/demo.png" alt="Demonstração do projeto"/>
</div>

## ⛏️ Construído com <a name = "construido_com"></a>

- [TypeScript](https://www.typescriptlang.org/) - Linguagem de programação
- [React](https://reactjs.org/) - Biblioteca para desenvolvimento Web
- [Sass](https://sass-lang.com/) - Linguagem de extensão do CSS
- [Jest](https://jestjs.io/pt-BR/) - Framework para testes

## ✍️ Autores <a name = "autores"></a>

- Desafio feito com :heart: by [@matheus-chaves](https://github.com/matheus-chaves)
- Projetado by [Rocketseat](https://rocketseat.com.br/) :purple_heart:
