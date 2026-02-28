# 🏗️ ACTA DE INSPECCIÓN TÉCNICA ESTRUCTURAL

### Auditoría INVIAS 2022 – NSR-10 – PAGA

**Mejoramiento Vía Granada – Guatapé (La Sonadora – La Peña)**

![Image](https://www.huila.gov.co/info/huila_bco/media/pubInt/thumbs/thpubInt_700X400_14189.webp)

![Image](https://ciprecon.com/assets/images/box-n-2.webp)

![Image](https://revistas.ufps.edu.co/index.php/ingenio/article/download/4586/5906/44771)

![Image](https://imgv2-1-f.scribdassets.com/img/document/356990396/original/ffcff0d507/1?v=1)

Aplicación web profesional desarrollada en **HTML + CSS + JavaScript puro** para la generación de:

> **Actas de Inspección Técnica Estructural**
> Control de Interventoría conforme a especificaciones **INVIAS 2022**, **NSR-10** y lineamientos ambientales **PAGA**

Optimizada para:

* 📱 Trabajo en campo (celular/tablet)
* 💻 Escritorio técnico
* 🖨 Generación de PDF institucional listo para radicación

---

# 🚀 Características Principales

* 📋 Evaluación estructurada por códigos INVIAS
* 🚦 Sistema semáforo (Cumple / No cumple / N/A)
* 📸 Galería multifoto por cada ítem
* 🏷 Carga dinámica de logos institucionales
* 📅 Fecha automática ajustada a `datetime-local`
* 📱 Diseño totalmente responsive
* 🖨 Encabezado repetitivo en impresión (formato profesional)
* ⚠️ Cláusulas técnicas de rechazo integradas
* 🔒 Funciona completamente offline

---

# 📂 Estructura del Proyecto

```bash
📁 auditoria-estructural-pro/
 └── 📄 index.html
```

Contiene en un único archivo:

* Maquetación completa
* Estilos pantalla + impresión
* Adaptación móvil avanzada
* Lógica JavaScript integrada
* Sistema de impresión con membrete repetitivo

No requiere:

* Backend
* Base de datos
* Frameworks
* Librerías externas

---

# 📋 Módulos de Auditoría Incluidos

---

## 1️⃣ Topografía, Movimiento de Tierras y Subrasante

Códigos evaluados:

* **INV-210** – Replanteo y Perfiles

  * Tolerancia altimétrica ±3 cm
  * Tolerancia planimétrica ±5 cm

* **INV-610** – Compactación y CBR

  * ≥ 95% Proctor Modificado
  * 1 ensayo cada 100 m
  * CBR > 3%

---

## 2️⃣ Estructura de Pavimento (Subbase y Placa Huella)

* **INV-320** – Subbase Granular

  * Espesor diseño 15 cm
  * Rasante +0 / -15 mm
  * Desgaste L.A. < 50%

* **CAP-8.14** – Concreto Placa Huella y Ciclópeo

  * Clase D (21 MPa)
  * Espesor 15 cm
  * Máx 40% rajón en ciclópeo

---

## 3️⃣ Obras de Arte y Estructuras (Box Culvert)

* **INV-640** – Acero de Refuerzo

  * Recubrimientos según NSR-10
  * Traslapos según despiece
  * Separación mínima normativa

* **INV-630** – Concreto Estructural

  * Clase C (28 MPa)
  * Asentamiento 4” ±1”
  * Curado mínimo 7–14 días

* **CAP-IV-2** – Prefabricados y Montaje

  * Transporte ≥ 80% f’c
  * Juntas NTC 5672
  * Plan de izaje obligatorio

---

# ⚠️ Cláusulas de Rechazo Automáticamente Documentadas

Incluye advertencias críticas basadas en:

* **INV-E-410**
* **INV-E-418**

Criterios incorporados:

* Irregularidad superficial > 0.4 cm (regla 3 m)
* Núcleos < 85% f’c promedio
* Núcleo individual < 75% f’c

👉 En estos casos, el sistema deja respaldo documental para **orden de demolición total**.

---

# 📸 Sistema Multifoto por Ítem

Cada criterio incluye:

* Carga múltiple de imágenes
* Vista previa inmediata
* Eliminación táctil con confirmación
* Integración automática en PDF

Características técnicas:

* Uso de `FileReader()`
* Conversión Base64 en memoria
* Compatible con iOS y Android
* No requiere servidor

---

# 🚦 Sistema Semáforo Dinámico

Estados disponibles:

* 🟢 CUMPLE
* 🔴 NO CUMPLE
* ⚪ N/A

Cambio automático de clases CSS:

```js
status-cumple
status-nocumple
status-na
```

Optimizado para navegadores móviles.

---

# 🖨️ Sistema de Impresión Profesional

Al presionar:

```
🖨️ Imprimir / Guardar PDF
```

El sistema:

* Activa `@media print`
* Repite encabezado en cada página
* Mantiene colores institucionales
* Ajusta tablas a formato formal
* Elimina botones y zonas de carga
* Conserva evidencias fotográficas

Recomendado:

> Imprimir → Guardar como PDF

---

# 📱 Adaptación Móvil Inteligente

En pantallas < 768px:

* Tablas convertidas en tarjetas
* Etiquetas dinámicas con `data-label`
* Galería en 2 columnas
* Firmas apiladas verticalmente
* Botón flotante de impresión

---

# 👷 Perfil de Usuario

* Interventor de obra
* Ingeniero Civil
* Supervisor estructural
* Inspector INVIAS
* Alcaldía Municipal
* Residente de obra

---

# 🔒 Seguridad y Limitaciones

* No guarda datos al cerrar navegador
* No almacena información en nube
* No reemplaza sistema oficial documental
* Se recomienda generar PDF inmediatamente después de diligenciar

---

# 🛠 Posibles Mejoras Futuras

* Guardado automático en `localStorage`
* Consecutivo automático de actas
* Firma digital táctil
* Exportación directa a PDF sin cuadro de impresión
* Dashboard de control estructural
* Versión multiobra

---

# 📌 Estado del Proyecto

🟢 Versión estable
📱 Totalmente responsive
🏗 Especializada en control estructural INVIAS
🖨 Lista para uso institucional

---

# 📄 Licencia

Uso técnico e institucional.
Libre modificación según requerimientos contractuales y normativos.

---

Si deseas, puedo prepararte también:

* 📘 Manual técnico formal en PDF
* ☁ Versión con almacenamiento en nube
* 🧾 Sistema con numeración automática de actas
* 🖊 Firma digital avanzada
* 🏛 Versión con identidad gráfica municipal completa

Solo dime cuál desarrollamos.
