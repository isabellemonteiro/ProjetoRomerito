# ProjetoRomerito
Tema: Cafeteria - Grão e Ofício

 
 Componentes simples desenvolvidos:
- Botões 
- Badges e etiquetas 
- Campos de formulário 
- Ícones sociais 
- Títulos de seção
- Links de navegação
- Imagens
- Textos e parágrafos

Componentes compostos desenvolvidos:

- Navbar:logo, links de navegação e botão de reserva.
- Hero:título, descrição e botão de acesso ao cardápio.
- Card de produto: imagem, badge, título, descrição, preço e botão.
- Seção Sobre: imagem e textos sobre a cafeteria.
- Seção de Cardápio:conjunto de cards de produtos.
- Formulário de reserva: campos para nome, data, horário e quantidade de pessoas.
- Rodapé: informações da cafeteria e ícones de redes sociais.

Onde foi utilizado Flexbox:
O Flexbox foi utilizado na barra de navegação, nos links da navbar, nos grupos do formulário, no rodapé e na área de preço e botão dos cards de produtos. 

Onde foi utilizado CSS Grid:
O CSS Grid foi utilizado na seção Cardápio em Destaque, através da classe .cardapio-grid, para organizar os cards dos produtos em colunas que se adaptam ao tamanho da tela.

Onde foi utilizado Position:
O position foi utilizado na navbar, com position: sticky para manter ela no topo durante a rolagem, também foi utilizado nos cards dos produtos, com 'position: relative' e nos badges com 'position: absolute'  permitindo posicionar as etiquetas sobre as imagens.

Onde foi utilizado Float:
O float foi utilizado na imagem da seção "Sobre Nossa Casa", fazendo com que a imagem fique à esquerda e os textos sejam posicionados ao seu redor.

Estratégia utilizada para responsividade:
Foi utilizada uma Media Query com limite de 768px para adaptar o site a telas menores, onde nesse tamanho a navbar passa a ficar vertical, a imagem da seção "Sobre" deixa de utilizar float e ocupa toda a largura disponível e o card destacado perde o efeito de escala.
