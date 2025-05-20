# Evidencias-Proyecto-Integrador
## Estadísticas Agregadas
### Se calcularon dinámicamente las siguientes estadísticas a partir de los productos filtrados:

- Cantidad total de productos filtrados.

- Precio máximo y mínimo.

- Suma total del precio de todos los productos filtrados.

- Promedio de precios.

- Promedio del porcentaje de descuento (discountPercentage).

- Cantidad de productos cuyo título tiene más de 20 caracteres.


## División del Código en Componentes (continuación)
- ProductList
## Muestra la lista de productos en formato de tarjetas (Card).
### Props recibidas:

- products: array de productos ya filtrados que deben renderizarse.

## StatsPanel
### Encargado de mostrar todas las estadísticas calculadas.
### Props recibidas:

- total: cantidad total de productos filtrados

- productosMas20: cantidad de productos cuyo título supera los 20 caracteres

- precioTotal: suma de los precios de todos los productos filtrados

- max: precio máximo

- min: precio mínimo

- promedioPrecios: promedio de precios

- discountPercentage: promedio de descuentos
