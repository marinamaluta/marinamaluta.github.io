# Aula 4: CSS / Links úteis / Slide 06 (github front-xp)

## Ordenação de declaração

  ### Agrupamento por tipo e relevância:<br>
  
Posição - position<br>
Modelo de caixa e display<br>
Fonte e tipografia: font-family<br>
Cor: color<br>
Background e bordas - background / border<br>
<br>

### Exemplo de lista:<br>
* dl: Definion list 
* dt: Definição de termo
* dd:Descrição do termo<br>

&lt;dl&gt;<br>
  &lt;dt&gt;Coffee&lt;/dt&gt;<br>
  &lt;dd&gt;Black hot drink&lt;/dd&gt;<br>
  &lt;dt&gt;Milk&lt;/dt&gt;<br>
  &lt;dd&gt;White cold drink&lt;/dd&gt;<br>
&lt;/dl&gt;<br>
<br>

#### Curiosidades<br>
* Font-family é herdável. Colocando no pai - Busca: MDN<br>
* Height e width não são herdáveis (inherited)<br>
* Taquigrafia css - múltiplos valores: border, margin, padding
<br>
* Reset.css - Arquivo css a ser importado no projeto para eliminar o código padrão - MAYER<br>
* Normalize.css - Mantém alguns códigos padrões úteis.<br>
* Os dois códigos, de acordo com o escolhido, deve ser incorporado ao código no css.<br>


**Polyfills** - Importar um código que algum desenvolvedor fez como se fosse padrão.<br>
Ex: css gradiente.<br>
<br>
**Validação csslint.net**- validar o código, mostra os erros. Usar junto com o caniuse. Tb o w3c css validator (neste coloca a url).
