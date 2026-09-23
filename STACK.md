# 🎨 Documentación de Stack Tecnológico — tp2-pp1-gconcina

## 📋 Información General del Proyecto

| Campo | Valor |
|---|---|
| **Autor** | gconcina |
| **Repo** | https://github.com/gconcina/tp2-pp1-gconcina.git |
| **Rama** | `main` |
| **Licencia** | No especificada |
| **Tecnología** | HTML5, CSS3, JavaScript Vanilla |
| **Framework UI** | Bootstrap 5.3.2 |
| **Iconos** | FontAwesome 6.4.0 |

---

## 🗂️ Estructura de Archivos

```
tp2-pp1-gconcina/
├── css/
│   ├── portfolio1.css      # 🏨 Sakura Ryokan
│   ├── portfolio2.css      # 🌃 Neon District 2077
│   ├── portfolio3.css      # 🏛️ Maison Dorée
│   ├── tpn3.css            # 🛒 Lúmen E-Commerce
│   └── minijuego.css       # 🎮 Caza al Objetivo
├── portfolio1.html         # 🏨 Sakura Ryokan
├── portfolio2.html         # 🌃 Neon District 2077
├── portfolio3.html         # 🏛️ Maison Dorée
├── tpn3.html               # 🛒 Lúmen E-Commerce
├── minijuego.html          # 🎮 Caza al Objetivo
└── tpn3.html (staged)      # Historial de commits
```

---

## 🎮 Página 1: Lúmen — Librería & Papelería Técnica (`tpn3.html`)

### Stack
- **HTML5** + **CSS3** + **JavaScript Vanilla**
- **Bootstrap 5.3.2** (CSS + JS Bundle)
- **FontAwesome 6.4.0** (iconografía)
- **Google Fonts**: Inter (cuerpo), Jost (títulos)
- **Persistencia**: `localStorage` para stock del catálogo

### Paleta de Colores
| Variable | Color | Uso |
|---|---|---|
| `--primary-color` | `#2b4c7e` | Primario (brand, botones) |
| `--accent-color` | `#e06d53` | Acento (floating cart, alertas) |
| `--bg-light` | `#f8fafc` | Fondo general |
| `--text-main` | `#1e293b` | Texto principal |
| `--card-border` | `#e2e8f0` | Bordes de tarjetas |

### Tipografía
- **Cuerpo**: Inter (`400`, `500`, `600`, `700`) — sans-serif
- **Títulos**: Jost (`500`, `600`, `700`, `800`) — sans-serif

### Características
- Catálogo de productos con filtrado por categoría y búsqueda
- Filtro de rango de precios (min/max)
- Carrito de compras con Offcanvas (Bootstrap)
- Gestión de stock en tiempo real con persistencia en `localStorage`
- Checkout con modal de confirmación
- Badges de stock ("X en stock", "Agotado")
- Responsive con Bootstrap grid

### Imágenes de productos
- Cuaderno: `mitiendanube.com` (webp)
- Estilógrafos: `libreriamayoristaleo.com.ar` (jpg)
- Bolígrafo: `ddkjx5kezodfx.cloudfront.net` (webp)
- Escuadra: `mitiendanube.com` (webp)
- Mochila: `unsplash.com`
- Portaminas: `m.media-amazon.com` (jpg)
- Agenda: `unsplash.com`
- Estuche: `http2.mlstatic.com` (webp)

---

## 🏨 Página 2: Sakura Ryokan (`portfolio1.html`)

### Stack
- **HTML5** + **CSS3**
- **Bootstrap 5** (CSS)
- **Google Fonts**: Noto Sans JP, Noto Serif JP, Shippori Mincho

### Paleta de Colores (temática japonés/washi)
| Variable | Color | Significado |
|---|---|---|
| `--washi` | `#f5f1e8` | Papel de arroz |
| `--washi-oscuro` | `#ebe4d3` | Papel de arroz oscuro |
| `--tinta` | `#1a1a1a` | Tinta sumi-e |
| `--tinta-suave` | `#3d3d3d` | Tinta suave |
| `--akane` | `#c8372d` | Rojo bermellón tradicional |
| `--akane-oscuro` | `#9c2820` | Rojo bermellón oscuro |
| `--oro-antiguo` | `#b8935a` | Oro antiguo |
| `--verde-musgo` | `#6b7a5a` | Verde musgo |

### Tipografía
- **Cuerpo**: Noto Sans JP — sans-serif
- **Títulos/Deco**: Noto Serif JP, Shippori Mincho — serif
- **Textura**: Fondo con patrón sutil de papel washi

### Características
- Estética tradicional japonesa (washi, sumi-e)
- Textura de papel con degradados sutiles
- Círculos enso decorativos de fondo
- Temática de hostería/ryokan japonés

---

## 🌃 Página 3: Neon District 2077 (`portfolio2.html`)

### Stack
- **HTML5** + **CSS3**
- **Bootstrap 5.3.3** (CSS)
- **Google Fonts**: Orbitron, Rajdhani

### Paleta de Colores (temática cyberpunk/neon)
| Variable | Color | Uso |
|---|---|---|
| `--neon-cyan` | `#00f0ff` | Neon cian (grid, acentos) |
| `--neon-magenta` | `#ff00e5` | Neon magenta |
| `--neon-yellow` | `#f6ff00` | Neon amarillo |
| `--dark-bg` | `#0a0118` | Fondo oscuro |
| `--dark-panel` | `#140829` | Paneles oscuros |
| `--grid-color` | `rgba(0, 240, 255, 0.15)` | Grid de fondo |

### Tipografía
- **Cuerpo**: Rajdhani (`400`, `500`, `600`, `700`) — sans-serif
- **Títulos**: Orbitron (`400`, `500`, `700`, `900`) — sans-serif tech
- **Efecto**: Grid animado de fondo, scroll-behavior smooth

### Características
- Estética cyberpunk/futurista
- Fondo con grid de líneas neón
- Colores neón vibrantes sobre fondo oscuro
- Temática 2077 / distrito futurista

---

## 🏛️ Página 4: Maison Dorée (`portfolio3.html`)

### Stack
- **HTML5** + **CSS3**
- **Google Fonts**: Cormorant Garamond, Poiret One
- **Sin Bootstrap** (CSS puro)

### Paleta de Colores (temática Art Déco / lujo)
| Variable | Color | Significado |
|---|---|---|
| `--noir` | `#0d0d0d` | Negro profundo |
| `--noir-riche` | `#1a1612` | Negro enriquecido |
| `--or` | `#d4af37` | Dorado |
| `--or-clair` | `#f4d47c` | Dorado claro |
| `--creme` | `#f5ecd7` | Creme/beige |
| `--bordeaux` | `#6b1e2c` | Burdeos |
| `--ombre` | `rgba(0, 0, 0, 0.6)` | Sombra |

### Tipografía
- **Cuerpo/Títulos**: Cormorant Garamond (`300`, `500`, `700`) — serif elegante
- **Display**: Poiret One — display Art Déco
- **Estilo**: Tipografía serif de alta gama

### Características
- Estética Art Déco de lujo
- Fondo con gradiente radial oscuro
- Paleta dorada/negra/burdeos
- Tipografía serif refinada
- Sin dependencia de Bootstrap

---

## 🎮 Página 5: Caza al Objetivo — Arcade Challenge (`minijuego.html`)

### Stack
- **HTML5** + **CSS3** + **JavaScript Vanilla**
- **Bootstrap 5.3.2** (CSS, para componentes base)
- **FontAwesome 6.4.0** (iconografía)
- **Google Fonts**: Outfit (UI), Press Start 2P (arcade)
- **Web Audio API** (eliminada — sin audio)
- **localStorage** (high scores por dificultad)
- **Sin modal de Bootstrap** (modal de ayuda implementado en CSS puro)

### Paleta de Colores (temática arcade oscuro)
| Variable | Color | Uso |
|---|---|---|
| `--bg-dark` | `#0f172a` | Fondo principal |
| `--card-bg` | `#1e293b` | Fondo de tarjetas |
| `--accent-green` | `#10b981` | Verde (aciertos) |
| `--accent-blue` | `#3b82f6` | Azul (UI) |
| `--accent-red` | `#ef4444` | Rojo (bombas, errores) |

### Tipografía
- **UI general**: Outfit (`400`, `600`, `800`) — sans-serif moderna
- **Título arcade**: Press Start 2P — pixel font retro
- **Efecto**: Texto con gradiente arcoíris en título principal

### Características del Juego
- **Tipo**: Juego de puntería (caza de objetivos)
- **Dificultades**: Fácil, Normal, Difícil, Extremo
- **Objetivos**: Normales (+10 pts), Dorados (+30 pts), Bombas (-20 pts)
- **Timer**: 20-35s según dificultad con barra de progreso
- **Spawning**: Objetos aparecen aleatoriamente en el tablero
- **Persistencia**: High scores por dificultad en `localStorage`
- **Modal de ayuda**: Implementado en CSS puro (sin Bootstrap JS)
- **Game Over**: Modal con estadísticas (precisión, impactos, récord)
- **Sonido**: Eliminado (AudioEngine removido)

### Animaciones CSS
- `@keyframes popIn` — entrada de objetivos
- `@keyframes pulseGold` — pulso en objetivos dorados
- `@keyframes shake` — temblor en bombas
- `@keyframes floatUp` — popup de puntuación flotante

---

## 📦 Dependencias Externas (CDN)

| Recurso | Versión | Uso |
|---|---|---|
| Bootstrap CSS | `5.3.2` | Layout, componentes |
| Bootstrap JS Bundle | `5.3.2` | Modales, offcanvas, collapses |
| FontAwesome | `6.4.0` | Iconografía |
| Google Fonts | Múltiples | Tipografía |

**Fuentes Google cargadas:**
- Inter, Jost (tpn3)
- Noto Sans JP, Noto Serif JP, Shippori Mincho (portfolio1)
- Orbitron, Rajdhani (portfolio2)
- Cormorant Garamond, Poiret One (portfolio3)
- Outfit, Press Start 2P (minijuego)

---

## 🔧 Patrones de Código

### JavaScript en todas las páginas
- **Vanilla JS** puro (sin frameworks)
- **Funciones** organizadas en el scope global
- **localStorage** para persistencia de datos (stock, high scores)
- **Event listeners** para interacción del usuario
- **DOM manipulation** con `createElement`, `innerHTML`, `querySelector`

### CSS en todas las páginas
- **Custom Properties** (CSS Variables) para paletas
- **BEM-like** naming en clases
- **Responsive** con Bootstrap grid (excepto portfolio3)
- **@keyframes** para animaciones
- **Transitions** para hover effects

---

## 📊 Matriz Comparativa de Páginas

| | tpn3 | portfolio1 | portfolio2 | portfolio3 | minijuego |
|---|---|---|---|---|---|
| **Tipo** | E-Commerce | Hotel | Cyberpunk | Luxury | Arcade Game |
| **Bootstrap** | ✅ | ✅ | ✅ | ❌ | ✅ (CSS) |
| **JS** | ✅ | ❌ | ❌ | ❌ | ✅ |
| **localStorage** | ✅ | ❌ | ❌ | ❌ | ✅ |
| **Google Fonts** | Inter + Jost | Noto + Shippori | Orbitron + Rajdhani | Cormorant + Poiret | Outfit + Press Start 2P |
| **Colores** | Azul/Anaranjado | Washi/Akane | Neon/Oscuro | Dorado/Negro | Slate/Verde |
| **Responsive** | ✅ | ✅ | ✅ | Parcial | ✅ |
| **Modales Bootstrap** | ✅ | ❌ | ❌ | ❌ | ❌ (CSS puro) |
| **Imágenes** | Unsplash, Amazon, ML, CDN | ❌ | ❌ | ❌ | ❌ |

---

## 📝 Notas de Git

| Commit | Mensaje | Archivos |
|---|---|---|
| `6a833a6` | Separar minijuego.css del HTML | `css/minijuego.css`, `minijuego.html` |
| `9399849` | Fix: minijuego funcional | `minijuego.html` |
| `c12fc3c` | Corregidas imágenes del catálogo | `tpn3.html` |
| `2087a19` | Añadido filtro min/max precio | `tpn3.html` |
| `3017e2b` | Añadidas funciones de stock | `tpn3.html` |
| `37f1d70` | Separado estilo CSS | `css/tpn3.css`, `tpn3.html` |
| `6cce463` | Subido trabajo práctico N3 | `tpn3.html` |
| `5b11835` | Fix inicial | — |
| `2ea10ee` | Commit inicial | — |

---

## 🛠️ Herramientas Utilizadas

- **Editor**: OpenCode (con agent `gentle-orchestrator`)
- **Navegador**: Vivaldi (pruebas locales)
- **Git**: Version control via `origin`
- **Hosting**: GitHub Pages compatible
- **CDN**: jsDelivr, FontAwesome CDN, Google Fonts, Unsplash, Amazon, Mercado Libre, CloudFront

---

*Documentación generada el 23 de Septiembre de 2026.*
