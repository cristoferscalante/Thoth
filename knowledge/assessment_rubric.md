# Rúbrica de evaluación

> Sistema de puntajes para priorizar rutas y generar planes ajustados al **nivel real** del/la aprendiz.

---

## 🟠 Escala de puntajes (0–5)

| Puntaje | Descripción breve              | Evidencia típica                                     |
|------:|---------------------------------|------------------------------------------------------|
| **5** | Dominio sólido, autónomo        | Resuelve mini-reto óptimo y explica trade-offs       |
| **4** | Bueno, pocos detalles por pulir | Solución correcta; mejoras menores de estilo/perf    |
| **3** | Aceptable, requiere guía        | Resuelve con pistas; faltan pruebas/estructura       |
| **2** | Débil, bases incompletas        | Errores frecuentes; confusión en conceptos clave     |
| **1** | Muy básico, necesita refuerzo   | No completa reto; conceptos aislados                 |
| **0** | Sin evidencia                   | Omite respuesta o fuera de tema                      |

**Cálculo por ruta:** promedio **ponderado** (ver `knowledge/skills_matrix.yml`).  
**Nivel global:** según umbrales en `knowledge/level_thresholds.yml` (p. ej., **Básico < 50**, **Intermedio 50–79**, **Avanzado ≥ 80**).

---

## 🟡 Criterios (ejemplo)

- **Fundamentos** (sintaxis, conceptos base)
- **Resolución de problemas** (lógica, complejidad)
- **Buenas prácticas** (estilo, testing, legibilidad)
- **Arquitectura / Diseño** (patrones, modularidad)
- **Datos / BD** (SQL/NoSQL, modelos)
- **DevOps / Sistemas** (Git, CLI, contenedores)
- **Seguridad** (OWASP básico, higiene)
- **Entrega / Comunicación** (claridad, trazabilidad)

> Los **pesos** de cada criterio se definen en `skills_matrix.yml`.

---

## 🟢 Cálculo

**Fórmula (ASCII):** `score_ruta = sum(w_i * p_i) / sum(w_i)`

- Empates: desempatar por **viabilidad** (tiempo/recursos declarados).
- Transparencia: anotar la **evidencia** que respalda cada puntaje (quiz, repo, mini-reto).

---

## 🧭 Salida estándar

- **🏆 Top-3 rutas** — con **2–3 razones** y **1–2 riesgos + mitigaciones** cada una.
- **📈 Nivel detectado** — Básico / Intermedio / Avanzado (e implicaciones en profundidad).
- **⏱️ Duración sugerida (2 opciones)** — pros/contras ligados a su **ritmo**.
- **🗓️ Acciones para 7 días** — 3 tareas **SMART** + **primer checkpoint**.

---

## 🧭 Plantilla de salida (resumen)

> Usa este formato para presentar la recomendación de forma consistente.

- **Nivel:** `Intermedio (68/100)`
- **Ruta 1 (recomendada):** `Frontend Profesional`
  - **Razones:** • disponibilidad 10 h/sem • base en JS sólida • preferencia UI/UX
  - **Riesgos/Mitigación:** • testing bajo → `módulo TDD semana 2`
- **Ruta 2:** `Backend con Node.js` | **Ruta 3:** `Data Foundations`
- **Duración sugerida:**
  - **A. 12 semanas** — + momentum / − carga alta
  - **B. 16 semanas** — + sostenible / − calendario mayor
- **Semana 1 (SMART):**
  1. Implementar landing accesible (A11y básico)
  2. Configurar tests unitarios iniciales
  3. Publicar demo (Vercel) + enlace a repo

**Checkpoint:** viernes — demo + cobertura mínima

---

## ✅ Criterios de calidad del informe

- **Coherencia:** cada recomendación referencia **datos del diagnóstico** (p. ej., “Disponibilidad: 10 h/sem”).
- **Trazabilidad:** incluir enlaces a **repo/quiz/evidencia**.
- **Claridad:** lenguaje profesional y cercano; bullets breves.
- **Accionable:** siempre incluir **próximos pasos** y **mitigaciones**.
