# JAVASCRIPT
# COLEÇÕES
## COLEÇÃO MAP
Começamos com a Estrutura de um MAP.

![Estrutura de uma Coleção MAP.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6a82c109-9908-4921-b45d-b62fd9470e23/Untitled.png)

Estrutura de uma Coleção MAP.

Agora veremos um pouco dos métodos que podemos exercitar no Map.

![Métodos dentro de uma estrutura Map.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0d5cb7f0-5774-4a45-ac41-1ef7cbe4b20c/Untitled.png)

Métodos dentro de uma estrutura Map.

Analisando a imagem, temos que para adicionar, basta você usar “.set” acompanhado de uma chave e um valor, ambos entre aspas.

Para ler, basta você usar o “.get” acompanhado de uma chave, entre aspas.

Para deletar, basta usar o “.delete” acompanhado de uma chave, entre aspas.

E se você ler um valor depois de o mesmo ser deletado, o console irá voltar “undefined”, pois o valor não existe mais naquela coleção.

Qual a diferença de um Map e um objeto?

Ambos são estrutura de dados no formato chave e valor. O que os diferencia é que o Map pode ter chaves de qualquer tipo (números e outro tipos de valores). O objeto sempre terá chaves no formato de strings.

Map possui a propriedade length, que serve para você ver o tamanho desse Map, enquanto que com o objeto você tem que inteirar em todas as propriedades para ver quantas propriedades tem.

O Map é mais fácil de iterar, pois é uma coleção aonde você já tem o tamanho e já consegue saber quantos elementos tem.

Usamos o Map quando o valor das chaves é desconhecida, o objeto usamos quando sabemos o valor da chave que estamos procurando.

Os valores do Map tem o mesmo tipo e no objeto não necessariamente você precisa ter valores do mesmo tipo.

## COLEÇÃO SET
Começamos com a Estrutura de um SET.

![Estrutura de um SET.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6be4fc16-0b4e-4cfe-8870-f95921c68588/Untitled.png)

Estrutura de um SET.

Um SET armazena apenas valores únicos, enquanto que os arrays podem armazenar valores repetidos. Os Sets também possuem algumas propriedades e métodos diferentes do array.

Agora sobre os métodos dos Sets, temos os seguintes métodos principais:

![Métodos básico de um Set.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0a069143-1ae9-454f-8822-ea0ecfceea3f/Untitled.png)

Métodos básico de um Set.

Então, um Set possui valores únicos. Em vez de usarmos a propriedade length para consultar o número de registros, usamos a propriedade size. Um Set não possui os métodos map, filter, reduce etc.

# DEBUGGING E ERROR HANDLING
## ECMASCRIPT ERROR E DOMEXCEPTION
ECMAScript Error

São erros que ocorrem em tempo de execução, ou seja, enquanto o seu código ta rodando, ele percebe que algo está errado, alguma variável não foi declarada, ou você esqueceu alguma coisa. Ele é composto por:

Mensagem

Nome do Erro

Linha em ocorreu o erro

Call Stack - linha de chamada que ocorreu no seu código até você chegar nesse erro.

DOMException

Erros relacionados ao Document Object Model (DOM), ou seja, erros que ocorrem quando ligamos o Javascript ao nosso site.

## THROW, TRY/CATCH E FINALLY
THROW

![Exemplo de um código com return e outro com throw.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8d52a686-bde4-4b15-8817-dfafe8a58877/Untitled.png)

Exemplo de um código com return e outro com throw.

Quando usamos “return”, note que o código retornará uma string com o conteúdo entre aspas que foi definido, no caso foi definido “String Inválida”. E quando nós usamos throw, note que ele declarará um erro mesmo, ele será setado com Uncaught, pois nós não declaramos um novo objeto de erro.

TRY...CATCH

Basicamente Try é uma declaração, que dentro dela você vai verificar um pedaço de código e se esse pedaço de código tiver algum tipo de erro, ele vai ser tratado na função Catch. Dentro do Catch, você pode manipular esse erro da maneira que preferir.

![Try...Catch com console.log.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f29fa7b1-4573-4c4a-9381-737292f9e782/Untitled.png)

Try...Catch com console.log.

![Try...Catch com throw.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/51c53eee-3e89-4d97-af1d-eecdcc06677e/Untitled.png)

Try...Catch com throw.

FINALLY

É uma instrução que vai ser chamada independente de ter ocorrido o erro ou não. Se ocorrer um erro, ele vai mostrar a String enviada e o erro, e se não ocorrer ele irá mostrar a String e não terá mensagem de erro.


## O OBJETO ERROR
O Objeto Error já é nativo do Javascript e nós podemos colocar uma série de propriedades e executar uma série de métodos dentro. Vamos entender a anatomia desses erros.

![Modelo de um erro.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a52cf394-308a-4067-b12f-e45fe99f34dc/Untitled.png)

Modelo de um erro.

Notamos que na imagem message, filename e linenumber são os parâmetros, e esses são opcionais, normalmente os programadores usam mais o message. Nós podemos também dar um nome a esse erro, sendo assim, no resultado será mostrado um nome e em seguida o que ocorreu de errado. Como no exemplo abaixo.

![Modelo de um erro com nome.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/95c1034d-985b-4c96-bd7d-7a4ed0b0f7d4/Untitled.png)

Modelo de um erro com nome.

## DEFINIÇÃO PROMISE ASYNC/AWAY
O QUE É ASSÍNCRONICIDADE?

Assíncrono é algo que não ocorre ou não se efetiva ao mesmo tempo. Por exemplo: as aulas presenciais, aonde se você precisa estar presente naquele momento para conseguir absorver o conteúdo, isso é algo síncrono. Já se compararmos com as aulas online, aonde o aluno estuda quando ele pode, isso é um exemplo de assíncronicidade.

O javascript por padrão rodará de maneira síncrona, ou seja, vai acontecer alguma coisa, ao terminar nós começamos outro processo e assim que este termina, nós começamos outro processo. Já no javascript assíncrono, podemos fazer uma coisa enquanto fazemos outra também.

O QUE SÃO PROMISES?

Promises é um objeto de processamento assíncrono. Inicialmente, o valor de uma promise é desconhecido, então ela pode ser resolvida ou rejeitada. Promises são promessas, ou seja, podemos fazer uma analogia com a compra de um ingresso para assistir um filme. Quando você compra esse ingresso, você está prometendo que vai assistir aquele filme naquele dia, mas você pode não conseguir assistir aquele filme pois diversas coisas pode acontecer para você perde-lo, por isso é um promessa, você não sabe o que vai acontecer.

Uma promise tem 3 estados, o pending (pendente), o fullfilled (completo), ou o reject (rejeitado). Sempre que declarada essa promise, ela estará como pendente, podendo passar para completo ou rejeitado.

ESTRUTURA DE UMA PROMISE

![Imagem de uma estrutura de uma promise.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/98fbd254-08f3-4a1f-bc93-26c30ada3fa6/Untitled.png)

Imagem de uma estrutura de uma promise.

Nessa estrutura temos que: para chamar a promise, basta você escrever as palavras “new Promise” e depois ela dará os dois resultados, resolve and reject. Então temos nessa promises que depois de recebê-la, o computador vai esperar por 2 segundos e em seguida irá mandar a mensagem “Resolvida”.

Outra coisa legal que podemos fazer é encadear algumas chamadas, com o await, mas isso veremos mais para frente.

ASYNC/AWAY

A palavra Async existe para definir funções assíncronas, ou seja, funções assíncronas precisam dessas duas palavras chaves. Quando você vai resolver uma promise, você precisa definir a palavra async para conseguir usar a palavra await, que é uma palavra especificamente para lidar com promises. O away vai parar seu código e mandar geral espera para se resolver a promise, e só depois voltar a rodar certinho.

Modelo de uma função assíncrona

![Modelo de uma função assíncrona.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b905ee33-5759-436d-bf99-0f46a1a0770a/Untitled.png)

Modelo de uma função assíncrona.

Se você chamar somente uma “resolvePromise”, sme o await, uma promise vai retornar outra promise, quando você estiver utilizando uma função assíncrona, você não pode simplesmente chamar ela, por se não ele vai falar que ta pendente, você precisadar await nessa função assíncrona para receber o resultado. Como no exemplo abaixo.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0260d926-e523-4c7f-83ef-b0286bf77948/Untitled.png)

Você também pode utilizar a função try...catch para resolver a promise, como por exemplo:

![Modelo de utilização do try...catch para resolver promise.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/68901805-7927-4aee-820f-7a2990307580/Untitled.png)

Modelo de utilização do try...catch para resolver promise.


## O QUE SÂO APIs
API siginifica Application Programming Interface. As APIs são uma forma de intermediar os resultados do backend com o que apresentado no frontend, e nós conseguimos acessar os resultados dessa API por meio de URLs, como por exemplo:

![Modelo de integração back com frontend.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0c923998-cfaa-4244-9a3c-4a7776967730/Untitled.png)

Modelo de integração back com frontend.

Durante nossa carreira de programador com JavaScript, veremos muito a extensão”.json”, que significa JavaScript Object Notation. Os resultados de APIs vem muitas vezes como “.json”, além de que se você quiser fazer um post, por exemplo, precisará mandar como “.json”.

![Modelo de um código com a extensão “.json”.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7b2b9bab-3561-400e-9c7c-61767a636529/Untitled.png)

Modelo de um código com a extensão “.json”.

FETCH

Esse metódo é a grande estrela do show quando falamos em consumo de APIs. Abaixo teremos um exemplo de utilização do fetch.

![Modelo de utilização do fetch.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/09699e65-6370-4add-a649-1157df5b67cb/Untitled.png)

Modelo de utilização do fetch.

Lembre-se de sempre mandar o fetch responder em “.json”.

Lembre-se também que o fetch sempre retornará uma Promise, ou seja, você sempre precisará utilizar o await.

Abaixo teremos algumas operações no banco com o fetch.

![Operações no banco com fetch.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/232e0a2a-7eae-497b-b919-1ad5bc0accda/Untitled.png)

Operações no banco com fetch.
