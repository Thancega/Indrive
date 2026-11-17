# TratoTaxi — prototipo visual fiel al Figma

Esta versión se creó **a partir de las páginas del PDF `drive.pdf` proporcionado por el usuario**. A diferencia de una reinterpretación genérica, utiliza imágenes optimizadas de las pantallas originales para preservar la distribución, el color, la tipografía y los elementos tal como aparecen en el boceto de Figma.

## Pantallas y navegación

- Pantalla 1: solicitud y tarifa (partida, destino, ajustes, pago, solicitud).
- Pantalla 3: sala de negociación, con Carlos, Jorge y Marcos.
- Pantallas 4, 5 y 7: viaje en curso según el conductor elegido.
- Pantallas 2, 6 y 8: cierre del viaje y valoración según el conductor elegido.
- Diálogos interactivos de demostración: contraoferta, cancelar, SOS, compartir ruta, llamar, mensaje, anomalía, pagar, resumen, calificación, propina y finalización.

## Ejecutar

Abre `index.html` en un navegador. No se requiere instalación de dependencias.

## Publicar en Vercel

1. Sube el contenido de esta carpeta a un repositorio de GitHub.
2. Crea un proyecto en Vercel e importa el repositorio.
3. Framework: **Other**; sin build command; directorio de salida: raíz (`.`).
4. Deploy.

## Alcance

Es un **prototipo visual interactivo basado en capturas del PDF**: las pantallas no son un redibujo en capas HTML/CSS completamente editables. Los botones usan zonas interactivas superpuestas y los diálogos son HTML real. Es ideal para enseñar el flujo académico de alta fidelidad y conservar el diseño; una app productiva requeriría reimplementar las pantallas como componentes, integrar mapas y servicios, autenticación y backend.

No realiza viajes, reservas, llamadas, mensajes, pago, geolocalización o comunicaciones SOS reales.

Actualización: se eliminó el bloque introductorio lateral; el prototipo aparece centrado.


## Funciones ampliadas
- Perfil editable (nombre, correo, teléfono y ciudad) con almacenamiento local en el navegador. No crea una cuenta ni requiere contraseña.
- Navegación a Perfil, Mis Tratos y Billetera desde la barra inferior de las pantallas originales.
- Al finalizar una demostración, el viaje se incorpora al historial y al registro de movimientos simulados.
- Billetera permite elegir método de pago de demostración. No procesa pagos.
- Para limpiar los datos, borra los datos del sitio en el navegador.
