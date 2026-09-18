# 🐬 Calderitas Xperience

Sitio web oficial de **Calderitas Xperience** — tours privados en lancha por la
**Bahía de Chetumal**: Isla Tamalcab y los cayos (Cayo Venado y Cayo Zorro),
con salidas desde el **muelle de Calderitas**, Quintana Roo.

🌐 **Web:** https://calderitasxperience.com

---

## Sobre el sitio

- Una sola página (`index.html`), **autocontenida** en HTML, CSS y JavaScript.
- Fotos reales incrustadas, **galería** con lightbox, **mapa de rutas** ilustrado
  y **reservas por WhatsApp** (el formulario abre el chat con los datos precargados).
- **Sin dependencias ni proceso de build**: se abre directamente en el navegador.

## Estructura

| Archivo | Descripción |
|---|---|
| `index.html` | Todo el sitio (contenido, estilos, imágenes y scripts). |
| `CNAME` | Dominio personalizado para GitHub Pages. |
| `README.md` | Este archivo. |

## Publicar / actualizar

Este sitio se publica con **GitHub Pages**:

1. Repositorio **público** con el archivo `index.html` en la raíz.
2. En **Settings → Pages**, *Source* = *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
3. Para actualizar, sube de nuevo `index.html` (reemplazando el anterior) y confirma
   el cambio; en ~1 minuto se refleja.

## Dominio personalizado

El sitio usa el dominio apex **calderitasxperience.com**.

En el panel DNS del proveedor del dominio:

- **4 registros A** con host `@` apuntando a:
  `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- **1 registro CNAME** con host `www` apuntando a `TU-USUARIO.github.io`

En **Settings → Pages → Custom domain** escribe `calderitasxperience.com` y activa
**Enforce HTTPS** cuando GitHub termine de emitir el certificado.

## Contacto

📱 WhatsApp: +52 983 191 7311 · 📍 Muelle de Calderitas, Bahía de Chetumal

---

© Calderitas Xperience. Experiencias personalizadas y seguras.
