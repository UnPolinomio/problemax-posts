---
title: ¿Qué es el factorial de un número (❗)?
category: Combinatoria
published: 2021-07-10
cover: {{.assets}}/portada.png
level: 1
---

Imagina que quieres acomodar en una fila a tus tres mascotas: un león (🦁), un ratón (🐁) y una serpiente (🐍). ¿de cuántas maneras puedes hacerlo?

Hay seis maneras:

1. 🦁🐁🐍
2. 🦁🐍🐁
3. 🐁🦁🐍
4. 🐁🐍🦁
5. 🐍🦁🐁
6. 🐍🐁🦁

Detente un momento para que compruebes por ti mismo que estas son todas las posibilidades.

## Contar de manera más inteligente 🧠

Vamos a contar todas las posibilidades de una manera diferente. Sabemos que hay tres lugares en la fila:

![Hay tres lugares en la fila]({{.assets}}/casillas.png)

¿De cuántas maneras podemos escoger un animal para poner hasta el frente de la fila? Hay tres opciones porque tienes tres mascotas.

![Hay tres opciones para el primer lugar]({{.assets}}/casillas-3.png)

Ahora que ya escogimos un animal para poner hasta el frente de la fila, ¿de cuántas maneras podemos escoger un animal para poner en medio de la fila? Hay dos opciones porque te quedan dos mascotas por acomodar.

![Hay dos opciones para el segundo lugar]({{.assets}}/casillas-3-2.png)

Finalmente, ¿de cuántas maneras podemos escoger un animal para poner hasta el final de la fila? Sólo hay una opción porque queda una mascota por acomodar.

![Hay una opción para el tercer lugar]({{.assets}}/casillas-3-2-1.png)

Teníamos tres opciones, luego dos, luego una. En total podemos decir que tenemos $3 \times 2 \times 1 = 6$ opciones para formar a los animales en una fila. Esta era la respuesta que habíamos encontrado en primer lugar.

## El factorial de un número ❗❕

¿Qué pasaría si tuvieras diez mascotas en vez de tres? Podrías utilizar el mismo razonamiento para calcular el número de formas de acomodar en una fila a tus diez mascotas. En ese caso habría $10 \times 9 \times 8 \times 7 \times 6 \times 5 \times 4 \times 3 \times 2 \times 1$ formas.

Como te puedes dar cuenta, es muy difícil escribir tantos números multiplicándose. Cuando quieres indicar que quieres multiplicar entre sí todos los números desde el 1 hasta el 10, puedes escribirlo simplemente como $10!$

De esa manera también podemos simplificar la respuesta del primer problema. Si tienes tres mascotas entonces hay $3! = 6$ maneras de acomodarlas en una fila.

El símbolo ! se refiere a la función factorial y cuando escribes $5!$ se lee "cinco factorial".

Como ejercicio te invito a que calcules el factorial de algunos números.
