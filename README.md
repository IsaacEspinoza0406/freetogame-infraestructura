# Infraestructura SOA - Actividad 6 AWOS.

Este repositorio contiene la configuración de la infraestructura para la Actividad 6: Consumo de APIs de Terceros. 

Mediante Docker Compose, este proyecto inicializa de forma simultánea y aislada los microservicios bajo una red virtual privada (`bridge`), garantizando el principio de desacoplamiento de la Arquitectura Orientada a Servicios (SOA).

## Servicios Configurados:
1. **Frontend Client:** Interfaz de usuario en Next.js (Puerto 5000).
2. **BFF / Proxy Service:** Capa de servicios en Node.js para el consumo seguro de FreeToGame (Puerto 4000).

## Instrucciones de despliegue
Ejecutar el siguiente comando en la raíz de este directorio:
```bash
docker compose up --build