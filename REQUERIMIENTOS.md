# Requerimientos Transportes Ltda.

**Contexto:** Empresa de transporte y distribuición de mercaderia necesita nuevo sistema de gestión de itinerario  

**Problema:**
  - Se necesita optimizar y modernizar su sistema de gestión de itinerarios, actualmente la empresa cuenta con un sistema antiguo y complicado de manejar, se utilizan principalmente planillas fisicas para gestionar todos los pedidos.
	
	Su sistema actual requiere mucho input de los camioneros y peonetas, debido a que ellos administran el pago del cliente y usan una ficha de papel para ver su itinerario, la cual no siempre se sigue al pie de la letra y en la cual resulta dificil registrar cambios inesperados.
 
**Usuarios:**:
    1. Personal administrativo (manejan itinerarios)
    2. Camioneros (Integración a futuro) (revisan su itinerario, el tipo de carga y metodo de pago del cliente)
    3. Clientes (Integración a futuro) (reciben los pedidos y gestionan los tiempos de llegada de la mercancia)
**Funciones Mínimas (MVP)**:
    1. Crear API para integraciones a un sistema.
    2. El sistema permite crear y adminsitrar:
		- Puntos de carga y descarga por tiempo, Horas de entrega, Volumen de los pedidos.
		- Registro de camiones (placa, modelo, capacidad, estado).
		- Registrar clientes y el tipo de pago realizado.
**Funciones a Futuro**:
	1. Aplicar API a un sistema para que:
		- Clientes vean sus pedidos con un tiempo estimado de entrega
        - Camioneros revisen su itinerario de manera más rápida
	2. Ubicación en tiempo real o aproximada de los camiones en ruta.
