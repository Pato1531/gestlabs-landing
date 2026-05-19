# GestLabs — Landing Page

Landing page comercial de **GestLabs**, marca paraguas de las plataformas **OnGest** y **EduGest** para institutos de inglés.

---

## 🚀 Deploy en Vercel (desde GitHub)

### 1. Subir a GitHub

```bash
git init
git add .
git commit -m "feat: landing GestLabs inicial"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/gestlabs-landing.git
git push -u origin main
```

### 2. Conectar a Vercel

1. Ir a [vercel.com](https://vercel.com) → **Add New Project**
2. Seleccionar el repo `gestlabs-landing`
3. Framework Preset: **Other** (sitio estático)
4. Root Directory: `/` (raíz)
5. Click **Deploy**

Vercel detecta automáticamente el `vercel.json` y despliega el `index.html` como sitio estático.

---

## 📁 Estructura del repo

```
gestlabs-landing/
├── index.html        # Landing page completa (HTML + CSS + JS inline)
├── vercel.json       # Configuración de deploy para Vercel
├── .gitignore
└── README.md
```

---

## 🌐 Dominio personalizado

Una vez deployado en Vercel:

1. **Settings → Domains** → agregar `gestlabs.com` o `www.gestlabs.com`
2. En tu registrador de dominio (Namecheap, GoDaddy, NIC.ar) agregar el CNAME:
   - `www` → `cname.vercel-dns.com`
   - Para el root (`@`) → IP que provee Vercel

---

## ✏️ Ediciones frecuentes

| Qué cambiar | Dónde en `index.html` |
|---|---|
| Número de WhatsApp | `wa.me/5491131749358` |
| Email de contacto | `hola@gestlabs.com` |
| Texto del hero | Sección `<!-- HERO -->` |
| Colores | Variables CSS `:root { }` al inicio del `<style>` |
| Links de productos | `href="https://ongest.vercel.app"` y `href="https://next-ezeiza.vercel.app"` |

---

## 🎨 Design Tokens

```css
--on-blue:   #0C447C   /* Azul OnGest / primario */
--on-teal2:  #1D9E75   /* Verde itálico / acento */
--edu-v2:    #534AB7   /* Violeta EduGest */
--edu-coral: #D85A30   /* Coral operativo */
```

---

## 📋 Checklist antes de publicar

- [ ] Registrar dominio `gestlabs.com`
- [ ] Crear email `hola@gestlabs.com` (Google Workspace o Zoho)
- [ ] Verificar número de WhatsApp activo: +54 9 11 3174-9358
- [ ] Registrar marca "GestLabs" en INPI Argentina (Clase 42)
- [ ] Revisar T&C y política de privacidad (Ley 25.326)

---

*Desarrollado por GestLabs · Buenos Aires, Argentina*
