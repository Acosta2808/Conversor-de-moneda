# Conversor de Monedas

Un conversor de monedas que utiliza una API externa para obtener tasas de cambio actualizadas.

## Requisitos

- Java 11+
- Maven
- IntelliJ IDEA (recomendado)

## Configuración

1. Clona este repositorio
2. Abre el proyecto en IntelliJ
3. Obtén una API key gratuita de [ExchangeRate-API](https://www.exchangerate-api.com/)
4. Reemplaza `TU_API_KEY` en `CurrencyConverterApp.java` con tu clave

## Uso

1. Ejecuta la aplicación
2. Ingresa la moneda de origen (ej. USD, EUR)
3. Ingresa la moneda de destino
4. Ingresa la cantidad a convertir
5. Verás el resultado de la conversión

## Tecnologías utilizadas

- Java
- Apache HttpClient
- Gson (para manejo de JSON)
- ExchangeRate-API

## Mejoras futuras

- Agregar historial de conversiones
- Permitir selección de monedas desde un menú
- Mostrar lista de monedas disponibles
- Implementar interfaz gráfica
