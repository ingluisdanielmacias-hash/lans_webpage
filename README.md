# LANS Edificaciones y Servicios Webpage

Una página web moderna, responsiva e innovadora para LANS EDIFICACIONES Y SERVICIOS ®, creada con HTML5, CSS3 y Bootstrap 5. Reemplaza la página original de Google Sites con un diseño profesional, mejor distribución de contenido, identidad visual corporativa y vistas completamente responsivas.

## 🎨 Características Principales

- **Diseño Responsivo Completo**: Optimizado para móviles, tablets y desktops con Bootstrap 5.
- **Identidad Visual Corporativa**: Colores turquesa/teal de LANS integrados en toda la página.
- **Logo Corporativo**: Secciones específicas para el logo principal y el logo circular.
- **Animaciones Modernas**: Efectos suaves, gradientes y transiciones mejoradas.
- **Estructura Intuitiva**:
  - **Header**: Logo y eslogan corporativo
  - **Navegación**: Menú responsive con hover effects
  - **Inicio**: Hero section atractivo con llamada a acción
  - **Antecedentes**: Historia y misión de la empresa
  - **Servicios**: Tarjetas con servicios principales y iconos
  - **Contacto**: Formulario de contacto integrado
  - **Footer**: Pie de página con información corporativa

## 📁 Estructura de Archivos

```
lans_webpage/
├── index.html                  # Página principal
├── styles.css                  # Estilos corporativos
├── README.md                   # Este archivo
└── assets/
    └── images/
        ├── logo-lans.png       # Logo principal (180x80px recomendado)
        └── logo-circle.png     # Logo circular (120x120px recomendado)
```

## 🖼️ Guía de Imágenes

Para que la página se vea perfectamente, debes agregar tus imágenes de logo en la carpeta `assets/images/`:

### Logo Principal (`logo-lans.png`)
- **Dimensiones Recomendadas**: 180 x 80 píxeles
- **Ubicación**: Parte superior izquierda del header
- **Uso**: Logo junto al nombre de la empresa

### Logo Circular (`logo-circle.png`)
- **Dimensiones Recomendadas**: 120 x 120 píxeles
- **Ubicación**: Parte derecha del header (visible solo en pantallas medianas y grandes)
- **Uso**: Logo decorativo con animación flotante

## 🎯 Pasos de Instalación

1. **Descarga o clona el proyecto** en tu computadora
2. **Agrega las imágenes del logo**:
   - Guarda el logo principal como `assets/images/logo-lans.png`
   - Guarda el logo circular como `assets/images/logo-circle.png`
3. **Abre el archivo** `index.html` en tu navegador web
4. ¡Listo! La página está lista para usar.

## 🎨 Paleta de Colores Corporativos

- **Color Primario**: #17A2B8 (Turquesa)
- **Color Primario Oscuro**: #0d7a8f (Turquesa Oscuro)
- **Color Primario Claro**: #d1f2f5 (Turquesa Claro)
- **Color Secundario**: #20B2AA (Agua Marina)
- **Color Oscuro**: #1a1a1a (Gris Oscuro)
- **Color Blanco**: #ffffff (Blanco)

## 🛠️ Personalización

### Cambiar Textos
Edita `index.html` para actualizar:
- Nombres de secciones
- Descripciones de servicios
- Información de contacto
- Cualquier otro contenido

### Cambiar Colores
Edita las variables CSS al inicio de `styles.css`:
```css
:root {
    --color-primary: #17A2B8;
    --color-primary-dark: #0d7a8f;
    --color-secondary: #20B2AA;
    /* ... más colores */
}
```

### Agregar Nuevas Secciones
1. Agrega un nuevo `<section>` en `index.html`
2. Crea los estilos correspondientes en `styles.css`
3. Añade el enlace de navegación en la barra de menú

## 📱 Responsive Design

La página se adapta automáticamente a:
- **Dispositivos móviles**: < 576px
- **Tablets**: 768px - 1024px
- **Desktops**: > 1024px

## 💡 Eslogan Corporativo

*"Construimos confianza, innovamos hogares, impulsamos progreso"*

Este eslogan se muestra en el header y en el footer de la página.

## 📦 Dependencias

- **Bootstrap 5.3.0**: Framework CSS (vía CDN)
- **Font Awesome 6.4.0**: Iconos (vía CDN)
- No requiere instalación local de paquetes

## 🚀 Deploy

Para publicar esta página en línea:

1. **GitHub Pages**: Sube la carpeta a un repositorio GitHub
2. **Hosting Web**: Copia los archivos a tu servidor web
3. **Servicios Gratuitos**: Usa Netlify, Vercel o similar

## 📝 Notas

- La página es completamente estática (HTML + CSS)
- No requiere servidor backend
- Los enlaces de navegación funcionan con scroll suave
- El formulario de contacto es un skeleton (requiere backend para funcionar completamente)

## 👨‍💻 Autor

Desarrollado para LANS EDIFICACIONES Y SERVICIOS ®

---

**Última actualización**: Abril 2026