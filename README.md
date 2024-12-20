# Descripción
En un día como hoy el primo de _Jvvb_ llamado _Avvb_ le dijo a _Jvvb_ que olvidó la contraseña de su celular, _Jvvb_ le pregunto a _Avvb_ si recuerda como hizo su contraseña, entonces _Avvb_ le dijo a _Jvvb_ como obtenía su contraseña, diciéndole estos criterios:

1. La contraseña se forma con solamente números primos

2. La contraseña viene conforme al procedimiento de _Avvb_

_Jvvb_ con solamente la pista de que la contraseña viene con solamente números primos y no sabe cómo es el procedimiento de _Avvb_, _Jvvb_ le dice a su primo que como es su procedimiento, entonces _Avvb_ le explica su procedimiento para que trate de recuperar su contraseña.

- En una matriz de tamaño $N$ * $M$ hacer un recorrido en espiral y colocar los pasos que llevas actualmente en la posición actual (en la posición $(0,0)$ llevas $1$ paso), desde la posición $(0,0)$ hasta que no se pueda avanzar mas, _Jvvb_ confundido le dice a su primo que no entendió como hacer la matriz de forma de espiral, asi que su primo _Avvb_ le hizo un dibujo de una matriz de $N$ = $3$ y $M$ = $5$:

![](https://raw.githubusercontent.com/JustinoHernandezTellez/La-contrasena-de-Avvb/main/contrasena%20del%20primo%20avvb.png)

- Después de eso recorrer la matriz desde la posición $(0,0)$ hasta la posición $(N - 1, M - 1)$ (cómo se recorre normalmente una matriz dicha de otra forma) e imprimir los números primos que se vaya encontrando (sin espacios) y ese será la contraseña de su celular :

_Avvb_ como buen ciudadano solo tiene los números de $N$ y $M$ (para evitar que encuentren su contraseña de forma rápida, le funcionó tanto esa estrategia que ni el la puede recuperar fácilmente), _Jvvb_ se dió cuenta que encontrar números primos no es tan rápido, entonces el decide contactarte, porque eres un programador competitivo.

# Problema
Ayuda a _Jvvb_ y a su primo
a encontrar la contraseña de acuerdo el procedimiento de _Avvb_.
# Entrada

Dos enteros $N$ y $M$, que es el tamaño de la matriz que ocupa _Avvb_ en su procedimiento.

# Salida

La contraseña del celular de _Avvb_ con un salto de linea(números enteros), de acuerdo a su procedimiento, si no
logras encontrar la contraseña entonces imprime "_avvb_ no tiene ningun tipo de contrasena" sin ñ  para evitar problemas en los casos de prueba, sin las comillas y con un salto de linea.

# Ejemplo

||input
1
5
||output
235
||description
Al realizar el procedimiento de _Avvb_ la matriz resultante es:
1 2 3 4 5
y al hacer el recorrido habitual de una matriz,
solamente nos encontramos con los números primos
2, 3 y 5
||input
10
10
||output
2357374143116771138397894761733159791729532319
||description
Realizar el procedimiento de _Avvb_
||end

# Límites

*  $1$ $≤$ $N$, $M$ $≤$ $1000$
