# 🚀 Portfolio v3 - Joel Josafat Hernández Saucedo

Un portafolio personal construido con **Astro**, que presenta mis habilidades como desarrollador backend agregando efectos visuales y un sistema de logros interactivo.

## ✨ Características

- 🎯 **Efectos Typewriter** - Animaciones de escritura
- 🎨 **Partículas Interactivas** - Sistema dual de partículas (CSS y Three.js)
- 🏆 **Sistema de Logros** - Elementos gamificados ocultos para descubrir
- 🎵 **Reproductor de Música** - Música ambiental basada en videojuego RPG retro
- 📱 **Diseño Responsivo** - Optimizado para todos los dispositivos
- 🌙 **Modo Oscuro** - Interfaz adaptable mediante el uso del kodigo Konami
- 🔧 **Filtros de Proyectos** - Sistema de categorización entre proyectos personales y profesionales
- ⚡ **Rendimiento Optimizado** - Carga rápida gracias a Astro

## 🛠️ Tecnologías Utilizadas

- **Framework**: Astro 5.11.0
- **Visualización 3D**: Three.js
- **Estilos**: CSS Vanilla con variables personalizadas
- **Tipado**: TypeScript
- **Iconos**: SVG personalizados

## 📁 Estructura del Proyecto

```
portfolio_v3/
├── public/
│   ├── documents/          # CV y documentos
│   ├── music/             # Archivos de audio
│   ├── projects/          # Imágenes de proyectos
│   └── favicon.svg
├── src/
│   ├── components/
│   │   ├── sections/      # Secciones principales
│   │   │   ├── Hero.astro
│   │   │   ├── AboutMe.astro
│   │   │   ├── Projects.astro
│   │   │   └── Contact.astro
│   │   └── ui/            # Componentes de interfaz
│   │       ├── MusicPlayer.astro
│   │       ├── Navbar.astro
│   │       ├── Particles3D.astro
│   │       └── ProjectCard.astro
│   ├── data/              # Datos del sitio
│   │   ├── skills.json
│   │   └── projects/
│   │       └── projects_es.json  # Proyectos con categorización
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

## 🚀 Instalación y Uso

1. **Clona el repositorio**

   ```bash
   git clone https://github.com/JoelJohs/portfolio_v3.git
   cd portfolio_v3
   ```

2. **Instala las dependencias**

   ```bash
   npm install
   ```

3. **Inicia el servidor de desarrollo**

   ```bash
   npm run dev
   ```

4. **Construye para producción**

   ```bash
   npm run build
   ```

5. **Previsualiza la build de producción**
   ```bash
   npm run preview
   ```

## 🎯 Comandos Disponibles

| Comando           | Descripción                                       |
| :---------------- | :------------------------------------------------ |
| `npm install`     | Instala todas las dependencias                    |
| `npm run dev`     | Inicia servidor de desarrollo en `localhost:4321` |
| `npm run build`   | Construye el sitio para producción                |
| `npm run preview` | Previsualiza la build localmente                  |
| `npm run astro`   | Ejecuta comandos de Astro CLI                     |

## 🔧 Sistema de Filtros de Proyectos

El portafolio incluye un sistema de filtrado para organizar los proyectos:

### 📂 Categorías

- **Todos** - Muestra todos los proyectos sin filtro
- **Profesionales** - Proyectos desarrollados para clientes o empresas
- **Personales** - Proyectos hechos para practicar o por diversión

### 🏗️ Estructura de Datos

Cada proyecto incluye la propiedad `type` para la categorización:

```json
{
  "title": "Nombre del Proyecto",
  "description": "Descripción del proyecto",
  "image": "/projects/imagen.png",
  "demo": "https://demo-url.com",
  "code": "https://github.com/usuario/repo",
  "technologies": ["Tech1", "Tech2"],
  "type": "personal" | "professional"
}
```

## 🏆 Sistema de Logros

El portafolio incluye un sistema de logros ocultos que los visitantes pueden desbloquear:

- 📧 **Rastro digital** - Copiar email de contacto
- 🔍 **Explorador curioso** - Visitar la sección de proyectos
- 🌙 **Sombras activadas** - Activar modo oscuro con Konami Code
- 🖱️ **Toque insistente** - Triple click en el logo
- 👨‍💻 **Explorador de código** - Abrir herramientas de desarrollador
- 🎵 **Ambiente sonoro** - Reproducir música
- ⚡ **Partículas mágicas** - Cambiar tipo de partículas
- ⏰ **Momento zen** - Permanecer inactivo por 1 minuto

## 📞 Contacto

- **Email**: jojohersa21@gmail.com
- **LinkedIn**: [joel-johs](https://www.linkedin.com/in/joel-johs)
- **GitHub**: [JoelJohs](https://github.com/JoelJohs)

---

## 📝 Updates

### 2025-01-24

- 🔧 **Sistema de Filtros de Proyectos**
  - Implementado sistema de categorización de proyectos (Personales/Profesionales)
  - Añadidos filtros con botones
  - Grid de 3 columnas que se adapta automáticamente
  - Transiciones suaves
  - Estructura de datos con propiedad `type`

### 2025-01-23

- 🎉 **Lanzamiento inicial del Portfolio v3**
  - Implementado sistema de efectos typewriter
  - Agregado sistema de partículas dual (CSS + Three.js)
  - Creado sistema de logros gamificado
  - Integrado reproductor de música ambiental
  - Implementado diseño responsivo completo
  - Agregado modo oscuro con Konami Code

---

## 📋 Pendientes

### 🌐 Funcionalidades Futuras

- [ ] **Multiidioma** _(Agregado: 2025-01-23)_

  - Implementar soporte para inglés y español
  - Sistema de cambio de idioma dinámico
  - Internacionalización de todos los textos

- [ ] **Blog Section** _(Agregado: 2025-01-23)_

  - Sección de artículos técnicos
  - Sistema de tags y categorías
  - Integración con markdown

- [ ] **Animaciones Avanzadas** _(Agregado: 2025-01-23)_
  - Transiciones de página más fluidas
  - Efectos de scroll personalizados
  - Microinteracciones mejoradas

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

---

_Hecho con ❤️ por Joel Josafat Hernández Saucedo_
