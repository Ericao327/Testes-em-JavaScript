# Variáveis Básicas em JavaScript

Neste módulo do curso de Node.js da Alura, vamos explorar as variáveis básicas em JavaScript. As variáveis são fundamentais na programação, pois são usadas para armazenar dados que podem ser utilizados e manipulados durante a execução de um programa.

## Tipos de Variáveis
JavaScript possui três formas principais de declarar variáveis:

1. **var**: É a forma mais antiga e tem escopo de função. Usar `var` não é recomendado nas versões mais recentes do JavaScript.

   ```javascript
   var nome = 'João';
   ```

2. **let**: Introduzida no ES6, `let` tem escopo de bloco, o que significa que uma variável declarada com `let` só é acessível dentro do bloco onde foi definida.

   ```javascript
   let idade = 25;
   ```

3. **const**: Também introduzida no ES6, `const` é usada para declarar variáveis que não podem ser reatribuídas. Seu escopo também é de bloco.

   ```javascript
   const pi = 3.14;
   ```

## Dicas de Uso
- Sempre prefira `let` e `const` a `var` para uma melhor prática de programação.
- Use `const` para valores que não precisam ser alterados, e `let` para valores que poderão mudar.

## Conclusão
Compreender as variáveis é um passo importante para quem está começando a programar em JavaScript. Elas formam a base para o desenvolvimento de aplicações mais complexas no ecossistema Node.js.
