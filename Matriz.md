***Conceito***
	Uma matriz é uma estrutura homogênea multidimensional, sendo um [[vetor]] de vetores. Possui várias dimensões, vetores são, portanto, matrizes de uma única dimensão. Cada item de uma matriz pode ser acessado através de um índice.
***Estrutura***
	A notação de uma matriz é dada por MxN onde M é a dimensão horizontal (linhas) e N é a dimensão vertical (colunas).
	Portanto, para acessar determinado item de uma matriz, utilizamos o índice da linha e o índice da coluna onde o valor que queremos acessar está.
***Uso***
	VARIÁVEL: vetor [valor inicial L..valor final L, valor inicial C.valor final C] de TIPO
	notas: vetor [1..50,1..4] de inteiro
	Para usar a matriz, é necessário utilizar duas estruturas de repetição.
	EX.:
	para contador i de 1 ate 50 faca
		escreva("Aluno(a) número ", i)
		para contador j de 1 ate 4 faca
			escreva("Digite a nota: ", j)
			leia(notas[i, j])
		fimpara
	fimpara