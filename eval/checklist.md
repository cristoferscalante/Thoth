# Checklist de auditoría

## 1. Onboarding ≤5 preguntas
- [ ] **Máximo 5 preguntas realizadas** durante el onboarding inicial
- [ ] **Preguntas cubren áreas clave**: motivación, experiencia previa, disponibilidad, preferencias
- [ ] **Respuestas documentadas** para personalización posterior
- [ ] **Tono conversacional** mantenido (no interrogatorio)
- [ ] **Transición natural** hacia la evaluación de nivel

### Criterios de validación:
- ✅ Número de preguntas ≤ 5
- ✅ Información suficiente para personalización
- ✅ Usuario se siente cómodo y motivado

## 2. Sondas de nivel aplicadas y justificadas
- [ ] **Mínimo 3 áreas evaluadas** (de las 5 disponibles: lógica, práctica, herramientas, datos, sistemas)
- [ ] **Preguntas principales y de seguimiento** realizadas según level_probe.md
- [ ] **Justificación clara** de por qué se eligieron esas áreas específicas
- [ ] **Adaptación durante evaluación** basada en respuestas del usuario
- [ ] **Evidencia documentada** de las respuestas para scoring

### Criterios de validación:
- ✅ Al menos 3/5 áreas evaluadas
- ✅ Preguntas siguen el formato establecido
- ✅ Justificación alineada con perfil del usuario
- ✅ Scoring basado en criterios objetivos

## 3. Nivel detectado y umbrales citados
- [ ] **Puntuación promedio calculada** (escala 0.0-5.0)
- [ ] **Clasificación asignada**: Básico (0.0-2.4), Medio (2.5-3.9), Avanzado (4.0-5.0)
- [ ] **Referencias específicas** a level_thresholds.yml
- [ ] **Cálculo basado en** promedio ponderado por ruta (skills_matrix.yml)
- [ ] **Fortalezas identificadas** por área evaluada
- [ ] **Áreas de mejora señaladas** con evidencia

### Criterios de validación:
- ✅ Puntuación justificada con evidencia
- ✅ Clasificación coherente con umbrales del proyecto (0.0-2.4/2.5-3.9/4.0-5.0)
- ✅ Referencias correctas a level_thresholds.yml y skills_matrix.yml
- ✅ Balance entre fortalezas y áreas de mejora

## 4. Top-3 rutas con razones y riesgos
- [ ] **Exactamente 3 rutas recomendadas** del tracks.yml
- [ ] **Razones específicas** para cada ruta basadas en:
  - Nivel detectado
  - Intereses manifestados
  - Contexto colombiano
  - Oportunidades de mercado
- [ ] **Riesgos identificados** para cada ruta:
  - Complejidad vs nivel actual
  - Demanda de tiempo
  - Requisitos previos faltantes
- [ ] **Orden de prioridad justificado**

### Criterios de validación:
- ✅ 3 rutas diferentes y relevantes
- ✅ Razones alineadas con evaluación
- ✅ Riesgos realistas y específicos
- ✅ Priorización clara y justificada

## 5. Sugerencia de duración + pros/contras
- [ ] **Duración específica propuesta** (ej: 100 días, 6 meses, 1 año)
- [ ] **Justificación basada en**:
  - Nivel actual del usuario
  - Disponibilidad de tiempo declarada
  - Complejidad de la ruta elegida
  - Objetivos de empleabilidad
- [ ] **Pros claramente listados** (mínimo 2)
- [ ] **Contras honestamente presentados** (mínimo 2)
- [ ] **Alternativas de duración** mencionadas si aplica

### Criterios de validación:
- ✅ Duración realista y específica
- ✅ Justificación sólida y personalizada
- ✅ Balance honesto de pros y contras
- ✅ Consideración de alternativas

## 6. Plan adaptado al nivel/ritmo
- [ ] **Referencia específica** a plan_blueprints.yml
- [ ] **Adaptaciones evidentes** basadas en:
  - Nivel detectado (básico/medio/avanzado)
  - Ritmo preferido del usuario
  - Disponibilidad de tiempo
  - Fortalezas y debilidades identificadas
- [ ] **Estructura clara** del plan (fases, hitos, entregas)
- [ ] **Recursos específicos** asignados por fase
- [ ] **Métricas de progreso** definidas

### Criterios de validación:
- ✅ Plan claramente personalizado
- ✅ Adaptaciones justificadas
- ✅ Estructura lógica y progresiva
- ✅ Recursos apropiados para el nivel

## 7. Próximos 7 días claros
- [ ] **Tareas específicas** para la primera semana
- [ ] **Orden cronológico** de actividades
- [ ] **Tiempo estimado** por tarea
- [ ] **Recursos necesarios** identificados
- [ ] **Criterios de éxito** para cada tarea
- [ ] **Punto de control** al final de la semana

### Criterios de validación:
- ✅ Tareas concretas y accionables
- ✅ Carga de trabajo realista
- ✅ Progresión lógica
- ✅ Claridad en expectativas

## 8. CHANGELOG actualizado
- [ ] **Entrada nueva** en CHANGELOG.md
- [ ] **Fecha de la sesión** registrada
- [ ] **Cambios principales** documentados:
  - Nivel asignado
  - Ruta recomendada
  - Plan creado
  - Personalizaciones aplicadas
- [ ] **Formato consistente** con entradas anteriores

### Criterios de validación:
- ✅ Entrada completa y fechada
- ✅ Información relevante capturada
- ✅ Formato estándar mantenido

## Criterios generales de calidad

### Coherencia del proceso
- [ ] **Flujo lógico** desde onboarding hasta plan final
- [ ] **Consistencia** entre evaluación y recomendaciones
- [ ] **Personalización evidente** en todas las etapas
- [ ] **Tono Thoth** mantenido durante toda la sesión

### Documentación y trazabilidad
- [ ] **Decisiones justificadas** con evidencia
- [ ] **Referencias correctas** a archivos del sistema
- [ ] **Información suficiente** para auditoría posterior
- [ ] **Formato profesional** y claro

### Experiencia del usuario
- [ ] **Sesión fluida** sin interrupciones técnicas
- [ ] **Usuario motivado** al final del proceso
- [ ] **Expectativas claras** establecidas
- [ ] **Próximos pasos** evidentes y accionables