## Título
**Monster Hunter AR: Juego de caza de criaturas mediante geolocalización y detección de planos**

---

## Objetivo del proyecto

El objetivo de esta práctica es desarrollar una aplicación móvil en **Unity utilizando AR Foundation**, que integre **geolocalización real del dispositivo** y **realidad aumentada**, permitiendo al usuario interactuar con objetos virtuales posicionados en el entorno físico.

El alumno deberá diseñar e implementar un videojuego en el que el jugador se desplace por el mundo real para localizar y capturar criaturas virtuales.

---

## Descripción general del proyecto

El juego consistirá en un sistema de caza de monstruos en realidad aumentada:

- El jugador utilizará su dispositivo móvil para desplazarse físicamente.
- Los monstruos estarán asociados a coordenadas GPS reales.
- Los monstruos se capturan secuencialmente (en un orden establecido)
- Al aproximarse a la posición de un monstruo, este aparecerá.
- Mediante detección de superficies reales, se colocará un modelo 3D del monstruo en el entorno.
- El jugador podrá interactuar con el monstruo mediante un sistema de combate simple.
- El objetivo será derrotar todos los monstruos disponibles.

---

## Requisitos funcionales mínimos

La aplicación deberá incluir obligatoriamente:

### 1. Geolocalización
- Uso del sistema de localización del dispositivo.
- Lectura en tiempo real de latitud y longitud.
- Cálculo de distancia entre el jugador y los objetivos.

### 2. Realidad aumentada
- Uso de **AR Foundation**.
- Detección de planos reales.
- Colocación de objetos virtuales sobre superficies reales.

### 3. Sistema de monstruos
- Mínimo 3 monstruos distintos.
- Cada monstruo debe tener:
  - Posición GPS.
  - Vida.
  - Estado (activo / derrotado).

### 4. Interacción
- Sistema de combate:
  - Disparo de proyectiles o interacción por toque.
- Detección de colisiones.
- Eliminación del monstruo al perder toda la vida.

### 5. Navegación
- Implementar una brújula o flecha que apunte hacia el siguiente monstruo.
- Mapa del entorno en el que están los monstruos y que puede ser consultado en cualquier momento del juego

### 6. Pantalla de Ayuda
- Pantalla de inicio
- Pequeño tutorial/explicación de la mecánica del juego
- Pantalla final

### 7. Animaciones y Sonidos
- Sonido y animación al aparecer un monstruo
- Sonidos durante el combate con el monstruo
---


## Requisitos de interfaz

La aplicación deberá mostrar al menos:

- Distancia al siguiente monstruo
- Indicador de dirección (brújula).
- Mapa (o acceso a este) del entorno y la posición (aproximada) de los monstruos
- Una vez que aparece un monstruo:
    - Vida del monstruo.
    - Botón de disparo o interacción.
 
    - 
