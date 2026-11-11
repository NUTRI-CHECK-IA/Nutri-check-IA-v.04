# NUTRI CHECK IA v0.4
Creado por Paola Andrea Reina Rios y Maria Jose Caicedo Rojas.

## Archivos
- `index.html`: la aplicación completa (un solo archivo).
- `Code.gs`: script NUEVO de Google Apps Script (guarda análisis, productos y usuarios).

## 1. Publicar la app en GitHub
1. En tu repositorio, abre `index.html` y pulsa el lápiz, o usa «Add file → Upload files» y sube el `index.html` nuevo con el mismo nombre.
2. «Commit changes». Espera 1-2 minutos y recarga con Ctrl+F5.

## 2. Actualizar el script de Google Sheets (IMPORTANTE)
El script anterior solo guardaba pocas columnas. Debes reemplazarlo:
1. Abre tu hoja de Google → Extensiones → Apps Script.
2. Borra todo el código y pega el contenido de `Code.gs`. Guarda (icono del disquete).
3. Implementar → Administrar implementaciones → lápiz (editar) → Versión: «Nueva versión» → Implementar.
4. La URL /exec NO cambia. La app ya la trae configurada.
5. En la app (como administrador): Ajustes → «Enviar prueba», y luego «Enviar todo a Sheets».

## Pestañas que crea el script en tu hoja
- `Analisis`: una fila por análisis, con todos los datos del producto, los cálculos, los sellos, la declaración y el empleado.
- `Productos`: el registro de productos.
- `Usuarios`: los empleados (nombre, rol, PIN cifrado).

## Usuarios
- El primer usuario que se crea es el administrador.
- El administrador crea a los empleados en «Usuarios». Cada análisis guarda quién lo hizo.
- Los usuarios se sincronizan por Google Sheets, así que se pueden usar desde varios computadores.
- El PIN identifica a cada persona; no es una seguridad fuerte.

## Importante
Los resultados son preliminares y académicos. No son certificación oficial.
