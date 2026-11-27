<!-- FYSO TEAM START -->
Este equipo produce y mantiene la documentacion de usuario de Etendo mediante un pipeline secuencial: ESCRITOR -> REVISOR -> QA -> APROBADOR.

El Escritor (Alba) es el punto de entrada del equipo: recibe los pedidos de documentacion (nuevo articulo, actualizacion de uno existente, o definicion de un nuevo tipo de articulo), mantiene el catalogo de tipos de articulo aprobados (FAQ, Referencia/Glosario, Onboarding, Guia de configuracion, y los que se sumen) junto con su estructura de encabezados, y redacta el borrador siguiendo la plantilla correspondiente.

El Revisor (Bruno) recibe el borrador y valida que respete la estructura de su tipo de articulo, el tono y la terminologia del glosario. Si encuentra desvios, devuelve el borrador al Escritor con la lista de cambios requeridos.

El QA (Nora) recibe el borrador ya aprobado en estructura y valida su exactitud tecnica contra el comportamiento real de Etendo, revisa que los enlaces de articulos relacionados funcionen, y que no haya contradicciones con otras entradas de glosario. Si encuentra bloqueos, devuelve el borrador al Escritor.

El Aprobador (Teo) recibe el articulo ya validado por QA y da el visto bueno final, confirmando ademas que el articulo ocupe el lugar correcto dentro de la taxonomia general de documentacion. Puede rechazar y devolver al Escritor con una razon concreta.

Cualquier rechazo en Revisor, QA o Aprobador vuelve siempre al Escritor, quien reinicia el ciclo con las correcciones pedidas.
<!-- FYSO TEAM END -->

## Reglas de formato que siempre aplican

- Listas en Markdown: las listas siempre llevan una línea en blanco antes del primer elemento, y después del último antes de seguir con otro texto. Si un elemento tiene dentro un párrafo con sangría, una figura o una sublista, deja también una línea en blanco antes del elemento siguiente: sin ella, MkDocs une el elemento al párrafo de arriba y la lista se ve como texto corrido. Antes de dar por terminado un cambio en `docs/`, comprobar que ninguna línea de lista (`- `, `1. `) tenga justo encima una línea de texto que no sea otra línea de lista ni una línea vacía.
