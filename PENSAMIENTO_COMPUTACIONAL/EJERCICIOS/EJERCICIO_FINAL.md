Realiza en algoritmo, pseudocodigo y diagrama de flujo, un Juego simple que pide al usuario que adivine un numero en 10 intentos, que imprima si lo atina, y si no le indique si el número ingresado es mayo o menor al almacenado, así como el número de intemtos restantes.


Ingresa al siguiente link para el resumen final

https://docs.google.com/presentation/d/17LildSvlBpnu-FRpMW1ITRiO21_f3Z0cF9q1Zrs6K5U/edit?usp=sharing


Algoritmo adivinanza
	
	
	definir num, incognita, i Como Entero
	
	i=10
	
	Escribir "Dame un numero para adivinar"
	leer incognita
	
	Para i=0 Hasta 10 Con Paso 1 Hacer
		Escribir "Dame un numero"
		leer num
		Si num==incognita
			
			Entonces
			escribir "Felicidades, adivinaste el numero"
			
		Sino
			
			Si num<incognita
				escribir "tu numero es menor, dame otro numero"
				
			Sino 
				escribir "tu numero es mayor, dame otro numero"
					
					i=i+1
					
					Si i==10 Entonces
						escribir "Perdiste tus 10 oportunidades, el numero era " incognita
						
					FinSi
				FinSi
				FinSi
				
	Fin Para
FinAlgoritmo
