# DetectorIA · ITED

**Un asistente académico en español para revisar y fortalecer tesis y artículos científicos, sección por sección.**

Creado por **Dr. Gerardo Ch. Chinguel (ITED)**.

## Qué contiene este proyecto

Las instrucciones de DetectorIA para una Gema de Google Gemini. Es un agente configurado mediante instrucciones en Markdown; este repositorio no incluye una aplicación ejecutable ni un detector estadístico de autoría.

**[Abrir las instrucciones completas](DetectorIA_ITED.md)**

## Qué hace

- Revisa claridad, precisión, argumentación y coherencia académica.
- Examina citas, referencias y afirmaciones que requieren verificación.
- Aplica criterios pertinentes a tesis y artículos científicos.
- Entrega un checklist con evidencia localizada, qué mejorar, cómo corregirlo y un ejemplo breve.
- Distingue entre cumplimiento, cumplimiento parcial, incumplimiento, información no verificable y criterios no aplicables.
- Interpreta reportes de similitud cuando el usuario aporta la información necesaria.

## Cómo utilizarlo

1. Abre `DetectorIA_ITED.md` y copia su contenido completo.
2. Crea una Gema en Gemini y utiliza ese contenido como instrucciones. Si la interfaz limita su extensión, utiliza las opciones de conocimiento disponibles y comprueba que la Gema pueda consultar el documento completo.
3. Adjunta una tesis, artículo o sección que tengas autorización para procesar.
4. Indica la sección que deseas revisar y, para tesis, el rango de páginas.
5. Revisa el checklist y elige un hallazgo para recibir orientación puntual.
6. Contrasta las recomendaciones y verifica las fuentes antes de incorporarlas al trabajo.

Ejemplo de solicitud:

> Revisa la introducción de mi tesis, páginas 4 a 7. Evalúa la delimitación del problema, el sustento de las afirmaciones y la coherencia con el objetivo. Si falta información, indícala como no verificable.

## Alcance y límites

Los patrones de estilo no prueban que un texto haya sido escrito por IA. DetectorIA está orientado a la mejora académica y no debe utilizarse como prueba de autoría, plagio o falta disciplinaria. No ofrece porcentajes fiables de detección de IA ni garantiza publicación o aprobación de una tesis.

Las referencias y los datos requieren comprobación externa. El resultado depende del modelo, los materiales disponibles y el contexto. DetectorIA se publica como base para evaluación comunitaria; no se presentan métricas de precisión ni validación experimental.

## Valora el proyecto y ayuda a mejorarlo

- **Dale una estrella (Star)** si te resulta útil.
- **[Comparte tu experiencia o una sugerencia](https://github.com/centroited/DetectorIA-ITED/issues/new)**: describe la versión utilizada, el tipo de sección, qué funcionó y qué mejorarías.
- **[Reporta un problema](https://github.com/centroited/DetectorIA-ITED/issues/new)**: incluye una muestra breve anonimizada, la respuesta obtenida y el comportamiento esperado.
- Propón cambios mediante un pull request. Consulta [cómo contribuir](CONTRIBUTING.md).

Para valorar una prueba, puedes puntuar del 1 al 5 la claridad del reporte, la pertinencia de los hallazgos y la utilidad de las correcciones. Añade un ejemplo que explique tu valoración. Estas valoraciones son experiencias de uso, no una medición de precisión científica.

**No publiques tesis completas, datos personales, documentos confidenciales ni material de terceros sin autorización.** Usa ejemplos ficticios o anonimizados en los espacios públicos.

## Próximas mejoras propuestas

- Reducir repeticiones y contradicciones en las instrucciones.
- Ofrecer reportes breves sin perder cobertura.
- Mejorar el manejo de secciones extensas y de información ya proporcionada.
- Construir casos de prueba públicos y anonimizados para comparar versiones.

## Autoría

**Dr. Gerardo Ch. Chinguel — ITED** · [ited.education](https://ited.education/)

El agente se publica con una denominación unificada, sin sufijo de versión. Consulta el [historial de cambios](CHANGELOG.md).
