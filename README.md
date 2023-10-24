# Olá, Mundo!
 Primeiro repositório do curso de Git e GitHub
 
Repositório criado durante uma aula ao vivo!

Essa linha eu adicionei diretamente no site do github. Que impressionante!

Edição ligada a markdown.
 ---

\ Estou na fase de Aprender Lógica. 
 Irei usar esse espaço para salvar as instruções de raciocinio: 
  1-input: Palavra usada para receber dados do usuário
  2-print: exibir resultado no console 
  3-if condição: condicional que controla se algo deve ou não ser feito
  4-else: cláusula a ser executada caso nenhuma condicional if seja executada 
  5-loop de X a Y: laço de repetição que irá iterar de X a Y
  6-loop X em Y:laço de repetição que irá iterar de X a Y 
  7-loop X em Y: laço de repetição que irá iterar X em uma coleção Y 
  8-while X: laço de repetição que acontecerá enquanto uma condição for verdadeira

  Mais uma dica relevante para estabelecer a lógica: USE 5Qs

Quais são os dados de entrada necessários ?
O que devo fazer com estes dados ?
Quais são as restrições deste problema ?
Qual é o resultado esperado ?
Qual é sequência de passos para chegar ao resultado esperado (Algoritmo final)?


Exemplo de problema: Escreva um programa que retorna o valor hora de um funcionario com base no seu salario mensal e horas trabalhadas por mês

Exemplo solução: 
  input:salario_por_mes
  input:horas_trabalhadas_por_mes
  valor_hora(variavel criada):salario_por_mes/horas_trabalhadas_por_mes
  print:valor_hora

Exemplo de problema 2: Crie um programa que pede ao usuário seu nome e depois o dá as boas-vindas dizendo "X seja bem-vindo", onde X é o nome do usuario

Exemplo de solução:
input:nome_usuario
print:nome_usuario+"seja bem-vindo""

Exemplo de problema 3: Crie um programa que recebe dois valores e exibe qual é o maior entre eles

Exemplo de solução:
input:valor_a
input:valor_b
If valor_a > valor_b print valor_a else print valor_b

Exemplo de problema 4: Crie um programa que recebe um número e imprime seu fatorial

Exemplo de solução:
*Partindo da premissa que não sei o que é fatorial, passo 1 pesquisar o que é fatorial. 
Pesquisa feita > O fatorial (!) de um número n, representado por n!, é a multiplicação de n por seus antecessores maiores ou iguais a 1. Essa operação é muito comum em análise combinatória. O numero precisa ser inteiro e positivo.
Exemplos:

4! =4 · 3 · 2 · 1 = 24
5! = 5 · 4 · 3 · 2 · 1= 120
6! = 6 · 5 · 4 · 3 · 2 · 1 = 720
7! = 7· 6 · 5 · 4 · 3 · 2 · 1 = 5040

Pesquisa feita, agora realizar a criação do programa
input: numero_input
if numero_input < 0 print"digite apenas numero inteiro maior que zero"
fatorial = 1
loop de 1 a numero_input
fatorial(variavel criada) numero_input*fatorial
print resultado
