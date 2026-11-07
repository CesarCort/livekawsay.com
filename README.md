# livekawsay.com

Landing estática. Todo el sitio está en `public/`.

## Deploy en Cloudflare Pages

    npx wrangler login
    npx wrangler pages deploy ./public --project-name livekawsay

O desde el dashboard: Workers & Pages → Create → Pages → Upload assets → subir `public/`.

Dominio: en el proyecto de Pages → Custom domains → `livekawsay.com` y `www.livekawsay.com`.

## Pendiente
- Reemplazar placeholders entre [corchetes] (precio, duración, WhatsApp, fotos).
- Conectar el formulario de correo (Formspree / Worker / Google Sheets).
