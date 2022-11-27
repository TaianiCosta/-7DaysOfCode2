# -7DaysOfCode2

* 2 Day *

Desafio:

	- Qual o seu nome?
	- Quantos anos você tem?
	- Qual linguagem de programação você está estudando?

	"Olá [nome], você tem [idade] anos e já está aprendendo [linguagem]!"
  
Resolução:

const nome = prompt ("Qual o seu nome?");<br /><br />
const idade = prompt ("Quantos anos você tem?");<br /><br />
const linguagem = prompt ("Qual linguagem de programação você está estudando?");<br /><br />
const apresentacao = 'Olá ${nome}, você tem ${idade} anos e já está aprendendo ${linguagem}!'
  
  alerta(apresentacao);
