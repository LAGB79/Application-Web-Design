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

---

## Opciones de Etiquetado de Markdown

* **Encabezados:** Se definen con almohadillas (`#`).
    * `# Título 1`
    * `## Título 2`
* **Énfasis:**
    * **Negrita:** Se encierra el texto en `**` (ej. `**Texto**`).
    * *Cursiva:* Se encierra el texto en `*` (ej. `*Texto*`).
* **Listas:**
    * **No ordenadas:** Usan guiones (`-`) o asteriscos (`*`).
    * **Ordenadas:** Usan números seguidos de un punto (`1.`).
* **Enlaces e Imágenes:**
    * Enlace: `[Texto](URL)`
    * Imagen: `![Descripción](Ruta de imagen)`
* **Bloques de Código:** Se usan tres comillas invertidas (\`\`\`) antes y después del código.

## Comandos Básicos de Git

### 1. Estado y Preparación
* **Verificar el estado del repositorio:**
    `git status`
    *Muestra qué archivos han cambiado o están listos para guardarse.*

* **Agregar archivos:**
    * Individualmente: `git add nombre_del_archivo.ext`
    * Globalmente (todos los cambios): `git add .`

### 2. Guardar Cambios (Commit)
* **Añadir comentarios al commit:**
    `git commit -m "Escribe aquí tu descripción del cambio"`

### 3. Sincronización
* **Subir cambios al repositorio remoto:**
    `git push origin main`
    *(Nota: `main` es la rama principal, a veces puede llamarse `master`).*

### 4. Gestión de Ramas (Branches)
* **Crear una rama:** `git branch nombre_nueva_rama`
* **Navegar (cambiar) de rama:** `git checkout nombre_rama` (o `git switch nombre_rama`)
* **Listar ramas:** `git branch`
* **Eliminar una rama:** `git branch -d nombre_rama`

### 5. Historial y Restauración
* **Regresar (Roll back) a un commit específico:**
    `git reset --hard <hash_del_commit>`
    *(Advertencia: Esto borra los cambios hechos después de ese commit).*