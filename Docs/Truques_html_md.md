# Truques de HTML no Markdown 🤝

### Você sabia que é possível utilizar HTML no Markdown? 😃

Primeiro vamos começar com as definições:

- Uma **<span style="color: #55BFC2">linguagem de marcação</span>** é um conjunto de instruções ou códigos que são incorporados em um texto para definir sua estrutura, formatação ou apresentação. 

- **<span style="color: #55BFC2">Markdown</span>** é uma linguagem de marcação leve e de fácil leitura que foi projetada para ser simples de escrever e fácil de converter em HTML. 

- **<span style="color: #55BFC2"> HTML**</span> é a linguagem de marcação padrão para a criação de páginas web. Ele define a estrutura e o layout de uma página, utilizando uma variedade de elementos marcados com tags. Cada tag HTML representa um elemento específico, como cabeçalhos, parágrafos, imagens, links, entre outros. Os navegadores web interpretam essas tags para exibir o conteúdo de uma página de maneira formatada e compreensível para os usuários.

Tendo em vista esses conceitos, como podemos utilizar o HTML no nosso arquivo Markdown?

O uso de HTML em um documento Markdown permite que você adicione elementos e formatações mais avançadas que não estão diretamente disponíveis na sintaxe básica do Markdown. Aqui estão algumas coisas que você pode fazer usando HTML em um documento:

## Links com Alvo em Nova Janela

Usando HTML, você pode adicionar a propriedade <span style="color: #55BFC2">**target="_blank"**</span> para abrir links em uma nova janela ou aba.

    <a href="https://www.exemplo.com" target="_blank">Visitar Exemplo</a>

## Você pode incorporar vídeos do YouTube ou áudio usando a tag iframe.

    <iframe width="560" height="315" src="https://www.youtube.com/embed/seu-video" frameborder="0" allowfullscreen></iframe>

## Estilos com CSS Embutido:

Você pode usar estilos CSS embutidos usando a tag style.

    <style> 
        p {  
            color: blue; 
        } 
    </style>  
    
    Parágrafo com texto azul.

## Elementos de Tabela Avançados

Se você precisa de uma tabela mais complexa, pode usar HTML para criar elementos table.

    <table> 
        <thead>  
            <tr> 
                <th>Header 1</th> 
                <th>Header 2</th> 
            </tr> 
        </thead> 
        <tbody> 
            <tr> 
                <td>Row 1, Cell 1</td> 
                <td>Row 1, Cell 2</td> 
            </tr> 
            <tr> 
                <td>Row 2, Cell 1</td> 
                <td>Row 2, Cell 2</td> 
            </tr> 
        </tbody> 
    </table>   

## Alterar a cor do texto

Em Markdown puro, não há uma maneira direta de alterar a cor do texto, pois o Markdown foi projetado para ser uma linguagem de marcação leve e fácil de ler. No entanto, você pode usar HTML embutido para aplicar estilos ao texto, incluindo a cor do texto. Aqui está um exemplo:

    <span style="color: red;">Este texto será vermelho.</span>
