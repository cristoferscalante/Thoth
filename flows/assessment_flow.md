# Flujo: diagnóstico (incluye nivel)


> Objetivo: identificar motivación, contexto y nivel del/la aprendiz para proponer **Top-3 rutas** y un **plan adaptado** (duración, profundidad y ritmo).

## 0. Preparación (breve)
**Finalidad:** aclarar alcance, uso de datos y tiempos.
- Mensaje de bienvenida (30–45 s) y consentimiento de uso de respuestas para personalización.
- Aviso: diagnóstico 3–5 min, máx. 5 preguntas de onboarding.

## 1. Saludo y encuadre
**Finalidad:** alinear expectativas.
- Qué hará Thoth y qué obtendrá el usuario (rutas + plan).
- Cómo puede detener o pausar el proceso.

## 2. Onboarding (≤ 5 preguntas)
**Entradas:** motivación, experiencia previa, disponibilidad, preferencias, restricciones.  
**Salida:** perfil inicial (metadata de diagnóstico).

## 3. Level probes + mini-retos
**Fuente:** `prompts/level_probe.md`.  
**Finalidad:** evidenciar dominio real (fundamentos, resolución de problemas, buenas prácticas).
- 1–2 micro-preguntas + 1 mini-reto breve.
- **Salida:** puntajes parciales por área (0–100).

## 4. Puntajes y nivel
**Finalidad:** clasificar **Básico / Intermedio / Avanzado** con umbrales claros.  
**Salida:** tabla de puntajes + nivel global + notas por área.
- Ejemplo de umbrales: B \< 50, I 50–79, A ≥ 80 (ajustables por área).

## 5. Top-3 rutas recomendadas
**Finalidad:** orientar decisión informada.
- Para cada ruta: **2–3 razones** (trazables a respuestas/puntajes) + **riesgos** y **mitigaciones**.
- Mostrar compatibilidad con motivación y disponibilidad.

## 6. Sugerencia de duración
**Finalidad:** ajustar carga y horizonte temporal.
- Opciones: **8 / 12 / 16 / 24 semanas** o **30 / 60 / 100 días**.
- Recomendar **horas/semana** (5 / 10 / 20 h) y ritmo (fundamentos → proyectos → validación).

## 7. Confirmación del usuario → reparametrizar plan
**Finalidad:** personalizar antes de generar el plan final.
- El usuario elige **ruta + duración**.
- Thoth reconfigura profundidad, hitos y recursos en función de la elección.

## 8. Plan y próximos 7 días
**Salida:** plan estructurado + micro-plan semanal inicial.
- **Hitos por semana**, recursos curados, criterios de finalización.
- **3 próximos pasos accionables** y primer checkpoint.

---