# Residencial Cantinho da Costeira - Sitio Web

Sitio web del Residencial Cantinho da Costeira, ubicado en Zimbros, Bombinhas - SC, Brasil. Página web estática con soporte bilingüe (portugués/español) para mostrar información sobre los apartamentos, servicios, ubicación y contacto.

## 📋 Descripción

El Residencial Cantinho da Costeira es un complejo de apartamentos para alquiler temporario ubicado a 100m de la playa de Zimbros en Bombinhas, Santa Catarina. El sitio web presenta información sobre los 4 apartamentos disponibles, servicios, galería de fotos y opciones de contacto.

## 🌐 Características

- **Bilingüe**: Soporte completo para portugués y español
- **Responsive**: Diseño adaptativo para móviles, tablets y desktop
- **SEO Optimizado**: Meta tags, structured data (Schema.org) y Open Graph
- **Accesible**: Implementa buenas prácticas de accesibilidad web
- **Performance**: Optimizado para carga rápida con preload de recursos críticos

## 📁 Estructura del Proyecto

```
residencial-cantinho/
├── index.html              # Página principal (HTML completo con CSS y JS inline)
├── maintenance.html         # Página de mantenimiento
├── README.md               # Este archivo
└── resources/
    ├── css/                # Estilos CSS (si los hay)
    ├── js/                 # Scripts JavaScript (si los hay)
    └── img/                # Imágenes del sitio
        ├── aptos/          # Fotos de apartamentos
        │   ├── amarillo/   # Apartamento Amarillo (Praia do Cardoso)
        │   ├── marron/     # Apartamento Marrón (Praia da Lagoa)
        │   ├── rojo/       # Apartamento Rojo (Praia Vermelha)
        │   ├── verde/      # Apartamento Verde (Praia de Zimbros)
        │   ├── banio.jpeg  # Foto común de baño
        │   ├── pieza.jpeg  # Foto común de habitación
        │   └── exterior/   # Fotos de áreas exteriores
        ├── fachada-*.jpg   # Fotos de fachada
        ├── praia-*.jpg     # Fotos hero de la playa
        ├── logo-main-*.png # Variantes del logo
        └── favicon.*       # Favicons
```

## 🏠 Apartamentos

El residencial cuenta con 4 apartamentos:

1. **Apto. Praia de Zimbros** (Verde) - Primer piso
2. **Apto. Praia Vermelha** (Rojo) - Planta baja
3. **Apto. Praia do Cardoso** (Amarillo) - Planta baja
4. **Apto. Praia da Lagoa** (Marrón) - Primer piso

Cada apartamento tiene capacidad para hasta 5 personas y cuenta con:
- 1 dormitorio con cama matrimonial y cama individual
- Aire acondicionado
- Cocina equipada integrada a la sala
- Sala de estar con sofá-cama y sofás adicionales
- 1 baño
- TV Smart
- Wi-Fi
- Churrasqueira individual
- 1 plaza de estacionamiento

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **CSS3**: Estilos (Tailwind CSS vía CDN)
- **JavaScript**: Funcionalidad interactiva (vanilla JS)
- **Schema.org**: Datos estructurados para SEO
- **Open Graph**: Metadatos para redes sociales

## 🚀 Despliegue

El sitio es completamente estático y puede ser desplegado en cualquier servicio de hosting estático:

- **Netlify**: Arrastra y suelta la carpeta
- **Vercel**: Conecta el repositorio
- **GitHub Pages**: Activa Pages en el repositorio
- **Amazon S3 + CloudFront**: Para mayor control
- **Cualquier servidor web**: Apache, Nginx, etc.

### Requisitos

- Servidor web estático (no requiere backend)
- Soporte para archivos estáticos (HTML, CSS, JS, imágenes)

## 📝 Mantenimiento

### Actualizar Información de Contacto

Edita directamente en `index.html`:
- Teléfono: Busca `+5547974003344`
- Email: Busca `cantinhodacosteira@gmail.com`
- WhatsApp: Busca `5547974003344`
- Instagram: Busca `cantinhodacosteira`

### Agregar/Actualizar Fotos

1. **Fotos de apartamentos**: Agrega imágenes en `resources/img/aptos/{color}/`
2. **Fotos de fachada**: Reemplaza `fachada-1.jpg` y `fachada-2.jpg`
3. **Fotos hero**: Reemplaza `praia-1.jpg` y `praia-2.jpg`
4. **Fotos exteriores**: Agrega en `resources/img/aptos/exterior/`

### Actualizar Textos

Los textos están directamente en el HTML. Busca las secciones correspondientes:
- Hero: Busca `hero.title`, `hero.subtitle`
- Apartamentos: Busca `apartments.title`
- Servicios: Busca `services.title`
- Ubicación: Busca `location.title`

### Cambiar Idioma

El sitio detecta automáticamente el idioma preferido del usuario y permite cambiarlo mediante un selector. Los textos están duplicados en el HTML con atributos `data-i18n`.

## 🎨 Personalización

### Colores

Los colores principales se definen en las variables CSS dentro de `index.html`. Busca `:root` para modificar:
- Color primario
- Colores de hover
- Colores de texto

### Estilos

Los estilos están inline en `index.html` dentro de la etiqueta `<style>`. Puedes modificar:
- Espaciados
- Tipografías
- Tamaños de componentes
- Animaciones

## 📱 Funcionalidades

- **Selector de idioma**: Cambio entre portugués y español
- **Navegación suave**: Scroll suave entre secciones
- **Galería de imágenes**: Lightbox para visualizar fotos
- **Formulario de contacto**: Formulario de consulta (conectado a Formspree)
- **Mapa interactivo**: Google Maps embebido
- **Enlaces de WhatsApp**: Enlaces directos con mensaje predefinido

## 🔍 SEO

El sitio incluye:
- Meta tags optimizados
- Structured Data (Schema.org) para LodgingBusiness
- Open Graph para redes sociales
- Twitter Cards
- Canonical URLs
- Hreflang para idiomas alternativos
- Meta tags geográficos

## 📞 Información de Contacto

- **Teléfono**: +55 47 97400-3344
- **Email**: cantinhodacosteira@gmail.com
- **WhatsApp**: +55 47 97400-3344
- **Instagram**: [@cantinhodacosteira](https://www.instagram.com/cantinhodacosteira)
- **Ubicación**: Zimbros, Bombinhas - SC, Brasil
- **Sitio web**: https://cantinhodacosteira.com

## 📍 Ubicación

- **Dirección**: Zimbros, Bombinhas - SC
- **Distancia a la playa**: 100m
- **Coordenadas**: -27.1383, -48.5075
- **Google Maps**: [Ver en Google Maps](https://maps.app.goo.gl/HjdH4ZtXETNSEvXP9)

## ✅ Checklist de Mantenimiento

Antes de publicar actualizaciones:

- [ ] Verificar que todas las imágenes se carguen correctamente
- [ ] Probar el cambio de idioma en ambos sentidos
- [ ] Verificar que los enlaces de WhatsApp funcionen
- [ ] Probar el formulario de contacto
- [ ] Verificar la responsividad en móvil y desktop
- [ ] Revisar que el mapa de Google Maps se muestre correctamente
- [ ] Verificar que los meta tags sean correctos
- [ ] Probar en diferentes navegadores (Chrome, Firefox, Safari, Edge)

## 🐛 Solución de Problemas

### Las imágenes no se cargan

- Verifica que las rutas en el HTML coincidan con la estructura de carpetas
- Asegúrate de que los nombres de archivo sean exactos (mayúsculas/minúsculas)
- Revisa la consola del navegador para ver errores 404

### El cambio de idioma no funciona

- Verifica que el JavaScript esté cargado correctamente
- Revisa la consola del navegador para errores
- Asegúrate de que los atributos `data-i18n` estén correctos

### El formulario no envía

- Verifica que la URL de Formspree en el atributo `action` sea correcta
- Revisa la consola del navegador para errores
- Verifica que todos los campos requeridos estén completos

## 📄 Licencia

Este proyecto es propiedad del Residencial Cantinho da Costeira.

## 🔄 Versión

- **Versión actual**: 1.0
- **Última actualización**: 2026

---

**Desarrollado para Residencial Cantinho da Costeira** 🏖️
