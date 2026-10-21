# ReclutaBot — Privacidad

Sitio estático para la política de privacidad y las instrucciones de eliminación de datos de ReclutaBot, registrado en Meta como **Prueba**.

- Responsable: Angel Esquen.
- Contacto público autorizado: angel_esquen1224@hotmail.com.
- Automatización: n8n Cloud.
- Generación de respuestas: Google Gemini cuando la función esté habilitada.

## Publicar en GitHub Pages

No requiere instalación ni compilación. En **Settings → Pages**, seleccionar **Deploy from a branch**, rama **main**, carpeta **/ (root)**. Abrir y comprobar la URL que indique GitHub.

- Política: `index.html`.
- Instrucciones de eliminación: `data-deletion.html`.
- Estilos: `styles.css`.
- `.nojekyll`: servir archivos estáticos sin Jekyll.

En Meta, introducir la URL pública de la política de privacidad; si se solicitan instrucciones de eliminación, utilizar la URL pública de `data-deletion.html`.

## Mantenimiento

La política debe coincidir con el funcionamiento real. Revisarla si se incorporan formularios, documentos, otros proveedores, bases de datos o cambios en la conservación. n8n Cloud aplica límites de conservación según plan y configuración; la página no presupone un número de días ni un borrado automático de la memoria.

Para solicitudes, revisar por separado memoria de conversación y ejecuciones identificables. No prometer plazos o resultados técnicos que aún no estén implementados.

## Referencias

- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
- https://docs.n8n.io/manage-cloud/cloud-data-management/
- https://ai.google.dev/gemini-api/terms

Este repositorio contiene solamente páginas informativas. No incluye credenciales, conversaciones, números de usuarios ni el flujo de n8n.
