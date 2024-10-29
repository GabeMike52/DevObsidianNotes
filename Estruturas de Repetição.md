***Conceito***
	Também chamada de laços de repetição, essas estruturas são feitar para repetir diversas vezes um mesmo [[Blocos de Código|bloco de código]]. Cada repetição desse laço é chamada de interação.
***Estrutura***
	**Para**
		Emprega uma [[Variáveis|variável]] contador que controla a quantidade de repetições executadas.
		```
		para (variável) de (valor inicial) ate (valor-limite) faca
			bloco de código
		fimpara
		```
	**Para Aninhado**
		Dois ou mais laços de repetição 'para' aninhados.
		```
		para (variável) de (valor-inicial) ate (valor-limite) faca
			para (variavel2) de (valor-inicial) ate (valor-limite) faca
				bloco de código
			fimpara
		fimpara
		```
	**Enquanto**
		Permite repetir um bloco de código *enquanto* determinada expressão lógica for verdadeira. Fornece uma estrutura de código mais 'simples' de ser compreendida.
		Nessa estrutura, faz-se necessário maior cuidado em fornecer um meio para que a expressão lógica seja satisfeita, para asssim evitar repetições intermináveis.
		```
		enquanto (expressão lógica) faca
			bloco de código
		fimenquanto
		```
	**Repita...até**
		Semelhante à estrutura enquanto, porém, o bloco de código é executado pelo menos uma vez, pois nessa estrutura, a avaliação da condição é feita somente no final de cada interação.
		```
		repita
			bloco de código
		ate (expressão lógica)
		```