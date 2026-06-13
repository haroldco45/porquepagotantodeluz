# ⚡ ¿Por qué pago tanto de luz? — Calculadora CU Colombia

PWA educativa que calcula y explica la tarifa de energía eléctrica en Colombia usando la fórmula oficial del Costo Unitario (CU) regulada por la CREG.

## 🚀 Funcionalidades

- Calculadora CU con consumo en kWh, estrato y operador de red
- Desglose visual de los 6 componentes (G + T + D + Cv + PR + R)
- Explicador interactivo con lenguaje sencillo ("chichimbiano")
- Compartir resultado por WhatsApp o copiar al portapapeles
- PWA instalable, funciona offline
- Diseño tipo tablero eléctrico industrial

## 📁 Archivos

| Archivo | Descripción |
|---|---|
| `index.html` | App completa (single-file) |
| `manifest.json` | Manifest PWA |
| `sw.js` | Service Worker para offline |
| `README.md` | Este archivo |

## 🏗️ Despliegue

### GitHub Pages
1. Crear repo `tarifa-luz-colombia`
2. Subir los 4 archivos
3. Activar Pages → rama `main` → carpeta raíz

### Netlify
1. Arrastrar carpeta a Netlify Drop
2. Listo ✅

## 📊 Fórmula CU — CREG

```
CU(n,m) = G(m) + T(m) + D(n,m) + Cv(m) + PR(n,m) + R(m)
```

| Componente | % aprox | Descripción |
|---|---|---|
| G — Generación | 30% | Costo de producir la energía |
| T — Transmisión | 7% | Líneas de alta tensión nacionales |
| D — Distribución | 40% | Red local (postes y cables del barrio) |
| Cv — Comercialización | 13% | Administración y facturación del operador |
| PR — Pérdidas | 7% | Energía robada o pérdidas técnicas |
| R — Restricciones | 3% | Cuellos de botella del sistema |

## ⚠️ Aviso legal

Los valores son estimados referenciales para fines educativos. Verificar con el operador de red correspondiente. Basado en CREG Resolución 119/2007 y concordantes.

## 🏢 Créditos

**Desarrollada por Vibras Positivas HM — Derechos de Autor Reservados**  
vibraspositivashm.com · Caucasia, Antioquia · 2026
