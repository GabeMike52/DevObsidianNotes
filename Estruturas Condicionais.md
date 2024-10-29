***Conceito***
	Gerencia o fluxo da execução de um programa através da tomada de decisões baseada em condições, isso torna um programa mais dinâmico e funcional.
***Uso***
	**Estrutura condicional básica que testa se determinada condição é cumprida** 
		```
		SE(expressão lógica)
			comando
		FIM
		```
	**Estrutura condicional que testa se determinada condição é cumprida e executa algo caso não seja**
		```
		SE(expressão lógica)
			comando
		SENÃO
			comando
		FIM
		```
	**Estrutura condicional que testa se determinada condição é cumprida e, caso não, passa outra condição para ser testada.**
		```
		SE(expressão lógica)
			comando
		SENÃO SE(expressão lógica)
			comando
		SENÃO
			comando
		FIM
		```