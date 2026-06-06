# 🚀 Guía completa: GitHub + Vercel + hotelproai.com

## Paso 1 — Crea una cuenta en GitHub (si no tienes)

1. Ve a **github.com**
2. Haz clic en "Sign up"
3. Elige un nombre de usuario (ej: `hotelproai`)
4. Confirma tu email

---

## Paso 2 — Crea un repositorio en GitHub

1. Estando en github.com, haz clic en el **+** (arriba a la derecha) → **"New repository"**
2. Ponle de nombre: `hotelproai-web`
3. Déjalo en **Public** (Vercel lo necesita en el plan gratuito)
4. Marca **"Add a README file"**
5. Haz clic en **"Create repository"**

---

## Paso 3 — Sube el index.html a GitHub

1. Dentro del repositorio que acabas de crear, haz clic en **"Add file"** → **"Upload files"**
2. Arrastra el archivo `index.html` a la zona de subida
3. Abajo del todo, escribe en "Commit message": `Primera versión web`
4. Haz clic en **"Commit changes"**

✅ Tu archivo ya está en GitHub.

---

## Paso 4 — Conecta GitHub con Vercel

1. Ve a **vercel.com** e inicia sesión (o crea cuenta gratis)
2. Haz clic en **"Add New Project"**
3. Selecciona **"Import Git Repository"**
4. Conecta tu cuenta de GitHub (botón "Add GitHub Account")
5. Busca y selecciona el repositorio `hotelproai-web`
6. En la pantalla de configuración, deja todo como está — Vercel detecta el HTML solo
7. Haz clic en **"Deploy"**

⏱ En ~30 segundos tendrás la web en una URL tipo `hotelproai-web.vercel.app`

---

## Paso 5 — Conectar el dominio hotelproai.com

### Si compraste el dominio EN Vercel:

1. Ve a tu proyecto en Vercel → pestaña **"Settings"** → **"Domains"**
2. Escribe `hotelproai.com` y haz clic en **"Add"**
3. Como el dominio ya está en Vercel, aparecerá un aviso: **"This domain is already managed by Vercel"**
4. Haz clic en **"Move to this project"** o **"Assign"**
5. ✅ Listo. En 2-5 minutos funciona con HTTPS automático.

### Si compraste el dominio en otro sitio (Namecheap, GoDaddy, etc.):

1. Ve a tu proyecto en Vercel → **Settings → Domains** → Añade `hotelproai.com`
2. Vercel te mostrará 2 registros DNS a configurar:
   - **Registro A**: apunta a `76.76.21.21`
   - **CNAME www**: apunta a `cname.vercel-dns.com`
3. Ve al panel DNS de donde compraste el dominio y añade esos registros
4. Espera 5-30 minutos para que propague

---

## Paso 6 — Actualizaciones futuras (súper fácil)

Cada vez que quieras cambiar algo en la web:

1. Edita el `index.html` en tu ordenador
2. Ve a tu repositorio en GitHub
3. Haz clic sobre `index.html` → botón del lápiz ✏️ → pega el contenido nuevo → **"Commit changes"**

**O más cómodo:** usa GitHub Desktop (app gratuita) para subir cambios arrastrando archivos.

→ Vercel detecta el cambio automáticamente y despliega la nueva versión en segundos.

---

## ✅ Checklist final

- [ ] Cuenta en GitHub creada
- [ ] Repositorio `hotelproai-web` creado
- [ ] `index.html` subido al repositorio
- [ ] Proyecto importado en Vercel
- [ ] Deploy exitoso (URL `.vercel.app` funciona)
- [ ] Dominio `hotelproai.com` conectado
- [ ] HTTPS activo (candado verde en el navegador)

---

## Próximo paso: Calendly

Cuando tengas el Calendly configurado, dime el link y en 2 minutos actualizo todos los botones de la web para que apunten directamente a tu calendario de reservas de auditoría.
