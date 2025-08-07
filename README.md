# 📊 Power BI – Dashboard de Inteligencia Comercial

Este proyecto consiste en el desarrollo de un **dashboard interactivo en Power BI** para una empresa multinacional tecnológica ficticia, con datos detallados de ventas correspondientes a los años 2007, 2008 y 2009. Aunque los datos provienen de una base simulada, su estructura y comportamiento reproducen con alta fidelidad **escenarios reales en entornos de análisis comercial y toma de decisiones estratégicas**.

El objetivo fue construir una solución robusta, visualmente clara y altamente interactiva que permita analizar ingresos, utilidad, descuentos, devoluciones y el comportamiento del cliente con granularidad y enfoque analítico.

---

## ✅ Descripción del proyecto

El reporte incluye múltiples páginas y un alto nivel de interactividad mediante **slicers, bookmarks, filtros cruzados, simuladores, predicciones y tooltips personalizados**. Algunos de los principales elementos implementados:

- **Comparativa de ingresos con y sin descuento**, y diferencias en precios por producto.
- **Rankings jerárquicos**:
  - Ranking general de tiendas.
  - Ranking por continente (filtrado dinámicamente).
  - Ranking de subcategorías por categoría.
  - Ranking de productos por subcategoría.
- **Selector de métrica clave (ingresos, utilidad, costos)** que alimenta simultáneamente:
  - Gráfico de columnas (mes vs. métrica seleccionada).
  - Barras por continente.
  - Treemap por subcategoría.
  - Diagrama de pastel por categoría.
- **Simulador de ajuste de precios**:
  - Selector horizontal que permite modificar el precio unitario en pasos de ±0.1%.
  - Tabla comparativa de resultados e impacto directo sobre ingresos y utilidad.
  - Gráfico de líneas con utilidad original vs ajustada.
- **Forecasting** (proyecciones de tendencia) para ingresos y utilidad ajustada.
- **Análisis de desempeño comparativo Año Actual vs Año Anterior (LY)**:
  - Gráficos con formato condicional (verde si mejora, rojo si no).
  - Visualización por mes, país y subcategoría.
- **Análisis semanal**: tabla cruzada por país y día de la semana, con slicers de año y semana.

🔍 Además:
- Tooltips enriquecidos y personalizados.
- Medidas DAX optimizadas para eficiencia y lógica contextual.
- Navegación intuitiva entre páginas mediante botones.

---

## 🧠 Habilidades técnicas aplicadas

- Power BI Desktop (modelado, diseño y navegación)
- Lenguaje DAX (ranking, lógica condicional, cálculos acumulados y comparación temporal)
- Forecasting y simulaciones financieras
- Diseño UX/UI aplicado a dashboards
- Visualizaciones avanzadas y personalización visual
- Optimización de performance
- Documentación y estructura del flujo analítico

---

## 🗃️ Datos utilizados

El dataset proviene de la base de datos educativa **ContosoSales**, atribuida a "juanpablo jofre". Aunque es un entorno simulado, está diseñado para representar con fidelidad **operaciones comerciales reales** de una empresa del sector retail tecnológico a **nivel global**.  
Se incluye información de ventas por producto, subcategoría, tienda, continente y periodo, permitiendo análisis completos de rentabilidad, estacionalidad y estrategia de precios.

---

## 📁 Archivos incluidos

- `Link Proyecto-y-Database`: Bloc de Notas con un link de Google Drive donde se encuentra la base de datos y el archivo Power BI.
- `Screenshots-DASHBOARD`: Esta carpeta contiene capturas de pantalla del dashboard desarrollado en Power BI como parte del proyecto de análisis de ventas y clientes.
- `README.md`: este archivo descriptivo del proyecto.

> 🎯 *Nota: por limitaciones de tamaño en GitHub, el archivo de base de datos está disponible vía enlace externo (Drive).*


