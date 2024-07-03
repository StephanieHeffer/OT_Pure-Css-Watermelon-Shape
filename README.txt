https://www.youtube.com/watch?v=sdRlMGkY-4s&ab_channel=OnlineTutorials


CSS
.shape: Estiliza a fatia de melancia.

position: absolute;: Define a posição absoluta da fatia.
top: 50%; left: 50%;: Posiciona a fatia no centro vertical e horizontal da tela.
transform: translate(-50%, -50%) translateY(40px) rotate(25deg);: Ajusta a posição da fatia, transladando-a para cima e rotacionando-a.
width: 320px; height: 160px;: Define as dimensões da fatia.
background: #ff395d;: Define a cor de fundo da fatia como vermelho.
border-left: 20px solid #92e256; border-right: 20px solid #92e256; border-bottom: 20px solid #92e256;: Define as bordas esquerda, direita e inferior da fatia com uma cor verde (representando a casca da melancia).
border-bottom-left-radius: 200px; border-bottom-right-radius: 200px;: Arredonda os cantos inferiores da fatia, dando uma forma de meia lua.
.shape::before: Estiliza um pseudo-elemento antes da fatia.

content: '';: Adiciona um conteúdo vazio ao pseudo-elemento.
position: absolute;: Define a posição absoluta do pseudo-elemento.
top: 0; left: -20px;: Posiciona o pseudo-elemento acima e ligeiramente à esquerda da fatia.
width: calc(50% + 20px); height: calc(100% + 20px);: Define as dimensões do pseudo-elemento, um pouco maiores que as dimensões da fatia.
background: rgba(255,255,255,.3);: Define a cor de fundo do pseudo-elemento com um pouco de transparência, simulando o brilho na casca da melancia.
span: Estiliza as sementes dentro da fatia.

display: block; width: 10px; height: 10px;: Define as dimensões das sementes.
background: #262626;: Define a cor de fundo das sementes como preto (representando as sementes de melancia).
border-radius: 50%;: Define as sementes com formato de círculo.
display: inline-block;: Define as sementes como elementos de bloco em linha.
margin: 20px;: Adiciona margem ao redor das sementes.
position: relative; left: 8.6%;: Posiciona as sementes em relação ao contêiner pai.
span:nth-child(6), span:nth-child(12), span:nth-child(13): Estiliza sementes específicas.

Define as sementes 6, 12 e 13 como transparentes, presumivelmente para simular uma distribuição aleatória de sementes.
HTML
Dentro do <div class="shape">, os <span> representam as sementes da fatia de melancia.