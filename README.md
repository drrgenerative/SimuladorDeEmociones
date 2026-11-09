# Brújula Emocional 🧭

Simulador de situaciones de la vida para practicar estrategias de manejo emocional, pensado para estudiantes de grado sexto.

Es una sola página (`index.html`), sin dependencias ni servidor: funciona en computadores de la sala de sistemas, tabletas y celulares. El progreso de cada estudiante se guarda solo en su navegador.

## Qué incluye

- **12 situaciones** del colegio, la casa y las redes (conflictos en el descanso, una mala nota, exposiciones, exclusión en WhatsApp, ciberacoso, presión de grupo, discusiones en casa…).
- En cada situación el estudiante **nombra lo que sentiría**, lo mide en un **termómetro emocional** (1 a 5) y **elige qué haría**. Si marca 4 o 5, el simulador le propone primero una respiración guiada.
- Las respuestas se clasifican con un **semáforo**: rojo (en caliente), amarillo (evitar) y verde (en calma). Cada opción muestra sus consecuencias, sin regaños.
- **Caja de herramientas** con 11 estrategias: semáforo, respiración del globo, ponerle nombre a la emoción, voz amable, mensaje yo, tiempo fuera, empatía, decir no, ciberescudo, 5-4-3-2-1 y pedir ayuda.
- **Mi plan de calma** imprimible (señal de alerta, 3 herramientas, 3 adultos de confianza).
- **Guía para docentes** con una sesión sugerida de 50 minutos y preguntas de reflexión.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo, `brujula-emocional`).
2. Sube los archivos `index.html` y `README.md` (botón **Add file → Upload files**).
3. Ve a **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`. Guarda.
5. En uno o dos minutos el simulador quedará en `https://TU-USUARIO.github.io/brujula-emocional/`.

## Personalizar

Abre `index.html` y busca la lista `SITUACIONES`. Cada situación tiene:

- `titulo`, `ico` (emoji), `lugar` y `texto`
- `emociones`: las emociones esperables
- `opciones`: tres respuestas con `tipo` (`verde`, `amarillo` o `rojo`), `texto` y `resultado`
- `herramientas`: las estrategias asociadas
- `frase`: una frase modelo para practicar en voz alta
- `reflexion`: una pregunta para discutir en clase

## Importante

Es una herramienta pedagógica y no reemplaza la atención de orientación escolar. Si un estudiante revela una situación de riesgo, active la Ruta de Atención Integral para la Convivencia Escolar.

Líneas de apoyo: **Línea 106** (Bogotá, gratuita, 24 horas; WhatsApp 300 754 8933) · **Línea 141** del ICBF (nacional) · **123** emergencias.
