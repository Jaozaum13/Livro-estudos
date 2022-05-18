# APRENDENDO O QUE SÃO ESTRUTURA DE DADOS E ALGORITMOS
## O QUE É ESTRUTURA DE DADOS
-   O QUE ESTRUTURA DE DADOS

Estrutura de dados é uma organizada de dados na memória de um computador ou em qualquer dispositivo de armazenamento, de forma que os dados possam ser utilizados da forma correta.

Como que nós aplicamos essas estruturas na memória? Nós criamos essa situação através de um algoritmo, então a gente vai lá e instrui o que você deseja fazer para o algoritmo. Um algoritmo são utilizado para manipular os dados nas estruturas de várias formas, você pode inserir, excluir, procurar e ordenar dados.

Em uma estrutura de dados deve-se saber como realizar um determinado conjunto de operações básicas, como por exemplo:

-   Inserir dados;
-   Excluir dados;
-   Localizar um elemento;
-   Percorrer todos os itens constituintes da estrutura para visualização;
-   Classificar os dados da maneira que desejar.

Nós também temos as principais estruturas de dados, que são:

-   Vetores e matrizes (arrays);
-   Registro;
-   Lista;
-   Pilha;
-   Fila;
-   Árvore;
-   Tabela Hash;
-   Grafos.

## VETORES E MATRIZES
Vetores e matrizes são estruturas simples que vão nos auxiliar quando dentro do algoritmo nós temos varias variáveis do mesmo tipo.

-   VETOR OU ARRAY UNI-DIMENSIONAL

É uma variável que armazena varias variáveis do mesmo tipo

O VETOR é uma estrutura de dados indexada, ou seja, pode-se armazenar uma determinada quantidade de valores do mesmo tipo.

-   MATRIZ OU ARRAY MULTI-DIMENSIONAL

É um vetor de vetores, uma matriz é um vetor que possui duas ou mais dimensões.

## O QUE SÃO REGISTROS
Enquanto ARRAYS nos permite armazenar vários dados de um único tipo, o recurso de REGISTRO nos permite armazenar mais de um tipo de dado.
Um registros são campos que especificam cada uma das informações que o compõem.

Toda estrutura de registro tem um nome (ex: livro), e seus campos podem ser acessados por meio do uso do operador ponto (.). Por exemplo, para acessar o preço de um livro, poderíamos utilizar a seguinte declaração:
livro.preco.

## O QUE SÃO LISTAS
Listas são estruturas de dados que armazena dados de um determinado tipo em uma ordem específica.

A diferença entre listas e arrays e que as listas tem um tamanho ajustável, enquanto que os arrays são de tamanhos fixos.

Existem dois tipos de listas:

-   LISTAS LIGADAS

Na estrutura de tipo lista existem os nós onde cada um dos nós conhece o valor que está sendo armazenado em seu interior, além de conhecer o elemento posterior a ele: por isso ela é chamada de “lista ligada”, pois os nós são amarrados com essa indicação de qual é o próximo nó.

-   LISTAS DUPLAMENTE LIGADAS

A diferença para a Lista Duplamente Ligada para a Lista Ligada é que na lista duplamente ligada ela é bidirecional, ou seja, você consegue ter uma ligação tanto com o próximo valor, quanto com o valor anterior. E isso ocasiona numa melhoria da navegação caso você deseje fazer o caminho reverso de uma lista, além de saber qual é o próximo elemento, ele vai saber qual é o elemento anterior.

## O QUE SÃO PILHAS (OU STACKS)
Uma PILHA é uma estrutura de dados que serve como uma coleção de elementos, e permite o acesso a somente um item de dados armazenado.
Nós só temos 2 tipos de PILHAS:

-   LIFO OU UEPS

LIFO (que significa Last in First Out), apresenta o seguinte critério: o primeiro elemento a ser retirado é o último que tiver sido inserido.

-   FIFO OU PEPS

FIFO (que signica First in First Out), apresenta o seguinte critério: o primeiro elemento a ser retirado é o primeiro que tiver sido inserido.

OBS: Dentro da estrutura PILHA, nós temos dois termos, PUSH E POP. PUSH significa inserir e POP significa remover um empilhamento.

## O QUE SÃO FILHAS
A estrutura do tipo FILA admite remoção e inserção de elementos sujeita a seguinte regra de operação:

O elemento removido é o que está na estrutura a mais tempo ou seja, o primeiro objeto inserido na fila é o primeiro a ser removido. Este é o mesmo conceito da estrutura do tipo FIFO.

## O QUE SÃO ÁRVORES
É uma estrutura que organiza seus elementos de forma hierárquica, onde existe um elemento que fica no topo da árvore e é chamado de raiz e existem os elementos subordinados a ele, que são chamados de nós ou folhas

## O QUE SÃO TABELAS HASH
A estrutura de TABELA HASH também é conhecida como tabela de espalhamento ou tabela de dispersão é uma estrutura de dados especial, que associa chaves de pesquisa a valores.

Uma tabela Hash é uma generalização da ideia de array, porém utiliza uma função denominada HASHING para espalhar os elementos, fazendo com que os mesmo fiquem de forma não ordenada dentro do “array” que define a tabela.

A tabela HASH permite nos associar “valores” a “chaves”.

VALORES: SÃO AS POSIÇÕES OU ÍNDICE ONDE OS ELEMENTOS SE ENCONTRAM.

CHAVES: SÃO PARTE DAS INFORMAÇÕES QUE COMPÕEM O ELEMENTO A SER MANIPULADO.

Sendo assim, o espalhar facilita a busca de dados, pois a partir de uma chave nós conseguimos acessar de forma rápida uma posição do “array”.

## O QUE SÃO GRAFOS
Grafos são estruturas que permitem programar a relação entre objetos. Os objetos são vértices ou “nós” (bolinhas) do grafo. Os relacionamentos são arestas (linhas que interligam as bolinhas).

Com a estrutura grafos nós conseguimos fazer qualquer tipo de busca e qualquer tipo de estrutura.
