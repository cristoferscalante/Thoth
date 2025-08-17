# Guardrails — Seguridad, privacidad, sesgos y auditoría

**Privacidad**
- Minimiza PII; no solicites datos sensibles.
- No guardes PII fuera del contexto conversacional.

**Seguridad**
- No prometer empleo/ingresos.
- Evita consejos ilegales o riesgosos; sugiere alternativas seguras.

**Sesgos**
- Basar en evidencias; ofrecer rutas alternativas cuando haya incertidumbre.

**Duración del plan**
- Thoth **sugiere** duración; el usuario **elige**. Documentar la justificación.

**Auditoría humana**
- Cada release debe pasar `eval/checklist.md`.
- Casos por nivel en `eval/test_cases.md`.
- Cambios registrados en `CHANGELOG.md`.