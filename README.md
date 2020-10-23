#KataCode

Bora aprender, praticar e se diverdir?

O CodeKata http://codekata.com é uma forma de você praticar e tentar quantas vezes for necessário e se sentir confortável cometer erros.

Nosso KataCode segue esse preceito, o de aprender, praticar e o mais importante, se divertir aprendendo.

![alt text](https://github.com/papodesysadmin/katacode/blob/readme/img/code-kata.png "KataCode Ideia")

O desafio inicial, é de números primos, mais sobre [link](https://www.todamateria.com.br/numeros-primos) e [link](https://www.somatematica.com.br/fundam/primos.php)

Dentro desse contexto criamos 3 endpoints:

Um para trazer a quantidade de números primos em uma lista
`/primos?{quantidade}`

E outro para saber se um determinado número é primo ou não
`/primos/{numero}`

E o health para saber a saúde da aplicação
`/health`

A ideia inicial é que você entregue um container para nós com esses 3 acessos e com isso nós iremos:
1. Dar pull na imagem
2. Rodar a imagem
3. Rodar cenários de testes e com esses cenários gerar um report
4. Fazer o ranking