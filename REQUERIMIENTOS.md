# Requerimientos Transportes Ltda.

**Contexto:** Importante Empresa de transporte(insertar nombre génerico) de la región de la Araucania y encargada de distribuir mercaderia en la zona necesita un nuevo sistema de gestión de itinerario.  

- **Problema:** Se necesita optimizar y modernizar su sistema de gestión de itinerarios, actualmente la empresa cuenta con un sistema antiguo y complicado de manejar, se utilizan principalmente planillas fisicas para gestionar todos los pedidos.
	
	Su sistema actual requiere mucho input de los camioneros, debido a que ellos llevan el registro de forma manual y administran el pago del cliente. Utilizan una planilla de papel para ver su itinerario, la cual no siempre se sigue al pie de la letra de lo estipulado y en la cual en ocasiones resulta dificil registrar cambios inesperados.
 
- **Usuarios**:
    1. Personal administrativo(administrador): Manejan los itinerarios.
    2. Camioneros(Usuario): Revisan su itinerario, el tipo de carga y metodo de pago del cliente.
    3. Clientes(Usuario): Reciben los pedidos y gestionan los tiempos de llegada de la mercaderia.
    4. Vendedores(Usuario): Proveen la mercaderia a los camioneros para distribuirla a los clientes.
        
- **Funciones Mínimas (MVP)**:
    1. Crear API para integraciones a un sistema.
    2. El sistema permite crear y adminsitrar:
		- Puntos de carga y descarga por tiempo, Horas de entrega, Volumen de los pedidos.
		- Registro de camiones (placa, modelo, capacidad, estado).
		- Registrar clientes y el tipo de pago realizado.
- **Funciones a Futuro**:
	1. Aplicar API a un sistema para que:
		- Clientes vean sus pedidos con un tiempo estimado de entrega
        - Camioneros revisen su itinerario de manera más rápida
	2. Ubicación en tiempo real o aproximada de los camiones en ruta.
