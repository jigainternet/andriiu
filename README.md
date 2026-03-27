# 🎨 Andriu Artista — Guía de Lanzamiento

Página web con la estrategia completa para monetizar la presencia de **@aandriiiu** en Instagram: captura de emails, lanzamientos de productos, membresía artística y todos los textos comerciales listos para usar.

👉 **Ver la página publicada:** jigainternet.github.io/andriiu([(https://jigainternet.github.io/andriiu/)])

---

## 🚀 Cómo publicar en GitHub Pages (paso a paso)

### Paso 1 — Crear el repositorio en GitHub

1. Ve a [github.com](https://github.com) e inicia sesión (o crea una cuenta gratuita)
2. Haz clic en el botón **"New"** (repositorio nuevo)
3. En **"Repository name"** escribe exactamente: `jigainternet.github.io/andriiu`
   - ⚠️ El nombre debe ser `tunombredeusuario.github.io` (con tu usuario real de GitHub)
   - Si tu usuario de GitHub es `aandriiiu`, el repo se llama `aandriiiu.github.io`
4. Marca la opción **"Public"** (debe ser público para GitHub Pages gratuito)
5. Deja desmarcado "Add a README file" (ya tienes uno)
6. Haz clic en **"Create repository"**

---

### Paso 2 — Subir los archivos

#### Opción A: Desde el navegador (sin instalar nada) ✅ Recomendada

1. En la página del repositorio recién creado, haz clic en **"uploading an existing file"**
2. Arrastra y suelta estos 3 archivos:
   - `index.html`
   - `README.md`
   - `.nojekyll`
3. En la caja de abajo ("Commit changes") escribe: `Primer commit: guía de lanzamiento`
4. Haz clic en **"Commit changes"**

#### Opción B: Desde la terminal (Git)

```bash
# Clona el repositorio vacío
git clone https://github.com/aandriiiu/aandriiiu.github.io.git

# Copia los archivos dentro de la carpeta clonada
cp index.html aandriiiu.github.io/
cp README.md aandriiiu.github.io/
cp .nojekyll aandriiiu.github.io/

# Entra a la carpeta y sube los cambios
cd aandriiiu.github.io
git add .
git commit -m "Primer commit: guía de lanzamiento"
git push origin main
```

---

### Paso 3 — Activar GitHub Pages

1. Ve a tu repositorio → pestaña **"Settings"**
2. En el menú lateral izquierdo, haz clic en **"Pages"**
3. En **"Source"**, selecciona **"Deploy from a branch"**
4. En **"Branch"**, selecciona **"main"** y carpeta **"/ (root)"**
5. Haz clic en **"Save"**

⏳ En 1–3 minutos, tu página estará disponible en:
**`https://aandriiiu.github.io`**

---

### Paso 4 — Verificar que funciona

1. Espera 2–3 minutos
2. Visita `https://aandriiiu.github.io` en tu navegador
3. Deberías ver la guía completa

> Si ves un error 404, espera 5 minutos más y recarga la página.

---

## 📁 Archivos del repositorio

| Archivo | Descripción |
|---|---|
| `index.html` | La guía completa — página principal del sitio |
| `README.md` | Este archivo con las instrucciones |
| `.nojekyll` | Indica a GitHub que no procese el sitio con Jekyll |

---

## ✏️ Cómo editar el contenido

El contenido está todo en `index.html`. Para editarlo:

1. En GitHub, haz clic en `index.html`
2. Haz clic en el icono del lápiz ✏️ (arriba a la derecha)
3. Edita el texto directamente en el navegador
4. Haz clic en **"Commit changes"**

Los cambios se publican en 1–2 minutos automáticamente.

---

## 🔗 Conectar un dominio propio (opcional)

Si tienes un dominio propio (ej. `andriiuartista.com`):

1. En **Settings → Pages → Custom domain**, escribe tu dominio
2. En tu proveedor de dominio, añade un registro CNAME:
   - **Nombre:** `www`
   - **Valor:** `aandriiiu.github.io`
3. Espera hasta 24h para que se propague

---

## 📬 Contacto

- Instagram: [@aandriiiu](https://www.instagram.com/aandriiiu/)

---

*Guía preparada con estrategia de lanzamiento completa — Marzo 2026*
