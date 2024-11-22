### Reto 3
Algoritmo para obtener los números primos hasta n, usando pseudocódigo y diagramas de flujo
<pre>
 Algoritmo Primos
	
    Escribir "Ingrese la cantidad de primos:"
    Leer cant
	
    Escribir 2 // El primer primo es 2
    mostrados <- 1
    n <- 3 // Iniciar con el primer número impar
	
    Mientras mostrados < cant Hacer
        es_primo <- Verdadero // Suponer que 'n' es primo
		
        Para i <- 3 hasta RC(n) con paso 2 Hacer
            Si n MOD i = 0 Entonces
                es_primo <- Falso // Si es divisible, no es primo
            FinSi
        FinPara
		
        Si es_primo Entonces
            Escribir n // Mostrar el número primo
            mostrados <- mostrados + 1
        FinSi
		
        n <- n + 2 // Saltar a los siguientes números impares
    FinMientras
	
FinAlgoritmo
</pre>

Este es el digrama de flujo del anterior pseudocodigo

![Diagrama de flujo](https://github.com/user-attachments/assets/8ac395c7-266d-4cb6-b46d-4c1909ae518e)


