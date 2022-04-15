# RECRIANDO A INTERFACE DE UM STREAMING
## DICAS NA HORA DE DESNVOLVER UM PROJETO
A primeira coisa que se deve fazer é criar as pastas e arquivos que você irá utilizar. Nesse caso, como será um projeto utilizando as tecnologias HTML, CSS E Javascript, criaremos uma pasta para os styles da página (CSS), uma pasta para a linguagem de programação (Javascript) e é recomendável que se crie pastas para os sources que você utilizará, nesse caso usaremos apenas imagens, mas podemos usar vídeos, textos, etc.

Cheque se as extensões que você irá usar estão todas instaladas, nesse primeiro projeto usaremos o Show Live Server, Auto Rename tag, para completar uma tag que você abrir mas esquecer de fechar, e o Dracula theme para ficar menos agressivo visualmente e prejudicarmso tanto nossa vista.

Tente utilizar o Emmet para ganhar mais tempo em seu código, mas enquanto estiver fixando conteúdo tente digitar para fazer isso melhor no futuro.

Caso você queira clonar a linha que você está, basta pressionar a tecla alt+shift+seta para baixo.

Para adicionar um comentário ao CSS, basta você adicionar “/**/”.

Quando você for criar um botão para o seu site, normalmente navegador já vai identificar que esse elemento é um botão, mas alguns navegadores não fazem essa função, então sempre coloque a propriedade “role=”button””.

## ANOTAÇÕES PARTE 6: ESTUDANDO WRAPPER
A tradução do termo wrapper é envelopar, basicamente o wrapper é um container, se aprofundarmos nos estudos de ambos, veremos que podem ter diferenças, mas no geral são bem parecidos. Se você for olhar no projeto do programa de streaming, o objetivo da class container é justamente envelopar tudo o que está dentro dela, formando a parte da série principal do seu site. O objetivo de se criar um único container para conter todas as informações de determinado site, é por causa que fica mais fácil você editar tudo, os elementos filhos estarão diretamente ligados com o elemento pai, assim criando modificações para o elemento pai, você passará essas mudanças para o elemento filho. Caso você queira alterar um botão por exemplo, este está dentro de um container, dentro do container principal, basta você apontar o container principal e em seguida apontar o container secundário, desta forma: “.serie-principal .container{}”.
