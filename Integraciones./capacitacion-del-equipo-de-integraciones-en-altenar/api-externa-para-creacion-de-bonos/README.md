# API externa para creación de bonos

Para crear bonos a los usuarios mediante la API externa, nuestro sistema actúa como cliente que consume el servicio del proveedor. Cuando necesitamos asignar un bono, nuestro backend realiza una petición a los endpoints específicos de la API del tercero, enviando los datos requeridos como el ID de usuario, monto del bono, código de promoción y fecha de expiración. La API externa valida esta información contra sus propias reglas de negocio y registra el bono en su sistema si todo es correcto. Nosotros recibimos una confirmación con los detalles del bono creado o un mensaje de error si hay problemas, como usuario no encontrado o incumplimiento de condiciones. Esta integración nos permite aprovechar la infraestructura del proveedor para gestionar bonificaciones sin desarrollar toda la lógica internamente, manteniendo la consistencia entre ambos sistemas mediante identificadores compartidos y mecanismos de sincronización.

La API consta de métodos y también de un listado de errores.

{% content-ref url="metodos/" %}
[metodos](metodos/)
{% endcontent-ref %}

{% content-ref url="lista-de-errores.md" %}
[lista-de-errores.md](lista-de-errores.md)
{% endcontent-ref %}

{% content-ref url="checklist-de-revision-de-integracion.md" %}
[checklist-de-revision-de-integracion.md](checklist-de-revision-de-integracion.md)
{% endcontent-ref %}
