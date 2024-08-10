Exercício 13 Criar um Componente de Galeria de Imagens

Crie um novo projeto React utilizando Vite. Dentro do projeto, crie um componente funcional chamado GaleriaImagens que exiba uma galeria de imagens utilizando um array estático de objetos. Cada objeto deve conter uma URL de imagem e uma legenda. Utilize o método map para iterar sobre o array e renderizar cada imagem junto com sua legenda.

Utilize o seguinte array estático de objetos para as imagens:

const imagens = [
{ url: 'https://via.placeholder.com/150', legenda: 'Imagem 1' },
{ url: 'https://via.placeholder.com/150', legenda: 'Imagem 2' },
{ url: 'https://via.placeholder.com/150', legenda: 'Imagem 3' }
];

No componente GaleriaImagens, renderize cada imagem dentro de um elemento <div> com uma classe CSS para estilizar a galeria, e inclua a legenda abaixo da imagem. Crie um arquivo CSS chamado GaleriaImagens.css e adicione estilos para centralizar as imagens e exibir as legendas de forma clara.

Após criar e estilizar o componente, importe-o e utilize-o no arquivo src/App.jsx. Verifique se a galeria de imagens é exibida corretamente e se as imagens estão centralizadas com suas legendas.
