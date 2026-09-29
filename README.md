# El Index: Prescritos

Selector aleatorio temático inspirado en *Library of Ruina* y *Limbus Company*. Pulsa **Sacar prescrito** para elegir una entrada de la lista.

## Editar los prescritos

Abre `prescritos.js` y modifica el arreglo `PRESCRITOS`: añade una línea entre comillas por cada entrada y sepárala de las demás con una coma. Guarda el archivo y recarga la página. No hay controles para cambiar la lista desde la web.

## Prescritos de combate

Edita `prescritos-combate.js`. Añade frases completas con artículo a `PRESCRITOS_COMBATE` (por ejemplo, `"una misión"`) y las identidades disponibles a la lista del pecador correspondiente en `IDENTIDADES_POR_PECADOR`. El botón de combate se activa cuando hay una acción y suficientes pecadores con identidades para el valor del deslizador. El deslizador selecciona entre 1 y 12 pecadores distintos y se elige una identidad aleatoria de cada lista.

El botón **Aleatorio**, bajo el deslizador, elige una cantidad de pecadores entre 1 y 12 y bloquea el ajuste manual mientras está activado. Vuelve a pulsarlo para editar el deslizador.

El botón **Recibir prescrito de estado** usa una acción aleatoria de `PRESCRITOS_COMBATE` y selecciona al azar entre uno y ocho elementos distintos de `PRESCRITOS_ESTADO`.

El emblema original está en `index-icon.svg.webp`; la página lo muestra sobre el fondo negro.

## Abrir

Abre `index.html` en un navegador. No requiere instalación, dependencias ni servidor.
