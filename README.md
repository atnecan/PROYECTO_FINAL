# 📊 Proyecto Final – Análisis de Ventas (Rossmann) con Power BI

> Dashboard operativo y análisis exploratorio de ventas, ticket medio y efecto de promociones para diferentes tipos de tienda.

---

## 🧭 Objetivo

Construir un dashboard en Power BI que permita:

- Entender la evolución mensual de ventas.
- Comparar Ventas Totales y Ticket Promedio por Tipo de Tienda.
- Medir el impacto de las promociones (uplift) y dónde aportan o destruyen valor.
- Proveer un informe reproducible con datos crudos, transformados y conclusiones claras.

---

## 📁 Estructura del repositorio

```bash
PROYECTO_FINAL/
├── 📁 DATOS/
│   └── rossmann_final.csv
├── 📁 DASHBOARD/
│   ├── ProyectoFinal.pbix
│   ├── Informe_final.pdf
│   └── 📁 capturas/
├── ProyectoFinal.ipynb
├── limpieza_de_datos.py
├── carga_de_datos.py
├── fusión_de_datos.py
├── eda.py
├── principal.py
├── Proyecto Final.docx
└── LÉAME.md


---

## 🧰 Requisitos y herramientas

- Power BI Desktop (versión actualizada)
- CSVs: rossmann_final.csv, store.csv, tienda.csv
- GitHub para control de versiones

---

## 🚀 Cómo abrir y usar el dashboard

1. Clona o descarga este repositorio.
2. Verifica que los datos CSV estén en la carpeta `data/`.
3. Abre `proyecto_final_rossmann.pbix` en Power BI Desktop.
4. Si es necesario, actualiza las rutas en Power Query.
5. Refresca los datos y explora el dashboard.

---

## 📈 Contenido del dashboard

**Página 1 – Resumen general**
- KPIs principales
- Evolución mensual de ventas

**Página 2 – Análisis por tienda**
- Top 10 tiendas
- Ventas y ticket medio por tipo de tienda

**Página 3 – Efecto de la Promoción**
- Comparativa de ventas con/sin promoción
- Ventas + ticket medio por tipo de tienda
- Uplift promocional (%)

---

## 🔎 Hallazgos clave

- Hipermercados concentran el mayor volumen de ventas.
- Tiendas especializadas tienen el ticket medio más alto.
- Las promociones incrementan el ticket medio en todos los tipos de tienda excepto en supermercados pequeños, donde el efecto es negativo (-39%).

---

## 🧪 Metodología

- Unión y limpieza de datos en Power Query
- Medidas en DAX para cálculo de KPIs y segmentaciones
- Visualizaciones claras, limpias y orientadas a toma de decisiones

---

## 📦 Datos

- `rossmann_final.csv`: dataset principal integrado
- `store.csv`, `tienda.csv`: datos auxiliares
- Todos los datos están incluidos para reproducibilidad

---

## 📄 Informe

Incluido en `/docs/Informe_proyecto_final.docx`, se detalla:

- Preparación de datos
- Lógica de medidas
- Decisiones de diseño
- Conclusiones de negocio

---

## 🔧 Próximos pasos

- Añadir mapa geográfico si se dispone de coordenadas o ciudades
- Publicar el dashboard en Power BI Service
- Realizar pruebas adicionales sobre campañas promocionales

---

## 👤 Autor

- **Marc (atnecan)**
- Proyecto final – Máster en Data Analytics & IA Developer – ThePower Business School

---

## 📝 Licencia

Proyecto con fines educativos.
