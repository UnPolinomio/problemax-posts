---
title: ¿Qué son los números primos? 👨‍👦
category: Teoría de Números
published: 2021-07-08
cover: {{.assets}}/criba-de-eratostenes.png
level: 1
---

¿Cuántos números dividen al 18? El 1, 2, 3, 6, 9, 18. Observa que podemos decir que $18 = 1 \times 18$ pero también $18 = 2 \times 9$ y $18 = 3 \times 6$. ¿De cuántas maneras podemos escribir al dieciocho como multiplicación de algunos números enteros mayores que 1?

Tomemos $18 = 2 \times 9$. Dado que $9 = 3 \times 3$ podemos decir que $18 = 2 \times 9 = 2 \times 3 \times 3$.

Piensa un momento y date cuenta que la **única** manera de escribir al 3 como multiplicación de dos números positivos es $3 = 1 \times 3$ (aunque el número uno no afecta la multiplicación). Ya no podemos seguir separando al número tres en más números. A este tipo de números se les llama números primos.

De la misma manera, la única manera de escribir al número dos es $2 = 1 \times 2$. Por eso el número dos es un número primo.

## Teorema fundamental de la aritmética

En el ejemplo anterior te puedes dar cuenta que ya no podemos seguir dividiendo al 18 en más números. Lo más lejos que pudimos llegar fue $18 = 2 \times 3 \times 3$. Y no es casualidad...

El **Teorema fundamental de la aritmética** nos dice que todo número entero mayor que uno o bien es un número primo o bien se puede escribir de una única manera como multiplicación de otros números primos (sólo podría variar el orden en que se multiplican).

En el caso del 18. La factorización en primos sería $2 \times 3 \times 3$ y el Teorema fundamental de la aritmética te asegura que es la única.

## Números primos y compuestos

Los números que no son primos se llaman números compuestos.

En la siguiente imagen están los números del cero al cien. Los rojos son números primos. Los verdes son los números compuestos.

![Criba de Eratóstenes]({{.assets}}/criba-de-eratostenes.png)

Como puedes ver, el número cero y el número uno no son ni primos ni compuestos, ¿puedes adivinar por qué?

## Ejemplos 📝

A continuación te doy algunos ejemplos de factorizaciones de algunos números:

- $8 = 2 \times 2 \times 2$
- $10 = 2 \times 5$
- $45 = 3 \times 3 \times 5$
- $2021 = 43 \times 47$
- $7 = 7$. Observa que solo hay un factor porque el número siete es un número primo.

Como ejercicio te invito a encontrar la factorización en primos de los siguientes números (te puedes apoyar de la imagen anterior que muestra cuáles son números primos y cuáles compuestos):

- 16
- 50
- 49
- 43
- 100
