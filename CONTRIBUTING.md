# Cómo contribuir a Awesome NotebookLM Slide Decks Prompts
 
¡Antes que nada, gracias por considerar contribuir a este proyecto! Gente como vos es la que hace que este repositorio sea un recurso tan valioso.
 
## Código de conducta
 
Este proyecto y todos los que participan en él se rigen por nuestro Código de conducta. Al participar, se espera que respetes este código. Por favor, informá cualquier comportamiento inaceptable a los mantenedores.
 
## ¿Cómo puedo contribuir?
 
### 1. Agregar nuevos prompts
¿Tenés un prompt de NotebookLM que funciona realmente bien? ¡Compartilo!
 
**Qué hace que un prompt sea una buena contribución:**
- ✅ Probado en la práctica y con eficacia comprobada
- ✅ Claro y bien estructurado
- ✅ Resuelve un problema real
- ✅ Incluye contexto y ejemplo
- ✅ Encaja en una de nuestras categorías
**Cómo enviarlo:**
1. Editá `COMPLETE_PROMPTS.md`
2. Agregá tu prompt en la sección correspondiente (o creá una nueva sección si hace falta)
3. Incluí una breve descripción de lo que hace el prompt
4. Agregá un ejemplo de cómo usarlo
5. Enviá un PR con una descripción clara
**Plantilla para nuevos prompts:**
```markdown
### [Nombre del prompt]
```
[Texto completo del prompt acá]
```
 
**Cuándo usar esto:**
[Describí el caso de uso y la situación]
 
**Ejemplo:**
```
[Mostrá un ejemplo con contenido real]
```
 
**Consejos para mejores resultados:**
- [Cualquier consejo especial]
```
### 2. Agregar nuevos estilos de diseño
¿Descubriste un estilo de diseño que produce resultados increíbles? ¡Documentalo!
 
**Qué necesitamos:**
- ✅ Nombre del estilo
- ✅ Especificación completa del prompt
- ✅ Imagen o descripción de ejemplo
- ✅ Cuándo usarlo
- ✅ Paleta de colores
- ✅ Pautas de tipografía
- ✅ Patrones de diseño
**Cómo enviarlo:**
1. Creá una especificación detallada siguiendo nuestro formato
2. Incluí el estilo en `COMPLETE_PROMPTS.md` dentro de "Artistic & Avant-Garde Styles" o la sección correspondiente
3. Agregá un checklist para el estilo en `QUICK_REFERENCE.md`
4. Enviá el PR con ejemplos
**Plantilla para nuevos estilos:**
```markdown
### [Nombre del estilo]
 
[Breve descripción]
 
```
# Especificación de [NOMBRE_DEL_ESTILO]
 
Identidad visual:
- Colores: [lista]
- Tipografía: [describir]
- Características clave: [lista]
- Estado de ánimo: [describir]
Patrones de diseño:
- [Patrón 1]
- [Patrón 2]
- [Patrón 3]
Cuándo usarlo:
- [Caso de uso 1]
- [Caso de uso 2]
Ideal para las audiencias:
- [Audiencia 1]
- [Audiencia 2]
```
 
Reglas de diseño:
- [Regla 1]
- [Regla 2]
```
 
### 3. Crear ejemplos de uso
¡Mostrale a la gente cómo usar realmente estos prompts!
 
**Qué necesitamos:**
- ✅ Escenario del mundo real
- ✅ Recorrido paso a paso
- ✅ Prompt real utilizado
- ✅ Consejos y trucos
- ✅ Errores comunes a evitar
**Cómo enviarlo:**
1. Creá un nuevo archivo en la carpeta `examples/`
2. Usá el formato: `[tipo]-[propósito].md`
3. Incluí: escenario, prompt, consejos, refinamientos
4. Agregá un enlace en README.md
5. Enviá el PR
**Plantilla de ejemplo de archivo:**
```markdown
# Ejemplo: [Escenario]
 
## Situación
[Describí el escenario del mundo real]
 
## Objetivo
[Qué estamos tratando de lograr]
 
## Prompt inicial
[El prompt real que usamos]
 
## Fuentes utilizadas
[Qué materiales subimos a NotebookLM]
 
## Resultados
[Describí lo que obtuvimos]
 
## Prompts de refinamiento
[Prompts de seguimiento para mejorarlo]
 
## Consejos profesionales
[Qué funcionó bien]
 
## Errores comunes
[Qué evitar]
 
## Estimación de tiempo
[Cuánto tardó esto]
```
 
### 4. Mejorar la documentación
¡Ayudá a que las guías sean más claras y útiles!
 
**Qué necesitamos:**
- ✅ Mejores explicaciones
- ✅ Ejemplos más claros
- ✅ Corrección de errores tipográficos
- ✅ Mejor organización
- ✅ Contexto adicional
- ✅ Mejor formato
**Cómo enviarlo:**
1. Hacé tus mejoras
2. Enviá el PR con una descripción clara
3. Explicá qué mejoraste y por qué
### 5. Reportar problemas y errores
¿Encontraste un problema? ¡Contanos!
 
**Un buen reporte de error incluye:**
- ✅ Título claro
- ✅ Pasos para reproducirlo
- ✅ Qué esperabas que pasara
- ✅ Qué pasó realmente
- ✅ Tu entorno (si es relevante)
- ✅ Capturas de pantalla o ejemplos
**Cómo enviarlo:**
1. Andá a la pestaña Issues
2. Hacé clic en "New Issue"
3. Usá la plantilla de reporte de errores
4. Proporcioná todos los detalles relevantes
5. Enviá
### 6. Sugerir mejoras
¿Tenés una idea para mejorar esto?
 
**Una buena sugerencia incluye:**
- ✅ Planteamiento claro del problema
- ✅ Solución propuesta
- ✅ Por qué esto importa
- ✅ Ejemplos si son relevantes
**Cómo enviarlo:**
1. Andá a Issues/Discussions
2. Describí tu sugerencia
3. Explicá el beneficio
4. Estate abierto al feedback
5. Enviá
---
 
## Pautas para el envío
 
### Proceso de Pull Request
 
1. **Hacé un fork del repositorio** en GitHub
```bash
   git clone https://github.com/TU-USUARIO/awesome-notebooklm-prompts.git
   cd awesome-notebooklm-prompts
```
 
2. **Creá una rama de funcionalidad**
```bash
   git checkout -b feature/nombre-de-tu-contribucion
```
 
3. **Hacé tus cambios**
   - Editá los archivos siguiendo las guías de estilo de abajo
   - Probá tus prompts (usalos realmente en NotebookLM si es posible)
   - Asegurate de que el formato sea consistente
   - Actualizá README.md si agregás contenido nuevo importante
4. **Hacé commit con mensajes claros**
```bash
   git add .
   git commit -m "Add: [descripción clara de lo que agregaste]"
   # Ejemplos:
   # git commit -m "Add: Watercolor design style with full specification"
   # git commit -m "Add: Example - Conference talk workflow"
   # git commit -m "Improve: Clearer explanation in Sharp-Edged Minimalism section"
```
 
5. **Subilo a tu fork**
```bash
   git push origin feature/nombre-de-tu-contribucion
```
 
6. **Abrí un Pull Request**
   - Proporcioná un título claro
   - Describí qué agregaste/cambiaste
   - Enlazá cualquier issue relacionado
   - Explicá por qué esta contribución es valiosa
   - Estate preparado para la discusión/feedback
### Guía de estilo para las contribuciones
 
#### Formato Markdown
- Usá encabezados claros (##, ###, ####)
- Usá viñetas para las listas
- Usá bloques de código para los prompts (```markdown)
- Poné en negrita los términos importantes (**término**)
- Incluí enlaces donde sea relevante
#### Pautas para los prompts
- **Claridad**: usá un lenguaje claro y directo
- **Completitud**: incluí todo el contexto necesario
- **Comprobabilidad**: debe funcionar tal como está escrito
- **Flexibilidad**: permitir la personalización
- **Ejemplos**: mostrar cómo usarlo
#### Estilo de escritura
- Escribí con claridad, no con lenguaje rebuscado
- Asumí algo de experiencia con NotebookLM, pero explicá lo básico
- Usá voz activa cuando sea posible
- Mantené las oraciones concisas
- Corregí antes de enviar
#### Nomenclatura de archivos
```
examples/[tipo]-[propósito].md
# Ejemplos:
examples/academic-conference-talk.md
examples/sales-investor-pitch.md
examples/training-educational-module.md
```
 
#### Organización de secciones
- Nuevos estilos de diseño → `COMPLETE_PROMPTS.md`
- Nuevos casos de uso → Agregar archivo de ejemplo a `examples/`
- Nuevas mejores prácticas → `QUICK_REFERENCE.md`
- Nuevos recursos → `RESOURCES.md`
- Nuevas secciones → Actualizar el índice de `README.md`
---
 
## Estándares de calidad del contenido
 
### Para los prompts
- [ ] Probado realmente con NotebookLM
- [ ] Produce resultados confiables
- [ ] Claro y sin ambigüedades
- [ ] Incluye el contexto necesario
- [ ] Bien formateado
- [ ] Ejemplo proporcionado
### Para los estilos de diseño
- [ ] Especificación completa incluida
- [ ] Paleta de colores definida
- [ ] Pautas de tipografía claras
- [ ] Patrones de diseño descritos
- [ ] Casos de uso identificados
- [ ] Reglas de diseño enumeradas
### Para los ejemplos
- [ ] Escenario del mundo real
- [ ] Recorrido paso a paso
- [ ] Prompt real mostrado
- [ ] Resultados descritos
- [ ] Consejos incluidos
- [ ] Errores comunes señalados
### Para la documentación
- [ ] Clara y concisa
- [ ] Bien organizada
- [ ] Enlaces correctos
- [ ] Formato adecuado
- [ ] Ejemplos incluidos
- [ ] Corregida
---
 
## Pautas de la comunidad
 
### Sé respetuoso
- Asumí buena intención
- Dá feedback constructivo
- Respetá las diferentes opiniones
- Sé acogedor con los recién llegados
### Sé útil
- Ayudá a otros con sus contribuciones
- Compartí conocimiento generosamente
- Dá feedback detallado
- Sugerí mejoras con criterio
### Sé honesto
- Reconocé las limitaciones
- Sé transparente sobre las pruebas realizadas
- Admití cuando no sabés algo
- Compartí tanto los éxitos como los fracasos
### Sé profesional
- Seguí el Código de conducta
- Mantené las discusiones en tema
- Respetá el tiempo de los demás
- Dá crédito cuando corresponda
---
 
## Reconocimiento
 
Los contribuyentes serán reconocidos en:
- ✅ README.md (sección de Contribuyentes)
- ✅ Agradecimiento en el PR
- ✅ Notas de la versión (para contribuciones importantes)
- ✅ Estadísticas del repositorio
¡Valoramos todas las contribuciones, desde nuevos prompts hasta correcciones de errores tipográficos!
 
---
 
## Configuración para el desarrollo
 
### Para trabajar localmente:
 
1. **Cloná el repositorio**
```bash
   git clone https://github.com/awesome-notebooklm-prompts.git
   cd awesome-notebooklm-prompts
```
 
2. **Hacé cambios en los archivos**
   - Los archivos markdown son texto plano, usá cualquier editor
   - Seguí las guías de estilo de arriba
   - Probá exhaustivamente
3. **Previsualizá tus cambios**
   - Usá una herramienta de vista previa de Markdown
   - Verificá que el formato se vea bien
   - Comprobá que los enlaces funcionen
4. **Hacé commit y subilo**
```bash
   git add .
   git commit -m "Tu mensaje de commit claro"
   git push origin nombre-de-tu-rama
```
 
---
 
## Cómo obtener ayuda
 
### ¿Preguntas?
- 💬 Abrí una Discussion
- 📧 Revisá primero los issues/PRs existentes
- 📚 Leé la documentación existente
- 🎓 Revisá los ejemplos
### ¿Estás trabado?
- Dividilo en pasos más pequeños
- Mirá contribuciones similares
- Preguntá en el hilo de discusión
- ¡No existen las preguntas tontas!
---
 
## Proceso de revisión
 
### Qué buscamos:
1. **Calidad** - ¿Cumple con nuestros estándares?
2. **Relevancia** - ¿Encaja en el alcance del repositorio?
3. **Precisión** - ¿Es correcto/está probado?
4. **Claridad** - ¿Es fácil de entender?
5. **Valor** - ¿Ayuda a la comunidad?
### Cronograma:
- Las revisiones suelen tardar entre 3 y 7 días
- Los mantenedores pueden pedir cambios
- Te daremos feedback constructivo
- ¡Se fusiona (merge) cuando esté listo!
---
 
## Atribución
 
Al contribuir, aceptás que:
- Tu contribución puede usarse bajo la Licencia MIT
- Tenés el derecho de contribuir con este contenido
- No estás violando los derechos de nadie
- Estás cómodo con que sea público y de uso libre
---
 
## ¿Preguntas o necesitás ayuda?
 
- 📖 Leé el README.md
- 🔍 Revisá los Issues/PRs existentes
- 💬 Abrí una Discussion
- 📧 Escribime un DM si hace falta
---
 
## ¡Gracias! 🙏
 
Cada contribución —ya sea un solo prompt, una mejora o un feedback— ayuda a que este recurso sea mejor para todos. ¡Gracias por ser parte de la comunidad!
 
---
 
**¡Feliz contribución!**
 
Para más información, consultá:
- [Código de conducta](CODE_OF_CONDUCT.md)
- [Licencia](LICENSE)
- [README](README.md)
 
