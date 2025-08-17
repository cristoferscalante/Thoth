# Sondas de nivel (básico/medio/avanzado)

## 1. Lógica y algoritmos

### Básico (0-2 puntos)
**Mini-reto**: "Tienes una lista de números [3, 1, 4, 1, 5]. ¿Cómo encontrarías el número más grande?"
- **Respuesta esperada**: Recorrer la lista comparando cada elemento
- **Seguimiento**: "¿Qué pasaría si la lista tuviera 1 millón de números?"
- **Indicadores de nivel básico**: Menciona bucles, no considera optimización

### Medio (3-4 puntos)
**Mini-reto**: "¿Cómo buscarías un nombre específico en una lista ordenada de 10,000 nombres?"
- **Respuesta esperada**: Menciona búsqueda binaria o divide y vencerás
- **Seguimiento**: "¿Cuál sería la diferencia en tiempo entre buscar uno por uno vs. tu método?"
- **Indicadores de nivel medio**: Entiende eficiencia, conoce algoritmos básicos

### Avanzado (5 puntos)
**Mini-reto**: "Diseña un algoritmo para encontrar duplicados en un array sin usar memoria extra."
- **Respuesta esperada**: Algoritmo in-place, considera trade-offs tiempo/espacio
- **Seguimiento**: "¿Qué complejidad temporal y espacial tiene tu solución?"
- **Indicadores de nivel avanzado**: Analiza complejidad, optimiza recursos

## 2. Aplicación práctica

### Básico (0-2 puntos)
**Escenario**: "Quieres crear una app donde los usuarios puedan registrarse y hacer login. ¿Cómo lo harías?"
- **Respuesta esperada**: Formularios, base de datos para usuarios, validación básica
- **Seguimiento**: "¿Dónde guardarías las contraseñas?"
- **Indicadores**: Entiende flujo básico, no considera seguridad avanzada

### Medio (3-4 puntos)
**Escenario**: "Diseña un sistema donde usuarios autenticados puedan crear, leer, actualizar y eliminar posts."
- **Respuesta esperada**: CRUD completo, autenticación, autorización, validaciones
- **Seguimiento**: "¿Cómo manejarías que solo el autor pueda editar su post?"
- **Indicadores**: Entiende arquitectura MVC, considera permisos

### Avanzado (5 puntos)
**Escenario**: "Diseña una API que maneje 10,000 usuarios concurrentes creando posts."
- **Respuesta esperada**: Considera escalabilidad, caching, rate limiting, base de datos
- **Seguimiento**: "¿Cómo evitarías que el sistema se caiga con picos de tráfico?"
- **Indicadores**: Piensa en arquitectura distribuida, performance, resilencia

## 3. Herramientas y flujo de trabajo

### Básico (0-2 puntos)
**Pregunta**: "¿Has usado Git? ¿Para qué sirve?"
- **Respuesta esperada**: Control de versiones, guardar cambios
- **Seguimiento**: "¿Qué comandos de Git conoces?"
- **Indicadores**: Conoce git add, commit, push básicos

### Medio (3-4 puntos)
**Pregunta**: "Explica qué harías si dos desarrolladores modifican el mismo archivo."
- **Respuesta esperada**: Menciona merge conflicts, branches, pull requests
- **Seguimiento**: "¿Cómo organizarías el trabajo en equipo con Git?"
- **Indicadores**: Entiende branching, colaboración, testing básico

### Avanzado (5 puntos)
**Pregunta**: "Describe tu flujo ideal desde desarrollo hasta producción."
- **Respuesta esperada**: CI/CD, testing automatizado, staging, deployment
- **Seguimiento**: "¿Cómo garantizarías que no se rompa producción?"
- **Indicadores**: Conoce pipelines, testing avanzado, monitoring

## 4. Datos y persistencia

### Básico (0-2 puntos)
**Pregunta**: "Tienes una tabla 'usuarios' con id, nombre, email. ¿Cómo obtienes todos los usuarios?"
- **Respuesta esperada**: SELECT * FROM usuarios
- **Seguimiento**: "¿Y solo los que tienen gmail?"
- **Indicadores**: Conoce SELECT básico, WHERE simple

### Medio (3-4 puntos)
**Pregunta**: "Tienes tablas 'usuarios' y 'pedidos'. ¿Cómo obtienes usuarios con sus pedidos?"
- **Respuesta esperada**: JOIN entre tablas
- **Seguimiento**: "¿Y si quieres usuarios SIN pedidos?"
- **Indicadores**: Entiende relaciones, diferentes tipos de JOIN

### Avanzado (5 puntos)
**Pregunta**: "Describe cómo procesarías 1GB de datos de ventas diarias para generar reportes."
- **Respuesta esperada**: ETL, agregaciones, índices, posible uso de herramientas como pandas
- **Seguimiento**: "¿Cómo lo harías si fueran 100GB?"
- **Indicadores**: Piensa en big data, optimización, herramientas especializadas

## 5. Sistemas y arquitectura

### Básico (0-2 puntos)
**Pregunta**: "¿Qué es Docker? ¿Para qué sirve?"
- **Respuesta esperada**: Contenedores, aislar aplicaciones
- **Seguimiento**: "¿Cuál es la diferencia con una máquina virtual?"
- **Indicadores**: Concepto básico de containerización

### Medio (3-4 puntos)
**Pregunta**: "¿Qué es CI/CD? ¿Por qué es útil?"
- **Respuesta esperada**: Integración continua, despliegue automático, testing
- **Seguimiento**: "¿Cómo implementarías CI/CD en un proyecto?"
- **Indicadores**: Entiende automatización, testing, deployment

### Avanzado (5 puntos)
**Pregunta**: "Diseña la arquitectura para una app que debe escalar a millones de usuarios."
- **Respuesta esperada**: Load balancers, microservicios, bases de datos distribuidas, caching
- **Seguimiento**: "¿Cómo manejarías la consistencia de datos?"
- **Indicadores**: Piensa en sistemas distribuidos, CAP theorem, resilencia

## Criterios de evaluación

### Escala de puntuación por área
- **0-2 puntos**: Nivel básico - Conocimientos fundamentales
- **3-4 puntos**: Nivel medio - Aplicación práctica y comprensión
- **5 puntos**: Nivel avanzado - Pensamiento sistémico y optimización

### Clasificación final
- **0-10 puntos**: Desarrollador Junior (Básico)
- **11-20 puntos**: Desarrollador Semi-Senior (Medio)
- **21-25 puntos**: Desarrollador Senior (Avanzado)

### Indicadores de calidad de respuesta

#### Respuesta de calidad básica:
- Menciona conceptos correctos
- Explica el "qué" pero no el "por qué"
- Soluciones directas sin considerar alternativas

#### Respuesta de calidad media:
- Explica el razonamiento detrás de la solución
- Considera pros y contras
- Menciona buenas prácticas
- Demuestra experiencia práctica

#### Respuesta de calidad avanzada:
- Analiza trade-offs y complejidades
- Considera escalabilidad y mantenibilidad
- Propone múltiples enfoques
- Demuestra pensamiento arquitectónico
- Menciona métricas y monitoreo

## Instrucciones para el evaluador

### Proceso de evaluación
1. **Hacer la pregunta principal** de cada área
2. **Escuchar la respuesta** sin interrumpir
3. **Hacer la pregunta de seguimiento** para profundizar
4. **Asignar puntuación** basada en indicadores
5. **Tomar notas** de fortalezas y áreas de mejora

### Señales de alerta
- **Respuestas memorizadas** sin comprensión
- **Sobreconfianza** sin fundamento
- **Evasión** de preguntas técnicas específicas
- **Inconsistencias** entre diferentes respuestas

### Adaptación durante la evaluación
- Si una respuesta es **muy básica**, simplificar la pregunta de seguimiento
- Si una respuesta es **muy avanzada**, profundizar con preguntas más complejas
- **Mantener el tono conversacional** y de apoyo
- **Dar pistas** si el usuario se bloquea completamente