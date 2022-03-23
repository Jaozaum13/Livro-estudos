# INTRODUÇÃO AO PORTUGOL
## APRENDENDO A COMO ULTILIZAR UMA ESTRUTURA DE REPETIÇÃO
-   O QUE É UMA ESTRUTURA DE REPETIÇÃO?

Dentro da lógica de programação é uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, de acordo com uma condição ou com um contador.

![Aqui temos um algoritmo para exemplificar a ESTRUTURA DE REPETIÇÃO, temos que um limite de 10 e o algoritmo vai contar até 10 e parar a execução.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/88dbb124-97c4-4195-8dbe-9248c3b134fd/Untitled.png)

Aqui temos um algoritmo para exemplificar a ESTRUTURA DE REPETIÇÃO, temos que um limite de 10 e o algoritmo vai contar até 10 e parar a execução.

![Aqui nós temos um algoritmo de tabuada do 9 para exemplificar uma ESTRUTURA DE REPETIÇÃO.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/188d9216-246e-4c7f-b48a-c8f81d742105/Untitled.png)

Aqui nós temos um algoritmo de tabuada do 9 para exemplificar uma ESTRUTURA DE REPETIÇÃO.

## O QUE SÃO LINGUAGENS DE PROGRAMAÇÃO
Linguagem de programação é uma escrita formal que especifica um conjunto de instruções e regras usadas para gerar programas (softwares). Um software pode ser desenvolvido para rodar em um computador, dispositivo móvel ou em qualquer equipamento que permita sua execução.

A função de uma linguagem de programação é servir de um meio de comunicação entre computadores e humanos. Logo você usará a linguagem de programação para o computador resolver um problema para você, porém, você precisará explicar esse problema para o computador.
#### LINGUAGENS DE ALTO E BAIXO NÍVEL
-   LINGUAGENS DE ALTO NÍVEL

As linguagens de alto nível são aquelas que a sintaxe se aproximam mais da nossa linguagem e se distanciam da linguagem da máquina. Como por exemplo, JavaScript, C#, PHP, C, C++, Python, etc.

-   LINGUAGENS DE BAIXO NÍVEL

As linguagens de baixo nível são aquelas que se aproximam mais da linguagem das máquinas. Para essas linguagens, você precisará ter o conhecimento sobre engenharia de hardwares para fazer alguma coisa. Como por exemplo, a mais conhecida delas que é a Assembly.
#### LINGUAGENS COMPILADAS OU INTERPRETADAS
-   LINGUAGENS COMPILADAS OU INTERPRETADAS
    
    -   LINGUAGENS DE PROGRAMAÇÃO COMPILADAS
    
    Esse tipo de linguagem utiliza um compilador, ou seja, você vai digitar o código e o compilador vai pegar o código e transformar em um arquivo executável (.exe) e vai executar o mesmo através do sistema operacional ou pelo processador. Simplificando, o compilador pega o seu código fonte e traduz para linguagem de máquina, para seu computador conseguir executar. São exemplos de linguagens compiladas, C#, VISUA BASIC, DELPHI, C++, ou seja, você precisa transforma elas em um arquivo executável e rodar elas sobre o sistema operacional.
    
    -   LINGUAGENS DE PROGRAMAÇÃO INTERPRETADAS
    
    É um tipo de linguagem em que o código fonte é executado por um programa de computador chamado interpretador e em seguida é executado pelo sistema operacional ou processador. Por exemplo, quando você abre um site na internet, o browser interpreta as linguagens de programação que são usadas ali, a mais conhecida se chama JavaScript, mas também temos o PHP e etc. Exemplos de linguagens interpretadas são: JavaScript, PHP, Python, etc.
    

Como o objetivo do curso de Lógica de Programação é você conseguir usar qualquer tipo de linguagem de programação de alto nível, nós começaremos a programar usando uma pseudolinguagem chamada PORTUGOL, que permite ao leitor desenvolver algoritmos estruturados em português de forma simples e intuitiva, independente de linguagem de programação. Usando essa pseudolinguagem, o programador consegue focar no programa em si, e não no equipamento que irá executar o algoritmo.
-   O QUE É UMA IDE

IDE é o ambiente gráfico de linguagens/pseudolinguagem de programação.

## APRENDENDO A ULTILIZAR DESVIOS CONDICIONAIS E BOAS PRÁTICAS EM PROGRAMAÇÃO
-   O QUE É DESVIO CONDICIONAL - SE

Nós utilizamos o desvio condicional SE, quando a condição a ser testada entre parênteses e as instruções que devem ser executadas entre chaves caso o desvio seja “verdadeiro”.

-   O QUE É SE - SENÃO

Imaginando que a condição se for falsa um conjunto de comandos deve ser executado. Nesse caso, use

senão {escreva(”Digite uma justificativa”)}

-   BOAS PRÁTICAS NA PROGRAMAÇÃO - COMENTÁRIOS

Muitas vezes dentro da empresa que você trabalha, pode acontecer de outro programador pegar o seu código para rever alguma coisa e acabar por não entender o que você queria fazer ali, ou até mesmo, você pode pegar esse código futuramente e não se lembrar do princípio do mesmo. Ai é que entra a importância do comentário em código.

NORMALMENTE os comentários são colocados no início do programa.

Os comentários no PORTUGOL são realizados com a função “//” que vai indicar ao PORTUGOL que este é um comentário e não uma ação do programa.

Tente SEMPRE colocar o nome do autor do código nos comentários para se seu código espalhar-se as pessoas saberem quem o fez.

-   DESVIO CONDICIONAL - CASO

Este comando é similar aos comandos SE e SENÃO, e reduz a complexidade na escolha de diversas opções. Apesar de suas similaridades com o SE, ele possui algumas diferenças. Neste comando não é possível o uso de operadores lógicos, ele apenas trabalha com valores definidos.

Se você estiver programando um menu de um programa que dá a opção de entrada nos streamings da NETFLIX, AMAZON PRIME E HBO MAX, por exemplo. Você consegue fazer esse programa usando QUATRO VEZES O COMANDO SE (ADICIONANDO SAIR DO MENU COMO UMA OPÇÃO DE VARIÁVEL). Porém se você precisar programar algo mais longo, com 200 opções, por exemplo, seria horrível ter que fazer 200 comandos SE manualmente. E é exatamente nesse caso que usaremos o comando CASO.

## TRABALHANDO COM LAÇOS DE REPETIÇÃO EM PORTUGOL
Só lembrando que Laços de Repetição ou Estrutura de repetição em programação é uma estrutura que permite executar mais de uma vez o mesmo comando ou conjunto de comandos, de acordo com uma condição ou com um contador.

Por exemplo escrevendo um algoritmo da tabuada do 9. Defina um contador ( que será o número que multiplicará o 9), defina uma variável “limite” para dizer qual será o limite que o algoritmo alcançará e defina uma última variável chamada resultado, que será o resultado da multiplicação do número 9, multiplicando todos os valores até atingir o limite que você sugeriu ao programa. E assim você cria uma estrutura de repetição, observe abaixo.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/080ccc22-2dd4-4589-bbb9-0020e4561733/Untitled.png)

Você também precisa indicar para o algoritmo que ele precisa adicionar mais uma unidade após a execução, e isso acontece exatamente quando você defini a função “CONTADOR ++.

E você indica para o algoritmo parar de multiplicar quando o limite for igual a 10, exatamente no ponto que defini a função “ENQUANTO(CONTADOR≤10)”.

## APLICAÇÃO PRÁTICA DE MATRIZES E VETORES
-   O QUE É UMA MATRIZ?

É uma coleção de variáveis do mesmo tipo, acessíveis com um único nome e armazenados contiguamente na memória

A individualização de cada variável de um vetor é feita através do uso de índices.

Os VETORES são matrizes de uma só dimensão.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e9ef6d77-d3e2-4cd4-8066-983a8cd2ade8/Untitled.png)

Como exemplo nós temos um algoritmo que recebe um VETOR com 4 posições definido na função “cadeia fruta[4]”. Na sequência de fruta que tem ali no meio do código, nós estamos definindo os valores de cada uma das 4 posições que definimos com o vetor de 4 posições. E na função “faca”, nós estamos pedindo para o programa escrever todas os valores de frutas definido.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f4ba6c81-caab-4504-8db2-ee2002b7501c/Untitled.png)

Aqui nós temos o exemplo da utilização de uma matriz.


