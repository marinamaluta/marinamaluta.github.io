Aula 5: Box Model / Border-box / Position

Box model (Modelo de caixa) <br>
<br>
1- Default (padrão) = Content-Box (caixa-conteúdo) *Widht e height<br>
Content (conteúdo)<br>
Padding (espaçamento entre o conteúdo e a borda)<br>
Border (após o padding)<br>
Margin<br>
<br>
2- Border-box (caixa-borda) <br>
Soma do padding + content<br>
<br>
*DIV: O default é block (no ex. ele não fica ao lado um do outro)<br>
*UL / LI: Block<br>
*IMG: Inline (permite que outro elemento inline fique ao seu lado)<br>
<br>
<br>
Para saber qual o tipo do display deve-ser procurar na documentação.<br>
Para acrescentar uma img com o tamanho definido - placeholder.com<br>
<br>
3- Position (posicionamento da caixa na tela)<br>
<br>
3.1- Static (é o padrão - de acordo com a codificação do html)<br>
posição = igual ao da marcação<br>
<br>
3.2- Relative<br>
posição = igual ao static mas modificável (de acordo com o top, bottom, right, left) <br>
obs: mesmo alterando o valor, a área total se mantém, não é ocupada por outro elemento.<br>
ex:  position: relative;<br>
       top: 20px;<br>
<br>
3.3- Absolute<br>
posição = se posiciona com relação ao ancestral mais próximo - Diferente do static. Ocupa o espaço vazio após a modificação realizada.<br>
<br>
3.4- Fixed<br>
posição = se posiciona sempre relativamente ao viewport.<br>
