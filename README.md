# Estudos-TS
Salvando os conceitos da sintaxe TypeScript

FUNÇÕES DE SETA-------
----------------------
Uma nova forma de estruturar uma função, possui uma flexibilidade que permite tornar o código ainda mais limpo dependendo da quantidade de parâmetros e do retorno.
Sua sintaxe tem 3 componentes: () => {}

() = Recebe os parâmetros da função.
=> = é a seta que aponta pro corpo da função
{} = o bloco onde o código da função será estruturado

Função normal ----------
hello = function() {
  return "Hello World!";
}
hello() // Hello World!

Função de seta ---------
hello = () => {
return "Hello World!";
}
hello() // Hello World!

Mais curto ainda -------
hello = () => "Hello World";
hello() // Hello World!

Em funções com um só parâmetro, pode-se remover também os parênteses.
Exemplo:
soma10 = a => a + 10
soma10(20) // 30

