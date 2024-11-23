Conversor de Monedas

Curso de Back-end con Java - Alura LATAM y Oracle
Este proyecto es un conversor de monedas desarrollado en Java como parte del curso de Back-end con Java impartido por Alura LATAM en colaboración con Oracle.
El programa utiliza una API de ExchangeRate para obtener tasas de cambio actualizadas y permite convertir montos entre diferentes monedas seleccionadas.

Índice

Características
Requisitos
Ejecución
Estructura del proyecto
Uso del programa
Tecnologías utilizadas
Autor

Características

Conexión a una API para obtener tasas de cambio en tiempo real.
Conversión entre monedas:
ARS (Peso argentino)
USD (Dólar estadounidense)
BRL (Real brasileño)
COP (Peso colombiano)
CLP (Peso chileno)
BOB (Boliviano boliviano)
Interfaz de usuario en consola con menú interactivo.
Validaciones para:
Ingresar opciones válidas.
Evitar montos negativos.
Manejo de errores en la conexión con la API.

Requisitos

Java JDK 17 o superior.
Conexión a Internet para acceder a la API de ExchangeRate.
Herramienta de desarrollo como IntelliJ IDEA, Eclipse o cualquier editor de texto con terminal.

Ejecución
Clona este repositorio en tu máquina local:
git clone https://github.com/tuusuario/conversor-monedas-java.git
Abre el proyecto en tu IDE o editor de texto favorito.
Asegúrate de que las dependencias estén configuradas y ejecuta el archivo Main.java.

Estructura del proyecto

src/

├── conversor/

│   ├── Main.java             # Clase principal con el menú interactivo

│   ├── api/

│   │   ├── ServicioAPI.java  # Lógica para conectarse a la API y manejar tasas

│   ├── modelos/

│   │   ├── Monedas.java      # Record para representar las tasas de cambio

│   │   ├── RespuestasAPI.java # Record para mapear la respuesta JSON de la API

Uso del programa

Al iniciar el programa, se muestra un menú con las siguientes opciones:
1. Convertir desde ARS
2. Convertir desde USD
3. Convertir desde BRL
4. Convertir desde COP
5. Convertir desde CLP
6. Convertir desde BOB
7. Salir
Selecciona la moneda de partida ingresando el número correspondiente.
Selecciona la moneda de destino de manera similar.
Ingresa el monto que deseas convertir (debe ser un número positivo).
El programa muestra el resultado de la conversión en la consola.
Puedes repetir el proceso o elegir salir del programa.

Tecnologías utilizadas

Java 17
Biblioteca Gson para procesar datos JSON.
Java HTTP Client para realizar solicitudes a la API.
API ExchangeRate para obtener las tasas de cambio.

Autor

Este proyecto fue desarrollado por Durand Camila Ayelen como parte del curso de Back-end con Java de Alura LATAM y Oracle.

Contribuciones
Si deseas contribuir a este proyecto, ¡puedes hacerlo! Solo realiza un fork del repositorio, haz tus cambios y envía un pull request.

