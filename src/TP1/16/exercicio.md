Exercício 16 Criar uma Lista de Produtos com Cartão de Produto

Crie um novo projeto React utilizando Vite. Dentro do projeto, crie um componente funcional chamado ListaProdutos. Este componente deve exibir uma lista de produtos usando um array estático e o método map para gerar um cartão de produto para cada item.

Utilize o seguinte array estático para os produtos:

const produtos = [
{
nome: "Tênis de Corrida",
descricao: "Tênis confortável para corridas diárias.",
preco: "R$ 299,90",
imagem: "https://via.placeholder.com/150"
},
{
nome: "Camisa de Ciclismo",
descricao: "Camisa respirável para ciclistas.",
preco: "R$ 129,90",
imagem: "https://via.placeholder.com/150"
},
{
nome: "Boné Esportivo",
descricao: "Boné ajustável para proteção solar.",
preco: "R$ 59,90",
imagem: "https://via.placeholder.com/150"
}
];
O componente ListaProdutos deve utilizar o método map para renderizar um componente CartaoProduto para cada item no array. O componente CartaoProduto deve incluir:

Imagem do Produto
Nome do Produto
Descrição
Preço
Crie um arquivo CSS chamado CartaoProduto.css para estilizar o cartão de produto, garantindo que ele tenha uma aparência profissional e organizada.

Assim que terminar, salve todos os links para os exercícios realizados em PDF nomeando o arquivo conforme a regra “nome_sobrenome_DR1_TP1.PDF” e poste como resposta a este TP.
