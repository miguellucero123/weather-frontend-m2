#  Torre del Paine - App_Clima

##  Descripción

Aplicación web interactiva de pronóstico climático para Torres del Paine y ciudades cercanas.

**Versión:** 2.0
**Fecha:** 2025-11-21
**Ciudades:** 10
**Pronóstico:** 7 días

---

##  Características

-  **10 Ciudades** - Cercanas a Torres del Paine
-  **Datos Reales** - API Open-Meteo
-  **Cards Interactivas** - Click para ver detalles
-  **Detalle de Día** - Click en pronóstico para ver detalles
-  **Mapa Interactivo** - Leaflet.js + OpenStreetMap
-  **Marcadores Coloreados** - Por temperatura
-  **Responsivo** - Móvil, tablet, desktop
-  **100% Funcional** - Sin dependencias complejas

---

##  Archivos Generados

```
weather_app_final/
├── index.html              # Aplicación web completa
├── weather_data.json       # Datos en JSON
├── climate_summary.csv     # Resumen en CSV
├── climate_summary.xlsx    # Resumen en Excel
└── README.md               # Este archivo
```

---

##  Requisitos

### Para Ejecutar Python:
- Python 3.7+
- requests
- pandas
- schedule (opcional)

### Para Ver la App:
- Navegador moderno (Chrome v90+, Firefox v88+, Safari v14+, Edge v90+)
- Conexión a internet

---

##  Cómo Usar

1. **Abre** `index.html` en tu navegador
2. **Selecciona** una ciudad en las cards
3. **Ve** el detalle con clima actual
4. **Haz click** en un día para ver detalles específicos
5. **Desplázate** hasta el final para ver el mapa
6. **Interactúa** con el mapa (zoom, drag, click)

---

##  Mapa

- **Proveedor:** OpenStreetMap
- **Librería:** Leaflet.js v1.9.4
- **Características:**
  - 10 marcadores de ciudades
  - Marcador especial para Torres del Paine
  - Colores según temperatura
  - Popups con información
  - Zoom y drag funcionales

### Colores del Mapa:
- 🔵 Azul Oscuro: < 5°C
- 🔵 Azul: 5-10°C
- 🔵 Cian: 10-15°C
- 🟢 Verde: 15-20°C
- 🟠 Naranja: > 20°C

---

##  Datos

- **Fuente:** Open-Meteo API (gratuita)
- **Ciudades:** 10
- **Pronóstico:** 7 días
- **Parámetros:**
  - Temperatura máxima/mínima
  - Humedad relativa
  - Velocidad del viento
  - Dirección del viento
  - Precipitación
  - Código climático WMO

---

##  Ciudades Incluidas

1. Puerto Natales (250 km)
2. Villa O'Higgins (380 km)
3. El Chaltén (220 km)
4. El Calafate (180 km)
5. Punta Arenas (350 km)
6. Río Gallegos (420 km)
7. Los Antiguos (290 km)
8. Perito Moreno (200 km)
9. Gobernador Gregores (330 km)
10. Tres Lagos (310 km)

---

##  Tecnologías

**Frontend:**
- HTML5 Semántico
- CSS3 (Gradientes, Animaciones, Responsive)
- JavaScript Vanilla
- Bootstrap 5 (CDN)
- Font Awesome (CDN)

**Mapas:**
- Leaflet.js v1.9.4
- OpenStreetMap

**Backend (Python):**
- requests - Descargas HTTP
- pandas - Análisis de datos
- json - Serialización de datos
- datetime - Timestamps

---

##  Diseño

- **Responsivo:** Mobile-first
- **Colores:** Azul y cian profesionales
- **Animaciones:** Transiciones suaves
- **Iconografía:** Font Awesome

---

##  Solución de Problemas

### Mapa no aparece
- ✓ Verifica conexión internet
- ✓ Usa navegador actualizado
- ✓ Limpia caché del navegador
- ✓ Abre DevTools (F12) para ver errores

### Datos no cargan
- ✓ Verifica conexión internet
- ✓ Recarga la página (F5)
- ✓ Espera 2-3 segundos

### Día no muestra detalle
- ✓ Asegúrate de hacer click en el día
- ✓ Scrollea para ver el detalle generado
- ✓ Abre DevTools (F12) Console

---

##  Licencia

Proyecto educativo - Módulo 2

---

##  Recursos

- [Open-Meteo API](https://open-meteo.com)
- [Leaflet.js](https://leafletjs.com)
- [Bootstrap](https://getbootstrap.com)
- [Font Awesome](https://fontawesome.com)

---

**Última actualización:** 2025-11-21 11:17:47
**Versión:** 2.0
**Estado:**  Completo y Funcional

## Desarrollado por: Miguel Lucero
