# -7DaysOfCode2

* 2 Day *

Desafio:

	- Qual o seu nome?
	- Quantos anos você tem?
	- Qual linguagem de programação você está estudando?

	"Olá [nome], você tem [idade] anos e já está aprendendo [linguagem]!"
  
Resolução:

  const seuNome = prompt ("Qual o seu nome?");
	const suaIdade = prompt ("Quantos anos você tem?");
	const linguagem = prompt ("Qual linguagem de programação você está estudando?");
  const apresentacao = '"Olá ${meuNome}, você tem ${minhaIdade} anos e já está aprendendo ${linguagem}!"'
  
  alerta(apresentacao);
