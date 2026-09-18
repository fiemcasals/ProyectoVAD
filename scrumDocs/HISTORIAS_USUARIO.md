# Historias de Usuario -- mauri_vad

_Generado automaticamente el 2026-09-18T15:59:16.118Z -- no editar a mano, se sobreescribe en cada publicacion._

## HU-01: generacion de carga de mapas y puntos de ruteo

La idea es poder cargar un mapa de los distintos lugares de navegacion y poder setear manual o automaticamente los puntos de referencia para armar el algoritmo de dijkstra

### Criterios de Aceptacion

- 1. tengo que poder cargar un mapa. y guardarlo
- 2. cargar automaticamente o manualmente los puntos que son los utilizados para configurar el diagrama de dijkstra
- 3. tener los endpoint listo para ser solicitados por otro algoritmo a fin de generar el camino
- 4. que opere como un nodo de ros, y publique en un topico la informacion
- 5. que tenga una interfaz agradable

### Detalle Tecnico y Reglas de Negocio

La idea es que se pueda configurar rapidamente el escenario donde va a operar el vehiculo
