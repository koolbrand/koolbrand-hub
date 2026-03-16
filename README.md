# Te Alquilo en Miami - Landing Page

Landing page profesional para alquiler de propiedades en Miami, orientada al mercado colombiano.

## Estructura

```
te-alquilo-en-miami/
├── index.html      # Landing page principal
└── README.md       # Este archivo
```

## Características

- ✅ Diseño premium-cálido (estilo Miami)
- ✅ Totalmente responsive (móvil, tablet, desktop)
- ✅ Video en hero section
- ✅ Filtros de propiedades por zona
- ✅ Modal de detalles de propiedades
- ✅ FAQ con acordeón
- ✅ Formulario de contacto
- ✅ Botón flotante de WhatsApp
- ✅ Animaciones suaves
- ✅ Sin dependencias externas (HTML/CSS/JS puro)

## Personalización

### Cambiar número de WhatsApp
Busca en el código: `https://wa.me/1234567890` y reemplázalo con tu número real (sin el +).

### Videos e imágenes
El video del hero está configurado para buscar en:
```
../mnt/clientes/Te Alquilo en Miami/Web/Video/Te akquilo miami - Video Web.mp4
```

Para producción, mueve el video a la carpeta del proyecto y actualiza la ruta en el HTML.

### Colores
Los colores principales están en las CSS variables al inicio del archivo:
- `--color-primary`: #1B4D3E (verde Miami)
- Modifica para ajustar a tu marca

## Despliegue

Simplemente sube los archivos a cualquier hosting:

1. **FTP/SFTP**: Sube `index.html` a la raíz
2. **Netlify/Vercel**: Arrastra y suelta el archivo
3. **GitHub Pages**: Haz push y activa Pages

## SEO

El HTML incluye:
- Meta description
- Title optimizado
- Estructura semántica
- Imágenes con alt text

## Compatibilidad

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers

---
ℹ️ Nota: El video requiere una ruta válida para funcionar. En desarrollo local, asegúrate de que la ruta al video sea correcta.