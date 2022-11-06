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


