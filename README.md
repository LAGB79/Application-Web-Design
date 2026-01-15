#Informacion del estudiante

* **NOMBRE:** [Luis Alonso Garcia Barron]
* **MATRICULA:** [AL03107051]
* **CARRERA** [IDS]
* **SEMESTRE** [Sextro]

##INFORMACION DE LA MATERIA

* **MATERIA:** [Diseño de aplicaciones web]
* **PROFESOR** [Fernando Añudo B]

###**Markdown** 
Markdown es un lenguaje de marcado ligero creado para redactar texto con formato de manera sencilla y legible. A diferencia de los procesadores de texto complejos como Word, Markdown utiliza caracteres simples de puntuación como asteriscos, guiones y almohadillas para definir estilos como negritas, listas o encabezados.

## Opciones de Etiquetado en Markdown
Markdown ofrece diversas opciones para dar formato al texto de manera simple:

* **Encabezados:** Se utilizan almohadillas para jerarquizar el contenido (ej. `# Título`, `## Subtítulo`).
* **Énfasis:**
  * **Negrita:** Se usa doble asterisco (`**texto**`).
  * *Cursiva:* Se usa un solo asterisco (`*texto*`).
* **Listas:**
  * **No ordenadas:** Se usan guiones (`-`) o asteriscos (`*`).
  * **Ordenadas:** Se usan números (`1.`, `2.`).
* **Código:**
  * En línea: Se usan comillas invertidas simples (`` `codigo` ``).
  * Bloque: Se usan tres comillas invertidas (\`\`\`).
* **Enlaces e Imágenes:**
  * Enlaces: `[Texto](url)`
  * Imágenes: `![Texto alternativo](url_imagen)`

## Comandos de Git Utilizados

### 1. Estado y Preparación
* **Verificar estado del repositorio:**
  `git status`
* **Agregar archivos al área de preparación (Staging):**
  * Un archivo específico: `git add nombre_archivo.ext`
  * Todos los archivos (Global): `git add .`

### 2. Guardar Cambios
* **Crear un commit con comentario:**
  `git commit -m "Tu comentario descriptivo aquí"`

### 3. Sincronización Remota
* **Subir cambios al repositorio remoto:**
  `git push origin main`

### 4. Gestión de Ramas (Branches)
* **Crear una rama:** `git branch nombre_rama`
* **Navegar/Listar ramas (Browse):**
  * Ver ramas existentes: `git branch`
  * Cambiar de rama: `git checkout nombre_rama`
* **Eliminar una rama:** `git branch -d nombre_rama`

### 5. Restaurar Repositorio
* **Regresar a un commit específico (Roll back):**
  `git reset --hard <hash_del_commit>`