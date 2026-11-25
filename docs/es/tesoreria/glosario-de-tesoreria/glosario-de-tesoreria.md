---
tags:
    - Tesorería
    - Cuentas
    - Cobros y pagos
    - Glosario
    - Etendo
---

# Glosario de Tesorería

!!! info
    Los términos de contabilidad, activos y amortización están en el [Glosario de Finanzas](../../finanzas/glosario-de-finanzas/glosario-de-finanzas.md).

## Archivar

Acción que deja de mostrar una cuenta en el listado de **Todas las cuentas** sin borrar su saldo ni su historial: la cuenta pasa al filtro **Inactivas**. Su opuesto es **Desarchivar**. No debe confundirse con **Eliminar cuenta**, una acción independiente que borra la cuenta de forma permanente y no se puede deshacer — a diferencia de Archivar, que es reversible. Ver [Conectar, desconectar, archivar, desarchivar o eliminar una cuenta](../como-conectar-desconectar-desactivar-o-eliminar-una-cuenta-bancaria/como-conectar-desconectar-desactivar-o-eliminar-una-cuenta-bancaria.md).

## Automatch

El motor de sugerencias automáticas de conciliación de Etendo. Compara las líneas pendientes de tu extracto bancario contra tus facturas, cobros y pagos por fecha e importe, y te propone las coincidencias para que las confirmes con un clic.

## Caja

Tipo de cuenta para el efectivo que se maneja fuera del banco (por ejemplo, la caja chica de una oficina o la caja de un punto de venta). A diferencia de un Banco o una Tarjeta, una Caja no se conecta ni importa extractos de una entidad externa: todos sus movimientos se registran a mano. Ver [Gestionar cajas contables y movimientos en efectivo](../como-gestionar-caja-y-movimientos-en-efectivo/como-gestionar-caja-y-movimientos-en-efectivo.md).

## Cobro

Registro del dinero que recibes de un cliente. Normalmente se crea desde una factura de venta, pero también puede originarse en una Entrada registrada a mano en una caja. En ambos casos queda disponible en la vista global **Tesorería > Cobro**. Ver [Gestionar pagos y cobros](../como-gestionar-pagos-y-cobros/como-gestionar-pagos-y-cobros.md) y [Gestionar cajas contables y movimientos en efectivo](../como-gestionar-caja-y-movimientos-en-efectivo/como-gestionar-caja-y-movimientos-en-efectivo.md).

## Concepto contable

La cuenta contable que se asigna a un movimiento, un cobro, un pago o una regla de matcheo. Determina en qué cuenta del plan contable queda registrada esa operación.

## Conciliado / Sin conciliar

Estado que indica si un movimiento ya quedó vinculado a su documento correspondiente (una factura, un cobro o un pago) durante la conciliación bancaria.

## Condición de pago

Plazo que das a tus clientes para pagarte, o el que te dan tus proveedores. Etendo lo usa para calcular cuándo vence cada factura. Ver [Cómo configurar las condiciones de pago](../como-configurar-las-condiciones-de-pago/como-configurar-las-condiciones-de-pago.md).

## Condición sobre el concepto

Campo de una regla de matcheo que define cómo se compara su patrón contra la descripción del movimiento: **Contiene**, **Empieza con** o **Coincide con patrón** (una sintaxis de búsqueda avanzada para patrones de texto complejos; si no estás familiarizado con expresiones regulares, usa **Contiene** o **Empieza con**).

## Contabilizado / Sin contabilizar

Indicador independiente de otros estados (como Borrador/Procesado en una Amortización, o Conciliado/Sin conciliar en un movimiento) que muestra si ya se generaron los asientos contables de un registro. En una Amortización se activa con la acción **Contabilizar**, disponible una vez que el registro está Procesado; en un movimiento queda determinado automáticamente al confirmarlo. Estas etiquetas también se muestran en las facturas, los albaranes y los albaranes de devolución, tanto en sus listas como en la barra superior del documento.

## Cuenta

Cuenta de banco, tarjeta o caja que registras en Etendo para llevar el control de tu dinero. Mantiene su propio saldo y su propio historial de movimientos, y puede conectarse por Open Banking o gestionarse sin conexión. Ver [Añadir y configurar un banco, tarjeta o caja](../como-anadir-y-configurar-un-banco-tarjeta-o-caja/como-anadir-y-configurar-un-banco-tarjeta-o-caja.md).

## Cuenta transitoria

Cuenta contable opcional que puedes asociar a una cuenta desde **Editar cuenta > Contabilidad**. Sirve para registrar de forma temporal operaciones cuyo concepto contable definitivo todavía no está claro, sin afectar directamente a la cuenta contable principal.

## Dimensiones contables

Campos opcionales para asociar un registro a un eje de análisis: **Proyecto**, **Centro de costo**, **Contacto** o **Producto**. Se usan en activos, líneas de amortización, movimientos, pagos y cobros. No afectan el saldo ni la conciliación, solo permiten filtrar y analizar tus registros por ese eje. Qué dimensiones están disponibles depende de cada formulario.

## Extracto bancario

Archivo con el detalle de los movimientos de una cuenta bancaria en un período. Se importa a Etendo (en formato, CSV o Excel) para generar sus movimientos automáticamente, o se descarga para tu propio registro. Ver [Importar o descargar el extracto bancario](../como-importar-o-descargar-el-extracto-bancario/como-importar-o-descargar-el-extracto-bancario.md).

## Movimiento

Cada entrada o salida de dinero dentro de una cuenta (transferencias, pagos, cobros, retiradas de efectivo). Tiene dos estados independientes: uno de conciliación (Sin conciliar / Conciliado) y uno de contabilización (Sin contabilizar / Contabilizado).

## Pago

Registro del dinero que entregas a un proveedor. Normalmente se crea desde una factura de compra, pero también puede originarse en una Salida registrada a mano en una caja. En ambos casos queda disponible en la vista global **Tesorería > Pago**. Ver [Gestionar pagos y cobros](../como-gestionar-pagos-y-cobros/como-gestionar-pagos-y-cobros.md) y [Gestionar cajas contables y movimientos en efectivo](../como-gestionar-caja-y-movimientos-en-efectivo/como-gestionar-caja-y-movimientos-en-efectivo.md).

## Reactivar

En un **Cobro** o un **Pago**, acción que revierte su confirmación (ver [Gestionar pagos y cobros](../como-gestionar-pagos-y-cobros/como-gestionar-pagos-y-cobros.md)). No debe confundirse con **Desarchivar**, la acción que reactiva una cuenta archivada (ver [Conectar, desconectar, desactivar o reactivar una cuenta](../como-conectar-desconectar-desactivar-o-eliminar-una-cuenta-bancaria/como-conectar-desconectar-desactivar-o-eliminar-una-cuenta-bancaria.md)).

## Regla de matcheo

Regla configurable que concilia automáticamente líneas de extracto recurrentes sin factura asociada —por ejemplo, una comisión bancaria mensual— sin que tengas que buscarlas a mano cada vez. Ver [Configurar reglas para automatizar la conciliación](../como-configurar-reglas-para-automatizar-la-conciliacion-bancaria/como-configurar-reglas-para-automatizar-la-conciliacion-bancaria.md).

## Tolerancia de conciliación

Margen configurable por cuenta, desde **Editar cuenta > General**, que le indica a Automatch y a las reglas de matcheo cuánta diferencia de fecha (en días) o de importe (en %) pueden aceptar para sugerir una coincidencia.

---

## Artículos Relacionados

- [¿Qué es la sección Tesorería?](../que-es-tesoreria/que-es-tesoreria.md)
- [Añadir y configurar un banco, tarjeta o caja](../como-anadir-y-configurar-un-banco-tarjeta-o-caja/como-anadir-y-configurar-un-banco-tarjeta-o-caja.md)
- [Gestionar pagos y cobros](../como-gestionar-pagos-y-cobros/como-gestionar-pagos-y-cobros.md)

---
Esta obra está bajo la licencia :material-creative-commons: :fontawesome-brands-creative-commons-by: :fontawesome-brands-creative-commons-sa: [CC BY-SA 2.5 ES](https://creativecommons.org/licenses/by-sa/2.5/es/){target="_blank"} de [Futit Services S.L](https://etendo.software){target="_blank"}.
