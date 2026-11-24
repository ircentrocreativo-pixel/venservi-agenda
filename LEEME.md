# VENSERVI · Agenda de mantenimiento recurrente

Demo de IR Centro Creativo. Es un sitio estático, sin servidor ni base de datos: funciona en cualquier celular o computadora.

## Contenido de la carpeta

- `index.html`: la aplicación completa.
- `img/`: el logo y las 11 fotos de los servicios.

No cambies los nombres de los archivos ni saques las fotos de la carpeta `img`.

## Subir a GitHub

1. Entra a github.com y crea un repositorio nuevo, por ejemplo `venservi-agenda`.
2. Elige **uploading an existing file** (subir archivos existentes).
3. Arrastra **el contenido** de esta carpeta: `index.html`, `LEEME.md` y la carpeta `img`. `index.html` tiene que quedar en la raíz del repositorio, no dentro de otra carpeta.
4. Pulsa **Commit changes**.

## Publicar con Cloudflare Pages

1. En dash.cloudflare.com entra a **Workers & Pages → Create → Pages → Connect to Git**.
2. Elige el repositorio `venservi-agenda`.
3. Configuración de compilación:
   - Framework preset: **None**
   - Build command: déjalo **vacío**
   - Build output directory: **/** (o déjalo vacío)
4. Pulsa **Save and Deploy**. En uno o dos minutos te da un enlace como `venservi-agenda.pages.dev`. Ese es el link para enviar al cliente.

Cada vez que subas un cambio a GitHub, Cloudflare actualiza el sitio solo.

## Importante

- Los clientes, visitas y placas son ficticios. Las fotos son material de VENSERVI y se muestran como «Foto de referencia».
- Lo que cada persona cambie (confirmar visitas, crear clientes) se guarda solo en su propio navegador. Con el botón «Restablecer demo» vuelve a los datos de ejemplo.
- La página tiene la etiqueta `noindex` para que no aparezca en Google mientras sea una demo.
