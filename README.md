# Taller-1 Diagrama de clases y UML
Para visualizar el diagrama de clases buscar en la zona readme y encontrara el pdf

## Descripción de componentes
Juego de estrategia inspirado en tamagochis de los años 90; donde el usuario a traves de su dispositivo móvil controla el movimiento del personaje.

### Componentes de Programación
- Contiene tanto en Android como en Eclipse la clase Main quien es considerado el "Ejecutable"
- Inicia comunicación entre Eclipse y Android; permitiendo ser visible la entrada y salida de información
- Utilización de hilos para evitar el congelamiento del juego
- Desde Android se inica cominicación desde el control a Eclipse
- Utilización de ObjectInputStream y ObjectOutStream para controlar la salida y entrada de los objetos del juego que requieren enviar información a eclipse

### Componentes de Diseño
- La interacción junto con las intrucciones debe de ser concisas y claras
- Se establece la conexión del control en Android y la interfaz del juego en eclipse
- Todo el tiempo se visualizará el tiempo del usuario
- Todo el tiempo se mostrará al usuario su puntaje
- Si el jugador gana se mostrará una pantalla especial con el resumen del juego
- Si el jugador gana se mostrará una pantalla especial con el resumen del juego
- Tiene un lienzo de 1200x700
