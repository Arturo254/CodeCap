# CodeCap
## Dev by Arturo Cervantes Galindo  
<p align="center"><img src="https://avatars.githubusercontent.com/u/133995595?v=4" width="200" alt="logo"></p>

📸 ¡Toma capturas de pantalla hermosas de tu código en VS Code!

## Características

- Guarda rápidamente capturas de pantalla de tu código.
- Copia las capturas de pantalla al portapapeles.
- Muestra números de línea.
- Muchas otras opciones de configuración.

## Instrucciones de uso

1. Abre la paleta de comandos (Ctrl+Shift+P en Windows y Linux, Cmd+Shift+P en OS X) y busca `CodeSnap`.
2. Selecciona el código que deseas capturar.
3. Ajusta el ancho de la captura de pantalla si lo deseas.
4. Haz clic en el botón de obturación para guardar la captura de pantalla en tu disco.

**Consejos**:

- También puedes iniciar CodeSnap seleccionando el código, haciendo clic derecho y seleccionando CodeSnap.
- Si deseas asignar un atajo de teclado a CodeSnap, abre la configuración de atajos de teclado y asigna `codesnap.start` a un atajo personalizado.
- Si deseas copiar al portapapeles en lugar de guardar, haz clic en la imagen y presiona el atajo de teclado para copiar (los valores predeterminados son Ctrl+C en Windows y Linux, Cmd+C en OS X), o asigna `codesnap.shutterAction` a `copy` en tu configuración.

## Ejemplos

[Tema Material](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme) + [Operator Mono](https://www.typography.com/fonts/operator/styles/operatormono)

![Example 1](https://raw.githubusercontent.com/kufii/CodeSnap/master/examples/material_operator-mono.png)

[Nord](https://github.com/arcticicestudio/nord-visual-studio-code) + [Cascadia Code](https://github.com/microsoft/cascadia-code)

![Example 2](https://raw.githubusercontent.com/kufii/CodeSnap/master/examples/nord_cascadia-code.png)

Monokai + [Fira Code](https://github.com/tonsky/FiraCode)

![Example 3](https://raw.githubusercontent.com/kufii/CodeSnap/master/examples/monokai_fira-code.png)

## Configuración

CodeCap es altamente configurable. Aquí tienes una lista de configuraciones que puedes cambiar para ajustar la apariencia de tus capturas de pantalla:

**`codesnap.backgroundColor`:** El color de fondo del contenedor del fragmento de código. Puede ser cualquier color CSS válido.

**`codesnap.boxShadow`:** La sombra de caja CSS para el fragmento de código. Puede ser cualquier sombra de caja CSS válida.

**`codesnap.containerPadding`:** El relleno para el contenedor del fragmento de código. Puede ser cualquier relleno CSS válido.

**`codesnap.roundedCorners`:** Valor booleano para usar esquinas redondeadas o esquinas cuadradas para la ventana.

**`codesnap.showWindowControls`:** Valor booleano para mostrar u ocultar los botones de ventana al estilo de OS X.

**`codesnap.showWindowTitle`:** Valor booleano para mostrar u ocultar el título de la ventana `nombre_de_carpeta - nombre_de_archivo`.

**`codesnap.showLineNumbers`:** Valor booleano para mostrar u ocultar números de línea.

**`codesnap.realLineNumbers`:** Valor booleano para comenzar desde el número de línea real del archivo en lugar de 1.

**`codesnap.transparentBackground`:** Valor booleano para usar un fondo transparente al tomar la captura de pantalla.

**`codesnap.target`:** Ya sea `container` para tomar la captura de pantalla con el contenedor, o `window` para tomar únicamente la ventana.

**`codesnap.shutterAction`:** Ya sea `save` para guardar la captura de pantalla en un archivo, o `copy` para copiar la captura de pantalla al portapapeles.

## Reconocimientos

El genial [Polacode](https://github.com/octref/polacode), por el concepto inicial.

[Carbon](https://carbon.now.sh/) por algunas ideas de diseño.
