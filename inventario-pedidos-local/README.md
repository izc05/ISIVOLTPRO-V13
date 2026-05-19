# IsiVoltPro Pedidos Almacén — Demo local

Demo web en HTML para probar en móvil el flujo de pedido diario antes de pasar a APK o sincronización con Google.

## Objetivo de esta versión

Validar el concepto en campo:

1. Añadir artículos al pedido diario.
2. Hacer foto o elegir imagen del móvil.
3. Guardar material, modelo/referencia, cantidad y observación.
4. Crear automáticamente código `MAT-000001`.
5. Generar QR automático por artículo.
6. Ver pedido del día.
7. Crear informe diario imprimible/guardable como PDF.
8. Mantener una base local en el navegador.
9. Exportar copia de seguridad JSON y CSV.
10. Importar copia JSON en otro móvil o navegador.

## Importante

La base de datos de esta versión es local. Se guarda en el navegador del móvil usando `localStorage`.

Eso quiere decir:

- Funciona sin Google Drive.
- No necesita servidor.
- No necesita iniciar sesión.
- Si borras los datos del navegador, se puede perder.
- Conviene exportar una copia JSON al final del día.

## Flujo recomendado

1. Abrir `index.html`.
2. Añadir 2 o 3 materiales con foto.
3. Revisar `Pedido hoy`.
4. Entrar en `Informe`.
5. Pulsar imprimir/guardar PDF.
6. Entrar en `Datos`.
7. Exportar copia JSON.

## Próximas mejoras

- Mejorar diseño del PDF.
- Crear sincronización con Google Sheets/Drive.
- Pasar a APK con Capacitor.
- Añadir escaneo QR real.
- Convertir materiales frecuentes en inventario real.
