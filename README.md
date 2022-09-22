# Algoritmos-de-Ordem
BUBBLESORT

Colocamos o vetor pré-definido e printamos para o usuário ver o antes e depois. n é o tamanho do vetor, como ele é incicializado no 0, em todos os for n < 6. 
Para organizarmos, vamos criar uma outra variável j para verificarmos todos os números - 1. 
No for do j, fazemos um if para que caso o número da posição anterior seja maior que o posterior, a variável aux seja puxada e registre o valor da posição j do vetor.
Então alteraremos o valor da posição j para o da posição j + 1(posterior) e o valor registrado em aux irá se tornar o valor de j + 1.
Com isso, o vetor vai estar organizado de forma crescente.

SELECTIONSORT

Nesse, faremos por métodos, declaramos o tamanho n do vetor, então entramos no método organizar, em um for, utilizaremos a variável i para determinar as posicões do vetor.
Como a primeira posição é 0, i deverá ser menor que n - 1. Seguindo em outro for, criaremos 2 variavéis para comparar as posições dos vetores. A variável minimo pega oque
está na posição i, enquanto a j pegará a posição superior, i + 1. Então inicializamos um if, para caso o valor na posição j seja maior que o valor na posição minimo,
substituimos o valor de minimo pelo de j ( minimo irá virar i+1, consequentemente j será i+2). Então a variável temp, irá pegar o valor da posição minimo do vetor e irá
alterar seu valor de forma a organizar o vetorna ordem crescente.
