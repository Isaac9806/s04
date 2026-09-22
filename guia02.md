Guía de Usuario: Registro de Productos

1. Introducción y Objetivo

1.1 ¿Qué permite realizar esta funcionalidad?

Esta guía explica cómo los vendedores pueden agregar nuevos artículos al sistema principal para que estén disponibles de inmediato para su facturación y venta.

2. Información necesaria antes de empezar

Antes de acceder al sistema, asegúrese de tener a la mano la siguiente información básica del artículo:

Código de barras (SKU) del fabricante.

Nombre comercial y marca.

Precio de costo y precio de venta al público.

Stock inicial en almacén.

3. Procedimiento de Registro

Siga estas instrucciones detalladamente para evitar errores de duplicidad en la base de datos:

Inicie sesión en el Panel de Administración con sus credenciales de vendedor.

En el menú lateral izquierdo, seleccione la opción "Inventario".

Haga clic en el botón verde de la esquina superior derecha que dice "+ Nuevo Producto".

Complete el formulario con la información solicitada.

Presione el botón "Guardar".

4. Resultados y Verificación

4.1 Mensaje del sistema

Una vez guardado, el sistema mostrará un mensaje genérico de confirmación en la parte inferior de la pantalla:

El registro se ha completado. Puede continuar agregando más productos.


4.2 Verificación técnica (Avanzado)

Si el equipo de soporte técnico necesita validar la creación en el servidor, este es el formato de respuesta que devuelve el sistema internamente:

{
  "status": "success",
  "data": {
    "product_id": 9845,
    "sku": "ITEM-001",
    "name": "Teclado Mecánico",
    "saved_at": "2026-09-22T18:30:00Z"
  }
}


5. Ayuda Adicional

Si encuentra algún error durante el proceso (como una alerta de "código duplicado"), por favor no intente registrar el producto nuevamente. Tome una captura de pantalla y contacte inmediatamente al equipo de sistemas a través de nuestro Portal de Soporte Técnico.