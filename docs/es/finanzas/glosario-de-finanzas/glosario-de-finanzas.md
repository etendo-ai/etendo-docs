---
tags:
    - Finanzas
    - Activos
    - Glosario
    - Etendo
---

# Glosario de Finanzas

!!! info
    Los términos de cuentas, cobros, pagos, extractos y conciliación bancaria están en el [Glosario de Tesorería](../../tesoreria/glosario-de-tesoreria/glosario-de-tesoreria.md).

## Activo

Bien fijo de la empresa (vehículo, equipo informático, maquinaria) que se amortiza a lo largo de su vida útil. Cada activo puede tener un plan de amortización asociado. Ver [Apuntar un activo](../como-apuntar-un-activo/como-apuntar-un-activo.md).

## Amortización

Distribución del valor de un activo a lo largo de su vida útil, calculada según el tipo de amortización y el tipo de cálculo definidos en el activo (Porcentaje o Tiempo). También es el nombre del registro que agrupa la ejecución de esa distribución para uno o varios activos en un período contable: al confirmarlo, genera los asientos contables correspondientes. Ver [Crear y ejecutar un plan de amortización](../como-crear-y-ejecutar-un-plan-de-amortizacion/como-crear-y-ejecutar-un-plan-de-amortizacion.md).

## Amortizado

Porcentaje o importe ya amortizado de un activo, calculado solo sobre los períodos de su plan que están en estado **Confirmado** (los **Pendientes** no cuentan, aunque su fecha ya haya pasado). Se muestra como porcentaje en el panel **Resumen de amortización** del activo, y como importe en euros en la columna **Amortizado real** de la vista de lista de **[Finanzas > Activos](https://app.etendo.ai/assets){target="_blank"}**. Ver [Activos: referencia de campos](../referencia-de-campos-de-activo/referencia-de-campos-de-activo.md).

## Asiento contable

Registro en tu contabilidad que refleja una operación de tu empresa: una venta, una compra, un cobro, un pago o el gasto de amortización de un período. Se genera al contabilizar el documento; hasta entonces, el documento aparece como **Sin contabilizar**.

## Borrador

Estado inicial y editable de una Amortización. En Borrador se pueden añadir, modificar o eliminar líneas y cambiar los datos generales.

## Categoría de activo

Tipo de bien al que pertenece un activo, por ejemplo *Equipos informáticos* o *Vehículos*. Propone la forma de amortizar al registrar el activo y define las cuentas contables de su amortización. Ver [Cómo configurar las categorías de activo](../como-configurar-las-categorias-de-activo/como-configurar-las-categorias-de-activo.md).

## Confirmar

Acción que pasa una Amortización de Borrador a Procesado. Es independiente de Contabilizar: un registro puede quedar Procesado y Sin contabilizar a la vez.

## Contabilizado / Sin contabilizar

Indicador independiente de otros estados (como Borrador/Procesado en una Amortización, o Conciliado/Sin conciliar en un movimiento) que muestra si ya se generaron los asientos contables de un registro. En una Amortización se activa con la acción **Contabilizar**, disponible una vez que el registro está Procesado; en un movimiento queda determinado automáticamente al confirmarlo. Estas etiquetas también se muestran en las facturas, los albaranes y los albaranes de devolución, tanto en sus listas como en la barra superior del documento.

## Contabilizar

Acción que genera los asientos contables de un documento ya Procesado y lo pasa a **Contabilizado**.

## Descontabilizar

Acción que revierte la contabilización de un documento ya **Contabilizado**. Disponible en el menú ⋮ de los documentos que ya están contabilizados.

## Dimensiones contables

Campos opcionales para asociar un registro a un eje de análisis: **Proyecto**, **Centro de costos**, **Contacto** o **Producto**. Se usan en activos, líneas de amortización, movimientos, pagos y cobros. No afectan el saldo ni la conciliación, solo permiten filtrar y analizar tus registros por ese eje. Qué dimensiones están disponibles depende de cada formulario. Las dimensiones **Proyecto** y **Centro de costos** se activan en **Finanzas > Esquema contable**, pestaña **Dimensiones**. Ver [Cómo revisar el esquema contable](../como-revisar-el-esquema-contable/como-revisar-el-esquema-contable.md).

## Factura Rectificativa

Factura que corrige el importe de otra factura ya confirmada, por ejemplo por un precio mal facturado, un descuento o bonificación, o una devolución de mercancía. Es de las llamadas «por diferencias»: no sustituye a la factura original, solo recoge la diferencia, en negativo si el importe baja o en positivo si sube. Existe tanto en ventas como en compras. Para poder confirmarla tiene que indicar, en su pestaña **Rectificaciones**, la factura o facturas que corrige. Ver [Crear una factura rectificativa](../../comercial/ventas/crear-una-factura-rectificativa/crear-una-factura-rectificativa.md) para ventas y [Registrar una factura rectificativa](../../operaciones/compras/registrar-una-factura-rectificativa/registrar-una-factura-rectificativa.md) para compras.

## Plan de amortización

Conjunto de líneas generadas al hacer clic en **Crear amortización** desde un activo, una por período, con su porcentaje e importe. Vive en la pestaña **Plan de amortización** del formulario de Activo. Después de generarlo, el botón pasa a llamarse **Recalcular amortización**. Ver [Crear y ejecutar un plan de amortización](../como-crear-y-ejecutar-un-plan-de-amortizacion/como-crear-y-ejecutar-un-plan-de-amortizacion.md).

## Procesado

Estado de una Amortización ya confirmada. Ya no se pueden editar sus líneas ni sus datos generales.

## Reactivar

Acción que revierte el estado de un registro ya confirmado. Su efecto exacto depende del tipo de registro: en una **Amortización**, devuelve el registro a Borrador y Sin contabilizar en un solo paso, deshaciendo tanto Confirmar como Contabilizar; en un **Cobro** o **Pago**, revierte su confirmación (ver [Gestionar pagos y cobros](../../tesoreria/como-gestionar-pagos-y-cobros/como-gestionar-pagos-y-cobros.md)). No debe confundirse con **Desarchivar**, la acción que reactiva una cuenta archivada (ver [Conectar, desconectar, desactivar o reactivar una cuenta](../../tesoreria/como-conectar-desconectar-desactivar-o-eliminar-una-cuenta-bancaria/como-conectar-desconectar-desactivar-o-eliminar-una-cuenta-bancaria.md)).

## Valor a amortizar

Resultado de restar el valor residual al valor del activo. Es la base sobre la que se calcula la amortización. Se autocompleta, pero es editable.

## Valor residual

Valor estimado de un activo al final de su vida útil. Debe ser menor o igual al valor del activo.

---

## Artículos Relacionados

- [¿Qué es la sección Finanzas?](../que-es-finanzas/que-es-finanzas.md)
- [Apuntar un activo](../como-apuntar-un-activo/como-apuntar-un-activo.md)
- [Crear y ejecutar un plan de amortización](../como-crear-y-ejecutar-un-plan-de-amortizacion/como-crear-y-ejecutar-un-plan-de-amortizacion.md)

---
Esta obra está bajo la licencia :material-creative-commons: :fontawesome-brands-creative-commons-by: :fontawesome-brands-creative-commons-sa: [CC BY-SA 2.5 ES](https://creativecommons.org/licenses/by-sa/2.5/es/){target="_blank"} de [Futit Services S.L](https://etendo.software){target="_blank"}.
