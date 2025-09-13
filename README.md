# Astrodex - Llave Astral 🌟

Formulario para generar llaves astrales personalizadas conectado con Make.com.

## 🚀 Deployment

Este proyecto usa GitHub Actions para deployment automático con secretos seguros.

### Configuración de Secrets

En GitHub, ve a Settings → Secrets and variables → Actions y agrega:

- `LOCATIONIQ_KEY`: Tu API key de LocationIQ
- `MAKE_WEBHOOK_URL`: Tu webhook URL de Make.com

### Deployment Automático

Cada push a `main` activa automáticamente:
1. ✅ Reemplazo de placeholders con secrets
2. ✅ Build del sitio
3. ✅ Deploy a GitHub Pages

## 🛡️ Seguridad

- ✅ API keys nunca expuestas en el código fuente
- ✅ Secrets manejados por GitHub Actions
- ✅ Deployment automático y seguro

## 🔧 Desarrollo Local

Para desarrollo local, reemplaza temporalmente los placeholders:
```javascript
const LOCATIONIQ_KEY = "tu_key_aqui";
const MAKE_WEBHOOK_URL = "tu_webhook_aqui";
```

**¡NUNCA hagas commit de las claves reales!**

## 📋 Features

- 🎯 Formulario responsivo
- 🌍 Autocompletado de lugares con LocationIQ
- ⏰ Cálculo de zonas horarias históricas
- ✉️ Integración con Make.com
- 🔒 HTTPS y dominio personalizado
- 🚀 Deployment automático