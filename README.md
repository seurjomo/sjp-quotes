# SJP Quote Generator — PWA

Progressive Web App para iPhone y Android. Se instala desde Safari y funciona offline.

## Archivos
```
SJP-QuoteApp/
├── index.html      ← App principal
├── manifest.json   ← Config PWA
├── sw.js           ← Service Worker (offline)
└── README.md
```

## Cómo instalar en iPhone (sin App Store)

### Opción A — GitHub Pages (gratis, recomendado)

1. Crea cuenta en github.com
2. New repository → nombre: `sjp-quotes` → Public
3. Upload files: sube `index.html`, `manifest.json`, `sw.js`
4. Settings → Pages → Source: `main` branch → Save
5. URL de tu app: `https://TU_USUARIO.github.io/sjp-quotes`

6. **En iPhone:** abre esa URL en Safari
7. Toca el botón de compartir (cuadro con flecha ↑)
8. "Añadir a pantalla de inicio"
9. ¡Listo! Aparece como app en tu pantalla.

### Opción B — Netlify (drag & drop, aún más fácil)

1. Ve a netlify.com → Log in
2. Arrastra la carpeta `SJP-QuoteApp` al área de deploy
3. Te da una URL en segundos
4. Repite el paso 6-9 de arriba

---

## Funcionalidades

- ✅ Genera PDF igual que la versión original
- ✅ Guarda clientes automáticamente
- ✅ Historial de las últimas 50 cotizaciones
- ✅ Funciona offline (después del primer uso)
- ✅ Diseño responsivo para iPhone
- ✅ Auto-numeración de cotizaciones
- ✅ Preview en tiempo real del total
- ✅ MXN/USD/CAD con IVA automático para MXN
- ✅ Recarga cotizaciones del historial para re-generar

## Notas

- Los datos se guardan en el dispositivo (localStorage)
- El PDF se descarga directamente
- Compatible con iPhone iOS 11.3+ (Safari)
