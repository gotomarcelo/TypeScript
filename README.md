<h1 align='center'>TypeScript</h1>
Here goes all my studies on TypeScript based o Alura's course.
<ul>
<li><a href='https://cursos.alura.com.br/course/typescript-evoluindo-javascript' target='_blank'>TypeScript parte 1: evoluindo seu JavaScript</a>.</li>
<li><a href='https://cursos.alura.com.br/course/typescript-avancando-linguagem' target='_blank'>TypeScript parte 2: avançando na linguagem</a>.</li>
</ul>

<h1>Uma nova linguagem?</h1>
O TypeScript é uma linguagem de programação que é um superset do JavaScript, o que significa que o TS (TypeScript) é uma forma de codificar o JS. Sabendo disso, o TS não é lido no navegador, mas traduzido para JS.

O TypeScript é uma forma de codificar JavaScript de forma mais presa, menos suscetível a erros, tanto que ela é uma linguagem fortemente tipada.

<br/>
<h1>Por que usar?</h1>
Quando estamos escrevendo em Programação Orientada A Objeto em JS, temos algumas falhas de objetos, na qual podemos facilmente acessar um método em um objeto pai, ou filho, sem restrições, podemos até adicionar métodos. Isso pode ser problemático em uma aplicação na qual o programador não pode de forma alguma adicionar ou deletar um método. Claro que exitem formas de bloquear isso em JS, como colocar # (cerquilha / hastag) na frente dos métodos, mas de qualquer maneira podemos alterar outros valores. E outra, ao fazermos um erro, o JavaScript só vai encontrar esse problema em runtime (quando estiver rodando), no qual o TypeScript nos informa o erro ou qualquer problema quando estamos escrevendo um código, legal né?!

<br/>
<h1>Como instalar?</h1>
Dentro da pasta onde está o seu projeto, no terminal digite:

```console
npm install typescript --save-dev
```
> O `save-dev` não leva para produção.
 
Ao fazer o de cima, será adicionado um script no arquivo package.json

> Vale mencionar que o node.js é obrigatório, pois é instalado através do npm.

Podemos passar configurações especiais para o compilador através do arquivo `tsconfig.json`