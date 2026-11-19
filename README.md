<img src="icono.png" width="72" alt="Logo de Visor de notas">

# Visor de notas

Visor de archivos Markdown y texto con un diseño minimalista inspirado en Notion. Es un solo archivo HTML que funciona sin internet y no depende de librerías externas.

**Úsalo en línea:** https://yefersonv5.github.io/visor-de-notas/

## Cómo usarlo

1. Abre el enlace de arriba, o descarga `index.html` y ábrelo con doble clic para usarlo sin internet.
2. Arrastra tus archivos a la ventana, usa **Abrir archivos** (`Ctrl O`) o pega texto (`Ctrl V`).

## Qué hace

- **Escribir y escuchar** (`Ctrl E`): espacio para escribir o pegar texto y que la aplicación lo lea en voz alta. Eliges la voz y la velocidad (de 0,5× a 4×) una vez y quedan guardadas. El texto se guarda solo en el navegador, se puede copiar, guardar como nota o borrar. Mientras lee, resalta la frase actual y puedes tocar cualquier frase para leer desde ahí (`Ctrl Enter` reproduce o pausa, `Esc` detiene). Si seleccionas una parte del texto con el mouse, lee solo esa parte.
- **Editor estilo Notion** en Escribir y escuchar: los atajos de Markdown se convierten mientras escribes (`#`, `##`, `###` títulos; `-` lista; `1.` numerada; `[]` tareas; `>` o `"` cita; ` ``` ` código; `---` divisor; `**negrita**`, `*cursiva*`, `` `código` ``, `~~tachado~~`, `==resaltado==`). Con `/` se abre el menú de bloques. Al pegar Markdown se convierte en bloques, y el botón Copiar copia con formato para pegar en Teams o en el correo.
- **Escuchar documento**: el botón de parlante en la barra superior lee en voz alta el archivo abierto. Al seleccionar texto aparece el botón **Leer selección** para escuchar solo ese fragmento.

- Markdown completo: títulos, listas anidadas, tareas, tablas, código, citas, enlaces e imágenes.
- Compatible con Obsidian: propiedades YAML, cuadros `> [!NOTE]`, `==resaltado==` y enlaces `[[Nota]]` entre archivos abiertos.
- Compatible con Pandoc: etiquetas `<badge>`, marcas `{=html}`, `[texto]{.underline}` y `[texto]{.mark}`.
- CSV como tabla (detecta `;` o `,`), JSON con formato y colores, TXT y LOG con números de línea.
- Índice automático, búsqueda dentro del documento, tema claro y oscuro, estilos de letra Predeterminado, Serif y Mono, tamaño de letra y ancho completo.
- Abre bien archivos guardados en Windows con otra codificación (tildes y ñ).
- Recuerda los archivos abiertos y tus ajustes en el navegador.

## Guardar las notas en una carpeta del PC (OneDrive o iCloud)

Las notas de **Escribir y escuchar** se pueden guardar como archivos `.md` en una carpeta de tu computador. Si esa carpeta está dentro de OneDrive o iCloud Drive, las notas se sincronizan solas con tus otros equipos.

1. Abre el visor en **Chrome o Edge de computador** (desde la página de GitHub Pages o el archivo descargado).
2. En la barra lateral pulsa **Conectar carpeta de notas** y elige o crea una carpeta, por ejemplo `OneDrive/Notas`.
3. Acepta el permiso para ver y editar archivos.

Cada nota es un archivo `.md` en esa carpeta y se guarda sola mientras escribes; el botón de disquete o `Ctrl S` la guarda al instante sobre el mismo archivo (no crea copias). Desde la barra lateral puedes crear notas (＋), abrirlas, renombrarlas (clic en el título) y borrarlas (doble clic en la papelera). Por seguridad, el navegador vuelve a pedir permiso cada vez que abres el visor: pulsa **Reconectar carpeta**. Si el archivo cambia en otro equipo, el visor trae la versión nueva al volver a la pestaña.

### Opción alternativa: GitHub

En el menú `···` > **Sincronizar con GitHub** puedes guardar las notas en un repositorio **privado** con una clave de acceso (fine-grained token con permiso *Contents: Read and write* solo sobre ese repositorio). Sirve en equipos donde no tienes OneDrive.

## Atajos

| Acción | Atajo |
|:--|:--|
| Abrir archivos | `Ctrl O` |
| Buscar | `Ctrl F` |
| Pegar texto | `Ctrl V` |
| Escribir y escuchar | `Ctrl E` |
| Escuchar o pausar (en Escribir y escuchar) | `Ctrl Enter` |
| Detener lectura | `Esc` |
| Mostrar u ocultar barra lateral | `Ctrl \` |
