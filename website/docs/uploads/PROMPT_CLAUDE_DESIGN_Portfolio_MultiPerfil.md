# 🎨 PROMPT PARA CLAUDE DESIGN
## Portfolio Profesional Multi-Perfil BIM + Estimación + Automatización

---

## 📌 RESUMEN EJECUTIVO

Diseña un **portfolio digital profesional** con 4 perfiles especializados (AI/Automation, Estimator, Steel Detailer, BIM Manager). Cada perfil tiene:
- **Estructura idéntica** (header, hero, projects, footer)
- **Identidad visual única** (colores, tipografía, animaciones características)
- **Funcionalidad completa** (dark/light mode, bilingüe EN/ES, responsive)
- **Modal expandible** para detalles de proyectos (galería, descripciones, herramientas, logros)

El usuario es **Leonardo Raudales**, ingeniero civil con 10+ años de experiencia. El portfolio debe comunicar profesionalismo, precisión técnica y versatilidad.

---

## 🏗️ ARQUITECTURA GENERAL

### Landing Page (Página Principal)
- **Objetivo:** Seleccionar perfil
- **Layout:** Grid 2x2 (desktop), responsive a 1 columna (mobile)
- **Elementos:**
  - Header superior con logo/título + toggles (dark/light, EN/ES)
  - Línea verde/cian decorativa en top
  - 4 tarjetas de perfil interactivas
  - Cada tarjeta: ícono + título + descripción + badges de tools + "Explore +" CTA
  - Footer con estadísticas globales (años exp, proyectos, clientes, etc.)
  - Cursor personalizado (punto verde pequeño a la izquierda, actual)

### Páginas de Perfil (4 variantes)
- **Estructura común:**
  1. Header (fijo, sticky)
  2. Hero Section (título + descripción breve + video animado de fondo)
  3. Selected Projects (grid 2 columnas desktop, 1 mobile)
  4. Footer (redes sociales + links)

---

## 🎨 IDENTIDAD VISUAL POR PERFIL

### Perfil 1: AI/AUTOMATION
**Color Primario:** Verde/Cian (#00ff88)
**Colores Secundarios:** Gris oscuro (#1a1f3a), Negro (#0a0e27)
**Tipografía:** Inter (headers), Open Sans (body) - Sans-serif moderna
**Tono Visual:** Futurista, tech, minimalista
**Elementos Característicos:** 
  - Líneas de código visibles en background
  - Iconografía tech (APIs, Python, Power Automate, Claude AI)
  - Animación: Líneas de datos fluyendo (sutil, de fondo)
**Video Hero:** Animación de flujo de datos/código (8-10 segundos, loop) - *El usuario lo proporciona*

### Perfil 2: ESTIMATOR
**Color Primario:** Azul Profesional (#1E90FF)
**Colores Secundarios:** Gris claro (#d3d1c7), Blanco (#f1efd8)
**Tipografía:** Poppins (headers), Roboto (body) - Sans-serif legible
**Tono Visual:** Corporativo, confiable, datos-driven
**Elementos Característicos:**
  - Gráficos/números prominentes
  - Iconografía de finanzas (PlanSwift, Excel, gráficos)
  - Animación: Contadores numéricos al scrollear (números suben/cambian)
**Video Hero:** Gráfico de barras animado subiendo + números incrementando (6-8 segundos, loop) - *El usuario lo proporciona*

### Perfil 3: STEEL DETAILER
**Color Primario:** Naranja/Cobre (#FF6B35)
**Colores Secundarios:** Gris metalizado (#888780), Negro (#2c2c2a)
**Tipografía:** Roboto (headers), Courier New monospace (specs técnicas)
**Tono Visual:** Industrial, preciso, técnico
**Elementos Característicos:**
  - Planos técnicos/medidas visibles
  - Iconografía industrial (Advance Steel, herramientas, acero)
  - Animación: Tarjetas de proyecto con efecto 3D subtle (elevación al hover)
**Video Hero:** Isometría de conexión de acero rotando (8-10 segundos, loop) - *El usuario lo proporciona*

### Perfil 4: BIM MANAGER
**Color Primario:** Púrpura (#9D4EDD)
**Colores Secundarios:** Teal (#1D9E75), Gris (#5F5E5A)
**Tipografía:** Open Sans (headers), Poppins (body) - Sans-serif clean
**Tono Visual:** Colaborativo, integrativo, coordinativo
**Elementos Característicos:**
  - Conexiones/flujos visibles entre elementos
  - Iconografía de coordinación (Revit, BIM 360, múltiples disciplinas)
  - Animación: Líneas de conexión animadas entre tarjetas de proyecto
**Video Hero:** Modelos BIM integrándose/coordinándose (10-12 segundos, loop) - *El usuario lo proporciona*

---

## 📐 WIREFRAME GENERAL (Estructura Idéntica)

```
┌──────────────────────────────────────────────────────┐
│ [Logo] [ESTIMATOR] [Dark/Light] [EN/ES] [Menu]      │  ← HEADER (sticky)
│ ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━   │
├──────────────────────────────────────────────────────┤
│                                                      │
│  ESTIMATOR                                           │
│  "Cost estimation, quantity takeoffs & project      │
│   bidding at scale with AI integration"            │
│                                                      │
│  [VIDEO ANIMADO - Hero Background]                 │
│  (El usuario proporciona video .mp4)               │
│                                                      │
├──────────────────────────────────────────────────────┤
│                                                      │
│  SELECTED PROJECTS                                  │
│                                                      │
│  [Project Card 1]  [Project Card 2]                │
│   +Click→ Modal    +Click→ Modal                    │
│                                                      │
│  [Project Card 3]  [Project Card 4]                │
│   +Click→ Modal    +Click→ Modal                    │
│                                                      │
│  [Project Card 5]  [Project Card 6]                │
│   +Click→ Modal    +Click→ Modal                    │
│                                                      │
├──────────────────────────────────────────────────────┤
│ LinkedIn │ Instagram │ GitHub │ Contact │ WhatsApp │  ← FOOTER
│                  [Botón Retorno a Home]              │
└──────────────────────────────────────────────────────┘
```

---

## 🎯 HEADER (Fijo/Sticky)

**Componentes:**
- Logo/Nombre: "LEONARDO RAUDALES" (pequeño, izquierda)
- Título Perfil: "ESTIMATOR" (centro, color del perfil)
- Navegación derecha:
  - Toggle Dark/Light (icono sol/luna)
  - Toggle EN/ES (bandera o texto "EN/ES")
  - Menu hamburguesa (mobile)
- **Línea decorativa horizontal** debajo (color del perfil, 1-2px)

**Comportamiento:**
- Fondo semi-transparente con backdrop blur (dark mode: transparente al negro, light mode: transparente al blanco)
- Al scrollear: sigue siendo sticky

**Altura:** ~60-70px

---

## 🎬 HERO SECTION

**Layout:**
```
┌─────────────────────────────────────┐
│                                     │
│    ESTIMATOR                        │  ← Título grande (h1, 42-48px)
│                                     │
│    Cost estimation, quantity        │  ← Subtítulo/descripción (16-18px)
│    takeoffs & project bidding       │
│    at scale with AI integration    │
│                                     │
│    ╔═══════════════════════════╗   │  ← Video background
│    ║  [VIDEO ANIMADO]          ║   │
│    ║  (proporcionado por user) ║   │
│    ║  Loop infinito, muted     ║   │
│    ╚═══════════════════════════╝   │
│                                     │
└─────────────────────────────────────┘
```

**Especificaciones:**
- **Altura:** 350-400px (responsive, cae a 250px en mobile)
- **Video:**
  - Tamaño: Full width, aspect ratio 16:9
  - Loop: Infinito
  - Audio: Muted
  - Overlay: Gradient suave (rgba(0,0,0,0.3) abajo)
  - Placeholder: Color del perfil + "Loading video..."
- **Texto:**
  - Color: Blanco (#ffffff)
  - Font weight: 600 (titulo), 400 (descripción)
  - Posicionamiento: Centrado, overlay sobre video
  - Sombra: text-shadow suave para legibilidad

---

## 📊 SELECTED PROJECTS SECTION

### Layout de Tarjetas
```
┌─────────────────────────────────────────────────────┐
│ SELECTED PROJECTS                                   │
│                                                     │
│  ┌──────────────────┐  ┌──────────────────┐       │
│  │ [Project Card 1] │  │ [Project Card 2] │       │
│  │ + Click to Open  │  │ + Click to Open  │       │
│  └──────────────────┘  └──────────────────┘       │
│                                                     │
│  ┌──────────────────┐  ┌──────────────────┐       │
│  │ [Project Card 3] │  │ [Project Card 4] │       │
│  └──────────────────┘  └──────────────────┘       │
│                                                     │
│  ┌──────────────────┐  ┌──────────────────┐       │
│  │ [Project Card 5] │  │ [Project Card 6] │       │
│  └──────────────────┘  └──────────────────┘       │
│                                                     │
└─────────────────────────────────────────────────────┘
```

### Tarjeta Individual de Proyecto
```
┌──────────────────────────┐
│ [Ícono del Proyecto]     │  ← 24px, color del perfil
│                          │
│ PROJECT TITLE            │  ← 14px bold, color del perfil
│ Company Name             │  ← 12px gray
│ Brief description        │  ← 11px lighter gray
│                          │
│ [Badge 1] [Badge 2]      │  ← Tools utilizadas (small badges)
│ [Badge 3]                │
│                          │
│ [Click to expand] →      │  ← CTA link
│                          │
└──────────────────────────┘
```

**Especificaciones:**
- **Grid:** 2 columnas (desktop), 1 columna (tablet/mobile)
- **Tamaño tarjeta:** ~280-300px width
- **Borde:** 1px solid (color del perfil, 50% opacity)
- **Hover Effect:** 
  - Border color: Full opacity
  - Transform: scale(1.02)
  - Box-shadow: 0 0 12px rgba(color_perfil, 0.2)
  - Transición: 0.3s ease
- **Padding:** 1.5rem
- **Gap entre tarjetas:** 1.5rem (horizontal), 2rem (vertical)

---

## 🪟 MODAL EXPANDIBLE (Project Details)

Se abre al hacer click en una tarjeta. **Centrado con overlay oscuro.**

### Estructura del Modal

```
┌─────────────────────────────────────────────────────┐
│ [Título Proyecto]           [X Cerrar]              │  ← Header
│ Empresa • Ubicación                                  │
├─────────────────────────────────────────────────────┤
│                                                     │
│  GALERÍA DE IMÁGENES                               │
│  ┌────────────────────────────────────────┐        │
│  │        [Imagen Principal - 16:9]       │        │
│  └────────────────────────────────────────┘        │
│  ┌──┐ ┌──┐ ┌──┐ ┌──┐                              │
│  │T1│ │T2│ │T3│ │T4│ (Miniaturas seleccionables) │
│  └──┘ └──┘ └──┘ └──┘                              │
│                                                     │
│  INFORMACIÓN DEL PROYECTO                          │
│  ┌──────────────┐ ┌──────────────┐               │
│  │ Rol          │ │ Duración     │               │
│  │ Detallista   │ │ 8 meses      │               │
│  └──────────────┘ └──────────────┘               │
│  ┌──────────────┐ ┌──────────────┐               │
│  │ Equipo       │ │ Métrica Key  │               │
│  │ 5 personas   │ │ 2,150 tons   │               │
│  └──────────────┘ └──────────────┘               │
│                                                     │
│  DESCRIPCIÓN                                        │
│  "Párrafo detallado del proyecto con contexto,     │
│   objetivos logrados, desafíos técnicos resueltos, │
│   y impacto en el proyecto..."                     │
│                                                     │
│  HERRAMIENTAS UTILIZADAS                           │
│  [Revit] [Advance Steel] [AutoCAD] [Navisworks]   │
│  [Excel] [BIM 360]                                │
│                                                     │
│  LOGROS Y RESULTADOS                               │
│  ✓ Resultado 1 específico                          │
│  ✓ Resultado 2 cuantificable                       │
│  ✓ Resultado 3 con métrica                         │
│  ✓ Resultado 4 impactante                          │
│                                                     │
├─────────────────────────────────────────────────────┤
│ [LinkedIn]   [Instagram]   [GitHub]                │  ← Footer CTA
│                                                     │
└─────────────────────────────────────────────────────┘
```

### Especificaciones del Modal

**Overlay:**
- Fondo: rgba(0, 0, 0, 0.85)
- Cerrable: Click fuera del modal o botón X
- Smooth transition: 0.3s ease

**Contenedor Modal:**
- Max-width: 700px
- Max-height: 90vh (scrolleable interno si es necesario)
- Border-radius: 12px
- Border: 1px solid (color del perfil, 50% opacity)
- Background: Color de fondo del perfil

**Header (Sticky):**
- Position: sticky top
- Display: flex, justify-space-between
- Padding: 1.5rem
- Border-bottom: 1px solid (color del perfil, 30% opacity)

**Botón Cerrar (X):**
- 32x32px, circular
- Border: 1px solid (color del perfil)
- Hover: background rgba(color_perfil, 0.1)

**Secciones Internas:**
- Separadas por border-top (1px, color del perfil, 30% opacity)
- Padding entre secciones: 1.5rem top/bottom
- Titulos de sección: 13px, UPPERCASE, color del perfil
- Letra-spacing: 0.5px

**Galería de Imágenes:**
- Imagen principal: aspect-ratio 16/9, border-radius 8px
- Miniaturas: 4 columnas, aspect-ratio 1:1, seleccionables
- Hover en miniaturas: border-color y box-shadow

**Grid de Información:**
- 2 columnas (info-grid)
- Cada item: background secondary, border subtle, padding 0.75rem
- Textos: label (11px gray), value (13px bold, color del perfil)

**Tools Badges:**
- Display: flex, flex-wrap, gap 0.75rem
- Badge style: border 0.5px (color del perfil), padding 0.5rem 0.75rem, border-radius 4px
- Texto: 11px, color del perfil, font-weight 500

**Achievements:**
- Display: flex flex-direction column, gap 0.75rem
- Cada item: border-left 2px (color del perfil), padding 0.75rem, background secondary
- Prefix: "✓ " en color del perfil

**Footer CTAs:**
- Grid 2 columnas gap 0.75rem
- Botones: border 1px (color del perfil), transparent background, hover rgba(color, 0.1)
- Padding: 0.75rem 1rem
- Font-size: 12px, font-weight 500
- Transición: 0.2s

---

## 🔄 FOOTER GLOBAL

```
┌─────────────────────────────────────────────────────┐
│                                                     │
│  LinkedIn  Instagram  GitHub  Contact  WhatsApp    │
│                                                     │
│              [← Back to Home]                       │
│                                                     │
└─────────────────────────────────────────────────────┘
```

**Especificaciones:**
- Padding: 2rem vertical, 1.5rem horizontal
- Display: flex, justify-content center, gap 2rem
- Border-top: 1px (color del perfil, 30% opacity)
- Icons: Tabler or similar, 20-24px
- Hover: color cambio, transform scale(1.1), transition 0.2s
- Botón Home: text-link, color del perfil, hover underline

---

## 🎮 INTERACTIVIDAD & NAVEGACIÓN

### Navegación Entre Perfiles
- Al hacer click en "Explore +" en landing page, entra al perfil
- Transición: Zoom + Fade (la tarjeta se agranda y desvanece, entra nuevo perfil)
- Duración: 500ms ease-out

### Elementos Interactivos
- **Tarjetas proyecto:** Hover = scale(1.02) + border color + shadow
- **Botones:** Hover = background rgba(color, 0.1) + scale(1.02)
- **Modal:** Open = overlay fade in, modal slide up desde abajo 
- **Dark/Light toggle:** Smooth transition 0.3s
- **Idioma toggle:** Cambio instantáneo de texto

### Cursor Personalizado
- Punto verde pequeño (#00ff88) a la izquierda
- Mantener en TODOS los perfiles
- Size: ~8-12px

---

## 🌓 DARK/LIGHT MODE

**Dark Mode (Default - prefers-color-scheme: dark):**
- Fondo base: #0a0e27
- Fondo secundario: #0f1533
- Texto primario: #ffffff
- Texto secundario: #888888
- Texto terciario: #666666
- Border: rgba(color_perfil, 30%-50%)

**Light Mode (prefers-color-scheme: light):**
- Fondo base: #ffffff / #f5f5f5
- Fondo secundario: #f1f1f1
- Texto primario: #1a1a1a
- Texto secundario: #555555
- Texto terciario: #999999
- Border: rgba(color_perfil, 20%-40%)

**Transición:** smooth 0.3s entre modos

---

## 🌐 BILINGÜE (EN/ES)

- **Toggle ubicación:** Header derecha (EN/ES flag o text)
- **Almacenamiento:** localStorage para persistencia
- **Contenido:** TODO el texto debe estar disponible en ambos idiomas
  - Landing page
  - Títulos de secciones
  - Descripciones de proyectos (los titles/companies pueden quedar igual)
  - Footer links
  - Botones CTA

---

## 📱 RESPONSIVE

**Breakpoints:**
- **Desktop:** 1200px+ (grid 2 cols projects)
- **Tablet:** 768px - 1199px (grid 2 cols, columnas más estrechas)
- **Mobile:** <768px (grid 1 col projects)

**Ajustes Mobile:**
- Landing page: 1 column de tarjetas (stack)
- Hero height: 250px
- Font sizes: -2px a -4px
- Padding: -0.25rem to -0.5rem
- Modal: width 95%, max-height 100vh
- Footer: stack vertical en mobile <480px

---

## 🎬 ANIMACIONES (Consistentes, no por perfil)

- **Transiciones entre pages:** 0.3s ease-out
- **Hover effects:** 0.2s-0.3s ease
- **Modal open/close:** 0.3s fade + slide
- **Dark/Light mode:** 0.3s smooth transition
- **Scroll animations:** Subtle, no distractoras

**Nota:** Las animaciones ADICIONALES son:
- Estimator: Contadores numéricos (números suben)
- Steel Detailer: Efecto 3D en tarjetas (elevation)
- BIM Manager: Líneas animadas de conexión

---

## 🎨 ELEMENTOS A CONSERVAR (Del portfolio anterior)

✅ Cursor personalizado (punto verde)
✅ Botón retorno a home (footer)
✅ Sistema de iconos/badges para Software & Tools
✅ Dark/Light mode
✅ Bilingüe EN/ES
✅ Landing page con 4 perfiles en grid
✅ Línea decorativa en header

---

## 📦 ARCHIVOS/ASSETS QUE PROPORCIONA EL USUARIO

**Videos para Hero (1 por perfil):**
1. `ai-automation-hero.mp4` (8-10 seg, 1920x1080, loop)
2. `estimator-hero.mp4` (6-8 seg, 1920x1080, loop)
3. `steel-detailer-hero.mp4` (8-10 seg, 1920x1080, loop)
4. `bim-manager-hero.mp4` (10-12 seg, 1920x1080, loop)

**Imágenes de Proyectos (galería de 4 por proyecto):**
- Formato: PNG/JPG, recomendado 1920x1080 para main, 600x600 para thumbnails
- Carpeta: `/images/projects/`

**Contenido de Proyectos (se agrega en SEGUNDA FASE):**
- Títulos, empresas, descripciones, herramientas, logros
- El diseño está listo para recibir este contenido

---

## ✅ CHECKLIST DEL DISEÑO

- [ ] Landing page con 4 tarjetas de perfil (grid 2x2, responsive)
- [ ] Header sticky con logo, profile title, dark/light, EN/ES, menu
- [ ] Hero section con video background (placeholders listos)
- [ ] Selected Projects con grid 2 col responsive
- [ ] Project cards con hover effects (scale + border + shadow)
- [ ] Modal expandible (centrado, overlay, scrolleable, completo)
- [ ] Footer con social links y back button
- [ ] Dark/Light mode funcional (prefers-color-scheme)
- [ ] Bilingüe EN/ES (estructura lista, textos placeholders en ambos idiomas)
- [ ] Colores únicos por perfil (AI, Estimator, Detailer, Manager)
- [ ] Animaciones transiciones entre perfiles (zoom + fade)
- [ ] Cursor personalizado consistente
- [ ] Responsive mobile/tablet/desktop
- [ ] Modal con galería, info grid, descripción, tools, achievements, CTAs
- [ ] Transiciones suaves 0.2s-0.5s
- [ ] Accesibilidad básica (botones, links, focus states)

---

## 📝 NOTAS FINALES

1. **El contenido es placeholder:** Nombres, descripciones, imágenes van en fase 2
2. **Videos son responsabilidad del usuario:** El diseño solo los embebe
3. **Tipografía:** Usar system fonts o Google Fonts gratuitas (Inter, Poppins, Roboto, Open Sans)
4. **No usar imagenes de fondo excepto en hero:** Keep clean, professional
5. **Animaciones sutiles, no distrayentes:** Este es un portfolio profesional, no un sitio de entretenimiento
6. **Mantener contraste y legibilidad en ambos modos** (dark/light)
7. **Código entregable:** HTML/CSS/JS vanilla o framework ligero (React es ok si es clean)

---

**Listo para iniciar el diseño. ¡Adelante!**