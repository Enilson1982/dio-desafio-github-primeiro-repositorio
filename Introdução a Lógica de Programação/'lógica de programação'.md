	    
##### [Retorne a página principal](https://github.com/Enilson1982/dio-desafio-github-primeiro-repositorio/blob/main/README.md)	

# Introdução a Lógica de programação <h1>

###### Programar é resolver problemas.  
###### Abstração é Habilidade de concentração em aspectos essenciais.
###### Algorítmo é uma sequencia de passos para resolver problemas.  
###### Pseudocódigo é uma forma genérica de escrever o algorítmo.
  
  Um ponto importante para entender a programação é  relaciona
  ndo-a com cada ação que são realizada em um dia.
  
  Segue algumas dicas de site de jogos para entender sobre programação:
  
  <https://studio.code.org/s/mc/lessons/1/levels/1>
   
  <https://rachacuca.com.br/jogos/pinguins-numa-fria/>
 
##### No link para auxiliar a programar com um programa que utiliza fluxograma e variáveis:
    
    <http://www.flowgorithm.org/download/>
    
##### Alguns elementos da programação:
    
  Expressões Literais:
    
   ex: nome = "jose da Silva" | media = (nota1,nota2,nota3,nota4)/4
    
  Operadores relacionais
    
  Símbolos | Significado
  ---------|------------
     ==    | igualdade
     !=    | diferente
    <=     | menor que
     ^     | potência
     %     | porcentagem  
     /     | divisão
     *     | multiplicação
     +     | soma
     -     | subtração
       
 Uma das formas de programar é usando fluxograma: Através do programa "flowgorithm.org" é possível criar alguns programas com esse recurso.
 A lógica dele é a seguinte: 
       
 Vem o comando Principal automáticamente e uma seta pra baixo clicando nessa seta aparece as opções que será a declaração a ser escolhida;
 Na opção Declarar pode-se escolher em forma de Texto então digita: nome, sobrenome, idade
 Na seguinte seta pode-se escolher a opção Escrever "Qual é seu nome?" é o que vai aparecer para o usuário.
 Na seguinte seta pode-se escolher a opção Ler nome (a máquina vai solicitar que digito o nome);
 Na seguinte seta pode-se escolher a opção Escrever ", Qual é seu sobrenome?" é o que vai aparecer para o usuário.
 Na seguinte seta pode-se escolher a opção Ler sobrenome (a máquina vai solicitar que digito o sobrenome);
  Na seguinte seta pode-se escolher a opção Escrever " , Qual é sua idade?" é o que vai aparecer para o usuário.
 Na seguinte seta pode-se escolher a opção Ler nome (a máquina vai solicitar que digite  idade)
       
Ao dar Play > o programa vai perguntar o nome sobrenome e a idade.
      Pode-se declarar também a opção Real ou Inteiro onde o programa vai aceitar apenas números para Ler.
      Pode-se atribuir uma operação ao nome declarado como Real ou Inteiro:
      ex: atribuir > 
      nome da variável media  ,  Expressão  (nota1+nota2+nota3+nota4)/4
      
     Pode-se também cotatenar: Na opção Escrever pode utilizar a seguinte expressão: 
      
      "Seu nome é:  " & nome & ", o sobrenome é:    " & sobrenome & ", sua idade é:  " & idade & ", sua média é: " & media
      
      O programa vai apresentar todas as informações cootatenadas.
      Em alguns programas pode cotatenar por +, . ou & 
      
      E a função Se utilizando essa expressão: media >= 7
      
      do lado falso coloca a opção Escrever "estude mais"
    
      do lado verdadeiro coloca a opção Escrever "Muito bem, aprovado!"
      
      Essa foi a parte de entendimento do programa flowgorithm.org.
      
	    
#### Outro programa aprendido foi o Portugol Studio: 

	    
[Programa](http://lite.acad.univali.br/portugol/)
      
	    
~~~~
      programa
  {	
	funcao inicio()	
	    {
	    
 // Declarar: nesse caso usa "cadeia" para  caracteres de palavras e "real" para adquirir números.
	    
	 
	    real nota1,nota2,nota3,nota4,media    
	    cadeia aluno                          
	                                    
      
       // Aparece escreva ("aparece o que está escrito na tela para o usuário digitar") e leia (ler o dado declarado):
                                
                    
	    
            escreva ("digite seu nome: ")                                             
            leia (aluno)                          
		escreva("digite a nota 1: ")
		leia (nota1)
		escreva("digite a nota 2: ")
		leia (nota2)
		escreva("digite a nota 3: ")
		leia (nota3)
		escreva("digite a nota 4: ")
		leia (nota4) 
      
                                         //Abaixo está a váriavel media
                                           e a expressão
      
		media = (nota1+nota2+nota3+nota4)/4

                                        //Abaixo esta a cotatenação na função 
	                               escreva nesse caso é cotatenado com o + 
      
		escreva ("O nome do aluno é: " + aluno + ", sua média é: " + media)
	}
		
		
		
	}
~~~~
      
### Repetição
      
programa
{
	
	funcao inicio()
	{
	 // Declarar números inteiros               
	    
		inteiro contador, limite, resultado, tabuada

	    //   Dar valores ao número
	    
		contador = 0
		limite = 10
	    
	    // Apresenta a pergunta e pede o número

		escreva ("Qual tabuada você quer que eu resolva?")
		leia  (tabuada)
	    
	// Usaa variavel faca(faça)	
		
	    faca
		{ 
	    // coloca a expressão
	    
		resultado = tabuada * contador
	    
	    
	    // O que vai aparecer para o usuário
	    
			escreva (tabuada + " x " + contador + " = " + resultado + "\n")
		
	    
	    // Aqui ele idica que é para maquina contar na condição abaixo	
	    
	    
	      contador ++
		
	    // Essa é a condição da contagem automática entre contador e limite  
	    
	   
		}enquanto (contador<=limite)

		
	}
}
					    
~~~~
				
					 
Matriz
					    
					    
				    
	programa
{
	
	funcao inicio()
					    
	}
					    
					    
A Matriz funciona como a seguinte tabela:
					    
	-------
        [] []
 
Os dois primeiros colchetes representam  Y que pode variar infinitamente, como as linhas.
		
 |Ponto Y|
 ------------
| 0 |
| 1 |
| 2 |
| 3 |
					    
					 
Já os outros dois representam as duas colunas				    
					    
					    
|Ponto X|
------------------------------					       
|   0	  |    1   |	
------------------------------
		  			
Juntado os dois temos a seguinte tabela:
					    
            |           X            |
-------------------------------------------
            |    0      |      1     |
-------------------------------------------
|     Y     |
------------------------------------------					   
|     0     | [0] [0]    |  [0] [1]   |
|     1     | [1] [0]    |  [1] [1]   |
|     2     | [2] [0]    |  [2] [1]   | 
|     3     | [3] [0]    |  [3] [0]   |			    
					    

// Abaixo os elemento dentro de cada chave o esquerdo representa o 0 e da direita o 1.
A primeira chave representa o n=umero 0 a segunda o 1 e a terceira o 3 sucessivamente

					    
cadeia dados[][]={{"João","São Paulo"},{"Ana","Salvador"},{"Maria","Pernambuco"},{"(71) 9999-6666","(74) 9999-0000"},{"(11) 9999-77777", (71) 99999-4444}}  

					    
// Para aparecer determinado elemento com sua localização X (direita ou esquerda)  e a Y (cada chave) 					    ------------------------------------------
	ex: [0] [0] aparece o nome João
	    [4] [0] aparece (71) 9999-6666				    
	    [3] [1] aparece Pernambuco
	    [0] [1] aparece São Paulo				    
					    
	     escreva ("Nome: ")
	     escreva (dados[0][0]  + "         " + dados[1][0] + "       " + dados[2][0] + ("\n")) 
	     escreva ("Estado: ")
	     escreva (dados[0][1]  + "  " + dados[1][1] + "  " + dados[2][1] + ("\n")) 
	     escreva ("Telefone: ")
	     escreva (dados[3][0]  + "  " + dados[3][1] + "  " + dados[4][0] + ("\n")) 
	     
	}
}				    
~~~~
Matriz com repetição					    

~~~~					    
	programa
{
	
	funcao inicio()
	 
\\ Declara com Inteiro e diz com quanto quer começar					    
\\ Declara a Cadeia com matriz					    
	{
		inteiro contador =0
		cadeia cesta[][]={{"pera","100"},{"jaca","200"},{"maçã","900"},{"uva","89"}}

\\ Usa a função faca e orienta  que siga apresentando todos elementos da coluna 0 e depois todos da coluna 1
e limita que seja menor que três.					    
					    
	    faca{
	    	escreva ("Produtos: " + cesta [contador][0] + "Quantidade: " + cesta [contador][1] + "\n")
	   contador++
	    }enquanto (contador<=3)
	}
}		
	    
	    	    
	    
Foram estes ensinamentos absorvidos com o orientador: @Denilson bonatti._ da Dio. 
Bootcamp - Philips Fullstack Developer | You Are You 
~~~
    
