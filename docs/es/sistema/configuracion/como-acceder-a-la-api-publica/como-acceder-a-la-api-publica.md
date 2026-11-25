---
title: Cómo acceder a la API pública de Etendo
tags:
    - Configuración
    - API
    - Seguridad
    - Etendo
features: [public-api-keys]
---

# Cómo acceder a la API pública de Etendo

La API pública te permite conectar Etendo con otras aplicaciones. Para usarla necesitas una **clave de API** propia. Desde la página **Claves de API** puedes crear tus claves, cambiarles el nombre, rotarlas, revocarlas y eliminarlas.

<!-- TODO: confirmar el nombre exacto de la página en la interfaz y su ruta en el menú lateral. -->

## 1. Comprueba los requisitos

Antes de empezar, ten en cuenta lo siguiente:

- Solo los usuarios con rol de administrador ven la página de claves de API.
- Cada usuario gestiona únicamente sus propias claves.
- La funcionalidad se activa por separado. Si no ves la página, pide a tu administrador que compruebe que la tienes disponible.

!!! info "Qué controla el acceso"
    Esta restricción solo oculta la página en la interfaz. No cambia el funcionamiento de la API en sí.

## 2. Accede a la página de claves de API

1. Inicia sesión en Etendo con un usuario administrador.
2. Abre **[Claves de API](https://app.etendo.ai/api-keys){target="_blank"}**.

<!-- TODO: indicar la ruta de menú lateral (sección y opción) si existe, y añadir captura de la vista lista de claves. -->

## 3. Crea una clave

1. Haz clic en el botón para crear una clave nueva.
2. Completa los datos que te pida el formulario.
3. Confirma la creación.

<!-- TODO: indicar el nombre exacto del botón, los campos del formulario (¿nombre?, ¿caducidad?, ¿permisos?) y cuáles son obligatorios. -->

<!-- TODO: confirmar si el valor completo de la clave se muestra solo al crearla. Si es así, añadir un aviso para que el usuario la copie y la guarde en un lugar seguro. -->

## 4. Gestiona tus claves

Desde la lista puedes hacer cuatro acciones sobre cada clave:

| Acción | Para qué sirve |
| --- | --- |
| **Renombrar** | Cambia el nombre de la clave para reconocerla mejor. |
| **Rotar** | Sustituye la clave por una nueva. |
| **Revocar** | Deja de permitir el acceso con esa clave. |
| **Eliminar** | Borra la clave de tu lista. |

<!-- TODO: confirmar los nombres exactos de las acciones en la interfaz, cómo se accede a cada una (menú de fila, botones) y qué ocurre con la clave anterior al rotarla. -->

<!-- TODO: aclarar la diferencia entre revocar y eliminar, y si se puede deshacer alguna de las dos. -->

## 5. Consulta la documentación de la API

La documentación pública de la API está disponible en **[app.etendo.ai/api](https://app.etendo.ai/api){target="_blank"}**.

<!-- TODO: describir qué contiene esa página (endpoints, ejemplos, autenticación) y cómo se envía la clave de API en las peticiones. -->

## Artículos Relacionados

<!-- TODO: añadir enlaces a artículos relacionados cuando existan. -->
