## Algoritmo de Fuerza Bruta

# Características

- Es el algoritmo más simple posible
- Consiste en probar todas las posibles posiciones del patrón en el texto
- Requiere espacio constante
- Realiza siempre saltos de un carácter
- Compara de izquierda a derecha
- Realiza la búsquea del patrón en un tiempo O(mn)
- Realiza 2n comparaciones previstas de los caracteres del texto

# Lógica

- Se sitúa el patrón en la primera posición, y se compara carácter a carácter hasta encontrar un fallo o llegar al final del patrón
- Se pasa a la siguiente posición y se repite el proceso
- El proceso finaliza al alcanzar el final del texto
- No existe un preprocesamiento del patrón
