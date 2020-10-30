# chileplebiscito2020-resultados
Plebiscito 2020 de Chile. Resultados por mesa y otros.

## Descripción de datos

- **llave**: string que identifica únicamente a cada mesa de votación.
- **region**: región.
- **comuna**: comuna.
- **circunscripcion electoral**: circunscripción electoral.
- **local**: local de votación.
- **mesa**: mesa de votación.
- **votantes**: número de votantes habilitadxs en la mesa.
- **apruebo**: número de votos para la opción "Apruebo".
- **rechazo**: número de votos para la opción "Rechazo".
- **participacion**: calculado como `(apruebo + rechazo) / votantes` (nota: no usar como nivel de participación ciudadana, que debiese incluir nulos y blancos).
- **proporcion hombres**: proporción entre el número de votantes habilitadxs en la mesa registradxs como "V" (de "varón") y `votantes` (nota: equivale a `1 - <proporcion mujeres>`).
- **proporcion mujeres**: proporción entre el número de votantes habilitadxs en la mesa registradxs como "M" (de "mujer") y `votantes` (nota: equivale a `1 - <proporcion hombres>`).

## Agradecimientos
 
 - Fuente de datos: Servicio Electoral de Chile (www.servel.cl, www.servelelecciones.cl)
 - Lenguaje: Python (www.python.org)
 - Librería de raspado: Selenium (https://selenium-python.readthedocs.io/)

## Otros

- Autor: [@gdiazc](twitter.com/gdiazc)
