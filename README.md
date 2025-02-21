# Trivial Futurista

Este es un proyecto de **Trivial Interactivo** que consume una **API REST pública** para obtener preguntas de trivial en diferentes categorías. La aplicación está diseñada con una interfaz moderna, incluyendo un temporizador para responder a cada pregunta.

---

## Funcionalidades
- **Pantalla de bienvenida:** Solicita el nombre del usuario antes de empezar a jugar.
- **Selección de categoría:** El usuario puede elegir entre diferentes categorías de preguntas (ej. Películas, Geografía).
- **Juego interactivo:** 
  - Preguntas de opción múltiple.
  - Temporizador de 10 segundos para responder cada pregunta.
  - Puntaje acumulativo en tiempo real.
- **Pantalla de resultados:** Muestra el puntaje final con opción de volver a jugar o cerrar sesión.
- **Diseño:** Con efectos de transparencia.

---

## Tecnologías Utilizadas
- **HTML**: Estructura de la aplicación.
- **CSS**: Diseño y efectos visuales.
- **JavaScript**: 
  - Llamadas asíncronas a la API REST usando `fetch`.
  - Manipulación dinámica del DOM.
  - Temporizador para las preguntas.

---

## API REST Utilizada
Se utiliza la **Open Trivia Database** para obtener preguntas aleatorias en diferentes categorías:
- [Open Trivia Database](https://opentdb.com/api_config.php)


