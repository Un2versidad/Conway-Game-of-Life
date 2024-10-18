![image](https://github.com/user-attachments/assets/dd64163c-91ac-4509-b37a-098507612d52)

# Conway's Game of Life

Este proyecto es una implementación del famoso "Juego de la Vida" de John Conway, una simulación basada en autómatas celulares que ilustra cómo la vida puede emerger a partir de reglas simples. Este código crea una cuadrícula interactiva en la cual puedes iniciar, pausar, reiniciar y limpiar el estado de la simulación. Además, es posible modificar la cuadrícula haciendo clic sobre ella.

## Descripción del Proyecto

El Juego de la Vida es un juego de cero jugadores que simula la evolución de células vivas en una cuadrícula bidimensional. Cada célula puede estar en uno de dos estados: viva o muerta. Las reglas que rigen la evolución de la cuadrícula son las siguientes:

- Una célula viva con menos de dos vecinos vivos muere (subpoblación).
- Una célula viva con dos o tres vecinos vivos sobrevive.
- Una célula viva con más de tres vecinos vivos muere (sobrepoblación).
- Una célula muerta con exactamente tres vecinos vivos se convierte en una célula viva (reproducción).

## Características

- **Iniciar**: Comienza la simulación con las reglas descritas.
- **Pausar**: Pausa la simulación en su estado actual.
- **Reiniciar**: Restablece la cuadrícula y carga un patrón predeterminado.
- **Limpiar**: Borra la cuadrícula por completo, deteniendo la simulación.
- **Interactividad**: Puedes hacer clic en las celdas para activarlas o desactivarlas.

## Estructura del Proyecto

El proyecto consta de un solo archivo HTML que incluye la lógica en JavaScript:

- **HTML**: Crea la estructura de la página con un `<canvas>` para dibujar la cuadrícula y botones para interactuar con la simulación.
- **CSS**: Estilos básicos para la disposición del contenido y los controles.
- **JavaScript**: Controla la lógica del juego, la actualización del estado de la cuadrícula y la interacción del usuario.

## Instalación

1. Clona este repositorio o descarga los archivos.
2. Abre el archivo `index.html` en cualquier navegador moderno.

## Uso

- **Iniciar la simulación**: Haz clic en el botón "Iniciar".
- **Pausar la simulación**: Haz clic en el botón "Pausar".
- **Reiniciar la cuadrícula**: Haz clic en "Reiniciar" para cargar un patrón inicial.
- **Limpiar la cuadrícula**: Haz clic en "Limpiar" para borrar la cuadrícula y detener la simulación.
- **Interacción manual**: Haz clic en cualquier celda del tablero para alternar su estado entre viva y muerta.

## Tecnologías Utilizadas

- **HTML5**: Para la estructura y elementos de la página.
- **Canvas**: Para dibujar la cuadrícula y el estado de las células.
- **JavaScript**: Para manejar la lógica del Juego de la Vida y las interacciones.
- **CSS**: Para un diseño simple y centrado.

## Ejecución del Proyecto

1. Descarga el archivo `index.html`.
2. Ábrelo en tu navegador.
3. Usa los botones de control para interactuar con el juego.

## Contribución

Si deseas contribuir a este proyecto, siéntete libre de hacer un fork y enviar un pull request con tus mejoras.

## Licencia

Este proyecto está disponible bajo la licencia MIT.
