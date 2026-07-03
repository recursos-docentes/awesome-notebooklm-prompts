# 🚀 Cómo subir esto a GitHub
 
Guía completa paso a paso para subir tu repositorio de NotebookLM Prompts a GitHub.
 
---
 
## Requisitos previos
 
Antes de empezar, asegurate de tener:
- ✅ Cuenta de GitHub (creala en [github.com](https://github.com) si hace falta)
- ✅ Git instalado en tu computadora ([git-scm.com](https://git-scm.com/))
- ✅ Todos los archivos del repositorio descargados de esta sesión
---
 
## Guía paso a paso
 
### Paso 1: Crear un nuevo repositorio en GitHub
 
1. **Andá a GitHub** → [github.com/new](https://github.com/new)
2. **Creá un nuevo repositorio:**
   - Nombre del repositorio: `awesome-notebooklm-prompts`
   - Descripción: "Una colección completa de más de 150 prompts de NotebookLM para crear presentaciones impactantes"
   - Visibilidad: **Público** (para que otros puedan descubrirlo)
   - Inicializar con: **NO** tildes "Add a README file" (ya tenemos uno)
   - Hacé clic en **Create repository**
3. **Copiá la URL de tu repositorio**
   - Vas a ver una URL como: `https://github.com/TU-USUARIO/awesome-notebooklm-prompts.git`
   - Guardala a mano para el siguiente paso
---
 
### Paso 2: Preparar tus archivos locales
 
1. **Creá una carpeta en tu computadora:**
```bash
   mkdir awesome-notebooklm-prompts
   cd awesome-notebooklm-prompts
```
 
2. **Copiá todos los archivos descargados dentro de esta carpeta:**
```
   awesome-notebooklm-prompts/
   ├── README.md
   ├── CONTRIBUTING.md
   ├── LICENSE
   ├── RESOURCES.md
   ├── .gitignore
   ├── notebooklm_complete_prompts.md
   ├── notebooklm_quick_reference.md
   └── examples/
       ├── academic-conference-presentation.md
       └── investor-pitch-deck.md
```
 
3. **Asegurate de que todos los archivos estén en su lugar:**
```bash
   ls -la
   # Debería mostrar todos los archivos listados arriba
```
 
---
 
### Paso 3: Inicializar Git y subir el repositorio
 
#### Opción A: Usando la línea de comandos (recomendado para la mayoría)
 
1. **Abrí la terminal/símbolo del sistema** en la carpeta
```bash
   cd awesome-notebooklm-prompts
```
 
2. **Inicializá Git:**
```bash
   git init
```
 
3. **Agregá todos los archivos:**
```bash
   git add .
```
 
4. **Creá el primer commit:**
```bash
   git commit -m "Initial commit: Add complete NotebookLM prompts library with 150+ prompts"
```
 
5. **Agregá el repositorio remoto** (reemplazá con TU URL):
```bash
   git remote add origin https://github.com/TU-USUARIO/awesome-notebooklm-prompts.git
```
 
6. **Verificá que se haya agregado el remoto:**
```bash
   git remote -v
   # Debería mostrar tu URL
```
 
7. **Subí el repositorio a GitHub:**
```bash
   git branch -M main
   git push -u origin main
```
 
8. **Ingresá tus credenciales de GitHub** cuando te las pida
   - Usuario: tu nombre de usuario de GitHub
   - Contraseña: tu token de acceso personal de GitHub (no tu contraseña habitual)
   **Cómo obtener un token de acceso personal:**
   - Andá a [github.com/settings/tokens](https://github.com/settings/tokens)
   - Hacé clic en "Generate new token"
   - Seleccioná el alcance: `repo` (control total de repositorios privados)
   - Copiá el token y usalo como contraseña
9. **¡Listo!** 🎉
```bash
   # Volvé a GitHub para verificar que funcionó
   # Deberías ver todos los archivos en: github.com/TU-USUARIO/awesome-notebooklm-prompts
```
 
#### Opción B: Usando GitHub Desktop (más fácil para principiantes)
 
1. **Descargá GitHub Desktop:** [desktop.github.com](https://desktop.github.com/)
2. **Instalalo e iniciá sesión** con tu cuenta de GitHub
3. **Creá un nuevo repositorio:**
   - File → New Repository
   - Nombre: `awesome-notebooklm-prompts`
   - Ruta local: elegí la carpeta donde están tus archivos
   - Hacé clic en Create
4. **Agregá los archivos:**
   - Los archivos deberían aparecer automáticamente
   - GitHub Desktop muestra la pestaña "Changes"
   - Escribí el mensaje de commit: "Initial commit: Add complete NotebookLM prompts library"
   - Hacé clic en Commit
5. **Publicá en GitHub:**
   - Hacé clic en el botón "Publish repository"
   - Hacelo público (opcional pero recomendado)
   - Hacé clic en Publish
6. **¡Listo!** 🎉
---
 
### Paso 4: Verificar tu repositorio
 
1. **Andá a GitHub:**
```
   https://github.com/TU-USUARIO/awesome-notebooklm-prompts
```
 
2. **Comprobá que veas:**
   - ✅ El README.md mostrándose correctamente
   - ✅ Todos los archivos en la carpeta raíz
   - ✅ La carpeta `examples/` con 2 archivos
   - ✅ Cantidad de archivos: 7 archivos markdown en total
3. **Asegurate de que el README se renderice bien**
   - GitHub debería mostrar tu README en la parte inferior de la página del repositorio
   - Todos los encabezados, enlaces y formato deberían verse bien
---
 
## Próximos pasos después de publicar
 
### 1. Agregar insignias (badges) a tu README
 
¡Las insignias de GitHub lucen tu repo! Agregá estas al inicio de tu README:
 
```markdown
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/TU-USUARIO/awesome-notebooklm-prompts?style=social)]()
```
 
Simplemente editá el README.md en GitHub y reemplazá `TU-USUARIO` con tu nombre de usuario real.
 
### 2. Crear temas (topics/labels)
 
Ayudá a que la gente descubra tu repositorio:
 
1. Andá a la configuración de tu repositorio
2. En "Topics", agregá:
   - `notebooklm`
   - `prompts`
   - `presentation`
   - `ai-tools`
   - `awesome-list`
   - `gemini`
### 3. Agregarlo a listas "awesome"
 
Ahora que tenés un buen repositorio, podés agregarlo a listas "awesome" existentes:
 
1. Buscá listas "awesome" relacionadas con NotebookLM o prompts
2. Hacé un fork del repositorio
3. Agregá tu repositorio a la lista
4. Enviá un pull request
Listas "awesome" populares para sumarte:
- [serenakeyitan/awesome-notebookLM-prompts](https://github.com/serenakeyitan/awesome-notebookLM-prompts) - **Contactá al mantenedor**
- [awesome-list](https://github.com/topics/awesome)
- Listas "awesome" relacionadas con IA/Prompts
### 4. Compartir tu repositorio
 
Contale a la gente sobre tu trabajo:
 
**Compartí en:**
- Twitter/X: `Acabo de publicar "awesome-notebooklm-prompts" - más de 150 prompts probados en la práctica para crear presentaciones impactantes con NotebookLM 🚀`
- LinkedIn: publicá sobre tu recurso y por qué lo creaste
- Reddit: compartilo en [r/notebooklm](https://www.reddit.com/r/notebooklm/)
- Discord: compartilo en comunidades de NotebookLM
- Email: enviaselo a comunidades interesadas
**Ejemplo de tweet:**
```
Acabo de publicar awesome-notebooklm-prompts 🎨
 
Más de 150 prompts probados en la práctica para crear presentaciones impactantes:
✨ Más de 20 estilos de diseño
✨ 6 formatos de presentación
✨ Ejemplos reales
✨ Guía de inicio rápido
 
Perfecto para investigadores, creadores, emprendedores y educadores.
 
github.com/TU-USUARIO/awesome-notebooklm-prompts
 
#NotebookLM #IA #Presentaciones
```
 
### 5. Configurar GitHub Pages (opcional)
 
Armá una hermosa página de aterrizaje para tu repositorio:
 
1. Andá a Settings → Pages
2. Configurá la fuente en la rama `main`
3. Elegí un tema
4. Tu sitio va a estar en: `TU-USUARIO.github.io/awesome-notebooklm-prompts`
---
 
## Actualizar tu repositorio más adelante
 
Una vez que tu repo esté en GitHub, así es como agregás actualizaciones:
 
### Agregar nuevos prompts
 
1. **Editá los archivos localmente:**
```bash
   # Abrí los archivos, hacé los cambios
   nano COMPLETE_PROMPTS.md
```
 
2. **Hacé commit y subí los cambios:**
```bash
   git add .
   git commit -m "Add: [descripción de lo que agregaste]"
   git push origin main
```
 
3. **Tus cambios aparecen en GitHub de inmediato** ✨
### Aceptar contribuciones
 
Cuando la gente envíe pull requests:
 
1. GitHub te avisa sobre el nuevo PR
2. Revisá los cambios
3. Hacé clic en "Merge pull request" para aceptarlo
4. ¡El contribuyente recibe el crédito!
---
 
## Solución de problemas
 
### "Authentication failed" (falló la autenticación)
- Asegurate de estar usando un **token de acceso personal**, no tu contraseña de GitHub
- Generá uno en: [github.com/settings/tokens](https://github.com/settings/tokens)
### "Permission denied (publickey)"
- Generalmente es un problema con la clave SSH
- Usá la URL HTTPS en su lugar: `https://github.com/TU-USUARIO/repo.git`
- O configurá SSH: [github.com/settings/keys](https://github.com/settings/keys)
### "Cannot push to remote" (no se puede subir al remoto)
- Asegurate de estar en el directorio correcto: `cd awesome-notebooklm-prompts`
- Verificá la URL remota: `git remote -v`
- Si está mal, corregila: `git remote set-url origin [URL-correcta]`
### "README not showing" (el README no se muestra)
- Asegurate de que el archivo se llame exactamente `README.md` (con mayúscula)
- Hacé commit y subilo: `git add README.md && git commit -m "Fix README" && git push`
### Los archivos se ven mal en GitHub
- Recargá la página (recarga forzada: Cmd+Shift+R o Ctrl+Shift+R)
- Esperá unos segundos a que GitHub lo procese
---
 
## Chuleta de comandos
 
```bash
# Configuración inicial
git init
git add .
git commit -m "Initial commit: mensaje"
git branch -M main
git remote add origin [TU-URL]
git push -u origin main
 
# Actualizaciones diarias
git add .
git commit -m "Tu mensaje"
git push
 
# Verificar estado
git status
git log --oneline
 
# Ver remoto
git remote -v
 
# Deshacer el último commit (antes del push)
git reset --soft HEAD~1
```
 
---
 
## Estadísticas de GitHub (interesantes para seguir)
 
Una vez que tu repo esté publicado, GitHub registra:
- ⭐ **Stars** - Cuánta gente lo valora
- 👀 **Watchers** - Quién sigue las actualizaciones
- 🍴 **Forks** - Cuánta gente lo copió para modificarlo
- 📊 **Traffic** - Cuántas visitas hay por día
- 💬 **Discussions** - Conversaciones de la comunidad
- 🔔 **Issues** - Reportes de errores y pedidos de funcionalidades
Podés ver todo esto en la pestaña "Insights" de tu repositorio.
 
---
 
## Consejos profesionales
 
### 1. Usá buenos mensajes de commit
```
✅ BIEN: "Add: Neo-Retro Dev Deck style with specifications"
✅ BIEN: "Improve: Clarify Sharp-Edged Minimalism checklist"
❌ MAL: "update"
❌ MAL: "fix stuff"
```
 
### 2. Creá un Release
Cuando tengas una versión estable:
1. Andá a la pestaña "Releases"
2. Hacé clic en "Create a new release"
3. Etiquetá la versión (por ejemplo, v1.0.0)
4. Agregá notas de la versión
5. La gente puede descargar versiones específicas
### 3. Agregá un CHANGELOG
Llevá registro de los cambios a lo largo del tiempo:
```markdown
## [1.0.0] - 2026-03-24
### Agregado
- Lanzamiento inicial con más de 150 prompts
- Más de 20 estilos de diseño con especificaciones
- Guía de referencia rápida
- 2 ejemplos detallados
 
### Cambiado
- Organizado por formato de presentación
 
### Corregido
- Mejor claridad en los prompts
```
 
### 4. Actualizaciones regulares
- Agregá nuevos prompts a medida que los descubras
- Corregí errores tipográficos y aclará contenidos
- Actualizá los ejemplos con resultados reales
- Mantené a la comunidad activa
---
 
## ¡Éxito! 🎉
 
Ahora tenés:
- ✅ Repositorio de GitHub creado
- ✅ Más de 150 prompts publicados
- ✅ Documentación README bien presentada
- ✅ Guías de contribución para otros
- ✅ Todo listo para que la comunidad lo descubra
---
 
## Siguiente paso: compartir y crecer
 
### Semana 1: Configuración y difusión
- [ ] Publicar en GitHub (¡ya lo hiciste!)
- [ ] Compartir en redes sociales
- [ ] Agregar topics de GitHub
- [ ] Compartir en comunidades
### Semanas 2-4: Interacción
- [ ] Responder preguntas/issues
- [ ] Agregar más ejemplos
- [ ] Refinar según el feedback
- [ ] Agradecer a los contribuyentes
### Mes 2 en adelante: Crecimiento
- [ ] Alcanzar 100 stars
- [ ] Recibir las primeras contribuciones de la comunidad
- [ ] Ampliar con tutoriales en video
- [ ] Construir una comunidad alrededor del proyecto
---
 
## ¿Preguntas?
 
Si te trabás:
1. Revisá las guías oficiales de GitHub: [github.com/docs](https://github.com/docs)
2. Buscá tu error en Stack Overflow
3. Preguntá en [r/github](https://www.reddit.com/r/github/)
4. Revisá el archivo CONTRIBUTING.md
---
 
**¡Felicitaciones por publicarlo! Creaste un recurso increíble para la comunidad.** 🚀
 
Ahora andá y ayudá a miles de creadores a construir presentaciones impactantes con NotebookLM!
 
---
 
**Versión**: 1.0
**Última actualización**: 24 de marzo de 2026
