# 🪙 Coin — Tu presupuesto mensual y anual

Coin es una app web **sencilla y gratuita** para llevar el control de tu presupuesto: registra lo que ganas, lo que gastas por categorías, y mira gráficas, tablas y un **análisis anual con ideas para optimizar tu dinero**.

> **No necesitas instalar nada ni saber programar.** Se abre en cualquier navegador (computador o celular). Tus datos se guardan **solo en tu equipo** — nada se sube a internet.

**Creada con [Claude Code](https://claude.com/claude-code)** como proyecto de la certificación de Platzi.

---

## ✨ Qué hace

- 💵 **Ingresos y gastos por mes**, totalmente editables (agrega, edita y borra).
- 🗂️ **Categorías de ejemplo ya listas** (Arriendo, Mercado, Transporte, Ocio, Viajes…) que puedes cambiar a tu gusto.
- 🎯 **Objetivos por porcentaje** (regla tipo 50/30/20 personalizable): defines cuánto quieres para ahorro, gastos fijos, variables y viajes.
- 📊 **Gráficas** de ingresos vs gastos, distribución del gasto, evolución del ahorro y "real vs objetivo".
- 📈 **Análisis anual** con resumen (mes más caro, categoría donde más gastas, tasa de ahorro) e **ideas automáticas de optimización**.
- 🌙 **Modo claro/oscuro**, moneda configurable (COP $, USD $, EUR €) y **respaldo Exportar/Importar** (JSON).

---

## 🚀 Cómo usarla

### Opción A — Abrir directamente (lo más fácil)
1. Descarga este proyecto (botón verde **Code → Download ZIP**) y descomprímelo.
2. Haz doble clic en **`index.html`**. ¡Listo, se abre en tu navegador!

### Opción B — Publicarla gratis en internet (GitHub Pages)
Así obtienes un **link** que puedes compartir con quien quieras.
1. Sube esta carpeta a un repositorio de GitHub.
2. En el repo ve a **Settings → Pages**.
3. En *Source* elige la rama **`main`** y la carpeta **`/root`**, y guarda.
4. En 1–2 minutos tu app estará en:
   `https://TU-USUARIO.github.io/coin/`

---

## 🧠 ¿Cómo se usa el análisis?

1. Entra a la pestaña **🎯 Objetivos** y define tus porcentajes (que sumen 100%).
2. En **🗓️ Mes**, registra tus ingresos y gastos de cada mes.
3. Mira la pestaña **📊 Resumen** para las gráficas.
4. Al final revisa **📈 Análisis anual**: te dice dónde te estás pasando y cuánto recortar para llegar a tu meta de ahorro.

> ¿Quieres probar rápido? En **📈 Análisis anual** hay un botón **✨ Cargar datos de ejemplo**.

---

## 🔒 Privacidad

Coin **no tiene servidor**. Toda tu información vive en el almacenamiento local (`localStorage`) de tu navegador. Si quieres respaldar o pasar tus datos a otro equipo, usa **⬇︎ Exportar** / **⬆︎ Importar**.

---

## 🛠️ Tecnología

- Un solo archivo `index.html` (HTML + CSS + JavaScript puro).
- **Sin librerías ni dependencias** — las gráficas están hechas con SVG. Funciona incluso sin internet.

## 📄 Licencia

MIT — libre para usar, modificar y compartir. Ver [LICENSE](LICENSE).
