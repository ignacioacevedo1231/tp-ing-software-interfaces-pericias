# 📋 Sistema de Gestión y Seguimiento de Pericias — Diseño de Interfaces

**Trabajo Práctico Anual — Ingeniería de Software I**  
Universidad Autónoma de Entre Ríos — Facultad de Ciencia y Tecnología  
Año 2026

Este repositorio contiene las maquetas HTML/CSS correspondientes al **punto 6 (Diseño de interfaces)** del TP anual sobre el sistema de gestión y seguimiento de pericias judiciales para la empresa *JustiData Solutions S.A.*

## 📁 Estructura del repositorio

```
interfaces-pericias/
├── index.html                  # Dashboard / Panel de control (prototipo opcional)
├── carga-informe.html          # ✅ Formulario de carga de un nuevo informe pericial
├── busqueda-informes.html      # ✅ Pantalla de búsqueda de informes
├── informe-pantalla.html       # ✅ Informe por pantalla (detalle de pericia)
├── css/
│   └── style.css               # Hoja de estilos compartida
└── README.md
```

## 🖥️ Interfaces implementadas

| Pantalla | Archivo | Descripción |
|----------|---------|-------------|
| Carga de informe | `carga-informe.html` | Registro de nuevo movimiento pericial (Informe Pericial o Ampliación). Incluye identificación (Organismo + Nro. de Pericia), tipo de pericia, área técnica, personas involucradas (peritos con rol y especialidad, evaluados, testigos), estado de la pericia y usuario que carga. |
| Búsqueda de informes | `busqueda-informes.html` | Buscador con filtros por número de pericia, organismo, expediente, tipo, estado, fechas y persona involucrada. Listado de resultados con acceso al detalle. |
| Informe por pantalla | `informe-pantalla.html` | Vista detallada de una pericia: datos generales, estado, personas involucradas con roles, línea de tiempo de movimientos, historial de cambios de estado y módulo de honorarios/pagos. |
| Panel de control | `index.html` | Dashboard opcional con resumen de pericias activas, pagos en mora y accesos rápidos (prototipo completo). |

## 🚀 Cómo ver las interfaces

1. Descarga o clona este repositorio.
2. Abre cualquiera de los archivos `.html` en tu navegador (Chrome, Edge, Firefox).
3. Para imprimir el informe (útil para el PDF del TP), usa `Ctrl + P` → Guardar como PDF. Las interfaces incluyen estilos optimizados para impresión.

## 🎓 Contexto académico

- **Materia:** Ingeniería de Software I  
- **Docentes:** Lic. Pamela Bonadeo, Lic. Damián Cian, Lic. Paolo Orundés Cardinali  
- **Trabajo:** TP Anual — Sistema de Gestión y Seguimiento de Pericias  
- **Enfoque:** Análisis y Diseño Estructurado  
- **Punto entregado:** 6. Diseño de interfaces  

---

*JustiData Solutions S.A. — Sistema de Gestión y Seguimiento de Pericias Judiciales*
