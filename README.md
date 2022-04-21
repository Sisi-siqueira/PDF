# PDF
## SILVANA NASCIMENTO SIQUEIRA
##                                                            Análise
Caminho a percorrer! Aqui estão alguns dos principais conceitos para condicionais:
- Uma if instrução verifica uma condição e executará uma tarefa se essa condição for avaliada como true.
- if...elseAs instruções tomam decisões binárias e executam diferentes blocos de código com base em uma condição fornecida.
- Podemos adicionar mais condições usando else ifinstruções.
- Operadores de comparação, incluindo <, >, <=, >=, ===e !==podem comparar dois valores.
- O operador lógico e &&, ou “e”, verifica se ambas as expressões fornecidas são verdadeiras.
- O operador lógico ||, ou “ou”, verifica se qualquer expressão fornecida é verdadeira.
- O operador bang, !, alterna a veracidade e a falsidade de um valor.
- O operador ternário é uma abreviação para simplificar if...elsedeclarações concisas.
- Uma switchinstrução pode ser usada para simplificar o processo de escrever várias else ifinstruções. A palavra- breakchave impede que os s restantes casesejam verificados e executados em uma switchinstrução.














## Revisão: Escopo
Nesta lição, você aprendeu sobre escopo e como isso afeta a acessibilidade de diferentes variáveis.
Vamos analisar os seguintes termos:
-	O escopo refere-se a onde as variáveis podem ser acessadas em todo o programa e é determinado por onde e como elas são declaradas.
-	Blocos são declarações que existem dentro de chaves {}.
-	Escopo global refere-se ao contexto dentro do qual as variáveis são acessíveis a todas as partes do programa.
-	Variáveis globais são variáveis que existem dentro do escopo global.
-	O escopo do bloco refere-se ao contexto no qual as variáveis são acessíveis apenas dentro do bloco em que são definidas.
-	Variáveis locais são variáveis que existem dentro do escopo do bloco.
-	O namespace global é o espaço em nosso código que contém informações com escopo global.
-	A poluição do escopo ocorre quando muitas variáveis existem em um namespace ou os nomes das variáveis são reutilizados. Ao continuar sua jornada de codificação, lembre-se de usar as práticas recomendadas ao declarar suas variáveis! Definir o escopo de suas variáveis com precisão garantirá que seu código tenha uma lógica limpa, organizada e modular.















## A propriedade .length
Uma das propriedades internas de um array é lengthe retorna o número de itens no array. Acessamos a .lengthpropriedade da mesma forma que fazemos com strings. Verifique o exemplo abaixo:
const newYearsResolutions = ['Keep a journal', 'Take a falconry class'];
 
console.log(newYearsResolutions.length);
// Output: 2
No exemplo acima, logamos newYearsResolutions.lengthno console usando as seguintes etapas:
- Usamos a notação de ponto , encadeando um ponto com o nome da propriedade ao array, para acessar a lengthpropriedade do newYearsResolutionsarray.
- Em seguida, registramos o lengthno newYearsResolutionconsole.
-	Como newYearsResolutiontem dois elementos, 2seria logado no console.
 Quando queremos saber quantos elementos há em um array, podemos acessar a .lengthpropriedade.


















## O método .push()
Vamos aprender sobre alguns métodos JavaScript integrados que facilitam o trabalho com arrays. Esses métodos são chamados especificamente em arrays para tornar tarefas comuns, como adicionar e remover elementos, mais simples.
Um método .push()nos permite adicionar itens ao final de um array. Aqui está um exemplo de como isso é usado:
const itemTracker = ['item 0', 'item 1', 'item 2'];
 
itemTracker.push('item 3', 'item 4');
 
console.log(itemTracker); 
// Output: ['item 0', 'item 1', 'item 2', 'item 3', 'item 4'];
Então, como .push()funciona?
-	Acessamos o pushmétodo usando a notação de ponto, conectando pushcom itemTrackerum ponto.
-	Então nós a chamamos como uma função. Isso porque .push()é uma função e que JavaScript nos permite usar diretamente em um array.
-	.push()pode receber um único argumento ou vários argumentos separados por vírgulas. Nesse caso, estamos adicionando dois elementos: 'item 3'e 'item 4'a itemTracker.
-	Observe que .push()as alterações ou mutações , itemTracker. Você também pode ver .push()referido como um método de array destrutivo , pois altera o array inicial.
Se você estiver procurando por um método que altere uma matriz adicionando elementos a ela, então .push()é o método para você!












## O método .pop()
Outro método de array, .pop(), remove o último item de um array.
const newItemTracker = ['item 0', 'item 1', 'item 2'];
 
const removed = newItemTracker.pop();
 
console.log(newItemTracker); 
// Output: [ 'item 0', 'item 1' ]
console.log(removed);
// Output: item 2
-	No exemplo acima, chamando .pop()o newItemTrackerarray removido item 2do final.
-	.pop()não recebe nenhum argumento, simplesmente remove o último elemento de newItemTracker.
-	.pop()retorna o valor do último elemento. No exemplo, armazenamos o valor retornado em uma variável removedpara ser usada posteriormente.
-	.pop()é um método que altera a matriz inicial.
Quando você precisar alterar uma matriz removendo o último elemento, use .pop().

















## Mais métodos de matriz
Existem muito mais métodos de array do que apenas .push()e .pop(). Você pode ler sobre todos os métodos de array que existem na documentação do array Mozilla Developer Network (MDN) .
.pop()e .push()altere o array no qual eles são chamados. No entanto, há momentos em que não queremos alterar o array original e podemos usar métodos de array não mutantes. Certifique-se de verificar o MDN para entender o comportamento do método que você está usando.Alguns métodos de arrays disponíveis para desenvolvedores JavaScript incluem: .join(), .slice(), .splice(), .shift(), .unshift(), e .concat()entre muitos outros. O uso desses métodos integrados facilita a execução de algumas tarefas comuns ao trabalhar com matrizes.
Abaixo, vamos explorar alguns métodos que ainda não aprendemos. Usaremos esses métodos para editar uma lista de compras. Ao concluir as etapas, você pode consultar a documentação do MDN para saber o que cada método faz!
O método join() junta todos os elementos de um array (ou um array-like object) em uma string e retorna esta string.
O método slice() retorna uma cópia de parte de um array a partir de um subarray criado entre as posições início e fim (fim não é necessário) de um array original. O Array original não é modificado.
____________________________________________________________________________________________
O método splice() altera o conteúdo de uma lista, adicionando novos elementos enquanto remove elementos antigos.
_____________________________________________________________________________________
O shift()método remove o primeiro elemento de uma matriz e retorna esse elemento removido. Este método altera o comprimento da matriz.
_____________________________________________________________________________________
O unshift()método adiciona um ou mais elementos ao início de um array e retorna o novo comprimento do array.
O slice()método retorna uma cópia superficial de uma parte de uma matriz em um novo objeto de matriz selecionado de startaté end ( endnão incluído) onde starte endrepresenta o índice de itens nessa matriz. A matriz original não será modificada.
const animals = ['ant', 'bison', 'camel', 'duck', 'elephant'];
console.log(animals.slice(2));
// expected output: Array ["camel", "duck", "elephant"]
console.log(animals.slice(2, 4));
// expected output: Array ["camel", "duck"]
console.log(animals.slice(1, 5));
// expected output: Array ["bison", "camel", "duck", "elephant"]
console.log(animals.slice(-2));
// expected output: Array ["duck", "elephant"]
console.log(animals.slice(2, -1));
// expected output: Array ["camel", "duck"]
console.log(animals.slice());
// expected output: Array ["ant", "bison", "camel", "duck", "elephant"]

## Matrizes aninhadas
Anteriormente, mencionamos que os arrays podem armazenar outros arrays. Quando uma matriz contém outra matriz, ela é conhecida como matriz aninhada . Examine o exemplo abaixo:
const nestedArr = [[1], [2, 3]];
Para acessar os arrays aninhados, podemos usar a notação de colchetes com o valor do índice, assim como fizemos para acessar qualquer outro elemento:
const nestedArr = [[1], [2, 3]];
 
console.log(nestedArr[1]); // Output: [2, 3]
Observe que nestedArr[1]irá pegar o elemento no índice 1 que é o array [2, 3]. Então, se quisermos acessar os elementos dentro do array aninhado, podemos encadear ou adicionar mais notação de colchetes com valores de índice.
const nestedArr = [[1], [2, 3]];
 
console.log(nestedArr[1]); // Output: [2, 3]
console.log(nestedArr[1][0]); // Output: 2
Na segunda console.log()instrução, temos duas notações de colchetes encadeadas a nestedArr. Sabemos que nestedArr[1]é a matriz [2, 3]. Então, para pegar o primeiro elemento desse array, usamos nestedArr[1][0]e obtemos o valor de 2.

## Revisar matrizes
Bom trabalho! Nesta lição, aprendemos esses conceitos sobre matrizes:
-	Arrays são listas que armazenam dados em JavaScript.
-	Arrays são criados com colchetes [].
-	Cada item dentro de uma matriz está em uma posição numerada, ou índice, começando em 0.
-	Podemos acessar um item em um array usando seu índice, com sintaxe como: myArray[0].
-	Também podemos alterar um item em um array usando seu índice, com sintaxe como myArray[0] = 'new string';
-	Os arrays têm uma lengthpropriedade, que permite ver quantos itens estão em um array.
-	As matrizes têm seus próprios métodos, incluindo .push()e .pop(), que adicionam e removem itens de uma matriz, respectivamente.
-	Os arrays têm muitos métodos que executam tarefas diferentes, como .slice()e .shift(), você pode encontrar a documentação no site da Mozilla Developer Network .
-	Alguns métodos internos estão mudando, o que significa que o método mudará o array, enquanto outros não estão mudando. Você sempre pode verificar a documentação.
-	Variáveis que contêm arrays podem ser declaradas com letou const. Mesmo quando declarados com const, os arrays ainda são mutáveis. No entanto, uma variável declarada com constnão pode ser reatribuída.
-	Arrays modificados dentro de uma função manterão essa mudança mesmo fora da função.
-	Arrays podem ser aninhados dentro de outros arrays.
-	Para acessar elementos em índices de cadeia de matrizes aninhadas usando a notação de colchetes.
Aprender a trabalhar e manipular arrays ajudará você a trabalhar com blocos de dados!

## Instruções
Procurando mais maneiras de praticar? Considere tentar estes:
-	Use a .lengthpropriedade para encontrar o último elemento de uma matriz.
-	Use os outros métodos na documentação do MDN não mencionados na lição.
-	Pegue todos os elementos em um array e faça uma string.
-	Encontre o valor de retorno de chamar .push()em uma matriz.
-	Aninhe uma matriz dentro de uma matriz.
-	Acesse um elemento na matriz aninhada.

