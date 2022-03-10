# Falabella Challenge

This project has been generated for a job interview purposes.

## Challenges

A partir del siguiente swagger: [https://catfact.ninja/](https://catfact.ninja/)

Crear 5 casos de prueba funcionales para cualquier servicio que allí encuentres

Casos definidos:

- Obtener todos los facts y verificar que no exista página previa ni siguiente en la respuesta
- Obtener random fact y buscar si existe en listado de facts
- Obtener fact de largo 20 y buscar si existe en listado de facts
- Validar largo de un random fact
- Iterar sobre páginas al azar de listado de facts

## Stack

We use Blazemeter's API Monitoring to API Automation

## Preconditions

- Create a [free account](https://auth.blazemeter.com/auth/realms/blazect/protocol/openid-connect/registrations?client_id=account&response_type=code&redirect_uri=https%3A%2F%2Fauth.blazemeter.com%2Fauth%2Frealms%2Fblazect%2Fprotocol%2Fsaml%2Fclients%2Fblazemeter) on Blazemeter

## Import tests

First, please log in into blazemeter.

- Go to [Api Monitoring](https://www.runscope.com/radar/) on Blazemeter
- Create a bucket with a friendly name
- Press the button "Import tests"
- Choose "Runscope API Tests"
- Browse and select the file "Api Automation - Falabella.json" located inside of this project
- Press the button "Import API test"
- Press "Close" button

## Running tests

- Select "All Tests" tab or "Tests" menu
- Press the button "Run All Tests"
