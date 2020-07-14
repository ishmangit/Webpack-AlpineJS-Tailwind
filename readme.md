Fallaba el build prod de la versión original. Para solucionarlo añadí la siguiente línea en el
package.json
```
{
...
"exports": false,
...
```
Eliminar línea si esto da errores en el futuro