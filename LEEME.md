# Mi Compañera 1.2 — candidato de pruebas

Actualización del proyecto Capacitor 8 existente. Conserva el mismo `appId` (`com.micompanero.app`) y el mismo almacenamiento local (IndexedDB/localStorage) para facilitar la actualización sin borrar los datos.

## Cambios
- Editor simplificado: título y contenido como foco principal.
- Cámara con elección entre tomar foto o seleccionar del teléfono.
- Adjuntos múltiples de imágenes y audios; miniaturas discretas en tarjetas.
- Carpetas personalizables sin formularios de categoría en el editor.
- Notas especiales de dinero: botones visuales para ingresos y gastos, concepto, importe y actividad/origen.
- Cierre diario calculado desde las notas de dinero; el módulo de Negocios ya no incluye ese cierre ni registra esos movimientos.
- Conserva eventos, negocios, transacciones y backups existentes.

## Compilar
1. Descomprime el ZIP.
2. En la carpeta del proyecto ejecuta `npm install`.
3. Ejecuta `npx cap sync android`.
4. Abre Android Studio con `npx cap open android`.
5. Genera APK de depuración para pruebas.

## Importante para probar
Este es un candidato de pruebas, no una versión certificada para publicar en Google Play. Hay que validar en el teléfono:
- Actualización sobre la versión anterior sin desinstalar.
- Que notas, carpetas, negocios, eventos y transacciones existentes sigan ahí.
- Cámara, galería y micrófono con permisos concedidos.
- Guardado de varias imágenes y grabaciones en una nota.
- Cierre diario con ingresos/gastos de varias notas de dinero.
- Copia de seguridad y restauración.

No desinstales la versión anterior ni limpies datos antes de probar. Haz primero una copia de seguridad desde la aplicación.
