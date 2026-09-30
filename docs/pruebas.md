\# Registro de pruebas de exportación



\## Prueba 1: Primera build de escritorio (Windows)



\- \*\*Fecha:\*\* 30/09/2026

\- \*\*Plataforma objetivo:\*\* Windows Desktop (x86\_64)

\- \*\*Ruta de exportación:\*\* `../build/mi-mini-juego.exe` (carpeta externa al repositorio de código)

\- \*\*Tipo de ejecutable:\*\* Binario independiente con PCK embebido y modo debug activo.



\### Procedimiento realizado:

1\. Exportación del proyecto desde Godot Engine 4.x usando el preset preconfigurado para Windows Desktop.

2\. Comprobación de que la carpeta de salida `build/` está fuera del árbol del código fuente.

3\. Ejecución directa del archivo `mi-mini-juego.exe` mediante doble clic en el explorador de archivos sin el motor Godot abierto.



\### Resultado:

\- La aplicación se inicia inmediatamente sin errores de librerías ni dependencias faltantes.

\- Se renderiza correctamente la escena principal (`main.tscn`) cargando el nivel con el mapa de tiles del castillo (`Castle2.png`) y la vista centrada mediante `Camera2D`.

\- La build es reproducible por terceros en cualquier entorno compatible con Windows 64 bits.



\### Incidencias:

\- Ninguna detectada durante la prueba de ejecución.

