Exercício 4 Filtrar Produtos Acima de um Preço

Crie uma função chamada filtrarAcimaPreco que receba um array de objetos representando produtos, onde cada produto tem uma propriedade preco. A função deve retornar um novo array contendo apenas os produtos com preço maior que um valor especificado.

Entrada:

const produtos = [
{ nome: "Laptop", preco: 1000 },
{ nome: "Tablet", preco: 400 },
{ nome: "Smartphone", preco: 1500 }
];

Exemplo de chamada da função:

filtrarAcimaPreco(produtos, 600)

Saída

[
{ nome: "Laptop", preco: 1000 },
{ nome: "Smartphone", preco: 1500 }
]
