# Requerimientos Transportes Ltda.

**Contexto:** Importante Empresa de transporte(insertar nombre génerico) de la región de la Araucania y encargada de distribuir mercaderia en la zona necesita un nuevo sistema de gestión de itinerario.  

- **Problema:** Se necesita optimizar y modernizar su sistema de gestión de itinerarios, actualmente la empresa cuenta con un sistema antiguo y complicado de manejar, se utilizan principalmente planillas fisicas para gestionar todos los pedidos.
	
	Su sistema actual requiere mucho input de los camioneros, debido a que ellos llevan el registro de forma manual y administran el pago del cliente. Utilizan una planilla de papel para ver su itinerario, la cual no siempre se sigue al pie de la letra de lo estipulado y en la cual en ocasiones resulta dificil registrar cambios inesperados.
 
- **Usuarios**:
    1. Personal administrativo(administrador): Manejan los itinerarios.
    2. Camioneros(Usuario): Revisan su itinerario, el tipo de carga y metodo de pago del cliente.
    3. Clientes(Usuario): Reciben los pedidos y gestionan los tiempos de llegada de la mercaderia.
    4. Vendedores(Usuario): Proveen la mercaderia a los camioneros para distribuirla a los clientes.
        
- **Funciones Necesarias (MVP)**:
    1. Creacion de la API para integraciones a un sistema.
    2. El sistema permite crear y adminsitrar:
		- Fecha y horas de carga y descarga de la mercancia, Volumen de los pedidos.
		- Ubicación por gps de los camiones en ruta para tener un estimado de la fecha y hora de llegada.
		- Confirmar la entrega al momento de la recepción del pedido.
  
- **Datos a guardar**:
  	1. Registro de los camiones(patente, modelo, capacidad, estado, etc.)
  	2. Pedidos(ID_pedido, fecha, cliente, total_pedido, metodo de pago, entregable, etc.)
  	3. Cliente(Nombre, Dirección, Fecha_entrega, etc.)

- **Reglas del negocio**:
	1. Días de la semana establecidos de reparto
 	2. Cantidad de horas que puede manejar un conductor por día no debe exceder las 12 horas dentro del marco legal
  	3. Camiones deben estar en optimas condiciones:
  		3.1. Revisión técnica al día
  	   	3.2. Doucmentos del vehiculo siempre en circulación
  	   	3.3. No exceder el peso de carga maximo soportado por el camión

- **Prioridades**:
  	1. Registro de los camiones, con su ubicación
  	2. Registro de la entrega de los pedidos
  	3. Almacenar los datos de entrega de cada pedido

- **Plazo deseado**:
  	1. Projecto final y funcional(por definir)
  
- **Funciones a Futuro**:
	1. Aplicar API a un sistema para que:
		- Clientes vean sus pedidos con un tiempo estimado de entrega
        - Camioneros revisen su itinerario de manera más rápida
	2. Ubicación en tiempo real o aproximada de los camiones en ruta.
