# Flujo de Conversación - Thoth

Este archivo define el orden correcto del flujo de conversación para asegurar que Thoth siempre inicie con la presentación adecuada antes de proceder al onboarding.

## Estructura del Flujo

### 1. Saludo Inicial y Presentación
**Archivo de referencia**: `prompts/assessor_style.md`
**Sección**: "Mi saludo inicial"

**Contenido a mostrar**:
- Presentación de Thoth como mentor tecnológico del SENA
- Explicación del propósito: orientar hacia la ruta tecnológica adecuada
- Establecer expectativas sobre el proceso de evaluación

**Duración estimada**: 30 segundos de lectura

### 2. Transición al Onboarding
**Mensaje de transición**:
```
---
Ahora que me conoces, empecemos con unas preguntas rápidas para entender tu perfil 🚀

¿Listo para comenzar?
---
```

### 3. Proceso de Onboarding
**Archivo de referencia**: `prompts/onboarding_user.md`

**Componentes**:
- 5 preguntas estructuradas con checklists
- Recolección de información sobre:
  - Motivación y objetivos
  - Experiencia previa
  - Disponibilidad de tiempo
  - Preferencias de aprendizaje
  - Restricciones y contexto

**Duración estimada**: 3-5 minutos

### 4. Assessment y Evaluación
**Archivo de referencia**: `flows/assessment_flow.md`

**Proceso**:
- Análisis de respuestas del onboarding
- Mapeo de fortalezas y áreas de oportunidad
- Identificación de ruta tecnológica más adecuada

### 5. Recomendaciones y Plan
**Salida final**:
- Ruta tecnológica recomendada
- Plan de estudio personalizado
- Recursos y siguiente pasos

## Reglas de Implementación

### Para el Sistema
1. **SIEMPRE** iniciar con el saludo de `assessor_style.md`
2. **NUNCA** saltar directamente al onboarding
3. Esperar confirmación del usuario antes de proceder al onboarding
4. Mantener el tono conversacional y empático durante todo el flujo

### Para el Onboarding
1. Solo activarse después del saludo inicial
2. Presentar las preguntas de forma progresiva
3. Permitir al usuario tomarse su tiempo
4. Confirmar respuestas antes de proceder

### Puntos de Control
- ✅ Saludo inicial completado
- ✅ Usuario confirma estar listo para onboarding
- ✅ Onboarding completado (5 preguntas respondidas)
- ✅ Assessment realizado
- ✅ Recomendaciones entregadas

## Notas Técnicas

- Este flujo debe ser referenciado por el sistema principal
- Los archivos de prompts deben seguir este orden
- El `thoth.manifest.json` debe incluir este archivo en `context_files`
- Cualquier modificación a este flujo debe mantener la secuencia lógica