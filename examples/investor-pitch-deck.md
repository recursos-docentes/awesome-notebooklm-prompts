# Ejemplo: Pitch Deck para Inversores (Recaudación de Fondos)
 
## Situación
 
Sos el fundador de una startup de IA presentando tu proyecto a VCs (fondos de capital de riesgo). Contás con:
- Un producto/MVP funcional
- Tracción de clientes y métricas iniciales
- Una visión convincente del mercado
- 15-20 minutos para la presentación
- Necesidad de recaudar una ronda Serie A
**Desafío:** ¿Cómo contar una historia de inversión convincente que enganche a los VCs mientras se demuestran los fundamentos del negocio?
 
---
 
## Objetivo
 
Crear un pitch deck para inversores que:
- ✅ Capte la atención en los primeros 30 segundos
- ✅ Deje clarísimo el problema
- ✅ Muestre la solución única
- ✅ Demuestre la oportunidad de mercado
- ✅ Pruebe tracción con métricas reales
- ✅ Muestre el camino hacia la rentabilidad
- ✅ Genere urgencia y convicción
- ✅ Cuente una narrativa coherente (no solo una descarga de datos)
---
 
## Preparación
 
### Materiales para subir a NotebookLM
1. **Descripción del producto** (¿qué hace?)
2. **Métricas de clientes** (ingresos, crecimiento, retención)
3. **Investigación de mercado** (TAM, SAM, SOM)
4. **Biografías del equipo** (¿por qué son el equipo indicado?)
5. **Panorama competitivo** (¿en qué te diferenciás?)
6. **Proyecciones financieras** (camino hacia la rentabilidad)
7. **Ejemplos de casos de uso** (historias de clientes)
### Perfil del inversor
- VCs sectoriales interesados en IA/SaaS
- Familiarizados con métricas de crecimiento
- Buscan evidencia de encaje producto-mercado (product-market fit)
- Enfocados en el potencial de salida (exit)
- Con poco tiempo (decidirán rápido)
### Narrativa central
"Estamos resolviendo [problema] que le cuesta a las empresas $[X]B anuales.
Nuestro enfoque es [único porque]. Ya logramos [punto de prueba].
Este mercado crece [tasa de crecimiento] y estamos posicionados para capturar [% de oportunidad]."
 
---
 
## Prompt inicial
 
```
Creá un pitch deck de inversores para Serie A (12-15 diapositivas) optimizado para VCs.
 
Estructura (Problema → Solución → Tracción → Pedido):
1. Gancho/Título (1)
2. Planteamiento del problema (1)
3. Oportunidad de mercado (1)
4. Tu solución (2)
5. Ventaja competitiva (1)
6. Tracción/Prueba (3)
7. Modelo de negocio (1)
8. Estrategia de entrada al mercado (Go-to-Market) (1)
9. Equipo (1)
10. Proyecciones financieras (1)
11. El pedido (1)
 
Diseño: estilo Neo-Retro Dev Deck
- Fondo tipo grilla color crema/blanco roto
- Bloques de color de alto contraste con bordes negros
- Tipografía audaz y segura
- Números y métricas específicos destacados de forma prominente
- Tono enérgico pero profesional
 
Requisitos clave:
- Cada afirmación respaldada por datos
- Números específicos (no "creciendo rápido")
- Citas reales de clientes o logos si es posible
- Diferenciación competitiva clara
- Reconocimiento honesto de los desafíos
- Visión convincente del futuro
```
 
---
 
## Lo que genera NotebookLM
 
```
DIAPOSITIVA 1: Gancho
Título: "El futuro de [tu categoría]"
Subtítulo: Una estadística contundente que muestre el problema
Visual: Audaz, simple, memorable
Objetivo: Lograr que escuchen la siguiente diapositiva
 
DIAPOSITIVA 2: El problema
Título: "Las empresas desperdician $2B anuales en [proceso ineficiente]"
Puntos clave:
- Las soluciones actuales toman X horas/cuestan $Y/tienen limitaciones Z
- El 80% de los usuarios reporta frustración con el enfoque actual
- Este es uno de los 3 principales dolores de cabeza para los CTOs
Visual: El problema visualizado (brecha, fricción, costo)
Nota del orador: Hacer que el problema se sienta real y cercano
 
DIAPOSITIVA 3: Tamaño de mercado
Título: "Mercado total direccionable (TAM): $50B"
Números:
- TAM: $50B (mercado total si ganás todo)
- SAM: $5B (realista si te va bien)
- SOM: $10M (tu objetivo realista al año 3)
Visual: Desglose de mercado o trayectoria de crecimiento
Nota del orador: Mostrar que es una oportunidad suficientemente grande como para justificar la inversión
 
DIAPOSITIVA 4: Nuestra solución (visión general)
Título: "Lo que construimos: [Frase resumen]"
Explicación:
- Descripción simple e intuitiva
- En qué se diferencia de la competencia
- ¿Por qué ahora? (tecnología, momento, equipo)
Visual: Captura simple de demo del producto o diagrama
Nota del orador: No entrar demasiado en lo técnico; enfocarse en el valor
 
DIAPOSITIVA 5: Nuestra solución (cómo funciona)
Título: "Flujo de trabajo de [Solución]"
Mostrar:
- Paso 1: Entrada del cliente
- Paso 2: Nuestra IA procesa
- Paso 3: Resultado de negocio
Visual: Diagrama de flujo simple o antes/después
Nota del orador: Ayudarlos a visualizar la experiencia del cliente
 
DIAPOSITIVA 6: Panorama competitivo
Título: "Por qué ganamos"
Matriz:
- Vos vs. 3-4 competidores principales
- Dimensiones clave: precio, velocidad, precisión, facilidad de uso
- Estás en la esquina superior derecha (el mejor en todo lo que importa)
Visual: Matriz competitiva simple
Nota del orador: Ser justo con los competidores pero claro respecto a las ventajas
 
DIAPOSITIVA 7: Tracción - Ingresos
Título: "Crecimiento de ingresos: 250% interanual"
Métricas:
- Año 1: $50K
- Año 2: $125K
- Proyección año 3: $312K
- MRR actual: $15K
- Costo de adquisición de clientes: $3K (recuperación: 4 meses)
Visual: Gráfico de trayectoria ascendente (tu gráfico más atractivo)
Nota del orador: Los ingresos reales son la mejor métrica de tracción
 
DIAPOSITIVA 8: Tracción - Clientes
Título: "12 clientes empresariales, 95% de retención"
Mostrar:
- Logos de clientes (si se pueden publicar)
- Cita testimonial de un cliente
- Caso de estudio: [Cliente] logró [resultado]
Visual: Logos o gráficos con testimonios
Nota del orador: La prueba social es poderosa
 
DIAPOSITIVA 9: Tracción - Uso
Título: "Engagement del producto: 40% de usuarios activos semanales"
Métricas:
- [X] transacciones por día
- [X] duración promedio de sesión
- [X] tasa de uso de funcionalidades
- NPS: [X] (referencia empresarial: 50)
Visual: Métricas de engagement clave destacadas
Nota del orador: Mostrar que la gente realmente lo está usando
 
DIAPOSITIVA 10: Modelo de negocio
Título: "Economía unitaria comprobada"
Modelo:
- SaaS: $[X] por mes por cliente
- Costo de adquisición de clientes: $Y
- Valor de vida del cliente (LTV): $Z
- Período de recuperación: 4 meses
Visual: Visualización simple de LTV/CAC
Nota del orador: Mostrar que la economía funciona
 
DIAPOSITIVA 11: Estrategia de entrada al mercado
Título: "Escalando hacia $100M"
Estrategia:
- Fuerza de ventas (inicio: 2, año 3: 10)
- Canal de socios (socios de integración empresarial)
- Comunidad/boca en boca (ya está sucediendo)
Cronograma: Año 1 (conquistar), Año 2 (expandir), Año 3 (dominar)
Visual: Línea de tiempo o embudo de marketing
Nota del orador: Mostrar cómo vas a crecer de forma eficiente
 
DIAPOSITIVA 12: El equipo
Título: "Construido por expertos en [industria]"
Miembros del equipo:
- CEO: [Trayectoria] | 10 años de experiencia relevante en [área]
- CTO: [Trayectoria] | Ex ingeniero en [empresa]
- VP de Ventas: [Trayectoria] | Construyó una línea de productos de $100M
Por qué vamos a ganar: [Insight específico de la trayectoria del equipo]
Visual: Fotos del equipo y biografías breves
Nota del orador: Los VCs invierten en equipos; hacé que crean en el tuyo
 
DIAPOSITIVA 13: Proyecciones financieras
Título: "Camino hacia la rentabilidad"
Mostrar:
- Año 1: $500K de ingresos, -$200K neto
- Año 2: $2M de ingresos, punto de equilibrio
- Año 3: $8M de ingresos, 40% de margen neto
Visual: Líneas de ingresos y ganancias cruzándose hacia la rentabilidad
Nota del orador: Mostrar que vas a ser un negocio sostenible
 
DIAPOSITIVA 14: El pedido
Título: "$2M de Serie A"
Uso de los fondos:
- Equipo de ventas: $500K
- Ingeniería (desarrollo): $700K
- Operaciones/infraestructura: $400K
- Colchón/runway: $400K
Cronograma: 18 meses hasta la Serie B a [valuación]
Visual: Gráfico circular simple de asignación
Nota del orador: Un pedido específico resulta creíble
 
DIAPOSITIVA 15: Visión
Título: "El futuro: [Visión inspiradora]"
Pintar un panorama:
- Año 5: [Hito realista]
- Año 10: [Liderazgo de categoría]
- Por qué importa: [Impacto social/de negocio]
Visual: Imagen o declaración inspiradora
Nota del orador: Terminar con convicción y visión
```
 
---
 
## Prompts de refinamiento
 
### Refinamiento 1: Fortalecer la narrativa
```
"Revisá el flujo del deck:
1. ¿Cada diapositiva se desprende de la anterior?
2. ¿Las transiciones son lógicas y convincentes?
3. ¿Cuenta una historia o solo enumera información?
 
Reescribí cualquier contenido que no haga avanzar la narrativa.
Agregá frases de transición entre las secciones principales."
```
 
### Refinamiento 2: Enfatizar la tracción
```
"La sección de tracción es tu momento más creíble.
Para cada métrica:
1. Por qué le importa esto a los inversores
2. Cómo se compara con las referencias del sector
3. Qué demuestra sobre tu negocio
 
Hacé que la sección de tracción sea la parte más fuerte del deck."
```
 
### Refinamiento 3: Abordar las preocupaciones de los inversores
```
"Anticipá las 5 principales preocupaciones de los inversores:
1. Tamaño de mercado - ¿Es suficientemente grande?
2. Competencia - ¿Por qué ganás vos?
3. Economía unitaria - ¿Los números cierran?
4. Equipo - ¿Pueden ejecutar?
5. Riesgo - ¿Qué podría salir mal?
 
Para cada preocupación, agregá una línea o subpunto que la aborde."
```
 
### Refinamiento 4: Generar urgencia
```
"Los VCs invierten cuando ven:
1. Una oportunidad de mercado enorme
2. Un equipo sólido
3. Encaje producto-mercado real
4. Impulso/tracción
 
Agregá elementos que generen urgencia:
- Amenazas competitivas
- Señales de demanda de clientes
- Cronograma hacia la Serie B y a qué valuación
- ¿Por qué ahora?"
```
 
---
 
## Consejos profesionales para pitches a inversores
 
### Los primeros 30 segundos ⏱️
**El momento que define todo.**
```
"Podrías abrir así:
 
Opción 1 (enfocada en el problema):
'Los equipos empresariales desperdician 40 horas por semana en [tarea] manual.
Nosotros reducimos eso a 4 horas. Ya estamos ahorrándoles $500K/año a nuestros clientes.'
 
Opción 2 (enfocada en la visión):
'En 5 años, todas las empresas de [industria] usarán IA para [tarea].
Estamos construyendo la plataforma que hace eso posible.'
 
Opción 3 (enfocada en la tracción):
'Pasamos de $0 a $500K en ingresos en 12 meses.
Cada cliente que adquirimos crece un 250% en su primer año.
Estamos acá porque tenemos más demanda de la que podemos atender.'"
```
 
### Densidad de datos ✅
- Usá los números de forma estratégica
- No sobrecargues con métricas
- Cada número debe respaldar tu narrativa
- "Aburrido pero creíble" le gana a "emocionante pero vago"
### El "¿Por qué ahora?" ✅
- Los VCs ven muchas buenas ideas
- ¿Por qué esta empresa gana ahora?
- ¿Qué cambió en el mercado/la tecnología?
- ¿Por qué empezaste esto justo ahora?
### Posicionamiento competitivo ✅
- **Evitá:** "No hay competencia" (señal de alerta)
- **Evitá:** "Somos 10 veces mejores" (poco realista)
- **Decí:** "Este es el panorama competitivo. Somos diferentes porque..."
- Usá una matriz 2x2 para mostrar el posicionamiento con claridad
### Manejar el escepticismo ✅
- Los VCs van a cuestionarte
- Respuestas seguras y honestas > respuestas defensivas
- Reconocé los riesgos reales
- Mostrá que pensaste bien las objeciones
### Cerrar con fuerza ✅
- Visión + pedido claro = combinación poderosa
- "Estamos recaudando $2M para [uso específico]"
- "Esto nos pone en camino hacia [hito]"
- "Nos encantaría contar con su apoyo para construir esto"
---
 
## Ejemplos de prompts específicos (casos reales)
 
### Sesión 1: Estructura y narrativa
```
"Creá un pitch deck de inversores de 12 diapositivas para una recaudación Serie A.
 
Mi empresa: [Tu empresa]
Qué hacemos: [Tu solución]
Validación de clientes: [Prueba de tracción]
 
Creá una narrativa convincente:
1. Enganchalos con el problema
2. Mostrá que lo resolvimos
3. Probalo con métricas reales
4. Mostrá el camino hacia una salida (exit) significativa
5. Pedí con claridad
 
Estilo: Neo-Retro Dev Deck - audaz, seguro, números claros
Enfoque: Cada afirmación debe estar respaldada por datos"
```
 
### Sesión 2: Diferenciación competitiva
```
"Creá una sección de posicionamiento competitivo.
 
Nuestros competidores:
- [Competidor 1] - fortalezas: X, debilidades: Y
- [Competidor 2] - fortalezas: A, debilidades: B
- [Competidor 3] - fortalezas: P, debilidades: Q
 
Por qué ganamos:
[Tu ventaja única]
 
Formato: matriz 2x2 con dimensiones que nos favorezcan
Sé honesto pero claro respecto a nuestra ventaja competitiva"
```
 
### Sesión 3: Énfasis en la tracción
```
"Hacé que la sección de tracción sea convincente.
 
Nuestras métricas:
- Ingresos: [Números]
- Crecimiento de clientes: [Tasa]
- Retención: [%]
- Testimonio de cliente: '[Cita]'
 
Para cada métrica:
1. Qué demuestra
2. Cómo se compara con las referencias del sector
3. Por qué debería importarle a los inversores
 
Hacé que esta sección sea la más fuerte visual y narrativamente."
```
 
---
 
## Errores comunes en los pitches y cómo corregirlos
 
| Error | Problema | Solución |
|---------|---------|-----|
| Sin ingresos | Etapa demasiado temprana | Liderar con uso, engagement, lista de espera |
| Números vagos | Suena inventado | Usar métricas específicas, citar fuentes |
| Sin mención de la competencia | Parece ingenuo | Mostrar el panorama competitivo, la diferenciación |
| Demasiado detalle | Se vuelve aburrido | Un número clave por diapositiva |
| Visión sin tracción | Sin credibilidad | Probar primero que funciona, luego pintar la visión |
| Pedido pequeño | Parece poco ambicioso | Pedido de tamaño adecuado con uso claro de los fondos |
| Diapositiva de equipo mínima | Invierten en equipos | Mostrar credenciales, trayectoria, por qué van a ganar |
 
---
 
## Ejemplo real de pitch deck (esqueleto)
 
### Diapositiva 1: Gancho
```
TÍTULO: "IA para la planificación empresarial"
SUBTÍTULO: "Ahorrando a los equipos 10 horas por semana"
VISUAL: Una estadística contundente o una cita de cliente
TIEMPO: 30 segundos para captar su atención
```
 
### Diapositiva 2: Problema
```
TÍTULO: "Los equipos empresariales desperdician más de $1M anuales"
DATOS:
- La planificación de horarios toma más de 10 horas/semana por gerente
- El 40% de las solicitudes de reunión se rechazan o reprograman
- La integración entre herramientas es manual y propensa a errores
VISUAL: Gráfico simple que muestre la magnitud del problema
TIEMPO: 1 minuto - hacer que sientan el dolor
```
 
### Diapositiva 3: Solución
```
TÍTULO: "Plataforma de planificación inteligente"
PUNTOS CLAVE:
- Solicitudes de agenda en lenguaje natural
- La IA optimiza para todos los participantes
- Se integra con Outlook, Google, Slack
- Toma 30 segundos en vez de 10 minutos
VISUAL: Demo rápida del producto o captura de la interfaz
TIEMPO: 1 minuto - mostrar que es elegante
```
 
### Diapositiva 4: Tracción
```
TÍTULO: "Resultados reales de clientes"
DATOS:
- 50 empresas usándolo (logos mostrados)
- 10 horas ahorradas por usuario por semana
- $250K de ACV total (Valor de Contrato Anual)
- 95% de NPS
TESTIMONIO: "[Cliente] logró [resultado]"
TIEMPO: 1.5 minutos - dejar que esto se asimile
```
 
### Diapositiva 5: Pedido
```
TÍTULO: "Serie A: inversión de $2M"
USO DE LOS FONDOS:
- Equipo de ventas: $700K
- Ingeniería: $800K
- Operaciones: $300K
- Runway: $200K
 
CRONOGRAMA: 18 meses hasta la Serie B con $20M de ARR
VISIÓN: Construir el sistema operativo para la gestión del tiempo empresarial
TIEMPO: 1 minuto - claro y específico
```
 
---
 
## Checklist previo al pitch
 
- [ ] Cada número es real (sin proyecciones disfrazadas de hechos)
- [ ] La sección de tracción es sólida (tu mejor prueba)
- [ ] La visión es convincente pero realista
- [ ] La diapositiva del equipo muestra experiencia relevante
- [ ] El modelo de negocio es claro y sólido
- [ ] El posicionamiento competitivo es honesto y fuerte
- [ ] El pedido es específico con un uso claro de los fondos
- [ ] La historia fluye lógicamente de una diapositiva a otra
- [ ] No hay jerga técnica que excluya a VCs no técnicos
- [ ] El diseño es limpio, no artificioso
- [ ] Los números se leen bien a distancia
- [ ] Cada diapositiva toma entre 1 y 2 minutos de presentación
- [ ] Se practicó con el tiempo real
- [ ] Hay diapositivas de respaldo/detalle para las preguntas
---
 
## Consejos para la presentación del pitch
 
### La sala
- Llegar temprano, probar la tecnología
- Hacer contacto visual con quienes toman las decisiones clave
- Hablar con seguridad pero sin arrogancia
- Hacer una pausa después de números grandes (dejar que se asimilen)
- Sonreír: ¡creés en esto!
### Manejo de preguntas
- **"¿Por qué ahora?"** → Momento de mercado + tecnología + equipo
- **"¿Quién es tu competencia?"** → Nombralos, mostrá por qué ganás
- **"¿Qué podría salir mal?"** → Sé honesto, mostrá que lo pensaste bien
- **"¿Cuál es tu margen bruto?"** → Mostrá que la economía unitaria funciona
- **"¿Por qué creés que vas a ganar?"** → Se trata del equipo + el momento + la ejecución
### El cierre
- Agradecerles su tiempo
- Recordarles tu pedido: "$2M de Serie A"
- Mostrar tu convicción: "Vamos a hacer esto con o sin ustedes"
- Próximos pasos: "Seguimos en contacto, con la esperanza de avanzar el mes que viene"
---
 
## Estimaciones de tiempo
 
| Tarea | Tiempo |
|------|------|
| Preparar materiales de origen | 5-10 min |
| Generación inicial en NotebookLM | 15-20 min |
| Rondas de refinamiento (2-3x) | 15-25 min |
| Convertir a diapositivas (diseño) | 30-45 min |
| Practicar y refinar | 20-30 min |
| **Total** | **90-150 min** |
 
---
 
## Seguimiento después del pitch
 
- Enviar agradecimiento con un resumen del deck de 1 página
- Hacer seguimiento con métricas detalladas (si las piden)
- Mantenerlos al tanto del progreso
- Construir la relación más allá de la decisión inmediata
- Aprender del feedback (incluso si no avanzan)
---
 
## Próximos pasos
 
1. **Probalo** con la historia de tu propia empresa
2. **Iterá** según el feedback de los inversores
3. **Practicá** en voz alta con inversores reales
4. **Refiná** según las preguntas que surjan
5. **Compartí** tus prompts si funcionan bien
---
 
**¿Preguntas?** Consultá el README principal para más recursos.
 
**¿Querés aportar tus propios prompts de pitch deck?** ¡Nos encantaría saber qué funciona!
 
