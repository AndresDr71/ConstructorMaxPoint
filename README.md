# ConstructorMaxPoint Application

Esta aplicación de JavaFX muestra una tabla con los resultados de los constructores con los máximos puntos en una competición. La aplicación carga los datos desde una base de datos utilizando un repositorio de consultas (`QueryRepository`) y los muestra en una interfaz gráfica.

## Características

- **Interfaz de Usuario**: Utiliza JavaFX para la interfaz gráfica, mostrando una tabla con los nombres de los constructores y sus puntos totales.
- **Cargado de Datos**: Los datos se cargan automáticamente al iniciar la aplicación desde un repositorio de consultas.
- **Estilo**: La aplicación aplica estilos básicos como negrita en las etiquetas y un fondo de color específico para la tabla.

## Estructura del Proyecto

- **ConstructorMaxPoint**: Clase principal que extiende `Application` y maneja la inicialización de la interfaz y el cargado de datos.
- **createLabel(String texto)**: Método para crear etiquetas con estilo.
- **createTableView()**: Método para crear la tabla que muestra los datos de los constructores.
- **loadInitialData()**: Método para cargar los datos iniciales desde el repositorio.
- **start(Stage primaryStage)**: Método principal que configura la interfaz gráfica y carga los datos al iniciar la aplicación.

![Imagen de WhatsApp 2024-07-22 a las 10 28 53_6b300f99](https://github.com/user-attachments/assets/8ee5805f-b029-41b4-b457-3ee0bd5d0328)
