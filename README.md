# Conversor de Monedas

## Descripción

Este proyecto es una aplicación de consola en Java que permite convertir entre varias monedas. 
Presenta un menú interactivo donde los usuarios pueden elegir la conversión que desean realizar, ingresar un monto y 
obtener el resultado de la conversión utilizando tasas de cambio actuales obtenidas de una API.

## Características

- Menú interactivo con múltiples opciones de conversión.
- Mensajes de bienvenida e instrucciones claras.
- Soporte para conversión entre las siguientes monedas:
  - Dólares (USD) a Euros (EUR)
  - Euros (EUR) a Dólares (USD)
  - Dólares (USD) a Pesos Mexicanos (MXN)
  - Pesos Mexicanos (MXN) a Dólares (USD)
  - Dólares (USD) a Reales Brasileños (BRL)
  - Reales Brasileños (BRL) a Dólares (USD)
  - Dólares (USD) a Pesos Argentinos (ARS)
  - Pesos Argentinos (ARS) a Dólares (USD)
- Permite realizar múltiples conversiones sin necesidad de reiniciar la aplicación.
- Utiliza la API de Exchange Rate para obtener tasas de cambio actualizadas.

## Requisitos

- Java 11 o superior
- IntelliJ IDEA (o cualquier otro IDE compatible con Java)
- Conexión a internet para acceder a la API de Exchange Rate

## Instalación

1. Clona el repositorio a tu máquina local:
    ```bash
    git clone https://github.com/YeisonRios10/challenge_oracle_conversor.git
    ```
2. Abre el proyecto en tu IDE preferido (por ejemplo, IntelliJ IDEA).
3. Asegúrate de tener Java 11 o superior instalado.

## Configuración

1. Crea un archivo `config.properties` en la raíz del proyecto.
2. Añade tu API Key para el servicio de Exchange Rate en el archivo `config.properties`:
    ```properties
    apiKey=tu_api_key_aqui
    ```

## Uso

1. Compila y ejecuta la aplicación desde tu IDE o usando la línea de comandos:
    ```bash
    javac -d bin src/*.java
    java -cp bin Principal
    ```
2. Al iniciar, verás un menú interactivo. Elige una opción de conversión y sigue las instrucciones.

## API Utilizada

Utilizamos la [Exchange Rate API](https://www.exchangerate-api.com/) para obtener las tasas de cambio actualizadas. 
Asegúrate de registrar tu propia API Key y agregarla al archivo `config.properties`.

## Autor

**Yeison Stiven Rios Molina**  
Estudiante de back-end con Java en Alura
