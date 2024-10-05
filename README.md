# projeto alura oracle

## teclado de telefone criado com html css e js
<br>
## codigo do projeto
<br>
## const listaDeTeclas = document.querySelectorAll('input[type=button]'); // seleciona as teclas do teclado
## const inputTel = document.querySelector('input[type=tel]'); // seleciona a entrada de dados, onde o numero da tecla vai aparecer quando o mesmo for clicado

## for (let indice = 0; indice < listaDeTeclas.length; indice++) { // laço de repetição
##   
##   const tecla = listaDeTeclas[indice]; /*** a variavel listadetecla nela esta armazenada um array de tecla 
##                                             ou seja, todas as teclas input que tem o atributo type="button" ou input[type=tel]
##                                             e todo dado em uma  posição do array é acessado atraves do seu indice
##                                             sendo assim o laço de repetição incrementa esse indice e a cada repecição
##                                             sera armazenado no cont tecla uma tecla de um indice diferente */
##   
##   tecla.addEventListener("click",function () { /**aqui o addeventlistner implementa um evento de click para a tecla selecionada,
##                                                 de um indice especifico */
##     inputTel.value = inputTel.value + tecla.value; /** atribui a entrada de dados onde é incerido o numero digitado 
##                                                     o valor da tecla que foi precionada */
##   })
## }
