## 2.-Bases-de-datos-y-SQL
### Contexto

El restaurante "Sabores del Mundo", es conocido por su auténtica cocina y su ambiente
acogedor.
Este restaurante lanzó un nuevo menú a principios de año y ha estado recopilando
información detallada sobre las transacciones de los clientes para identificar áreas de
oportunidad y aprovechar al máximo sus datos para optimizar las ventas.

### Objetivo
Identificar cuáles son los productos del menú que han tenido más éxito y cuales son los que
menos han gustado a los clientes.

### Pasos a seguir

### a) Crear la base de datos con el archivo create_restaurant_db.sql

### b) Explorar la tabla “menu_items” para conocer los productos del menú.

1.- Realizar consultas para contestar las siguientes preguntas:
● Encontrar el número de artículos en el menú. 32
● ¿Cuál es el artículo menos caro y el más caro en el menú?  menos caro edamame, más caro Shrimp Scampi
● ¿Cuántos platos americanos hay en el menú? 6
● ¿Cuál es el precio promedio de los platos? 13.29

### c) Explorar la tabla “order_details” para conocer los datos que han sido recolectados.

1.- Realizar consultas para contestar las siguientes preguntas:
● ¿Cuántos pedidos únicos se realizaron en total? 5370
● ¿Cuáles son los 5 pedidos que tuvieron el mayor número de artículos? 
● ¿Cuándo se realizó el primer pedido y el último pedido? primer pedido 202301-01, y ultimo pedido 2023-03-31
● ¿Cuántos pedidos se hicieron entre el '2023-01-01' y el '2023-01-05'? 5370

### d) Usar ambas tablas para conocer la reacción de los clientes respecto al menú.

1.- Realizar un left join entre entre order_details y menu_items con el identificador
item_id(tabla order_details) y menu_item_id(tabla menu_items).

e) Una vez que hayas explorado los datos en las tablas correspondientes y respondido las
preguntas planteadas, realiza un análisis adicional utilizando este join entre las tablas. El objetivo es identificar 5 puntos clave que puedan ser de utilidad para los dueños del restaurante en el lanzamiento de su nuevo menú. Para ello, crea tus propias consultas y utiliza los resultados obtenidos para llegar a estas conclusiones.



#/*Lo anterior ayuda a enteder qué tipo de comida es la 
más vendida y posiblemente podrían agregarse más opciones 
de categorias más vendidas, ajustar los precios segun el ticket etc. 

![image](https://github.com/user-attachments/assets/c0f6605b-2a42-4b25-8e85-8c9ee68f1a5e)

