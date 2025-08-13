# Ana Ortuño Estética - Landing Page

Landing page profesional para el negocio de estética de Ana Ortuño.

## 🎨 Estructura del Proyecto

```
anaortunoestetica/
├── assets/
│   ├── icons/
│   ├── images/
│   └── logo/
├── css/
│   └── styles.css          # CSS compilado
├── scss/
│   └── main.scss          # Archivo principal de SASS
├── index.html
├── package.json
└── README.md
```

## 🚀 Instalación y Uso

### Prerrequisitos
- Node.js y npm instalados
- SASS CLI (se instala automáticamente con npm)

### Instalación
```bash
# Instalar dependencias
npm install

# O instalar SASS globalmente
npm install -g sass
```

### Desarrollo
```bash
# Compilar SASS una vez
npm run sass

# Compilar SASS en modo watch (automático)
npm run sass:watch

# Compilar para producción (minificado)
npm run build
```

## 🎯 Características

- **Diseño Responsivo**: Adaptado para móviles, tablets y desktop
- **SASS/SCSS**: Estilos organizados con variables, mixins y anidación
- **Optimizado**: CSS minificado para producción
- **Moderno**: Utiliza las mejores prácticas de CSS

## 🎨 Variables SASS

El proyecto utiliza variables SASS para mantener consistencia:

```scss
// Colores principales
$primary-color: #B18522;
$primary-dark: #8B6A1B;
$secondary-color: #FFEBB0;
$accent-color: #FFF9E6;

// Tipografías
$font-primary: "Nunito", "Poppins", sans-serif;
$font-heading: "Poppins", sans-serif;
```

## 📱 Responsive Design

El sitio está optimizado para:
- **Móviles**: < 768px
- **Tablets**: 768px - 1024px  
- **Desktop**: > 1024px

## 🔧 Comandos Útiles

```bash
# Ver versión de SASS
sass --version

# Compilar con source maps
sass scss/main.scss css/styles.css --source-map

# Compilar con estilo expandido (para debugging)
sass scss/main.scss css/styles.css --style expanded
```

## 📄 Licencia

MIT License - Victoria Ortuño
