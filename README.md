# Thoth — Asistente de orientación profesional con planes adaptativos

**Propósito.** Ayudar a futuros especialistas de tecnología a encontrar la ruta profesional más afín y ejecutar un **plan de especialización adaptado** a su **nivel (básico/medio/avanzado)**, **profundidad** y **ritmo**. Thoth **sugiere** una duración (p. ej., 8/12/16/24 semanas o 30/60/100 días), **pero la decisión final es del usuario**.

**Usuarios objetivo.** Aprendices SENA (ADSO), estudiantes técnicos/tecnológicos, perfiles junior, instructores y mentores.

**Alcance.**
- Diagnóstico conversacional + mini‑assessment y **detección de nivel**.
- Mapeo de fortalezas a **2–3 rutas** (tracks) con riesgos y mitigaciones.
- **Generación de plan** 30/60/100 días o 8/12/16/24 semanas **ajustado por nivel y ritmo**.
- Seguimiento con métricas e iteración (re‑enrutamiento si cambian metas).
- Auditoría humana para seguridad, completitud y control de sesgos.

**No alcance.** No garantiza empleo; no sustituye orientación psicológica; no pide datos sensibles innecesarios; no promete ingresos.

## Cómo usar
1) Ejecuta **onboarding** → contexto, metas, tiempo disponible, restricciones.
2) Corre **assessment** → obtiene puntajes por criterio y **nivel** (básico/medio/avanzado).
3) Revisa **recomendaciones** → 2–3 rutas con explicación y **sugerencia de duración**.
4) El usuario elige duración; Thoth **adapta profundidad y ritmo**.
5) Genera **plan** + **proyecto aplicado (MVP)** + **métricas**.
6) Activa **seguimiento** semanal y ajustes.

## Estructura del repo
- `system.md`: instrucciones internas parametrizadas por nivel/ritmo.
- `guardrails.md`: límites y auditoría.
- `knowledge/`: RAG con reglas de nivel y blueprints de planes.
- `flows/`: diagnóstico, recomendación y seguimiento con control de nivel.
- `eval/`: casos por nivel, rúbrica y checklist.
- `templates/`: formatos reutilizables por duración y nivel.
- `config.json`: capacidades y metadatos.

## Roadmap (beta → estable)
- v0.2: Añadir `level_probe.md`, `level_thresholds.yml`, `plan_blueprints.yml`.
- v0.3: Planes por todas las rutas en 3 niveles, con ejemplos de MVP.
- v1.0: Assessment adaptativo + simulación de entrevistas + seguimiento automático.

## Enlaces relacionados

**Lógica**  
`https://github.com/cristoferscalante/thoth_logica.git`

**Thoth**  
`https://github.com/cristoferscalante/Thoth.git`

**IA**  
`https://chatgpt.com/g/g-68a136fe19848191ba1a1b3ac04d9fc1-thoth-asistente-de-orientacion-profesional`

## Contribuir
- Mantener fuentes y justificaciones en `knowledge/`.
- Respetar `guardrails.md` y cubrir **test_cases.md** antes de merge.