# Dropwizard trabajo examen final 
- Implementar 2 microservicios
- Cada uno con proyecto en dorpwizard diferente que se conecte a base de datos diferentes.
- Cada microservicio debe administrar para su cuenta la persistencia de su modelo.
- se sugiere las siguientes:
	*Clientes (Customers)
	*Pedidos (Orders)
- Debe tener cada uno su contenedor de docker

Validaciones:
Al eliminar un Cliente debe validar si tiene pedidos.
Se implementa un microservicio "ordersHttpClient" y se valida las excepciones
Al crear un pedido valida tambien la dirección.
