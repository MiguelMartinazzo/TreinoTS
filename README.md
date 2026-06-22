# Projeto TypeScript - Estudos Iniciais

Este projeto foi desenvolvido com o objetivo de praticar os principais conceitos iniciais da linguagem **TypeScript**, explorando tipagem estática, variáveis, arrays, objetos, classes e valores especiais como `null` e `undefined`.

O projeto também conta com um arquivo de configuração `tsconfig.json`, responsável por definir como o código TypeScript será compilado para JavaScript.

## Sobre o Projeto

A aplicação é um projeto simples de estudos, executado via terminal, que demonstra o uso de diferentes recursos fundamentais do TypeScript.

Entre os conteúdos praticados estão:

- Declaração de variáveis com tipos explícitos e implícitos;
- Uso dos tipos `string`, `number` e `boolean`;
- Operações com números;
- Concatenação de strings;
- Verificação de tipos com `typeof`;
- Criação e manipulação de arrays;
- Uso do método `forEach`;
- Criação de objetos com tipagem;
- Objetos aninhados;
- Uso de `null` e `undefined`;
- Criação de classes;
- Uso de construtores.

## Exemplo de Classe

O projeto conta com uma classe chamada `Cliente`, utilizada para representar um cliente com `id` e `nome`.

```ts
class Cliente {
    id: number;
    nome: string;

    constructor(_id: number, _nome: string) {
        this.id = _id;
        this.nome = _nome;
    }
}
