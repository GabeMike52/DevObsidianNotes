***Conceito***
	São [[Blocos de Código|blocos de programas]], ou subprogramas, nomeados que executam determinada tarefa dentro de um algoritmo maior, mas não retornam valor algum apesar de poderem receber valores. Para serem executados, precisam ser chamados dentro do corpo do algoritmo principal após terem sido criados antes do inicio desse algoritmo.
***Uso***
	**Procedimentos podem ser sem ou com parâmetros.**
	1. Sem parâmetros:
		```procedimento <nome-do-procedimento>
		var
		//seção para declarar variáveis que serão utilizadas somente dentro do //procedimento
		inicio
		//código em si
		fimprocedimento```
	2. Com parâmetros:
		```procedimento <nome-do-procedimento> (<parâmetros>:<tipo-do-parâmetro>)
		var
		//Seção de declarações internas
		inicio
		//Seção de comandos
		fimprocedimento```
	**Diferença entre procedimentos com e sem parâmetros**
		Um parâmetro é utilizado para realizar um procedimento que precisa de [[dados]] de outra parte do [[Algoritmos|algoritmo]]. É utilizado quando queremos uma informação que não vem do usuário, mas está em outra parte do programa. Os parâmetros passam os argumentos, que são o valor propriamente dito. 
		Para explicar de forma mais didática, um procedimento é como um desenhista, desenhe algo, algo é o parâmetro, como argumento podemos passar  'árvore', desenhe árvore, logo, nosso procedimento executa um desenho de uma árvore.