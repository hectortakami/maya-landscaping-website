# 🚀 DESPLIEGUE EN NETLIFY — GUÍA RÁPIDA

## Lo que tienes listo:

✅ **Carpeta `deploy/`** con tu sitio completo y funcional
✅ **Todas las integraciones configuradas:**
   - WhatsApp (enlace directo con mensaje pre-llenado)
   - Email (mailto)
   - Teléfono (tel)
   - Instagram (enlace externo)
   - Formulario de cita → WhatsApp

✅ **Bilingüe** (Español/English)
✅ **Responsive** (funciona en móvil, tablet, desktop)

---

## 3 pasos para desplegar en vivo:

### **Paso 1: Crea un repositorio nuevo en GitHub**
- Ve a github.com → "New repository"
- Nombre: `maya-landscaping-website`
- Haz clic en "Create repository"

### **Paso 2: Sube los archivos**
```bash
# En tu terminal (en la raíz del proyecto):
git init
git add .
git commit -m "Initial commit - Maya Landscaping website"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/maya-landscaping-website.git
git push -u origin main
```

### **Paso 3: Conecta a Netlify**
- Ve a [netlify.com](https://netlify.com)
- Haz clic en "New site from Git"
- Selecciona GitHub y autoriza
- Selecciona el repositorio `maya-landscaping-website`
- En "Deploy settings":
  - **Build command:** (déjalo vacío)
  - **Publish directory:** `deploy`
- Haz clic en "Deploy site"

✅ **¡Listo!** Tu sitio estará en vivo en 1-2 minutos con una URL como:
`https://maya-landscaping-abc123.netlify.app`

---

## Después: Personalizaciones opcionales

- **Dominio propio:** En Netlify → Site settings → Domain management
- **Email personalizado:** Usa un servicio como Formspree o EmailJS
- **Fotos reales:** Reemplaza los placeholders en `deploy/index.html`

---

## Preguntas frecuentes

**P: ¿Puedo editar la página después de desplegar?**
R: Sí. Edita `deploy/index.html`, haz push a GitHub, y Netlify redesplegará automáticamente.

**P: ¿Cuesta dinero?**
R: No. Netlify es gratis para sitios estáticos. GitHub también.

**P: ¿Dónde se alojan las fotos?**
R: En la carpeta `deploy/` (o en un CDN como Cloudinary si quieres optimizar).

**P: ¿Cómo agrego análisis / estadísticas?**
R: Netlify incluye analytics básico gratis. Para más, usa Google Analytics.

---

¿Necesitas ayuda con algún paso? Avísame.
