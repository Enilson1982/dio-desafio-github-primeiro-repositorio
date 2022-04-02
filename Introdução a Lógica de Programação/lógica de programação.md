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
       
 Vem o comando PrincipaL automáticamente e uma seta pra baixo clicando nessa seta aparece as opsões que será a declaração a ser escolhida;
 Na opção Declarar pode-se escolher em forma de Texto ai digita: nome, sobrenome, idade
 Na seguinte seta pode-se escolher a opção Escrever "Qual é seu nome?" é o que vai aparecer para o usuário.
 Na seguinte seta pode-se escolher a opção Ler nome (a máquina vai solicitar que digito o nome);
 Na seguinte seta pode-se escolher a opção Escrever ", Qual é seu sobrenome?" é o que vai aparecer para o usuário.
 Na seguinte seta pode-se escolher a opção Ler sobrenome (a máquina vai solicitar que digito o sobrenome);
  Na seguinte seta pode-se escolher a opção Escrever " , Qual é sua idade?" é o que vai aparecer para o usuário.
 Na seguinte seta pode-se escolher a opção Ler nome (a máquina vai solicitar que digite  idade)
       
Ao dar Play > o programa vai perguntar o nome sobrenome e a idade.
      Pode-se declarar também a opção Real ou Inteiro onde o programa vai aceitar apenas núme para Ler.
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
      
     ##### Outro programa aprendido foi o Portugol Studio:
	   <http://lite.acad.univali.br/portugol/> 
      
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
      
      
      
programa
{
	
	funcao inicio()
	{
		inteiro contador, limite, resultado, tabuada

		contador = 0
		limite = 10

		escreva ("Qual tabuada você quer que eu resolva?")
		leia  (tabuada)
		
		faca
		{ 
			resultado = tabuada * contador
			escreva (tabuada + " x " + contador + " = " + resultado + "\n")
			contador ++
			
		}enquanto (contador<=limite)

		
	}
}
      
     Esse programa foi feito da seguinte forma: apartir da segunda chave digita: real nota1,nota2,nota3,nota4,media
       
       depois vem o local para Declarar, onde serão colocados os elemento trabalhados: onde você pode declarar rm forma de texto, real      
       
           
       
       
Entretanto apenas da forma demonstrada que conseguir realizar o processo de git push e git fetch.
Seguindo esses passos que aprendi com o orientador: @Denilson bonatti._ da Dio. 
Bootcamp - Philips Fullstack Developer | You Are You  
