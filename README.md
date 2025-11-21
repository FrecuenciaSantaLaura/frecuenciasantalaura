# 📻 Frecuencia Santa Laura - Sitio Web Oficial

Página web estática de la radio escolar **Frecuencia Santa Laura**, alojada gratuitamente con **GitHub Pages**.  
Transmite en vivo usando **MyRadioStream** y muestra en tiempo real:  
✅ Título de la canción  
✅ Número de oyentes  
✅ Estado de la transmisión (en línea / sin fuente / caído)

---

## 🌐 URL Pública

Visita la radio en:  
👉 **https://[tu-usuario-de-github].github.io/frecuenciasantalaura/**

*(Reemplaza `[tu-usuario-de-github]` con tu nombre real de GitHub)*

---

## 🛠️ Cómo Personalizar

Este sitio está construido solo con **HTML, CSS y JavaScript** (sin backend).  
Puedes editar directamente en GitHub o localmente.

### 1. **Datos de transmisión**
- El stream se obtiene desde:  
  `http://s26.myradiostream.com:22812/`
- Los metadatos (título, oyentes) se leen desde:  
  `http://s26.myradiostream.com:22812/7.html`

> Si cambias de servidor en MyRadioStream, actualiza estas URLs en `index.html`.

### 2. **Contacto y redes sociales**
Edita estos enlaces en `index.html`:
- **WhatsApp**: reemplaza el número en `https://wa.me/56912345678`
- **Instagram**: actualiza la URL de tu cuenta

### 3. **Contador de visitas**
Actualmente usa **Hitwebcounter**.  
Para cambiarlo:
- Ve a [https://www.hitwebcounter.com](https://www.hitwebcounter.com)
- Genera tu propio contador
- Reemplaza la URL de la imagen en la sección `.counter-section`

### 4. **Logo (opcional)**
- Sube un archivo `logo.png` a este repositorio.
- Descomenta la línea del `<img>` en el `<header>` de `index.html`.

---

## 🎨 Diseño

- **Colores principales**:
  - Turquoise: `#00C8C8` (acento)
  - Fondo: `#FFFFFF`
  - Texto: `#333333`
- **Responsive**: se ve bien en móviles y computadores.
- **Sin frameworks**: código ligero y rápido.

---

## 📦 Tecnologías Usadas

- **GitHub Pages**: alojamiento gratuito
- **MyRadioStream**: transmisión en vivo (versión AirFree)
- **corsproxy.io**: para leer metadatos desde el navegador (CORS)
- **HTML5 + CSS3 + Vanilla JavaScript**: sin dependencias

---

## 📝 Notas Importantes

- Este sitio **no usa PHP ni backend**, por lo que es 100% compatible con GitHub Pages.
- El reproductor usa la URL de stream directa de MyRadioStream (sin iframe publicitario).
- Los datos de oyentes y título se actualizan cada **15 segundos**.

---

## 👥 Creado por

Equipo de **Frecuencia Santa Laura**  
Academia Santa Laura  
Santiago, Chile 🇨🇱

---

> ✨ "Dale Play a tu Recreo"
