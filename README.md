# JOBMadrid-22-Data-Science
reto Data Science JOBMadrid '22

<h3>Sobre el desafío</h3>

<h1>IT JUNIOR Hackathon - JOBMadrid'22</h1>
<h2>Background</h2>
<p>IT Akadelivers es una empresa de reparto a domicilio especializada en la entrega de paquetes en menos de 1 hora, lo que se denomina (Q-commerce = Quick commerce) Esta empresa tiene una aplicación móvil con la que sus usuarios pueden elegir entre un catálogo de productos de tiendas locales de su ciudad y que les sean entregados en menos de 10 minutos a la dirección que deseen.

Cuando un usuario pide un pedido a través de Akadelivers se le cobra directamente el coste total (coste del producto + gastos de servicio + gastos de envío). Una vez el usuario ha pagado un producto, el repartidor que se encuentre más próximo a la tienda que tiene el producto se acerca a esta, paga el producto, lo recoge y lo lleva a la dirección que el usuario ha elegido. Akadelivers se lo llevara a la dirección indicada.</p>

<h2>Dataset</h2>

<ul>
<li>
<p><b>order_id</b>: Número de identificación del pedido.</p>
</li>
<li>
<p><b>local_time</b>: Hora local a la que se realiza el pedido.</p>
</li>
<li>
<p><b>country_code</b>: Código del pais en el que se realiza el pedido.</p>
</li>
<li>
<p><b>store_address</b>: Número de tienda en a la que se realiza el pedido.</p>
</li>
<li>
<p><b>payment_status</b>: Estado del pedido.</p>
</li>
<li>
<p><b>n_of_products</b>: Número de productos que se han comprado en ese pedido.</p>
</li>
<li>
<p ><b>products_total</b>: Cantidad en Euros que el usuario ha comprado en la app.</p>
</li>
<li>
<p><b>final_status</b>: Estado final del pedido (este será la variable 'target' a predecir) que indicara si el pedido será finalmente entregado o cancelado. Hay dos tipos de estado:</p>
<ul>
<li>CanceledStatus: La entrega se ha cancelado.</li>
<li>DeliveredStatus: La entrega se ha realizado correctamente.</li>
</ul>
</li>
</ul>

<p >Archivos:</p>

<ul>
<li><b>train.csv</b>: Este dataset contiene tanto las variables predictoras como el estado del pedido (TARGET).</li>
<li><b>text_X.csv.</b>: Este dataset contiene las variables predictoras con las que se tendrá que predecir el estado de un pedido.</li>
</ul>

<h2>Objetivos</h2>

<ul>
<li>
<ol>
<li>¿Cuáles son los 3 paises en los que más pedidos se realizan?</li>
</ol>
</li>
<li>
<ol start="2">
<li>¿Cuáles son las horas en las que se realizan más pedidos en España?</li>
</ol>
</li>
<li>
<ol start="3">
<li>¿Cuál es el precio medio por pedido en la tienda con ID 12513?</li>
</ol>
</li>
<li>
<ol start="4">
<li>Teniendo en cuenta los picos de demanda en España, si los repartidores trabajan en turnos de 8horas.</li>
</ol>
<ul>
<li>Turno 1 (00:00-08:00)</li>
<li>Turno 2 (08:00-16:00)</li>
<li>Turno 3 (16:00-00:00)</li>
</ul>
</li>
</ul>
<p>Qué porcentaje de repartidores pondrías por cada turno para que sean capaces de hacer frente a los picos de demanda. (ej: Turno 1 el 30%, Turno 2 el 10% y Turno 3 el 60%).</p>
<ul>
<li>
<ol start="5">
<li>Realiza un modelo predictivo de machine learning a partir del dataset 'train.csv' en el cual a partir de las variables predictoras que se entregan en el dataset 'test_X' se pueda predecir si el pedido se cancelará o no (columna 'final_status').</li>
</ol>
</li>
</ul>
