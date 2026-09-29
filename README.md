## Editar los prescritos

Abre `prescritos.js` y modifica el arreglo `PRESCRITOS`: añade una línea entre comillas por cada entrada y sepárala de las demás con una coma. Guarda el archivo y recarga la página. No hay controles para cambiar la lista desde la web.

## Prescritos de combate

Edita `prescritos-combate.js`. Añade frases completas a `PRESCRITOS_COMBATE` y las identidades disponibles a la lista del pecador correspondiente en `IDENTIDADES_POR_PECADOR`. El botón de combate se activa cuando hay una acción y suficientes pecadores con identidades para el valor del deslizador. El deslizador selecciona entre 1 y 12 pecadores distintos y se elige una identidad aleatoria de cada lista.

El botón **Recibir prescrito de estado** usa una acción aleatoria de `PRESCRITOS_COMBATE` y selecciona al azar entre uno y ocho elementos distintos de `PRESCRITOS_ESTADO`.
