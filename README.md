# livekawsay.com

Landing estática. Todo el sitio está en `public/`.

## Deploy en Cloudflare Workers

El dominio `livekawsay.com` está conectado al Worker `livekawsay-com`. Desde la raíz del proyecto:

    npx wrangler login
    npx wrangler deploy

No usar `wrangler pages deploy`: publica en el proyecto de Pages `livekawsay`, que no sirve el dominio.

## Pendiente
- Reemplazar placeholders entre [corchetes] (precio, duración, WhatsApp, fotos).
- Conectar el formulario de correo (Formspree / Worker / Google Sheets).
