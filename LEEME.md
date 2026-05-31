# CDI – App de Listas de Chequeo (PWA)
## Centro de Diagnóstico Automotriz de Pasto

---

## ¿Qué es esta app?

Es una **Progressive Web App (PWA)**: funciona en el navegador pero se instala
en el celular como si fuera una app nativa — sin Play Store ni App Store.

Funciona **100% sin internet** una vez instalada.

---

## Archivos incluidos

```
CDI_PWA/
├── index.html          ← La app completa
├── manifest.json       ← Configuración PWA (nombre, icono, colores)
├── sw.js               ← Service Worker (modo offline)
├── icons/              ← Iconos para Android e iPhone
│   ├── icon-192x192.png
│   ├── icon-512x512.png
│   ├── apple-touch-icon.png
│   └── ... (más tamaños)
└── LEEME.md            ← Este archivo
```

---

## PASO 1 – Publicar la app en internet (GRATIS)

La app necesita estar en un servidor web para poder instalarse.
La opción más fácil y gratuita es **GitHub Pages**:

1. Crea una cuenta gratuita en [github.com](https://github.com)
2. Crea un repositorio nuevo (nombre sugerido: `cdi-chequeo`)
3. Sube todos los archivos de esta carpeta `CDI_PWA/`
4. Ve a **Settings → Pages → Source: main branch → /root**
5. En unos minutos tu app estará en:
   `https://TU_USUARIO.github.io/cdi-chequeo/`

---

## PASO 2 – Instalar en Android

1. Abre Chrome en el celular
2. Ve a la URL de tu app (del paso anterior)
3. Chrome mostrará un banner **"Añadir a pantalla de inicio"** — toca **Instalar**
4. Si no aparece el banner: toca los **3 puntos** del menú → "Añadir a pantalla de inicio"
5. ¡Listo! Aparece como app con el logo de CDI

---

## PASO 3 – Instalar en iPhone

1. Abre **Safari** (debe ser Safari, no Chrome)
2. Ve a la URL de tu app
3. Toca el botón de **compartir** (cuadrado con flecha hacia arriba)
4. Toca **"Añadir a pantalla de inicio"**
5. ¡Listo!

---

## PASO 4 – Conectar con Google Drive (opcional)

Para que los Excel se guarden automáticamente en Drive:

1. Ve a [script.google.com](https://script.google.com)
2. Nuevo proyecto → pega el código de `apps_script_drive.js`
3. Reemplaza `ID_DE_LA_CARPETA` con el ID de tu carpeta de Drive
4. **Implementar → Nueva implementación → Aplicación web**
   - Ejecutar como: Yo
   - Acceso: Cualquier usuario
5. Copia la URL generada
6. Pégala en el campo **"URL Google Drive"** dentro de cualquier formulario de la app
   (la app la recuerda para la próxima vez)

---

## Funcionalidades

- ✅ 7 equipos con sus listas de chequeo completas
- ✅ Checkboxes B (Bueno) y M (Malo) por cada día de la semana
- ✅ Exporta Excel con formato idéntico a la planilla física
- ✅ Historial de registros guardado localmente
- ✅ Funciona sin internet (offline)
- ✅ Se instala como app en Android e iPhone
- ✅ Conexión opcional con Google Drive
- ✅ Compatible con impresión

---

## Soporte

Si necesita ayuda con la configuración, puede volver a solicitar asistencia
indicando en qué paso está.
