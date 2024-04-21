## Requisitos Funcionales y Criterios de Aceptación
### 1. Configuración de Nivel de Dificultad
**Requisito:** El sistema debe permitir a los jugadores seleccionar el nivel de dificultad antes de comenzar el juego.

**Criterios de Aceptación:**
- Opciones de dificultad fácil, medio y difícil disponibles para selección.
- La configuración de dificultad debe influir en la mecánica del juego, como la frecuencia de regeneración de imágenes y la puntuación.
- Tiempos de regeneración específicos:
  - Fácil: cada 8 segundos.
  - Medio: cada 6 segundos.
  - Difícil: cada 5 segundos.

### 2. Registro de Usuarios
**Requisito:** El sistema debe permitir a los usuarios registrarse antes de acceder al juego.

**Criterios de Aceptación:**

- Interfaz de registro intuitiva y fácil de usar.
- Los usuarios deben proporcionar un nombre de usuario único y una contraseña segura.
- Validación de campos para garantizar la integridad de la información ingresada.
- Almacenamiento seguro de la información de usuario en la base de datos.
  
### 3. Sistema de Puntuación
**Requisito:** El sistema debe calcular y mostrar la puntuación de los jugadores durante el juego.

**Criterios de Aceptación:**

- Cada vez que un jugador regenera una imagen con éxito, se le otorga una cantidad específica de puntos.
- Los puntos deben acumularse a lo largo del juego y mostrarse en tiempo real.
- La puntuación máxima posible debe ser claramente establecida y comunicada a los jugadores.
- El sistema debe registrar las puntuaciones más altas y mostrarlas en una tabla de clasificación.

### 4. Gestión de Sesiones de Juego
**Requisito:** El sistema debe administrar las sesiones de juego de manera efectiva.

**Criterios de Aceptación:**

- Los jugadores pueden iniciar una sesión de juego nueva en cualquier momento después de iniciar sesión.
- La sesión de juego debe poder suspenderse y reanudarse más tarde.
- El sistema debe controlar el tiempo de inactividad y cerrar automáticamente las sesiones inactivas después de un período definido.
- Los jugadores deben poder ver un historial de sus sesiones de juego anteriores.
