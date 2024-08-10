Exercício 9 Agrupar Produtos por Categoria

Desenvolva uma função chamada agruparPorCategoria que receba um array de objetos representando produtos, onde cada produto tem uma propriedade categoria e uma propriedade nome. A função deve retornar um objeto onde as chaves são as categorias e os valores são arrays contendo os nomes dos produtos pertencentes a cada categoria.

Exemplo de uso:

Entrada:

const produtos = [

{ nome: "Laptop", categoria: "Eletrônicos" },
{ nome: "Camisa", categoria: "Roupas" },
{ nome: "Smartphone", categoria: "Eletrônicos" },
{ nome: "Calça", categoria: "Roupas" },
{ nome: "Fone de Ouvido", categoria: "Eletrônicos" }
];

Saída:

{

"Eletrônicos": ["Laptop", "Smartphone", "Fone de Ouvido"],
"Roupas": ["Camisa", "Calça"]
}
