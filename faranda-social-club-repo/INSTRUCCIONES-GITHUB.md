# Instrucciones para subir a GitHub — Faranda Social Club

## Opción A: Subida vía interfaz web (más fácil)

### 1. Crear el repositorio en GitHub

1. Ve a [github.com](https://github.com) e inicia sesión
2. Click en el botón **"+"** arriba a la derecha → **"New repository"**
3. Completa:
   - **Repository name:** `faranda-social-club`
   - **Description:** "Membership premium de pago para Faranda Hotels & Resorts"
   - **Visibility:** Private (si quieres que solo tu equipo lo vea) o Public
   - **NO marques** "Initialize this repository with a README" (ya lo tenemos)
4. Click **"Create repository"**

---

### 2. Subir los archivos

**Opción 2A: Drag & Drop (más simple)**

1. Descarga el .zip del repositorio que te entrego
2. Descomprime el .zip en tu computadora
3. En GitHub, en la página del repo recién creado, verás una opción **"uploading an existing file"**
4. Arrastra TODA la carpeta descomprimida a GitHub
5. Escribe un commit message: "Initial commit — Faranda Social Club proyecto completo"
6. Click **"Commit changes"**

**Opción 2B: GitHub Desktop (recomendado si vas a trabajar frecuentemente)**

1. Descarga [GitHub Desktop](https://desktop.github.com/)
2. Instala y vincula tu cuenta de GitHub
3. Click **"Add"** → **"Add existing repository"**
4. Selecciona la carpeta descomprimida del proyecto
5. Click **"Publish repository"**

---

### 3. Invitar a tu equipo

1. En el repositorio de GitHub, ve a **Settings** → **Collaborators**
2. Click **"Add people"**
3. Introduce el email o username de GitHub de cada persona del equipo
4. Selecciona el nivel de acceso:
   - **Write:** pueden editar y hacer commits
   - **Read:** solo pueden ver
5. Envía la invitación

---

## Opción B: Subida vía Git (línea de comandos)

### Requisitos
- Tener Git instalado ([descargar aquí](https://git-scm.com/downloads))
- Tener cuenta de GitHub

### Pasos

```bash
# 1. Descomprime el .zip en una carpeta
cd /ruta/a/la/carpeta/faranda-social-club-repo

# 2. Inicializa Git
git init

# 3. Agrega todos los archivos
git add .

# 4. Haz el primer commit
git commit -m "Initial commit — Faranda Social Club proyecto completo"

# 5. Conecta con el repositorio remoto de GitHub
# (Reemplaza 'TU-USUARIO' con tu username de GitHub)
git remote add origin https://github.com/TU-USUARIO/faranda-social-club.git

# 6. Crea la rama main
git branch -M main

# 7. Sube el código
git push -u origin main
```

---

## Después de subir el repositorio

### 1. Verifica que todo está bien

- Abre el repositorio en GitHub
- Verifica que todas las carpetas están:
  - `/docs`
  - `/references`
  - `/landing`
  - `/assets`
  - `/handoff`
  - `README.md`

### 2. Comparte el link con tu equipo

El link será: `https://github.com/TU-USUARIO/faranda-social-club`

Compártelo vía email o Slack con instrucciones:

```
Hola equipo,

Les comparto el repositorio del proyecto Faranda Social Club:
https://github.com/TU-USUARIO/faranda-social-club

Por favor:
1. Lean el README principal
2. Revisen /docs/00-project-overview.md
3. Abran /landing/social-club-v3/ para ver la landing más avanzada
4. Consulten /docs/06-open-questions.md para decisiones pendientes
5. Lean /handoff/team-readme.md para entender cómo trabajar en el repo

Cualquier duda, avisen.
```

---

## Estructura del repositorio (para referencia)

```
faranda-social-club/
│
├── README.md                           ⭐ Empezar aquí
│
├── /docs
│   ├── 00-project-overview.md
│   ├── 01-strategy-summary.md
│   ├── 02-naming-options.md
│   ├── 03-membership-benefits.md
│   ├── 04-pricing-and-commercial-logic.md
│   ├── 05-social-calendar-concept.md
│   └── 06-open-questions.md
│
├── /references
│   ├── design-system-notes.md
│   ├── disloyalty-benchmark.md
│   └── current-program-faranda-direct-privileges.md
│
├── /landing
│   ├── README.md                       ← Explica versiones de landing
│   ├── /v1                             (histórico)
│   ├── /v2                             (histórico)
│   ├── /v2-1                           (histórico)
│   ├── /social-club                    (histórico)
│   ├── /social-club-premium            (histórico)
│   └── /social-club-v3                 ⭐ VERSIÓN ACTUAL
│
├── /assets
│   ├── /reference-images
│   └── /faranda-assets
│
└── /handoff
    ├── team-readme.md                  ← Guía para el equipo
    └── next-steps.md                   ← Próximos pasos del proyecto
```

---

## Documentos clave que tu equipo debe leer primero

**En este orden:**

1. **`README.md`** (raíz) → contexto general
2. **`/docs/00-project-overview.md`** → qué es el proyecto y por qué existe
3. **`/docs/01-strategy-summary.md`** → decisiones estratégicas tomadas
4. **`/landing/social-club-v3/faranda-social-club-v3.html`** → ver la landing más avanzada
5. **`/docs/06-open-questions.md`** → qué decisiones siguen pendientes
6. **`/handoff/team-readme.md`** → cómo trabajar en el repo

---

## Preguntas frecuentes

### ¿El repositorio debe ser público o privado?

**Recomendación:** Privado, al menos inicialmente.

- **Privado** = solo tu equipo lo ve
- **Público** = cualquiera en internet puede verlo

Puedes cambiarlo después en Settings → Danger Zone → Change visibility.

---

### ¿Cómo agrego archivos HTML de las landings?

1. Copia el archivo HTML en la carpeta correspondiente en tu computadora
2. Si estás usando GitHub Desktop: aparecerá automáticamente en "Changes"
3. Escribe un commit message: "Agregar landing Social Club v3"
4. Click "Commit to main"
5. Click "Push origin"

---

### ¿Cómo hago cambios en los documentos?

**Vía interfaz web:**
1. Abre el archivo en GitHub
2. Click en el ícono del lápiz (Edit)
3. Haz tus cambios
4. Scroll abajo, escribe commit message
5. Click "Commit changes"

**Vía Git local:**
1. Edita el archivo en tu editor de texto
2. `git add .`
3. `git commit -m "Descripción del cambio"`
4. `git push`

---

### ¿Qué pasa si dos personas editan el mismo archivo?

GitHub detecta conflictos y te pide que los resuelvas manualmente.

**Buena práctica:** Usar Pull Requests para cambios importantes (ver `/handoff/team-readme.md`).

---

## Soporte

Si tienes problemas técnicos con Git/GitHub:
- [Documentación oficial de GitHub](https://docs.github.com)
- [GitHub Desktop Guides](https://docs.github.com/en/desktop)

---

**Última actualización:** Abril 2026
