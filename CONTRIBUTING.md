# Cómo colaborar con Forestando Juntos

Puedes aportar sin saber programar. En este taller preparamos propuestas documentadas para que el administrador del sitio las evalúe. El administrador decide e implementa los cambios en la web.

Un **repositorio** es el espacio de GitHub que reúne los archivos del proyecto. El enlace facilitado para este taller es [fbarriac/ForestandoJuntos](https://github.com/fbarriac/ForestandoJuntos).

> Esta guía propone un flujo de participación. No se pudo revisar la configuración del repositorio: las instrucciones que dependen de sus opciones se aplican cuando estén disponibles.

## Elige cómo aportar

| Aporte | Información útil |
| --- | --- |
| Reportar una instrucción confusa | Sección o paso, qué intentaste entender y una redacción más clara. |
| Corregir documentación | Texto actual, texto propuesto y motivo de la corrección. |
| Probar el taller | Fecha, dispositivo, navegador, pasos, resultado esperado y observado. |
| Proponer una mejora | Necesidad, personas beneficiadas, cambio delimitado y forma de comprobarlo. |

Revisa los aportes existentes antes de abrir uno nuevo. Si alguien ya documentó la misma necesidad, añade información en esa conversación.

## Documenta tu aporte

Copia este formato en tu propuesta. Escribe «No probado» o «No aplica» cuando corresponda.

~~~markdown
## Necesidad
¿Qué problema o posibilidad de mejora identificaste y a quién afecta?

## Ubicación
Pantalla, sección del manual o archivo involucrado.

## Evidencia y prueba
Fecha, dispositivo, navegador y pasos realizados.
Resultado esperado:
Resultado observado:
Evidencia disponible o limitación de acceso:

## Propuesta
Describe un solo cambio. Distingue lo existente de lo sugerido.
Si propones estadísticas, indica la pregunta, los datos necesarios y el cálculo o agrupación.

## Criterios de aceptación
- [ ] Resultado concreto y observable que permitiría comprobar la mejora.

## Registro ficticio utilizado
Nombre público, código si se generó y fecha aproximada.
Indica si solicitas revisión o eliminación al administrador.
No incluyas el PIN ni datos personales de contacto.

## Pendientes de verificar
Qué falta comprobar y qué información necesitarías del administrador.
~~~

Ejemplo de título: «Explicar el PIN de cuatro dígitos en el manual». Es una mejora detectada al comparar el manual compartido con las capturas del formulario.

## Abre un issue

Un **issue** es una conversación de GitHub donde se documenta una tarea, un problema o una propuesta. Es la vía principal sugerida para este taller.

1. Inicia sesión en GitHub y abre el repositorio.
2. Entra en **Issues**, si esa pestaña está disponible.
3. Revisa las conversaciones existentes y pulsa **New issue** o su equivalente en español.
4. Si aparecen plantillas, elige la adecuada; si se permite una propuesta en blanco, puedes usar el formato anterior.
5. Escribe un título concreto y la descripción. Revisa la vista previa y publica con el botón de envío.
6. Conserva el enlace para continuar la conversación y responder las preguntas de revisión.

Si no aparece Issues o no puedes publicar, conserva tu propuesta y anota el impedimento. [PENDIENTE: el responsable debe comprobar el acceso y habilitar la recepción de issues o definir un canal alternativo antes de convocar participantes].

## Prueba y registra con cuidado

El administrador permite registros ficticios en el sitio actual durante su periodo de pruebas y puede eliminarlos después.

- La convención propuesta es comenzar el nombre público con «PRUEBA TALLER» e indicar que es ficticio en la referencia del lugar.
- Utiliza datos de prueba y medios de contacto que controles cuando sean obligatorios.
- Guarda el PIN de forma privada. Oculta contactos y PIN en las capturas que compartas.
- Registra tanto los éxitos como los errores y los pasos que no pudiste completar.
- Incluye los identificadores disponibles para que el administrador revise y elimine el registro.

El panel administrativo no es un requisito para participar. Si una propuesta depende de sus datos, indica qué necesitas que confirme el administrador. No presentes una estadística sugerida como si ya existiera.

## Envía una corrección de documentación, si corresponde

Una **pull request** o **solicitud de cambios** permite proponer modificaciones a archivos para que otra persona las revise antes de incorporarlas. Es opcional: una propuesta redactada dentro de un issue también es válida.

Para un archivo de texto disponible en GitHub, como README.md:

1. Abre el archivo y selecciona el icono del lápiz para editar.
2. Si GitHub solicita crear un **fork**, acepta crear esa copia del repositorio en tu cuenta para preparar el cambio.
3. Corrige un solo asunto y revisa **Preview** o «Vista previa».
4. Pulsa **Commit changes** para abrir la confirmación y escribe un mensaje breve. Un **commit** es un cambio guardado con un mensaje que explica qué se modificó.
5. Antes de confirmar el guardado, si tienes permiso de escritura y aparece la opción, elige una **rama** nueva: una versión separada de trabajo para preparar la revisión.
6. Confirma con **Commit changes** o **Propose changes**, según lo que muestre GitHub, y continúa hasta **Create pull request**. Comprueba el repositorio de destino, describe la corrección y enlaza el issue relacionado, si existe.

Este procedimiento se aplica a archivos editables de texto. Para el manual PDF, puedes proponer el texto en un issue; no hace falta editar el PDF. El responsable del repositorio revisa las solicitudes de documentación; los cambios en el sitio quedan a cargo del administrador.

## Qué ocurre después

La propuesta queda lista para revisión cuando incluye la necesidad, la evidencia disponible, el cambio delimitado y sus criterios de aceptación. El administrador puede pedir información, aprobarla o explicar por qué no la incorporará. Publicarla no significa que ya esté implementada.

Ayuda oficial: [crear un issue](https://docs.github.com/es/issues/tracking-your-work-with-issues/using-issues/creating-an-issue) y [editar archivos desde GitHub](https://docs.github.com/es/repositories/working-with-files/managing-files/editing-files).
