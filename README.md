# AI Financial Software Engineer

Portafolio y páginas legales del asistente de WhatsApp (AI Financial Software Engineer).

| Archivo | Para qué sirve |
|---|---|
| `index.html` | Portafolio con el simulador y el contacto |
| `privacy.html` | Política de privacidad (la pide Meta) |
| `terms.html` | Condiciones del servicio (las pide Meta) |
| `datos.html` | Instrucciones de eliminación de datos (las pide Meta) |

## Publicar en GitHub Pages

1. En github.com crea un repositorio **público** nuevo, por ejemplo `portafolio`.
2. **Add file → Upload files** y sube los cinco archivos de esta carpeta. Pulsa **Commit changes**.
3. Ve a **Settings → Pages**. En **Source** elige **Deploy from a branch**, rama **main**, carpeta **/ (root)** y guarda.
4. Espera uno o dos minutos. Tu sitio quedará en `https://TU-USUARIO.github.io/portafolio/`.

## Datos para pegar en Meta

En **developers.facebook.com → tu app → Configuración de la app → Básico**:

| Campo en Meta | Valor |
|---|---|
| URL de la política de privacidad | `https://TU-USUARIO.github.io/portafolio/privacy.html` |
| URL de las Condiciones del servicio | `https://TU-USUARIO.github.io/portafolio/terms.html` |
| URL de eliminación de datos del usuario | `https://TU-USUARIO.github.io/portafolio/datos.html` |
| Correo de contacto de la app | `abrahanrodrigueza@gmail.com` |
| URL del sitio web (si la pide) | `https://TU-USUARIO.github.io/portafolio/` |

Reemplaza `TU-USUARIO` por tu usuario de GitHub. Después de guardar, vuelve a la pantalla **Publicar**.

## Revisa antes de publicar

La política incluye compromisos concretos. Cámbialos en `privacy.html` y `datos.html` si no los vas a cumplir:

- **Conservación:** máximo 12 meses desde el último mensaje.
- **Plazo de respuesta y eliminación:** máximo 30 días.
- **Sin entrenamiento propio:** no se usan las conversaciones para entrenar modelos.
- **Verificación de firma de Meta:** requiere `WHATSAPP_CLOUD_APP_SECRET` configurado en Hermes.

Esto es un texto general y no sustituye la revisión de un abogado.
