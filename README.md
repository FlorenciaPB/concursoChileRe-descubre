# 🗿 Memorice Ancestral: Momias Chinchorro
Proyecto Final Unidad 3 — Taller de Diseño de Interfaces 
**Postulación Concurso *Chile Re-Descubre*

---

## 📌 Tema Elegido
**Momias Chinchorro** — Hito seleccionado de la categoría *Patrimonio, Naturaleza y Ciencia Básica* del libro *"Hecho en Chile. 50 ideas, descubrimientos e innovaciones"*.

---

## 💡 Descripción Conceptual
**Memorice Ancestral: Momias Chinchorro** es una experiencia web interactiva de divulgación patrimonial que combina mecánicas de memoria visual con **Interacción Natural (NUI)** mediante visión por computador.

A través de un tablero de 12 fichas (6 parejas), el usuario descubre los fundamentos científicos, materiales y sociales de la momificación artificial más antigua del mundo. Al completar los pares, el jugador enfrenta una prueba de retención conceptual para consolidar el aprendizaje.

---

## 🎮 Instrucciones de Uso e Interacción

### 1. Ejecución en Navegador
1. Ingresa al prototipo desplegado en **GitHub Pages** o abre `index.html` mediante un servidor local (`Live Server` o `python -m http.server`).
   > **Nota:** Para activar la cámara web, el navegador requiere contexto seguro (`HTTPS` o `localhost`).
2. Selecciona **📷 Jugar con Cámara (MediaPipe)** para usar control gestual o **🖱️ Jugar con Mouse / Táctil** como modo alternativo.

### 2. Controles Gestuales (Módulo 01 — MediaPipe Hands)
- **Desplazar cursor (`🖐️`):** Mueve tu mano abierta frente a la cámara web para apuntar sobre las fichas del tablero.
- **Voltear ficha (`✊`):** Cierra el puño o junta los dedos pulgar e índice (gesto de pinza) sobre la ficha seleccionada para girarla.

### 3. Dinámica del Juego
1. **Búsqueda de pares:** Encuentra las 6 parejas temáticas.
2. **Cápsulas de divulgación:** Cada pareja encontrada despliega brevemente su palabra clave junto a un dato científico antes de ocultarse.
3. **Prueba de memoria final:** Al despejar el tablero, escribe los 6 conceptos descubiertos para evaluar tu retención y revisar tus métricas de tiempo e intentos.

---

## 🛠️ Tecnologías Empleadas
- **MediaPipe Hands & Camera Utils:** Detección y seguimiento en tiempo real de 21 puntos clave (*landmarks*) de la mano para reconocimiento de posición y gestos sin contacto.
- **HTML5 & JavaScript (ES6+):** Arquitectura modular del juego, lógica de estados, validación de respuestas y cronómetro.
- **Tailwind CSS:** Interfaz responsiva con estética inspirada en el desierto costero del norte de Chile y animaciones 3D (`CSS 3D Transforms`).
- **Web Audio API:** Síntesis procedural de retroalimentación sonora para volteo de fichas, aciertos y finalización de partida.

---

## 🎥 Registro Audiovisual
- **Cápsula Audiovisual:** https://youtu.be/rbM7kDj_yPM?si=fhbGGuzcO4i-b1CA
---
