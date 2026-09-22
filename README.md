# TALLER-INTEGRADOR- JOSHUA ANDERSEJ WERMINSKY PEÑARANDA

| Defecto encontrado | Porque era el problema | Como se corrigió |
|---|---|---|
| Nombre del archivo CSS con espacios y mayúsculas (`Estilos Del Sitio.CSS`) | Podía fallar al cargar en servidores sensibles a mayúsculas/minúsculas, dejando la página sin estilos | Se renombró a `estilos.css` y se actualizó el `href` en el HTML |
| Los `<label>` no estaban asociados a sus `<input>` | Al hacer clic en el texto no se enfocaba el campo, y los lectores de pantalla no anunciaban a qué campo pertenecía cada etiqueta | Se agregó el atributo `for="n1"`, `for="n2"`, `for="n3"` en cada label |
| Variable `data1` declarada pero nunca usada | Código muerto que confunde a quien lee el archivo y sugiere una funcionalidad incompleta | Se eliminó la línea `let data1 = [];` |
| Función `calcularAntiguo` comentada | Código muerto de una versión anterior del programa (calculaba con 2 notas en vez de 3) | Se eliminaron las líneas comentadas de esa función |