# Casos de prueba (por nivel)

## A — Básico con 5h/sem (Frontend)

### Perfil del usuario
- **Experiencia**: Poco o nada de código, quizás HTML/CSS básico
- **Motivación**: Alta, busca cambio de carrera
- **Disponibilidad**: 5 horas/semana (noches y fines de semana)
- **Recursos**: PC limitada, conexión básica a internet
- **Contexto**: Vive en ciudad intermedia de Colombia

### Señales esperadas en evaluación
- **Lógica**: Resuelve problemas simples pero se confunde con algoritmos
- **Práctica**: No ha construido proyectos completos
- **Herramientas**: Conoce navegador, no Git ni terminal
- **Datos**: No experiencia con bases de datos
- **Sistemas**: No conoce conceptos de arquitectura

### Respuestas típicas del assessment
- **Onboarding**: "Quiero aprender a crear páginas web", "Trabajo en oficina pero quiero programar"
- **Nivel probe**: Puntuación 0.5-2.0 en áreas técnicas, 4.0+ en motivación
- **Preferencias**: Visual, paso a paso, proyectos tangibles

### Resultado esperado
- **Nivel detectado**: Básico (promedio 0.0-2.4)
- **Ruta recomendada**: Frontend Web (HTML/CSS/JS)
- **Duración sugerida**: 12-16 semanas
- **Plan adaptado**: 
  - Fundamentos de programación
  - HTML/CSS desde cero
  - JavaScript básico
  - Proyecto: Landing page personal
- **Próximos 7 días**: Configurar entorno, tutorial HTML básico

### Criterios de validación
- ✅ Nivel Básico asignado correctamente
- ✅ Duración realista para disponibilidad limitada
- ✅ Plan accesible sin herramientas complejas
- ✅ Proyecto final alcanzable

## B — Medio con 10h/sem (Datos/Backend)

### Perfil del usuario
- **Experiencia**: Python básico, SQL de cursos online
- **Motivación**: Alta, quiere especializarse en datos
- **Disponibilidad**: 10 horas/semana (dedicación constante)
- **Recursos**: PC decente, acceso a herramientas
- **Contexto**: Profesional en Bogotá/Medellín

### Señales esperadas en evaluación
- **Lógica**: Resuelve algoritmos básicos, entiende estructuras de datos
- **Práctica**: Ha hecho scripts simples, conoce funciones
- **Herramientas**: Usa Python, conoce pandas básico
- **Datos**: Entiende SQL SELECT, ha trabajado con CSV
- **Sistemas**: Conceptos básicos de APIs

### Respuestas típicas del assessment
- **Onboarding**: "Trabajo con Excel pero quiero automatizar", "Me gustan los datos"
- **Nivel probe**: Puntuación 2.5-3.5 en áreas técnicas
- **Preferencias**: Proyectos con datos reales, automatización

### Resultado esperado
- **Nivel detectado**: Medio (promedio 2.5-3.9)
- **Ruta recomendada**: Data Engineering o Backend Development
- **Duración sugerida**: 8-12 semanas
- **Plan adaptado**:
  - Python intermedio
  - Bases de datos relacionales
  - APIs REST básicas
  - Proyecto: Pipeline ETL + API CRUD
- **Próximos 7 días**: Configurar PostgreSQL, ejercicios SQL avanzado

### Criterios de validación
- ✅ Nivel Medio asignado correctamente
- ✅ Ruta alineada con experiencia previa
- ✅ Proyecto integra múltiples tecnologías
- ✅ Duración permite profundización

## C — Avanzado con 20h/sem (Cloud/Security)

### Perfil del usuario
- **Experiencia**: Administrador de sistemas, conoce Linux
- **Motivación**: Especialización en seguridad/DevOps
- **Disponibilidad**: 20 horas/semana (tiempo completo de estudio)
- **Recursos**: Múltiples PCs, acceso a cloud
- **Contexto**: Profesional senior buscando transición

### Señales esperadas en evaluación
- **Lógica**: Resuelve problemas complejos, piensa en arquitectura
- **Práctica**: Ha construido sistemas, conoce patrones
- **Herramientas**: Domina terminal, Git, ha usado Docker
- **Datos**: Entiende bases de datos, optimización
- **Sistemas**: Conoce redes, servidores, conceptos de seguridad

### Respuestas típicas del assessment
- **Onboarding**: "Administro servidores pero quiero seguridad", "Conozco Docker básico"
- **Nivel probe**: Puntuación 4.0+ en múltiples áreas
- **Preferencias**: Retos técnicos, infraestructura, automatización

### Resultado esperado
- **Nivel detectado**: Avanzado (promedio 4.0-5.0)
- **Ruta recomendada**: Cloud Security o DevSecOps
- **Duración sugerida**: 8 semanas o 60 días intensivos
- **Plan adaptado**:
  - Hardening de sistemas
  - Detección de amenazas
  - CI/CD con seguridad
  - Proyecto: Pipeline seguro con monitoreo
- **Próximos 7 días**: Configurar lab de seguridad, análisis de vulnerabilidades

### Criterios de validación
- ✅ Nivel Avanzado asignado correctamente
- ✅ Duración intensiva apropiada
- ✅ Plan desafiante pero alcanzable
- ✅ Proyecto de nivel profesional

---

## Casos límite y escenarios de error

### D — Usuario sobrestimado (Edge Case)

**Perfil**: Dice tener "experiencia en programación" pero solo ha hecho cursos online

**Señales contradictorias**:
- **Onboarding**: "Sé programar en varios lenguajes"
- **Nivel probe**: No puede explicar conceptos básicos, puntuación 1.0-2.0
- **Expectativas**: Quiere "desarrollo avanzado" inmediatamente

**Resultado esperado**:
- **Detección correcta**: Nivel Básico a pesar de claims
- **Manejo de expectativas**: Explicación clara del nivel real
- **Plan realista**: Fundamentos antes de avanzar
- **Validación**: ✅ Sistema detecta inconsistencias

### E — Usuario subestimado (Edge Case)

**Perfil**: Modesto sobre sus habilidades pero tiene experiencia sólida

**Señales contradictorias**:
- **Onboarding**: "Solo sé un poco de programación"
- **Nivel probe**: Resuelve problemas complejos, puntuación 3.5-4.5
- **Experiencia real**: Años de desarrollo pero sin título formal

**Resultado esperado**:
- **Detección correcta**: Nivel Medio/Avanzado basado en evidencia
- **Reconocimiento**: Validación de habilidades reales
- **Plan apropiado**: Desafío acorde a capacidades
- **Validación**: ✅ Sistema prioriza evidencia sobre claims

### F — Disponibilidad irreal (Error Case)

**Perfil**: Promete más tiempo del que realmente tiene

**Señales de alerta**:
- **Onboarding**: "Puedo dedicar 40 horas/semana"
- **Contexto real**: Trabajo tiempo completo + familia
- **Expectativas**: Quiere "terminar rápido"

**Resultado esperado**:
- **Detección de riesgo**: Guardrails activados
- **Ajuste realista**: Plan para 10-15 horas/semana máximo
- **Advertencia clara**: Sobre consecuencias de sobrecarga
- **Validación**: ✅ Sistema protege al usuario de burnout

### G — Recursos insuficientes (Error Case)

**Perfil**: Quiere ruta que requiere recursos que no tiene

**Limitaciones**:
- **Hardware**: PC muy antigua, RAM limitada
- **Conectividad**: Internet intermitente
- **Económicas**: No puede pagar herramientas premium

**Resultado esperado**:
- **Adaptación automática**: Ruta con herramientas gratuitas
- **Alternativas claras**: Opciones de bajo recurso
- **Plan B**: Ruta alternativa si recursos mejoran
- **Validación**: ✅ Sistema considera limitaciones reales

### H — Motivación inconsistente (Warning Case)

**Perfil**: Señales mixtas sobre compromiso real

**Indicadores de riesgo**:
- **Onboarding**: Respuestas vagas sobre motivación
- **Expectativas**: "Quiero ganar dinero rápido"
- **Compromiso**: Evade preguntas sobre dedicación

**Resultado esperado**:
- **Evaluación cuidadosa**: Más preguntas de motivación
- **Plan conservador**: Duración más larga, hitos frecuentes
- **Seguimiento**: Puntos de control más frecuentes
- **Validación**: ✅ Sistema identifica riesgos de abandono

---

## Métricas de validación del sistema

### Precisión de clasificación
- **Target**: >90% de usuarios correctamente clasificados
- **Medición**: Comparación con evaluación manual experta
- **Casos críticos**: Especial atención a casos límite D y E

### Satisfacción del usuario
- **Target**: >85% considera el plan "realista y útil"
- **Medición**: Encuesta post-assessment
- **Indicadores**: Claridad, relevancia, factibilidad

### Tasa de completación
- **Target**: >70% completa al menos 50% del plan
- **Medición**: Seguimiento a 4 semanas
- **Factores**: Duración sugerida vs real, recursos vs necesidades

### Detección de riesgos
- **Target**: >95% de casos F, G, H identificados correctamente
- **Medición**: Revisión manual de casos con señales de alerta
- **Acción**: Activación de guardrails apropiados

### Coherencia interna
- **Target**: 100% de assessments pasan checklist de auditoría
- **Medición**: Aplicación automática de checklist.md
- **Criterios**: Alineación nivel-ruta-plan-duración

---

## Instrucciones para testing

1. **Ejecutar casos A, B, C**: Validar funcionamiento normal
2. **Probar casos límite D, E**: Verificar robustez del sistema
3. **Simular errores F, G, H**: Confirmar activación de guardrails
4. **Medir métricas**: Aplicar criterios de validación
5. **Documentar resultados**: Registrar en CHANGELOG.md

**Frecuencia recomendada**: Testing completo cada 2 semanas o después de cambios significativos al sistema.