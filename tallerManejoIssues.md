id: aca-012025-taller-03
summary: Taller 3 - Manejo de issues
categories: git, version control, issues
status: Published
authors: Metzi Aguilar, David Garcia, Erika Paz, Kevin Escobar

## Introducción al concepto de Issues

### 1.1 ¿Qué es un issue en GitHub?

En GitHub, un issue representa una entrada de seguimiento dentro de un repositorio. Se utiliza como una herramienta para documentar y gestionar tareas, errores, ideas o solicitudes relacionadas con el proyecto. Cada issue contiene un título, una descripción y puede incluir etiquetas, comentarios, asignaciones, referencias al código y más.

Su funcionamiento es similar al de un ticket en un sistema de soporte: se crea cuando se detecta o se plantea algo que debe abordarse, y permanece abierto hasta que se resuelve y se cierra.

### 1.2 Un issue no siempre es un problema

Aunque comúnmente se asocia el término issue con un error3. 3. 
### 1.3 ¿Para qué se usa?
Los issues se emplean para diversos fines dentro del desarrollo de software y la gestión de proyectos. Entre los usos más comunes se encuentran los siguientes:

- Reporte de errores (bugs) detectados en el sistema
- Registro de tareas pendientes por implementar
- Propuestas de mejora en funcionalidades existentes
- Solicitudes de nuevas características
- Anotaciones de problemas relacionados con la documentación
- Discusión de decisiones técnicas o estratégicas

Gracias a su versatilidad, los issues permiten mantener centralizada la información relevante sobre el estado y evolución de un proyecto.

### 1.4 Ventajas de su uso en un equipo
La utilización sistemática de issues ofrece múltiples beneficios en contextos colaborativos, entre los cuales se destacan:

- Mejora la comunicación entre los miembros del equipo
- Facilita el seguimiento de tareas y responsabilidades
- Aumenta la transparencia sobre el estado del proyecto
- Permite organizar el trabajo de forma más eficiente
- Proporciona un historial consultable de decisiones y problemas abordados
- Favorece la vinculación entre código y gestión del proyecto

Además, GitHub permite relacionar directamente los issues con commits o pull requests, lo cual fortalece la trazabilidad entre el trabajo realizado y los objetivos planteados.

## Exploración del panel de Issues en GitHub

El panel de issues en GitHub constituye el espacio principal desde el cual se gestionan todos los asuntos registrados dentro de un repositorio. A través de esta interfaz es posible visualizar, filtrar, clasificar y actualizar los issues según su estado y características.

A continuación, se describen los elementos fundamentales que componen dicho panel.

### 2.1 Acceso al panel de Issues
El panel de issues se encuentra en la parte superior de cualquier repositorio público o privado, dentro de la pestaña identificada como “Issues”. Al hacer clic en dicha pestaña, se mostrará una lista con todos los issues existentes en el repositorio.

### 2.2 Visualización general
La vista principal del panel presenta los issues en formato de lista. Cada entrada incluye un título, un número identificador precedido por `#`, el nombre del autor, la fecha de creación y el estado (abierto o cerrado). También se muestran etiquetas (labels) si han sido aplicadas, así como posibles asignaciones y hitos (milestones).

### 2.3 Filtros y búsqueda
En la parte superior del listado se encuentra una barra de búsqueda que permite filtrar los issues según diversos criterios:

- Estado: abiertos (`is:open`) o cerrados (`is:closed`)
- Autor (`author:nombre_usuario`)
- Responsable asignado (`assignee:nombre_usuario`)
- Etiquetas específicas (`label:etiqueta`)
- Contenido por palabras clave

Esta funcionalidad permite localizar rápidamente issues relevantes dentro de un repositorio con gran volumen de entradas.

### 2.4 Clasificación y organización
Además de los filtros, GitHub permite organizar los issues mediante:

- **Etiquetas (labels):** Categorías visuales que ayudan a identificar el tipo de issue (por ejemplo, `bug`, `enhancement`, `question`).
- **Asignaciones (assignees):** Usuarios responsables de atender el issue.
- **Hitos (milestones):** Agrupaciones por versión o fase del proyecto.
- **Proyectos (projects):** Tableros de trabajo tipo kanban donde se visualiza el avance de los issues según su estado.

## Creación de un issue

El proceso de creación de un issue en GitHub permite registrar formalmente una tarea, error, propuesta o inquietud dentro del repositorio. Esta acción constituye el primer paso para garantizar su seguimiento y resolución por parte del equipo.

Para que un issue sea útil, debe estar redactado de forma clara, estructurada y contener la información necesaria para su comprensión y atención.

### 3.1 Título del issue
El título debe resumir de forma precisa el propósito del issue. Se recomienda utilizar una redacción breve, pero suficientemente descriptiva, que permita identificar el contenido sin necesidad de abrir la entrada completa.

Ejemplos:
- “Error al guardar formularios con campos vacíos”
- “Propuesta de mejora en el sistema de autenticación”
- “Agregar validaciones al formulario de contacto”

### 3.2 Cuerpo del issue
El cuerpo constituye el espacio principal para detallar el contenido. Puede redactarse de forma libre o estructurada, aunque se recomienda seguir un formato que incluya los siguientes elementos:

- **Contexto:** Descripción general del entorno o módulo en el que se ha detectado o se desea aplicar el cambio.
- **Descripción detallada:** Explicación clara del problema, tarea o sugerencia.
- **Pasos para reproducir (en caso de errores):** Secuencia necesaria para replicar el comportamiento observado.
- **Resultado actual vs. resultado esperado:** Comparación que permite evidenciar el desvío o justificar la necesidad del cambio.
- **Evidencia complementaria:** Capturas de pantalla, fragmentos de código o enlaces útiles.

### 3.3 Asignación de responsables (Assignees)
GitHub permite asignar uno o más usuarios como responsables del issue. Esta asignación facilita la distribución del trabajo y deja constancia de quién está encargado de resolver el asunto.

### 3.4 Aplicación de etiquetas (Labels)
Las etiquetas permiten clasificar el issue según su naturaleza. Algunas etiquetas comunes incluyen:

- `bug`: indica un error o mal funcionamiento
- `enhancement`: sugiere una mejora
- `question`: plantea una duda
- `documentation`: se refiere a contenido escrito del proyecto

La utilización coherente de etiquetas facilita la navegación y el filtrado posterior.

### 3.5 Asociación a hitos (*Milestones*)
Los hitos permiten agrupar issues relacionados con una versión específica del proyecto, una fase de trabajo o una fecha de entrega. Esta funcionalidad resulta útil para planificar y visualizar el avance del desarrollo en etapas.

## Seguimiento y trabajo con issues
Una vez creado un issue, comienza el proceso de seguimiento y colaboración para resolverlo o completarlo. GitHub proporciona diversas funcionalidades que permiten gestionar esta actividad de manera eficiente, registrando cada intervención y facilitando la colaboración entre los miembros del equipo.

### 4.1 Comentarios y discusión
Dentro de cada issue, se dispone de un espacio para comentarios. En este apartado se puede:

- Discutir detalles técnicos o funcionales relacionados con el issue
- Proponer soluciones y alternativas
- Compartir enlaces o evidencia adicional
- Hacer preguntas o aclaraciones

Cada comentario queda registrado con fecha, hora y autor, lo que permite reconstruir el historial completo de la conversación.

### 4.2 Referencias a código y otros elementos
GitHub permite vincular un issue con otros elementos del repositorio mediante menciones. Estas referencias se hacen utilizando el símbolo `#` seguido del número del issue, pull request o commit correspondiente.

Ejemplos:

- `Relacionado con #12`
- `Soluciona #45`
- `Ver commit 9d3a1b7`

Estas referencias ayudan a establecer conexiones claras entre el issue y el trabajo realizado en el código fuente.

### 4.3 Tareas dentro de un issue
Cuando un issue contiene varias subtareas, se puede incluir una lista de verificación (checklist) utilizando la siguiente sintaxis en Markdown:

```
- [ ] Validar los campos del formulario
- [ ] Implementar el mensaje de error
- [ ] Escribir pruebas unitarias
```

Una vez completada una tarea, puede marcarse como hecha (`- [x]`). Esto permite llevar un control visual del avance dentro del mismo issue.

### 4.4 Cambios de estado
Un issue puede encontrarse en uno de los siguientes estados:

- **Abierto:** aún no ha sido resuelto o está en proceso.
- **Cerrado:** ha sido resuelto satisfactoriamente o se ha descartado.

El estado puede actualizarse manualmente desde la interfaz de GitHub, o bien automáticamente al completar una pull request que lo referencie con expresiones como:

- `Closes #10`
- `Fixes #8`
- `Resolves #15`

Este cierre automático asegura que el seguimiento quede correctamente documentado.

## Cierre de issues
El cierre de un issue representa el momento en que la tarea, problema o solicitud planteada ha sido resuelta o atendida de manera satisfactoria. Esta acción marca formalmente la conclusión del seguimiento dentro del repositorio y contribuye a mantener actualizado el estado del proyecto.

### 5.1 Cierre manual
Un issue puede cerrarse manualmente desde la interfaz de GitHub. Para ello, se debe acceder al issue correspondiente y hacer clic en el botón “**Close issue**” ubicado al final de la conversación. Esta opción es adecuada cuando la solución se ha implementado directamente o cuando se desea archivar un issue por decisión del equipo.

### 5.2 Cierre automático mediante pull request
GitHub permite automatizar el cierre de issues cuando se integran soluciones mediante pull requests. Para ello, dentro del mensaje del commit o de la descripción del pull request, se incluye una expresión como:

```
Closes #12
Fixes #7
Resolves #5
```

Al fusionar el pull request que contiene dicha expresión, el issue correspondiente será cerrado automáticamente. Esta funcionalidad mejora la trazabilidad entre el código y la gestión de tareas.

### 5.3 Reapertura de un issue
En caso de que un issue haya sido cerrado por error, o que el problema persista tras su aparente resolución, es posible reabrirlo. Para ello, se utiliza el botón “**Reopen issue**”, visible en la parte inferior de un issue cerrado.

Esta opción garantiza que ningún asunto quede sin atender en caso de resoluciones prematuras o insuficientes.

## Buenas prácticas
El uso correcto y coherente de los issues favorece la organización, la eficiencia y la calidad del trabajo colaborativo dentro de un proyecto. A continuación, se describen algunas prácticas recomendadas para asegurar un manejo adecuado de los issues en GitHub.

### 6.1 Uso de plantillas de issues (Issue Templates)
GitHub permite crear plantillas personalizadas para estandarizar la redacción de los issues en un repositorio. Estas plantillas ayudan a que todos los reportes contengan la información mínima necesaria, facilitando su comprensión y posterior resolución.

Las plantillas se definen mediante archivos en formato Markdown ubicados en la ruta:

```
.github/ISSUE_TEMPLATE/
```

Cada archivo representa una plantilla distinta y puede estar acompañado por un archivo de configuración llamado `config.yml`.

Ejemplo de plantilla simple (`bug_report.md`):

```
---
name: Reporte de error
about: Reportar un fallo o comportamiento inesperado en el sistema
---

## Descripción del error
Describir claramente el problema encontrado.

## Pasos para reproducir
1. Ir a '...'
2. Hacer clic en '...'
3. Observar el resultado

## Resultado esperado
Describir qué se esperaba que ocurriera.

## Evidencia
Agregar capturas de pantalla, enlaces o cualquier información relevante.
```

Ejemplo de plantilla para feature (`new_feature.md`):

```
---
name: Solicitud de funcionalidad
about: Proponer una nueva característica o mejora para el proyecto
title: "[Feature] "
labels: enhancement
assignees: 
---

## Descripción de la funcionalidad
Describir de forma clara y concisa la nueva funcionalidad que se desea incorporar.

## Justificación
Explicar por qué esta funcionalidad es necesaria o qué problema resuelve. Incluir cualquier beneficio esperado.

## Propuesta de solución
Describir cómo se podría implementar esta funcionalidad. Si es posible, incluir una idea general del flujo o cambios requeridos.

## Alternativas consideradas
Mencionar otras opciones que hayan sido consideradas y explicar por qué no se eligieron.

## Información adicional
Agregar cualquier otro dato útil, como capturas de pantalla, enlaces de referencia, diagramas o ejemplos relacionados.
```

Al utilizar plantillas, se logra:

- Reducir omisiones de información importante
- Homogeneizar la redacción de los issues
- Facilitar el trabajo de quienes dan seguimiento
- Agilizar la toma de decisiones

El uso de plantillas resulta especialmente útil en proyectos colaborativos, abiertos o con múltiples mantenedores.

### 6.2 Otras buenas prácticas:

- **Etiquetado coherente:**
Se recomienda aplicar etiquetas de forma consistente para clasificar los issues. Esto permite filtrar entradas con facilidad y detectar patrones recurrentes, como errores frecuentes o solicitudes comunes.

- **Asignación de responsables:**
Asignar al menos una persona encargada de cada issue contribuye a evitar ambigüedades sobre quién debe atender el asunto. También permite distribuir adecuadamente la carga de trabajo dentro del equipo.

- **Actualización periódica:**
Los issues deben mantenerse actualizados. Si cambian las condiciones, el estado del desarrollo o se encuentra una solución alternativa, es importante dejar constancia en los comentarios. Esto permite que toda la información relevante permanezca centralizada.

- **Evitar duplicados:**
Antes de crear un nuevo issue, se recomienda realizar una búsqueda para comprobar si el asunto ya ha sido reportado. Evitar duplicados ayuda a concentrar la discusión y evita dispersión de esfuerzos.

##a Actividad práctica

## Actividad práctica: Gestión colaborativa de Issues

### Objetivo
El objetivo de esta actividad es poner en práctica el uso correcto de issues en un entorno colaborativo, aplicando las buenas prácticas de documentación, asignación, clasificación, referencia y cierre mediante pull requests, utilizando además convenciones profesionales en el manejo de Git.

### Instrucciones

Cada estudiante deberá colaborar activamente en un repositorio compartido siguiendo las siguientes indicaciones:

#### 1. Creación de Issues

- Deberás crear **dos issues** en el repositorio:
  - Un **issue de tipo feature** (nueva funcionalidad).
  - Un **issue de tipo bug** (reporte de error).
- Cada issue debe estar **correctamente documentado** utilizando las plantillas proporcionadas (`new_feature.md` y `bug_report.md`) e incluir:
  - Un título claro y descriptivo.
  - Cuerpo estructurado según la plantilla correspondiente.
  - Asignación de al menos un **responsable (assignee)**.
  - Aplicación de **etiquetas (labels)** acordes (`enhancement`, `bug`, etc.).
  - Asociación a un **milestone** y a un **project** en el tablero del repositorio.

#### 2. Participación colaborativa

- Deberás participar activamente en la **discusión de al menos un issue creado por otro compañero/a**, realizando comentarios significativos que aporten al análisis, propuesta de solución o mejora del issue.

#### 3. Cierre de un issue

- Deberás **cerrar uno de tus propios issues** (feature o bug) mediante una **pull request que lo cierre automáticamente**, utilizando expresiones como `Closes #X`, `Fixes #Y`, etc.
- El **issue que cierres debe haber contado con al menos una participación de otro compañero/a en la discusión**.

#### 4. Entrega final

- La pull request de cierre deberá incluir un archivo en formato Markdown con la siguiente información:
  ```markdown
  ## Información del estudiante
  - Nombre completo: [Nombre]
  - Carné: [Carné]

  ## Referencias a los Issues
  - Issue de feature: #X
  - Issue de bug: #Y
  - Issue comentado (discusión): #Z
  ```

### Criterios de evaluación

| Criterio                                              | Puntos |
|--------------------------------------------------------|--------|
| Creación correcta del issue de feature                 | 2 pts  |
| Creación correcta del issue de bug                     | 2 pts  |
| Uso adecuado de labels, milestone, project y assignee  | 1 pt   |
| Participación significativa en un issue ajeno          | 1 pt   |
| Pull request que cierra correctamente un issue         | 2 pts  |
| Archivo Markdown con información solicitada            | 1 pt   |
| Uso de **Conventional Commits** en todos los commits   | 0.5 pt |
| Aplicación de **GitFlow** en el trabajo colaborativo   | 0.5 pt |
| **Total**                                              | **10** |

### Consideraciones adicionales

- Es obligatorio el uso de **conventional commits** para todos los mensajes de commit. Ejemplos:
  - `feat: agregar autenticación con GitHub`
  - `fix: corregir validación de formularios`
- El flujo de trabajo debe seguir el modelo **GitFlow**, utilizando ramas como `feature/`, `bugfix/`, `release/`, etc.
- La entrega se considerará incompleta si los issues no cumplen completamente con las estructuras de las plantillas.