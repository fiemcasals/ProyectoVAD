# Historias de Usuario -- mauri_vad

_Generado automaticamente el 2026-09-19T15:29:31.365Z -- no editar a mano, se sobreescribe en cada publicacion._

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

## HU-02: Sistema central de operacion del vehiculo

Esta va a ser la raiz para cargar todos los aspecots necesarios a fin de permitir la operacion y funcionalidades extras del vehiculo. vamos a empezar por la carga de mapas, una vez que tengamos el nucleo con un rol admin y usuarios con privilegios.(privilegios adefinir a futuro segun las funcionalidades que se le vayan creando)

### Criterios de Aceptacion

- 1.que tenga un sistema de login
- 2. que tenga un sistema de recuperacion de contraseña
- 3. que tenga una interfaz amigable
- 4. que tenga un sistema de registros
