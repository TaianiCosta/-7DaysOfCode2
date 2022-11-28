# -7DaysOfCode2

* 2 Day *

Desafio:

const nome = prompt ("Qual o seu nome?");

const idade = prompt ("Quantos anos você tem?");

const linguagem = prompt ("Qual linguagem de programação você está estudando?");

alert(`Olá ${nome}, você tem ${idade} anos e já está aprendendo ${linguagem}!`);

Desafio:

Exercício Opcional:

Você gosta de estudar [linguagem]? Responda com o número 1 para SIM ou 2 para NÃO.

1 > Muito bom! Continue estudando e você terá muito sucesso.

2 > Ahh que pena... Já tentou aprender outras linguagens?

Resolução:

const pergunta = prompt ('Você gosta de estudar [linguagem]?');

const resposta1 = ('Muito bom! Continue estudando e você terá muito sucesso.');

const resposta2 = ('Ahh que pena... Já tentou aprender outras linguagens?');

if (pergunta == 1) {
  alert (resposta1);
}

if (pergunta == 2) {
  alert (resposta2);
}
