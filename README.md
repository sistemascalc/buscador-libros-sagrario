# Buscador de Libros — Sagrario Metropolitano

Repositorio público de actualizaciones para la aplicación de escritorio **Buscador de Libros**.

## Funcionamiento de las actualizaciones

La aplicación consulta automáticamente la publicación más reciente de este repositorio al iniciar. Si encuentra una versión superior:

1. muestra un aviso;
2. descarga el instalador de Windows;
3. muestra el progreso;
4. solicita reiniciar;
5. instala la actualización conservando los datos locales y la calibración de impresión.

## Publicar una versión nueva

1. Aumentar el número de versión de la aplicación.
2. Generar el instalador x64.
3. Crear una publicación (Release) con una etiqueta como `v1.3.0`.
4. Adjuntar el instalador con un nombre que contenga `Instalador` y termine en `x64.exe`.
5. Publicar la versión.

La aplicación usa la sección **Releases** como fuente oficial. No se deben eliminar versiones que todavía estén instaladas en equipos de trabajo.

## Versión base

La primera versión preparada para actualizaciones automáticas es la **1.2.0**.

Incluye búsqueda por fechas y personas, administración protegida, estadísticas e impresión de copias de actas de Confirmación en hoja carta.
