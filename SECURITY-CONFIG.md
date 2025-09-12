# Astrodex - Configuración de Credenciales

## 🔧 Configuración Requerida

Antes de usar el sitio, debes reemplazar los siguientes placeholders en `index.html`:

### 1. LocationIQ API Key
- **Buscar:** `TU_NUEVA_LOCATIONIQ_KEY_AQUI`
- **Reemplazar con:** Tu nueva clave de LocationIQ
- **Obtener en:** https://locationiq.com/dashboard

### 2. Google reCAPTCHA Site Key
- **Buscar:** `TU_NUEVA_RECAPTCHA_SITE_KEY_AQUI`
- **Reemplazar con:** Tu nueva site key de reCAPTCHA
- **Obtener en:** https://www.google.com/recaptcha/admin

### 3. Make.com Webhook URL
- **Buscar:** `TU_WEBHOOK_URL_DE_MAKE_AQUI`
- **Reemplazar con:** Tu URL de webhook de Make.com
- **Formato:** `https://hook.us1.make.com/tu_webhook_id_aqui`

## 🚨 Seguridad

- **NUNCA** commitees las claves reales al repositorio público
- Regenera todas las claves que estuvieron expuestas
- Considera usar variables de entorno para proyectos más grandes

## 🚀 Deployment

Una vez configuradas las credenciales:

```bash
git add .
git commit -m "Configure API credentials"
git push origin main
```

El sitio se desplegará automáticamente en GitHub Pages.
