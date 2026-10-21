# Configuración de ProyectoDAWII

Configuración centralizada para los microservicios. Cada archivo `<nombre-del-servicio>.yml` se sirve desde Spring Cloud Config Server.

## Variables de entorno requeridas

- `AUTH_DB_USERNAME`, `AUTH_DB_PASSWORD`
- `DIARY_DB_USERNAME`, `DIARY_DB_PASSWORD`
- `WEATHER_DB_USERNAME`, `WEATHER_DB_PASSWORD`
- `JWT_SECRET`
- `WEATHER_API_KEY`

Configure estas variables en el entorno de cada servicio antes de arrancarlo. No publique sus valores en este repositorio.
