programa
{
	
	funcao inicio()
	{
	escreva("Escolha uma das opções: 1 - Abrir Netflix 2 - Abrir Amazon Prime 3 - Abrir HBO GO 4 - Sair")
	inteiro menu=0
	escreva("\n" + "Sua escolha: ")
	leia (menu)
	
	escolha (menu)
	{
	caso 1:
		escreva("Ok!! Abrir Netflix!")
	pare
	
	caso 2:
		escreva("Ok!! Abrir Amazon Prime!")
	pare
	
	caso 3:
		escreva("Ok!! Abrir HBO GO!")
	pare
	
	 caso 4:
	 escreva("Saindo do menu....")
	caso contrario:
	escreva ("Você deve escolher as opções 1, 2 ou 3")
	}
	}	
}