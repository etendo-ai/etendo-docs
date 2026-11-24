---
title: Portal del cliente
status: beta
description: >-
  Descubre qué ve tu cliente al abrir el enlace al portal que llega con cada
  documento de venta que envías por email, cuánto dura el acceso y cómo acepta
  o rechaza tus presupuestos desde ahí.
tags:
  - Ventas
  - Comercial
  - Email
  - Portal del cliente
  - Etendo
---

# Portal del cliente

--8<-- "overrides/snippets/funcionalidad-beta.md"

El portal del cliente es una web donde tus clientes consultan los documentos de venta que les has enviado y responden a tus presupuestos, sin tener que pedirte copias ni contestarte por correo.

Tu cliente no necesita usuario ni contraseña: entra con el enlace que le llega en el email cada vez que le [envías un documento](../enviar-documentos-por-email/enviar-documentos-por-email.md). Desde el portal puede:

- Ver y descargar sus **presupuestos**, **pedidos**, **albaranes** y **facturas**.
- Consultar qué tiene pendiente contigo: presupuestos por responder, facturas por pagar y pedidos en curso.
- **Aceptar o rechazar** un presupuesto. Es lo único que puede cambiar: el resto del portal es de solo lectura.

## Cómo llega tu cliente al portal

Si tu cuenta tiene el portal activado, no tienes que hacer nada distinto: cuando envías un presupuesto, un pedido, un albarán o una factura con el botón **Enviar**, el email lleva un botón **Ver documento en el portal** y el mismo enlace escrito en texto, por si el programa de correo del cliente no muestra el botón.

<!-- CAPTURA PENDIENTE: email de envío de un documento de venta con el botón «Ver documento en el portal» y el enlace en texto -->
<figure markdown="span">
  ![Email de envío de una factura con el botón Ver documento en el portal y el enlace en texto debajo](assets/portal-del-cliente-1.png)
  <figcaption>Cada email de documento de venta incluye el acceso al portal.</figcaption>
</figure>

Si tu cuenta todavía no tiene el portal, los emails se envían como siempre, sin el botón ni el enlace.

El enlace abre directamente el documento que enviaste. Desde ahí tu cliente puede moverse por todo el portal y ver el resto de documentos que tiene contigo.

## Cuánto dura el acceso

Cada enlace sirve durante **48 horas**. En ese plazo tu cliente puede abrirlo todas las veces que quiera.

- **Reenviar un documento no anula los enlaces anteriores.** Cada envío trae su propio enlace, y los que ya mandaste siguen funcionando hasta que caducan.
- **Si tu cliente abre un enlace caducado, no tienes que hacer nada.** El portal le muestra **Te hemos enviado un enlace nuevo** y le llega automáticamente el email **Su nuevo enlace al portal de cliente de …**, a las mismas direcciones a las que mandaste el documento.

<!-- CAPTURA PENDIENTE: pantalla del portal «Te hemos enviado un enlace nuevo» al abrir un enlace caducado -->
<figure markdown="span">
  ![Pantalla del portal con el mensaje Te hemos enviado un enlace nuevo](assets/portal-del-cliente-2.png)
  <figcaption>Al abrir un enlace caducado, el cliente recibe uno nuevo por email.</figcaption>
</figure>

!!! info "Un enlace nuevo cada 15 minutos como máximo"
    Si tu cliente vuelve a abrir el enlace caducado antes de que pasen 15 minutos, el portal le muestra **Ya te enviamos un enlace nuevo** y no sale otro email. Así no le llenas el buzón si hace varios clics seguidos.

### Cuándo no se da acceso

El portal muestra **No podemos darte acceso al portal**, y no envía ningún enlace nuevo, en estos casos:

- El contacto está bloqueado como cliente o inactivo en [Contactos](../../contactos/gestionar-tus-contactos/gestionar-tus-contactos.md).
- El plan de tu empresa en Etendo ha vencido.

!!! tip "Cómo cortar el acceso a un cliente"
    No hay un botón para revocar el acceso. El acceso se corta solo cuando el enlace caduca, y deja de renovarse si bloqueas al cliente o lo desactivas en su ficha.

## Qué ve tu cliente en el portal

El portal lleva el nombre y el logo de tu empresa, y muestra solo los documentos que tu empresa le ha emitido a ese cliente. Si trabajas con varias empresas en Etendo, cada una tiene su propio portal, con su nombre y sus documentos.

### Inicio

La página de inicio le saluda con **Esto es lo que tienes pendiente con …** y el nombre de tu empresa. Por defecto muestra los **Últimos 12 meses**, y el cliente puede cambiar el período con el selector de arriba.

<!-- CAPTURA PENDIENTE: página de inicio del portal en web, con la barra lateral, las tarjetas «Requiere tu atención», «Tu saldo» y el gráfico «Facturado por mes» -->
<figure markdown="span">
  ![Inicio del portal del cliente con la barra lateral, las tarjetas de pendientes, el saldo, los documentos recientes y el gráfico de facturación por mes](assets/portal-del-cliente-3.png)
  <figcaption>El inicio resume lo que el cliente tiene pendiente contigo.</figcaption>
</figure>

- **Requiere tu atención** — tarjetas con los presupuestos por responder, las facturas vencidas, los pedidos en curso y los albaranes del mes.
- **Tu saldo** — lo pagado este año y lo que queda pendiente de pago.
- **Documentos recientes** — los últimos documentos que le has emitido.
- **Facturado por mes** — un gráfico con lo que le has facturado mes a mes.

A la izquierda está la barra lateral, con el logo y el nombre de tu empresa, el acceso a **Inicio** y, en **Mis documentos**, los listados de **Albaranes**, **Facturas**, **Pedidos** y **Presupuestos**, cada uno con un contador de pendientes. Abajo aparece el nombre del cliente. Si hace clic en él, ve su nombre y su email y puede cambiar el idioma del portal.

En la barra superior tiene un buscador para encontrar cualquier documento por su número o su referencia.

### Listados de documentos

Cada listado muestra por defecto los documentos del último mes. Para encontrar otros, tu cliente tiene:

- **Pestañas por estado** — para ver de un vistazo, por ejemplo, las facturas pagadas o los pedidos completados.
- **Selector de fechas** — con **Hoy**, **Ayer**, **Últimos 7 días**, **Últimos 30 días**, **Últimos 12 meses**, **Todo el tiempo** y **Personalizado**.

Al pie de la tabla hay una fila con el **Total** y el botón **Cargar más** para seguir viendo documentos.

<!-- CAPTURA PENDIENTE: listado de Facturas del portal en web, con las pestañas por estado, el selector de fechas y la fila Total -->
<figure markdown="span">
  ![Listado de facturas del portal con las pestañas por estado, el selector de rango de fechas, las columnas de la tabla y la fila Total](assets/portal-del-cliente-4.png)
  <figcaption>El listado de facturas, con su estado de pago y el importe pendiente de cada una.</figcaption>
</figure>

En **Facturas**, cada fila muestra la fecha, el número, la referencia, el vencimiento, el estado, el estado de pago, la base imponible, el total y el importe pendiente.

!!! info "Los borradores no se ven"
    El portal solo muestra documentos confirmados. Lo que tengas en **Borrador** en Etendo no le aparece a tu cliente.

### Detalle de un documento

Al abrir un documento se ve la vista previa del PDF, con zoom y pantalla completa, y a su lado un resumen:

- **Total**, fecha y estado.
- Método de pago, base imponible e impuestos.
- En las facturas, también el vencimiento, el estado de pago y el importe pendiente.
- En los presupuestos, también la fecha **Válido hasta**.

<!-- CAPTURA PENDIENTE: detalle de una factura en el portal, con la vista previa del PDF, el resumen, «Emitido por» y los documentos relacionados -->
<figure markdown="span">
  ![Detalle de una factura en el portal con la vista previa del PDF a la izquierda y el resumen, el botón Descargar PDF y los documentos relacionados a la derecha](assets/portal-del-cliente-5.png)
  <figcaption>El detalle muestra el mismo PDF que le enviaste por email.</figcaption>
</figure>

El botón **Descargar PDF** baja exactamente el mismo PDF que le mandaste por email. El detalle indica también **Emitido por** con el nombre de tu empresa.

En **Documentos relacionados** tu cliente puede saltar de un documento a otro de la misma venta: por ejemplo, del pedido al albarán y del albarán a la factura.

### En el móvil

El portal se adapta al móvil. En lugar de la barra lateral hay una barra inferior con **Inicio**, **Presupuestos**, **Facturas** y **Más**, que abre **Pedidos** y **Albaranes**. Los listados se ven como tarjetas, y el buscador está detrás del icono de la lupa.

<!-- CAPTURA PENDIENTE: portal en el móvil, con la home («Pendiente de pago») y la barra inferior; idealmente junto al detalle de un documento -->
<figure markdown="span">
  ![Portal del cliente en el móvil con la tarjeta Pendiente de pago, los contadores, los documentos recientes y la barra inferior de navegación](assets/portal-del-cliente-6.png)
  <figcaption>En el móvil, el inicio destaca lo que queda pendiente de pago.</figcaption>
</figure>

- **Inicio** — muestra una tarjeta **Pendiente de pago** con el botón **Ver facturas pendientes**, los contadores y los documentos recientes.
- **Detalle** — muestra el resumen, las líneas, el botón **Ver PDF** (que abre el documento a pantalla completa), la descarga y los documentos relacionados. Los botones para aceptar o rechazar un presupuesto están al final.

### Idioma

El portal se abre en español. Tu cliente puede cambiarlo a inglés haciendo clic en su nombre, abajo a la izquierda (en el móvil, desde su icono de usuario). Se traducen los menús, las pestañas, los estados y los motivos de rechazo. El PDF no cambia: sigue en el idioma en que emitiste el documento.

## Aceptar o rechazar un presupuesto

Tu cliente puede responder a un presupuesto desde el portal. Para evitar respuestas por error, la decisión siempre se confirma desde un email.

### Cuándo puede responder

Los botones **Aceptar** y **Rechazar** solo aparecen en los presupuestos que están **Bajo evaluación** y que no han caducado. Si el presupuesto no tiene fecha de validez, se considera vigente. Si ya pasó su fecha **Válido hasta**, el portal muestra **Este presupuesto ha caducado** y no deja responder.

Una vez que el presupuesto tiene respuesta, se ve con su nuevo estado y sin botones.

### 1. El cliente elige su respuesta

- **Si acepta**, se abre la ventana **¿Deseas aceptar este presupuesto?**, con el correo al que le llegará la confirmación y el aviso de que la decisión será definitiva.
- **Si rechaza**, tiene que elegir un motivo: **Precio**, **Plazo de entrega**, **Condiciones de pago**, **He elegido otro proveedor**, **Ya no lo necesito** u **Otros**. Con **Otros**, tiene que escribir una descripción.

<!-- CAPTURA PENDIENTE: ventana de rechazo con la lista de motivos (opcionalmente, junto a la ventana «¿Deseas aceptar este presupuesto?») -->
<figure markdown="span">
  ![Ventana para rechazar un presupuesto en el portal con la lista de motivos de rechazo](assets/portal-del-cliente-7.png)
  <figcaption>Para rechazar, el cliente tiene que indicar el motivo.</figcaption>
</figure>

En los dos casos, el portal le muestra después **Confirma tu decisión por correo**.

### 2. El cliente confirma desde el email

Le llega el email **Confirma la aceptación del presupuesto …** o **Confirma el rechazo del presupuesto …**, con el logo de tu empresa, la etiqueta **Confirmación pendiente** y los datos del presupuesto: la empresa, el número y el importe total si lo acepta, o el motivo si lo rechaza.

<!-- CAPTURA PENDIENTE: email «Confirma la aceptación del presupuesto …» con la tarjeta «Datos del presupuesto» y el botón «Confirmar aceptación» -->
<figure markdown="span">
  ![Email de confirmación de aceptación de un presupuesto con la etiqueta Confirmación pendiente, los datos del presupuesto y el botón Confirmar aceptación](assets/portal-del-cliente-8.png)
  <figcaption>La respuesta solo se aplica cuando el cliente pulsa el botón del email.</figcaption>
</figure>

!!! warning "Hasta que no confirma, el presupuesto sigue pendiente"
    Aceptar o rechazar en el portal no cambia nada todavía. El presupuesto sigue **Bajo evaluación** hasta que tu cliente hace clic en **Confirmar aceptación** o **Confirmar rechazo** en ese email.

Al confirmar, se abre la página **¡Presupuesto aceptado!** o **¡Presupuesto rechazado!**, con el resumen y la nota **La empresa emisora ha sido notificada**.

<!-- CAPTURA PENDIENTE: página «¡Presupuesto aceptado!» con el resumen y la nota «La empresa emisora ha sido notificada» -->
<figure markdown="span">
  ![Página del portal con el mensaje Presupuesto aceptado, el resumen del presupuesto y la nota La empresa emisora ha sido notificada](assets/portal-del-cliente-9.png)
  <figcaption>La página que ve el cliente después de confirmar.</figcaption>
</figure>

El botón de confirmación sirve una sola vez y no caduca. Estos son los avisos que puede ver tu cliente si lo usa más tarde:

| Situación | Lo que ve tu cliente |
| --- | --- |
| Vuelve a abrir un email que ya confirmó | **Esta decisión ya estaba aplicada** |
| El presupuesto caducó antes de que confirmara | **Este presupuesto ha caducado. No se ha aplicado nada** |
| Pidió aceptar y rechazar, y ya confirmó una de las dos | **Ya se confirmó otra decisión**. Vale la primera que confirmó. |

### 3. Qué cambia en Etendo

Cuando tu cliente confirma:

- El usuario de tu empresa que envió el presupuesto recibe el email **<Cliente> ha aceptado el presupuesto …** o **<Cliente> ha rechazado el presupuesto …**.
- El presupuesto pasa a **Aceptado** o a **Cerrado - Rechazado**.

<!-- CAPTURA PENDIENTE: presupuesto en Etendo con estado «Cerrado - Rechazado», la nota «Rechazado por el cliente desde el portal. Motivo: …» y el campo «Razón de rechazo» -->
<figure markdown="span">
  ![Presupuesto en Etendo en estado Cerrado - Rechazado con la nota del motivo del cliente y el campo Razón de rechazo](assets/portal-del-cliente-10.png)
  <figcaption>El motivo del cliente queda guardado en las notas del presupuesto.</figcaption>
</figure>

**Si lo acepta**, Etendo no crea ningún pedido por su cuenta. Desde **Aceptado**, conviertes tú el presupuesto en pedido o en factura, como siempre (ver [Crear y gestionar presupuestos](../crear-y-gestionar-presupuestos/crear-y-gestionar-presupuestos.md#3-cierra-el-presupuesto-segun-la-respuesta-del-cliente)).

**Si lo rechaza**, su motivo queda en las notas del presupuesto, con el texto **Rechazado por el cliente desde el portal. Motivo: …**. Además, puedes rellenar el campo **Razón de rechazo** con un motivo interno para tu equipo. Ese campo tu cliente no lo ve.

## Artículos Relacionados

- [Enviar documentos por email](../enviar-documentos-por-email/enviar-documentos-por-email.md)
- [Crear y gestionar presupuestos](../crear-y-gestionar-presupuestos/crear-y-gestionar-presupuestos.md)
- [Gestionar tus facturas de venta](../gestionar-tus-facturas-de-venta/gestionar-tus-facturas-de-venta.md)

---
Esta obra está bajo la licencia :material-creative-commons: :fontawesome-brands-creative-commons-by: :fontawesome-brands-creative-commons-sa: [CC BY-SA 2.5 ES](https://creativecommons.org/licenses/by-sa/2.5/es/){target="_blank"} de [Futit Services S.L](https://etendo.software){target="_blank"}.
