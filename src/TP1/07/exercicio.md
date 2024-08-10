Exercício 7 Verificar Disponibilidade de Estoque

Desenvolva uma função chamada verificarEstoque que receba um array de objetos representando produtos, onde cada produto tem uma propriedade quantidadeEmEstoque. A função deve retornar um array contendo apenas os produtos que têm quantidade em estoque maior que zero.

Exemplo de uso:

Entrada:

const produtos = [

{ nome: "Laptop", quantidadeEmEstoque: 5 },
{ nome: "Tablet", quantidadeEmEstoque: 0 },
{ nome: "Smartphone", quantidadeEmEstoque: 3 }
];

Saída:

[

{ nome: "Laptop", quantidadeEmEstoque: 5 },
{ nome: "Smartphone", quantidadeEmEstoque: 3 }
]
