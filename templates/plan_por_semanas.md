# Plan {{duracion}} semanas — {{ruta}} (Nivel: {{nivel}}, Ritmo: {{horas_sem}} h/sem)

## Información del plan

**Ruta seleccionada:** {{ruta}} (`tracks.yml: {{track_key}}`)
**Nivel detectado:** {{nivel}} (según `level_thresholds.yml`)
**Duración:** {{duracion}} semanas
**Ritmo semanal:** {{horas_sem}} horas/semana
**Enfoque principal:** {{focus}}
**Proyecto objetivo:** {{proyecto_objetivo}}
**Fecha de inicio:** {{fecha_inicio}}
**Fecha estimada de finalización:** {{fecha_fin}}

---

## Objetivos por fases

### 🎯 Fase inicial (Semanas 1-{{fase1_end}})
**Objetivo:** Establecer fundamentos sólidos

**Metas específicas:**
- Configurar entorno de desarrollo completo
- Dominar conceptos básicos de {{ruta}}
- Completar {{ejercicios_fase1}} ejercicios fundamentales
- Crear {{proyectos_fase1}} mini-proyectos de práctica

**Criterios de éxito:**
- [ ] Entorno configurado y funcional
- [ ] Evaluación de fundamentos ≥ 70%
- [ ] {{proyectos_fase1}} proyectos funcionales en portfolio

### 🚀 Fase intermedia (Semanas {{fase2_start}}-{{fase2_end}})
**Objetivo:** Aplicar conocimientos en proyecto intermedio

**Metas específicas:**
- Desarrollar proyecto intermedio funcional
- Integrar {{tecnologias_intermedias}} tecnologías complementarias
- Implementar mejores prácticas de {{ruta}}
- Participar en {{code_reviews}} code reviews

**Criterios de éxito:**
- [ ] Proyecto intermedio desplegado
- [ ] Evaluación técnica ≥ 75%
- [ ] Feedback positivo de peers

### 🏆 Fase final (Semanas {{fase3_start}}-{{duracion}})
**Objetivo:** Completar proyecto objetivo y preparación profesional

**Metas específicas:**
- Finalizar {{proyecto_objetivo}} con todas las funcionalidades
- Optimizar rendimiento y experiencia de usuario
- Preparar portfolio profesional
- Practicar entrevistas técnicas

**Criterios de éxito:**
- [ ] {{proyecto_objetivo}} desplegado con métricas
- [ ] Portfolio profesional completo
- [ ] ≥ 80% éxito en entrevistas mock

---

## Hitos principales

### 📋 Hitos por cuartiles
- **{{milestone_1}}** (Semana {{milestone_1_week}})
- **{{milestone_2}}** (Semana {{milestone_2_week}})
- **{{milestone_3}}** (Semana {{milestone_3_week}})
- **{{milestone_4}}** (Semana {{milestone_4_week}})

### 🎯 Entregables clave
1. **Mini-proyectos** (Semanas 1-{{fase1_end}}): {{mini_projects_count}} proyectos básicos
2. **Proyecto intermedio** (Semanas {{fase2_start}}-{{fase2_end}}): Aplicación funcional
3. **{{proyecto_objetivo}}** (Semanas {{fase3_start}}-{{duracion}}): Proyecto final completo
4. **Portfolio profesional** (Semana {{duracion}}): Presentación de trabajos

---

## Desglose semanal detallado

{{#each semanas}}
### 📅 Semana {{numero}}: {{titulo}}

**Objetivos de la semana:**
- {{objetivo_1}}
- {{objetivo_2}}
- {{objetivo_3}}

**Horas programadas:** {{horas_semana}} horas
**Distribución:**
- Teoría/Lectura: {{horas_teoria}} h ({{porcentaje_teoria}}%)
- Práctica/Código: {{horas_practica}} h ({{porcentaje_practica}}%)
- Proyecto: {{horas_proyecto}} h ({{porcentaje_proyecto}}%)
- Review/Testing: {{horas_review}} h ({{porcentaje_review}}%)

**Entregables:**
- [ ] {{entregable_1}}
- [ ] {{entregable_2}}
- [ ] {{entregable_3}}

**Recursos de la semana:**
- 📖 Lectura: {{recurso_lectura}}
- 🎥 Video/Tutorial: {{recurso_video}}
- 💻 Herramienta: {{recurso_herramienta}}
- 🔗 Documentación: {{recurso_docs}}

**Evaluación:**
- Método: {{metodo_evaluacion}}
- Criterio: {{criterio_evaluacion}}
- Peso: {{peso_evaluacion}}% del total

**Checkpoint:**
{{#if checkpoint}}
🔍 **Evaluación intermedia**
- Tipo: {{checkpoint.tipo}}
- Duración: {{checkpoint.duracion}}
- Criterios: {{checkpoint.criterios}}
{{/if}}

---
{{/each}}

## Adaptaciones por nivel

### 📚 Nivel Básico (Score: 0.0-2.4)
**Enfoque:** Fundamentos sólidos con práctica guiada

**Adaptaciones específicas:**
- **Ritmo:** Más tiempo en conceptos fundamentales
- **Proyectos:** Plantillas y guías paso a paso
- **Stack:** Tecnologías estables y bien documentadas
- **Evaluación:** Más práctica, menos teoría abstracta
- **Soporte:** Mentoría semanal y recursos adicionales

**Distribución de tiempo:**
- Fundamentos: 40%
- Práctica guiada: 35%
- Proyecto personal: 20%
- Review y consolidación: 5%

### ⚖️ Nivel Medio (Score: 2.5-3.9)
**Enfoque:** Equilibrio entre teoría y práctica con despliegue

**Adaptaciones específicas:**
- **Ritmo:** Progresión estándar con retos intermedios
- **Proyectos:** Mayor autonomía con checkpoints
- **Stack:** Tecnologías modernas y herramientas profesionales
- **Evaluación:** Balance teoría/práctica con despliegue obligatorio
- **Soporte:** Mentoría quincenal y peer programming

**Distribución de tiempo:**
- Conceptos avanzados: 30%
- Desarrollo autónomo: 40%
- Proyecto aplicado: 25%
- Optimización y despliegue: 5%

### 🚀 Nivel Avanzado (Score: 4.0-5.0)
**Enfoque:** Especialización, performance y arquitectura

**Adaptaciones específicas:**
- **Ritmo:** Acelerado con temas especializados
- **Proyectos:** Arquitectura compleja y optimización
- **Stack:** Tecnologías de vanguardia y herramientas avanzadas
- **Evaluación:** Énfasis en performance, seguridad y escalabilidad
- **Soporte:** Mentoría mensual y contribuciones open source

**Distribución de tiempo:**
- Arquitectura y patrones: 25%
- Desarrollo avanzado: 35%
- Optimización y performance: 20%
- Investigación y contribuciones: 20%

---

## Sistema de seguimiento y métricas

### 📊 Métricas semanales

**Indicadores de progreso:**
- **Horas completadas:** {{horas_sem}} h/semana (target)
- **Entregables a tiempo:** ≥ 90% on-schedule
- **Calidad de código:** ≥ 7/10 promedio
- **Participación:** Activa en comunidad/reviews

**Métricas técnicas:**
- **Tests pasando:** ≥ 95% success rate
- **Code coverage:** ≥ 70% (si aplica)
- **Performance:** Cumplimiento de benchmarks
- **Documentación:** Completa y actualizada

### 🎯 KPIs por fase

**Fase inicial:**
- Configuración exitosa: 100%
- Fundamentos dominados: ≥ 80%
- Mini-proyectos completados: {{proyectos_fase1}}/{{proyectos_fase1}}

**Fase intermedia:**
- Proyecto intermedio funcional: 100%
- Tecnologías integradas: {{tecnologias_intermedias}}
- Code reviews participadas: {{code_reviews}}

**Fase final:**
- {{proyecto_objetivo}} completado: 100%
- Portfolio profesional: Completo
- Preparación laboral: ≥ 80% readiness

### 📈 Dashboard de progreso

**Indicadores visuales:**
- 🟢 **En buen camino:** > 80% en todos los KPIs
- 🟡 **Atención requerida:** 60-80% en KPIs clave
- 🔴 **Riesgo alto:** < 60% en cualquier KPI

**Alertas automáticas:**
- Retraso > 1 semana en entregables
- Calidad de código < 6/10
- Participación < 70% esperada
- Horas semanales < 80% del target

---

## Recursos y herramientas

### 🛠️ Stack tecnológico base

**Herramientas de desarrollo:**
- **Editor/IDE:** {{ide_recomendado}}
- **Control de versiones:** Git + {{plataforma_git}}
- **Terminal:** {{terminal_recomendado}}
- **Testing:** {{framework_testing}}
- **Despliegue:** {{plataforma_deploy}}

**Tecnologías específicas de {{ruta}}:**
{{#each tech_stack}}
- **{{categoria}}:** {{tecnologias}}
{{/each}}

### 📚 Recursos de aprendizaje

**Documentación oficial:**
{{#each docs_oficiales}}
- [{{nombre}}]({{url}}): {{descripcion}}
{{/each}}

**Cursos y tutoriales:**
{{#each cursos}}
- [{{titulo}}]({{url}}): {{duracion}} - {{nivel}}
{{/each}}

**Libros recomendados:**
{{#each libros}}
- **{{titulo}}** por {{autor}}: {{capitulos_relevantes}}
{{/each}}

### 🌐 Comunidades y networking

**Comunidades técnicas:**
- **{{comunidad_principal}}:** {{descripcion_comunidad}}
- **Stack Overflow:** Tags {{tags_relevantes}}
- **GitHub:** Repositorios {{repos_referencia}}
- **Discord/Slack:** {{servidores_recomendados}}

**Eventos y meetups:**
{{#each eventos}}
- **{{nombre}}:** {{frecuencia}} - {{ubicacion}}
{{/each}}

---

## Evaluación y checkpoints

### 🔍 Checkpoints programados

{{#each checkpoints}}
#### Checkpoint {{numero}} - Semana {{semana}}
**Tipo:** {{tipo_evaluacion}}
**Duración:** {{duracion}}
**Formato:** {{formato}}

**Criterios de evaluación:**
{{#each criterios}}
- {{criterio}}: {{peso}}% del total
{{/each}}

**Entregables requeridos:**
{{#each entregables}}
- [ ] {{entregable}}
{{/each}}

**Criterios de aprobación:**
- Puntuación mínima: {{puntuacion_minima}}%
- Entregables completos: {{entregables_requeridos}}%
- Calidad técnica: ≥ {{calidad_minima}}/10

---
{{/each}}

### 📋 Evaluación final

**Componentes de la evaluación:**
1. **{{proyecto_objetivo}} (40%):** Funcionalidad, calidad técnica, documentación
2. **Portfolio (25%):** Presentación profesional, variedad de proyectos
3. **Evaluación técnica (20%):** Conocimientos teóricos y prácticos
4. **Presentación (15%):** Comunicación y demostración de competencias

**Criterios de certificación:**
- [ ] {{proyecto_objetivo}} cumple criterios de aceptación
- [ ] Portfolio profesional completo
- [ ] Evaluación técnica ≥ 80%
- [ ] Presentación exitosa
- [ ] Participación activa durante el programa

---

## Plan de contingencia

### ⚠️ Escenarios de riesgo

#### Retraso en cronograma
**Señales:** > 1 semana de retraso acumulado
**Acciones:**
- Priorizar entregables core
- Aumentar horas semanales temporalmente
- Solicitar mentoría adicional
- Simplificar alcance manteniendo objetivos de aprendizaje

#### Dificultades técnicas
**Señales:** < 60% éxito en evaluaciones
**Acciones:**
- Refuerzo intensivo en áreas débiles
- Recursos adicionales específicos
- Mentoría técnica especializada
- Posible extensión de 1-2 semanas

#### Pérdida de motivación
**Señales:** Disminución en participación/calidad
**Acciones:**
- Sesión de coaching motivacional
- Reconexión con objetivos personales
- Ajuste de proyecto a intereses específicos
- Conexión con success stories

### 🔄 Adaptaciones dinámicas

#### Aceleración del programa
**Condiciones:** Progreso > 120% del esperado
**Opciones:**
- Funcionalidades adicionales en {{proyecto_objetivo}}
- Contribuciones a proyectos open source
- Mentoría a otros participantes
- Exploración de tecnologías avanzadas

#### Extensión del programa
**Condiciones:** Necesidad de más tiempo para consolidar
**Opciones:**
- Extensión de 2-4 semanas adicionales
- Enfoque en calidad sobre velocidad
- Refuerzo en fundamentos
- Proyecto adicional de práctica

---

**Generado por:** Thoth v{{version}}
**Fecha de creación:** {{fecha_creacion}}
**Última actualización:** {{fecha_actualizacion}}
**Próxima revisión:** {{fecha_revision}}