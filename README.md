# Taller colaborativo: mejora Forestando Juntos

Una experiencia abierta para probar el registro de árboles, detectar dificultades y preparar una propuesta que ayude a mejorar Forestando Juntos, su interacción con las personas y las estadísticas de las siembras registradas.

**El resultado del taller es una propuesta documentada para revisión del administrador.** No se requieren conocimientos de programación. El administrador decide e implementa los cambios en el sitio.

- **Sitio:** [forestandojuntos.org](https://forestandojuntos.org/).
- **Repositorio:** [fbarriac/ForestandoJuntos](https://github.com/fbarriac/ForestandoJuntos). Un repositorio es el espacio de GitHub que reúne los archivos y el historial de un proyecto.
- **Duración:** [PENDIENTE: duración acordada del taller].

> Primera versión de la guía. La secuencia de actividades y el formato de entrega que siguen son una propuesta de organización del taller. La descripción del funcionamiento se apoya en la información del administrador, las capturas compartidas y el manual del sembrador; no constituye una prueba independiente del sitio.

## Objetivo y público

Al terminar, podrás identificar una necesidad concreta, respaldarla con una observación y redactar una mejora con criterios que permitan comprobar su resultado.

Puede participar cualquier persona interesada: miembros de la organización, estudiantes, docentes y otros colaboradores. Basta con poder navegar por una página y completar un formulario; los pasos de GitHub se explican en la guía de participación.

## Estado actual

El sitio está en periodo de pruebas, antes de su difusión general. Según el administrador:

- Las personas reciben un plantón, lo siembran y registran la siembra con fotografía, ubicación y datos del árbol y del sembrador.
- Las siembras registradas se pueden ubicar en un mapa.
- El panel administrativo muestra el total de árboles registrados y los conteos por provincia y tipo de árbol. Su acceso está reservado al administrador.
- Se probaron registros ficticios con varias personas. Se detectaron fallos intermitentes al guardar, que el administrador informa como corregidos. Las pruebas continúan.

Las capturas muestran campos para ubicación, especie, fecha, provincia, entorno, referencia del lugar, datos del sembrador, fotografía y un PIN de cuatro dígitos. El manual explica el registro, pero omite el paso del PIN y presenta un orden diferente al del formulario capturado.

**Pendiente de verificar:** guardar y sincronizar sin internet, comprobante por WhatsApp, aprobación administrativa antes de la publicación, seguimiento mediante PIN y descarga del certificado. Son funciones descritas en el manual o anunciadas en las capturas; no se han aportado pruebas de su funcionamiento durante la preparación de esta guía.

## Requisitos y preparación

- Celular o computadora con navegador e internet. Para esta actividad se propone trabajar con conexión.
- Acceso al sitio y al manual disponible en su menú «Guía / Manual».
- Una fotografía para el registro de prueba. La pantalla compartida indica JPG o PNG, con un máximo de 10 MB.
- Permiso de ubicación si decides usar el GPS, que es el sistema que permite al dispositivo obtener su posición.
- Un lugar donde tomar notas. Para publicar aportes en GitHub necesitarás una cuenta y acceso al repositorio.

No necesitas acceso administrativo ni instalar programas de desarrollo.

**Pruebas autorizadas:** el administrador permite registros ficticios en el sitio actual durante esta etapa y puede eliminarlos después. No hay una versión de pruebas separada. Como convención propuesta para el taller, usa un nombre público que comience con «PRUEBA TALLER» y aclara en la referencia del lugar que es una siembra ficticia.

Si el formulario exige correo o teléfono, utiliza un medio de contacto que controles. Evita datos de terceros y guarda el PIN de forma privada.

## Actividad paso a paso

### 1. Explora y elige qué observar

Abre el sitio, consulta el manual y localiza el registro y el mapa. Piensa en una pregunta concreta: ¿se entiende cómo ubicar el árbol?, ¿qué ocurre después de enviar?, ¿se explica para qué sirve el PIN?

Toma como referencia las estadísticas que el administrador ya confirma: total, provincia y tipo de árbol. No necesitas entrar al panel para proponer una mejora; indica cuándo una idea requeriría información que solo puede aportar el administrador.

### 2. Realiza un registro de prueba

Sigue el manual y las instrucciones del formulario. En las capturas, los controles están organizados así:

1. Abre «Registrar Siembra» o «Registrar Mi Árbol», según el botón visible.
2. Selecciona la ubicación en el mapa. «Usar mi GPS Actual» obtiene la posición del dispositivo; comprueba si corresponde al lugar que quieres indicar y ajusta el marcador cuando sea necesario.
3. Completa especie, fecha de siembra, provincia, entorno y referencia del lugar. Identifica el registro como ficticio.
4. Completa los datos del sembrador y el nombre público propuesto para las pruebas.
5. Adjunta la fotografía mediante «Tomar con Cámara» o «Elegir de Galería».
6. Introduce un PIN de cuatro dígitos o utiliza «Generar PIN aleatorio» y guárdalo.
7. Envía el formulario usando el control disponible al final. Anota si aparece una confirmación, un código o un mensaje de error; no des por guardado el registro solo por haber pulsado el botón.

Si la pantalla difiere de esta guía, registra la diferencia como un hallazgo. Si no puedes completar un paso, documenta el impedimento y continúa con tu propuesta usando esa evidencia.

### 3. Comprueba y documenta lo observado

Busca la siembra en el mapa y anota el resultado. El manual indica que hay revisión administrativa antes de la publicación; ese flujo queda pendiente de confirmar, por lo que la ausencia inmediata del marcador no demuestra por sí sola un fallo.

Registra fecha, dispositivo, navegador, pasos realizados, resultado esperado y resultado observado. Si hay un error, copia su mensaje. En las capturas de evidencia, oculta datos personales y PIN.

Conserva el nombre público y el código del registro, si se generó, para que el administrador pueda identificarlo y eliminarlo. Solicita su revisión en tu aporte y deja constancia cuando confirme la limpieza.

### 4. Escoge una sola mejora

Delimita un cambio que pueda entenderse y evaluarse por separado. Estas son **sugerencias para explorar**, no funciones implementadas ni decisiones aprobadas:

| Enfoque | Ejemplo de propuesta |
| --- | --- |
| Instrucciones | Añadir al manual una explicación del PIN. |
| Interacción | Mejorar el mensaje que aparece cuando un registro no se guarda. |
| Estadísticas | Filtrar los conteos por fecha de siembra y provincia. |
| Calidad de los datos | Proponer cómo distinguir registros de prueba de siembras reales en los conteos. |

Si propones una estadística, explica qué pregunta responde, qué datos necesita, cuáles ya se recogen y cómo se agruparían o calcularían. Un ejemplo con números ficticios puede mostrar el resultado esperado. Los conteos de registros, por sí solos, no demuestran supervivencia de árboles ni impacto ecológico.

### 5. Redacta y entrega tu propuesta

Usa el formato de [CONTRIBUTING.md](CONTRIBUTING.md). Distingue lo observado, lo informado por otra persona, lo sugerido y lo que falta probar.

La vía propuesta de entrega es un **issue**, un espacio de GitHub para documentar una tarea, un problema o una idea y conversar sobre ella. Consulta la guía de participación para publicarlo. Si no tienes acceso, conserva la propuesta completa y registra ese impedimento; la habilitación del acceso queda pendiente del responsable del repositorio.

## Resultado esperado y comprobación

El taller produce una propuesta lista para que el administrador la analice. Comprueba que:

- [ ] Describe una sola necesidad concreta y a quién beneficia resolverla.
- [ ] Incluye evidencia o señala claramente qué no se pudo probar.
- [ ] Explica el cambio propuesto y cómo comprobar su resultado.
- [ ] Distingue funciones existentes, sugerencias y pendientes.
- [ ] Incluye los datos necesarios para identificar cualquier registro ficticio utilizado y solicitar su eliminación.
- [ ] Está publicada en un issue, o se conserva completa con el impedimento de publicación documentado.

La aceptación e implementación de la propuesta son decisiones posteriores del administrador.

## Materiales y ubicación

README.md y CONTRIBUTING.md son los documentos de esta primera versión, propuestos para el nivel principal del repositorio. No se pudo consultar la organización existente del repositorio desde el entorno donde se preparó esta guía.

| Material | Ubicación o estado |
| --- | --- |
| Guía del taller | Este README.md. |
| Guía para colaborar | [CONTRIBUTING.md](CONTRIBUTING.md). |
| Sitio para las pruebas | [forestandojuntos.org](https://forestandojuntos.org/). |
| Manual del sembrador | Menú «Guía / Manual» del sitio. [PENDIENTE: ruta o enlace directo al manual dentro del repositorio]. |
| Primer issue propuesto | El borrador PRIMER_ISSUE.md de este paquete está listo para copiar como título y descripción de una tarea; todavía no está publicado. |

## Dificultades y pendientes

- Repetir y documentar las pruebas de guardado después de las correcciones reportadas.
- Contrastar el manual con la interfaz actual y añadir el paso del PIN.
- Verificar las funciones anunciadas que siguen sin pruebas documentadas.
- Confirmar que se pueden recibir issues y que los participantes tienen acceso.
- Completar la duración y la ubicación del manual en el repositorio.
- Eliminar los registros ficticios utilizados antes de interpretar los conteos como siembras reales.

## Cómo participar

Puedes reportar una instrucción confusa, probar el registro, corregir documentación o proponer una mejora de interacción o estadísticas. Consulta [CONTRIBUTING.md](CONTRIBUTING.md) para conocer los pasos y el formato de los aportes.
