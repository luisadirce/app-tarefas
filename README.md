# To do tasks

<p >Esse é o primeiro desafio feito no curso Ignite da Rocketseat da trilha de ReactJS, com fins educacionais.</p>

<!--ts-->

- [Sobre](#sobre)
- [Como usar](#como-usar)
  - [Pre Requisitos](#pre-requisitos)
  - [Instalações](#instalacoes)
- [Testes](#testes)
- [Tecnologias](#tecnologias)
<!--te-->

<h3 id="sobre">Sobre</h3>
É um projeto simples, no qual é possível adicionar, remover e marcar tarefas como concluídas.

Esse projeto foi desenvolvido no Iginite da Rocketseat na trilha de ReactJS. É um curso bem completo com toda a parte teórica e prática.

<h3 id="pre-requisitos">Pré-requisitos</h3>

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:

- [Node.js](https://nodejs.org/en/) e
- [yarn](https://classic.yarnpkg.com/en/docs/install/#debian-stable).

Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

<h3 id="instalacoes">Instalações</h3>

```bash
#Instalar dependências:
$ yarn

#Executar projeto:
$ yarn dev
```

<h3 id="testes">Testes</h3>

O projeto deve ser capaz de passar por quatro testes:

- **should be able to add a task**

Para que esse teste passe, você deve permitir que task seja criada e com isso, exibida em tela. As taks criadas devem conter os atributos seguindo o padrão da interface, que é:

```tsx
interface Task {
  id: number;
  title: string;
  isComplete: boolean;
}
```

- **should not be able to add a task with an empty title**

Para que esse teste passe, antes de criar uma nova task, você deve validar se algo foi digitado no input e não permitir a criação da task caso o valor seja vazio, caso o valor digitado seja vazio, você deve impedir a criação da task.

- **should be able to remove a task**

Para que esse teste passe, você deve permitir que ao clicar no botão com ícone de uma lixeira, a task relacionada a esse botão seja removida do estado da aplicação, consequentemente sendo removida da tela.

- **should be able to check a task**

Para que esse teste passe, você deve permitir que ao clicar no checkbox ao lado da task, ela seja marcada como concluída ou não concluída de acordo com seu estado atual, alterando seu valor de `isComplete` de `false` para `true` ou ao contrário, de `true` para `false`.

```bash
#Executar testes:
$ yarn test
```

<h3 id="tecnologias">🛠 Tecnologias </h3>

As seguintes ferramentas foram usadas na construção do projeto:

- [Node.js](https://nodejs.org/en/)
- [React](https://pt-br.reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
