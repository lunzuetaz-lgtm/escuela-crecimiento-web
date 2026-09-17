# Escuela de Crecimiento — publicación en Netlify

Esta carpeta contiene la landing de Escuela de Crecimiento preparada para Netlify y con la burbuja de Chatbase instalada.

## Publicación mediante GitHub y Netlify

1. Crear en GitHub un repositorio privado llamado `escuela-crecimiento-web`.
2. Subir a la raíz del repositorio el archivo `index.html` de esta carpeta.
3. En Netlify, elegir **Add new project → Import an existing project → GitHub**.
4. Seleccionar `escuela-crecimiento-web`.
5. Configurar:
   - Branch to deploy: `main`
   - Build command: dejar vacío
   - Publish directory: `.`
6. Pulsar **Deploy**.

## Último ajuste en Chatbase

Cuando Netlify asigne la dirección pública, entrar en Chatbase:

**Channels → Chat bubble → Manage → Allowed Domains**

Añadir el dominio de Netlify, por ejemplo `nombre-elegido.netlify.app`. Si posteriormente se utiliza un dominio propio, añadirlo también.

## Actualizaciones

La página conserva la presentación publicada en Canva en el momento de preparar este archivo. Si se modifica el diseño original de Canva, habrá que generar una nueva versión de `index.html` para trasladar esos cambios.
