EJERCICIO

1. Explica, en tus propias palabras, por qué es necesario que las computadoras representen los datos en binario.
2. Convierte el número binario 10011011 a decimal y a hexadecimal.
3. Investiga y describe cómo se representa una imagen en formato PNG en el disco.
4. Analiza la siguiente situación: ¿Qué sucede si intentas almacenar un número mayor al que puede representar un byte (por ejemplo, 300)? ¿Cómo lo maneja Python?

SOLUCION
1. Las computadoras solo entienden dos estados: encendido o apagado. Eso es como un interruptor que solo puede estar en dos posiciones. Entonces, usan solo dos números:
0 para apagado  
1 para encendido  
Así pueden guardar y procesar información de manera muy rápida y confiable.

2. 10011011 en decimal es igual a 155 y en hexadecimal es igual a 9B

3. Un archivo PNG no es una foto como tal, sino muchos datos guardados en un formato especial.  
Está hecho de:  
Una firma que dice “esto es un PNG”. Varias partes que guardan cosas como el tamaño, colores y los datos comprimidos de la imagen. Todo eso está guardado en unos y ceros (binario) en el disco.

4. Un byte puede guardar números desde 0 hasta 255, porque tiene 8 bits (o 8 dígitos en binario).
El número 300 es más grande que 255, así que no cabe en un byte. En lenguajes como C, si pones 300 en un byte, se guarda solo el resto después de dividir por 256 (que es 44).
En Python, los números pueden ser tan grandes como quieras, así que no hay problema con 300. Pero si usas un byte específico (por ejemplo, en un archivo o un array de bytes), Python te dará un error porque 300 no cabe en un byte.
