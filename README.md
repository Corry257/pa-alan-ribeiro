# pa-alan-ribeiro
Repositório para aulas de programação e algoritmos 


# Arrays (conjunto, lista)
- O Array é um tipo d dado que serve para agrupar um conjunto de valores;

- Podemos inserir qualquer tipo de dado na lista;

- A sintaxe é [1,2,3,4,5];
- Sempre [], dados separados por virgula;
- Veremos arrays em mais detalhes futuramente, é uma estrutura de dadps muito importante e muito utilizada; 

# Array Associativo 

- O array associativo é basicamente um array, porém com chave e valor; 
- A estrutura base é a mesma, mas vamos construir dessa maneira:

     $arr = ['nome' => 'Andre'.idade => 42]

- Chave entre aspas, seta para apontar o valor e valor;

# Exercício 6

- Crie um arquivo PHP;
- Crie um array com caracteristicas de um carro;
- Imprima duas caracteristicas. 

# Exercício 7

- Crie um arquivo PHP;
- Crie um array associativo com caracteristicas de uma pessoa;
- Desafio: faça um if checando se ela é maior de idade e imprima uma mensagem, caso seja:

# Objetos 

- Php possui o paradigma de orientação a objetos;
Podemos criar classes e objetos, e o objeto é considerado um tipo de dado;
- Objetos possuem métodos que são susas ações e propriedades que são 
suas caracteristicas;
- Veremos objetos em maiores detalhes futuramente.

# null 

- O tipo de dado Null tem apenas um valor, o NULL; 
- Um caso de uso do Null seria checar se uma variável tem ou não valor;
- Podemos chegar se um valor é null com is_null()

# Sobre as variáveis 

- É a forma que temos para  declarar um valor e salva-lo na memória;
- Uma variável em PHP tem o $ na frente do seu nome;
- Ex: $nome = "Alan".
- Podemos salvar qualquer tipo de dado;
- Podemos alterar o valor de uma variável com o comando echo.

# exercício 08

- crie um arquivo php;
- crie três  variáveis com tipos de dados diferentes;
- Imprime estas variáveis.

# exercício 09

- Crie um arquivo PHP;
- Crie duas variáveis com números;
- Crie uma terceira com a soma destes dois números;
- lembrando: a soma pode ser feita com o simbolo +;
Ex: 2 + 4.

# variavel de variavel 

- Podemos criar uma variável por meio do nome de outra variavel, com um valor diferente;
- O simbolo para esta função é o $$
$x = "teste";
$$x = 5;
- Após a execução do código, a variavel teste (conteúdo do $x) será criada com o valor 5.

# Escopo 

- Como em outras linguagens em PHP também temos escopo de variáveis;

- Local: variável declarada em uma função;

- global: variaveis declaradas fora de funções;

- Static: Variavel declarada dentro da função, porém o seu valor permanece salvo entre chamadas da função;

- Parametros de função: variáveis passadas para uma função, podendo ser utilizadas ao longo da mesma. 

# Escopo Local

- A variavel local tem seu escopo definido dentro de uma função:

- ela não é acessivel dora da mesma;
o seui valor sempre é resetado

# Escopo global 

- A principal caracteristica da varupavek gkivbak pe ser deckarada fira de fybções;

- Por comportamento padrão não são acessiveis dentro de funções;

- Precisamos utilizar a palavra global para isso;

Essa função da variavel global não ser acessivel dentro de funções, previne muito problermas no software.

# Variável Estática 

- A variável estática é declarada com a instrução static; 

- O valor da mesma é mantido e alterado a cada execução de uma função;

- É interessante este comportamento pois as variáveis de escopo local sempre são resetadas. 

# paramentros de função

- Os parâmetros de função também são considerados tipos de variáveis;

- Este recurso nos ajuda a criar funções com valores dinâmicos;

- Podendo alterá-los a cada invocalão da mesma;

- Podemos passar mais de um parametro para uma função. 

# Expressões e Operadores - O que é uma expressão? 

- Uma instrução de código que será avaliada e resultatá em um valor;

- Uma simples impressão de um texto é uma expressão;

- Uma soma ou operação matematica mais complexa tambném;

- Na programação realizaremos diversas expressões durante nosso código, para formar nosso software. 

# Auto incremento e auto decremento 

- Podemos incrementar um valor 

# Operadores de compraração 

- As operações com poperadores de comparação resultarão em true or false;

- Igualdade: == 

- idêntico: ===

- Diferença: !=

- Não idêntico: !==

- Maior e maior ou igual a: > e >=

-

# Operador de igualdade 

- Com o Operador de igualde vericamos se um valor é igual ao outro: 

- O simbolo é: ==

- Exemplo: 5 == 4 #false
- Exemplo: 3 == 3 #true 

# Exercício 15

- Crie uma operação que retorne falso com igualdade: 
- Crie uma operação que retorne verdadeiro com igualdade: 

# Operador de diferença 

- Com o operador de diferença vericamos se um valor édiferente de outro; 

- O simbolo é: !=

- exemplo: 5 != 5  #false 

- exemplo: 10 != 5 #true 

# Operador não idendito a 

- Com o operador não idêntico a verificamos se um valor é diferente de outro. avaliando o seu tipo também:

- O simbolo é: !==

- Exemplo: 5 !== 4 #false
- Exemplo: 3 !== "3" #true