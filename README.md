### Reto 3
Algoritmo para obtener los números primos hasta n, usando pseudocódigo y diagramas de flujo
<pre>
 Definir función PRIMO(n):
    Inicializar s como VERDADERO
    Para k desde 2 hasta raíz_cuadrada(n) + 1 hacer:
        s ← s Y (n módulo k ≠ 0)
    Fin Para
    Retornar s

Leer y convertir a entero el número ingresado, guardar en y
Si PRIMO(y) entonces:
    Mostrar "Es primo"
Si no:
    Mostrar "No es primo"
</pre>
---
