# 🏗️ ERP Industrial Control: Gestión 360° de Ciclo de Vida de Construcción

> **De la Oficina Técnica a la Obra:** Una solución integral diseñada para cerrar la brecha operativa entre la administración financiera (Enkontrol) y la ejecución de ingeniería industrial en campo.

---

## 📋 Resumen del Proyecto

Este ecosistema ERP nace para resolver la desconexión documental y operativa en proyectos de construcción industrial. A diferencia de un sistema contable tradicional, este ERP se enfoca en el **Control de Procesos Críticos**, integrando la metodología BIM, el blindaje fiscal de subcontratistas y la movilidad en sitio.

---

## 🚀 Estado del Desarrollo

### ✅ Módulos Implementados (Demo Funcional)

| Módulo | Archivo | Descripción |
|--------|---------|-------------|
| **Dashboard Principal** | [`index.html`](index.html) | Panel de beneficios con métricas clave, KPIs y visualización de impacto |
| **CDE - Control Documental** | [`Templates/CDE · CONTROL DOCUMENTAL.html`](Templates/CDE%20·%20CONTROL%20DOCUMENTAL.html) | Gestión de planos, validación QR, flujo de aprobaciones y control de versiones |
| **Control de Obras** | [`Templates/Control de Obras.html`](Templates/Control%20de%20Obras.html) | Centro de mando para seguimiento de avance, almacén y QA/QC |
| **Portal de Proveedores** | [`Templates/Portal Provedores.html`](Templates/Portal%20Provedores.html) | Blindaje fiscal, semáforo de cumplimiento y gestión de certificados |

### 🎯 Características Implementadas

#### Dashboard Principal ([`index.html`](index.html))
- Panel de beneficios con métricas de reducción de retrabajos (-25%)
- KPIs de cumplimiento legal (100% expedientes actualizados)
- Análisis de eficiencia en compras (5-8% ahorro)
- Visualización de impacto en cierre de proyectos (-50% tiempo)
- Interfaz responsive con diseño oscuro profesional

#### CDE - Control Documental ([`CDE · CONTROL DOCUMENTAL.html`](Templates/CDE%20·%20CONTROL%20DOCUMENTAL.html))
- **Validación QR de Planos:** Sistema de códigos QR para verificar vigencia de documentos en campo
- **Control de Versiones:** Indicadores visuales de estado (Vigente/Obsoleto/En Revisión)
- **Flujo de Aprobaciones:** Workflow con tiempos de respuesta y alertas
- **Metadatos de Documentos:** Información estructurada por disciplina, área y responsable
- **Visor Integrado:** Previsualización de planos con herramientas de zoom y navegación

#### Control de Obras ([`Control de Obras.html`](Templates/Control%20de%20Obras.html))
- **Centro de Mando:** Dashboard ejecutivo con avance físico y financiero
- **Gestión de Almacén:** Control de entradas/salidas con escaneo de códigos
- **Checklists QA/QC:** Protocolos digitales de inspección por especialidad
- **Reportes de Avance:** Gráficos de tendencia y curvas S
- **Alertas de Desviación:** Notificaciones de retrasos y sobrecostos

#### Portal de Proveedores ([`Portal Provedores.html`](Templates/Portal%20Provedores.html))
- **Semáforo de Cumplimiento:** Validación automática de documentos fiscales
  - Opinión SAT (32 días de vigencia)
  - IMSS (30 días)
  - REPSE (30 días)
  - Infonavit (30 días)
- **Bloqueo Automático:** Restricción de pagos si documentos están vencidos
- **Certificados de Calidad:** Carga obligatoria de Mill Test Reports
- **Cuadros Comparativos:** Análisis de precios ponderados históricos
- **Generación de QR:** Códigos para acceso rápido a expediente del proveedor

---

## 🛠️ Stack Técnico

| Componente | Tecnología |
|------------|------------|
| **Frontend** | HTML5, CSS3, JavaScript Vanilla |
| **Estilos** | CSS Custom Properties, Flexbox, Grid |
| **Fuentes** | Inter (UI), JetBrains Mono (código) |
| **Iconos** | Font Awesome 6.x |
| **Gráficos** | Chart.js 4.4.0 |
| **Códigos QR** | QRCode.js |

### Características Técnicas Destacadas
- **Diseño Responsive:** Adaptable a desktop, tablet y móvil
- **Tema Oscuro Profesional:** Paleta de colores corporativa (#0b1a24, #0f2638)
- **Sin Dependencias Backend:** Demo 100% frontend, ejecutable localmente
- **Componentes Modulares:** Estructura reutilizable basada en cards
- **Accesibilidad:** Etiquetas semánticas y navegación por teclado

---

## 🚀 Cómo Ejecutar

### Opción 1: Abrir directamente en el navegador
Simplemente abre el archivo [`index.html`](index.html) en tu navegador (doble clic o arrastrar el archivo al navegador).

### Opción 2: Servidor HTTP local
Ejecuta este comando en tu terminal:

```bash
cd /workspaces/GProA_ERP_Industrial_Control && python3 -m http.server 8000
```

Luego accede a: `http://localhost:8000`

Ambos métodos funcionan sin necesidad de configuración adicional.

---

## 🗺️ Roadmap de Implementación (12 Semanas)

| Fase | Título | Estado | Entregable Clave |
|------|--------|--------|------------------|
| **01** | **Cimentación de Datos** | 🔵 Planificado | Mapeo de WBS y limpieza de catálogos Enkontrol |
| **02** | **Blindaje Operativo** | 🟡 En Demo | Portal de Proveedores y Control de Planos (QR) |
| **03** | **Control en Campo** | 🟡 En Demo | App de Almacén y Checklists de Calidad (QA/QC) |
| **04** | **Inteligencia de Negocio** | 🔵 Planificado | Integración BIM 5D y Dashboards Directivos |
| **05** | **Go-Live Piloto** | 🔵 Planificado | Implementación en proyecto real e Hypercare |

**Leyenda:** ✅ Completado | 🟡 En Demo | 🔵 Planificado

---

## 📈 Beneficios Esperados

| Beneficio | Métrica | Impacto |
|-----------|---------|---------|
| **Reducción de Retrabajos** | Control de versiones de planos | -25% |
| **Cumplimiento Legal** | Expedientes de subcontratistas | 100% actualizados |
| **Eficiencia en Compras** | Análisis de históricos | 5-8% ahorro |
| **Cierre de Proyecto** | Elaboración Dossier de Calidad | -50% tiempo |

---

## 📁 Estructura del Proyecto

```
GProA_ERP_Industrial_Control/
├── index.html                          # Dashboard principal de demo
├── README.md                           # Documentación del proyecto
├── LICENSE                             # Licencia MIT
├── erp_terminal.txt                    # Instrucciones de ejecución
└── Templates/
    ├── CDE · CONTROL DOCUMENTAL.html   # Módulo de control documental
    ├── Control de Obras.html           # Módulo de control de obra
    └── Portal Provedores.html          # Portal de proveedores
```

---

## 🔮 Próximos Pasos

1. **Integración con Backend:** Desarrollar API REST para persistencia de datos
2. **Base de Datos:** Implementar PostgreSQL/SQL Server para almacenamiento
3. **Autenticación:** Sistema de login con roles y permisos
4. **Integración Enkontrol:** Conexión con API de Enkontrol para datos maestros
5. **App Móvil:** Desarrollo de aplicación nativa para uso en campo
6. **Visor BIM:** Integración con Autodesk Forge para modelos Revit

---

## 🤝 Soporte y Contacto

Para dudas sobre la implementación o acceso al ambiente de demo:

*Este proyecto es desarrollado por **GProA Technology S. de R.L. de C.V.** y está diseñado exclusivamente para el sector de Construcción Industrial.*

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [`LICENSE`](LICENSE) para más detalles.
