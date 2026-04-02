# Team README — Faranda Social Club

## Bienvenido al proyecto

Este repositorio contiene todo el trabajo estratégico, comercial, de contenido y diseño del **Faranda Social Club**, un membership premium de pago para Faranda Hotels & Resorts.

---

## ¿Por dónde empezar?

### Si es tu primera vez en este repo:

1. **Lee el README principal** en la raíz del repositorio
2. **Lee** `/docs/00-project-overview.md` para entender el contexto
3. **Revisa** `/docs/01-strategy-summary.md` para ver decisiones estratégicas
4. **Abre** `/landing/social-club-v3/faranda-social-club-v3.html` — es la versión más avanzada de la landing
5. **Consulta** `/docs/06-open-questions.md` para ver qué decisiones siguen pendientes

---

## Estructura del repositorio

```
/docs                   → Documentación estratégica y comercial
  00-project-overview.md
  01-strategy-summary.md
  02-naming-options.md
  03-membership-benefits.md
  04-pricing-and-commercial-logic.md
  05-social-calendar-concept.md
  06-open-questions.md

/references             → Benchmarks y contexto de referencia
  design-system-notes.md
  disloyalty-benchmark.md
  current-program-faranda-direct-privileges.md

/landing                → Versiones HTML de landing page
  /v1                   (histórico)
  /v2                   (histórico)
  /v2-1                 (histórico)
  /social-club          (histórico)
  /social-club-premium  (histórico)
  /social-club-v3       ⭐ VERSIÓN ACTUAL BASE DE TRABAJO

/assets                 → Imágenes y recursos visuales
  /reference-images
  /faranda-assets

/handoff                → Documentos para el equipo
  team-readme.md        (este archivo)
  next-steps.md
```

---

## Roles y responsabilidades sugeridas

| Rol | Responsabilidad en este proyecto |
|-----|----------------------------------|
| **Marketing/Brand** | Validar naming, definir brand identity del club, comunicaciones |
| **Comercial/Revenue** | Aprobar pricing, proyección de uptake, validar modelo económico |
| **Ops Hoteleras** | Validar que perks son ejecutables, definir runbook operativo |
| **IT/Tech** | Integración CRM, motor de reservas con Member Rate, pasarela de pago |
| **Contenido/Copy** | Refinar copy de landing, crear contenidos de Social Calendar |
| **Diseño/UX** | Diseñar brand identity del club, versión final de landing |
| **Legal** | Revisar términos y condiciones, política de cancelación |

---

## Cómo trabajar en este repo

### 1. Lectura y revisión
- Todos los documentos en `/docs` y `/references` están abiertos a comentarios
- Si encuentras algo que no tiene sentido, **abre un Issue** en GitHub

### 2. Proponer cambios
- Si quieres proponer cambios a estrategia, perks, pricing, copy:
  - Crea un **branch** con tu nombre o tema (ej. `maria/pricing-revision`)
  - Haz tus ediciones
  - Abre un **Pull Request** para que el equipo revise
  - Discute en comentarios del PR
  - Merge a `main` cuando esté aprobado

### 3. Iterar sobre landing
- La landing base está en `/landing/social-club-v3/`
- Si creas una nueva versión:
  - Crea nueva carpeta `/landing/social-club-v4/` (o nombre descriptivo)
  - No borres versiones anteriores (son histórico)
  - Actualiza el README principal indicando cuál es la nueva versión base

### 4. Decisiones pendientes
- Consulta `/docs/06-open-questions.md`
- Si tienes respuesta a alguna pregunta abierta, **crea un Issue** o **comenta en el doc**
- Cuando una decisión se cierre, actualiza el documento correspondiente

---

## Estado actual del proyecto (abril 2026)

| Elemento | Estado |
|----------|--------|
| **Naming** | 🟡 En revisión — favorito: "Faranda Social Club" |
| **Pricing** | 🟡 Propuesta USD 79/año — pendiente aprobación final |
| **Perks** | 🟡 Definidos — pendiente validación ops |
| **Social Calendar** | 🟡 Concepto claro — pendiente calendario piloto |
| **Landing** | 🟢 Versión v3 lista — pendiente ajustes de contenido/diseño |
| **Brand Identity** | 🔴 Pendiente — ¿el club tiene logo propio? |
| **Integración técnica** | 🔴 Pendiente — CRM, motor de reservas, pago |

🟢 = Listo  
🟡 = En progreso  
🔴 = No iniciado

---

## Contactos clave

| Rol | Nombre | Email/Slack |
|-----|--------|-------------|
| **Project Lead** | [Nombre] | [email/slack] |
| **Marketing** | [Nombre] | [email/slack] |
| **Comercial** | [Nombre] | [email/slack] |
| **Ops** | [Nombre] | [email/slack] |
| **IT/Tech** | [Nombre] | [email/slack] |

---

## FAQ del equipo

### ¿Puedo editar directamente en `main`?
No. Crea un branch, haz tus cambios, abre Pull Request. Mantiene orden y trazabilidad.

### ¿Qué hago si encuentro un error en un documento?
Abre un Issue en GitHub describiendo el error. O crea PR con la corrección.

### ¿Dónde están las versiones anteriores de la landing?
En `/landing/v1`, `/landing/v2`, etc. Son histórico, no bases actuales de trabajo.

### ¿Cuál es la versión de landing que debo usar/revisar?
**`/landing/social-club-v3/faranda-social-club-v3.html`** — versión base actual.

### ¿Qué pasa si necesito crear contenido nuevo (ej. un nuevo documento)?
Agrégalo en la carpeta correspondiente (`/docs` si es estratégico, `/handoff` si es operativo, etc.). Actualiza el README principal con un link si es relevante.

### ¿Hay un timeline del proyecto?
Consulta `/handoff/next-steps.md` para próximos pasos y milestones sugeridos.

---

## Reglas de oro

1. **No inventes decisiones cerradas** — si algo no está aprobado, márcalo como propuesta
2. **Distingue entre aprobado, en revisión y pendiente** — usa el sistema de estados 🟢🟡🔴
3. **Documenta los "por qué"** — no solo qué se decidió, sino por qué se descartaron alternativas
4. **Mantén el histórico** — no borres versiones anteriores de documentos o landing
5. **Comunica cambios importantes** — si cierras una decisión crítica, avisa al equipo

---

## Recursos externos útiles

- **Faranda Hotels & Resorts:** [farandahotels.com](https://farandahotels.com)
- **Dis-loyalty (benchmark):** [dis-loyalty.com](https://dis-loyalty.com)
- **GitHub Guides:** [guides.github.com](https://guides.github.com)

---

**¡Éxito con el proyecto!**

Si tienes dudas sobre cómo usar este repo, pregunta al Project Lead o consulta la documentación de GitHub.

---

**Última actualización:** Abril 2026