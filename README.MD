# 🏢 Portal Interno de Recursos Humanos

Este es un prototipo funcional de un **Portal de Recursos Humanos** diseñado para la gestión interna de empleados, visualización de vacantes y envío de solicitudes administrativas. 

El proyecto está optimizado para ser desplegado de forma rápida y gratuita a través de **GitHub Pages**.

## 🚀 Demostración en Vivo
Puedes ver el portal funcionando directamente en tu navegador a través del siguiente enlace:
👉 **[REMPLAZA_CON_TU_ENLACE_DE_GITHUB_PAGES](https://github.io)**

---

## 🛠️ Tecnologías Utilizadas
El proyecto se desarrolló bajo un enfoque de **archivo único independiente** (Single File Component), facilitando su distribución y carga:
*   **HTML5:** Estructuración semántica del contenido (tablas, formularios, secciones).
*   **CSS3:** Diseño moderno, adaptabilidad y estilos responsivos integrados en `<style>`.
*   **JavaScript (Vanilla):** Lógica del lado del cliente sin dependencias ni librerías externas.

---

## 🌟 Características Principales

### 1. Funcionalidad Automatizada (Interconectividad)
*   Al hacer clic en **"Postularse"** en cualquier vacante de la tabla, la página se desplaza automáticamente al formulario.
*   El sistema autocompleta el cuadro de texto de la justificación con el nombre específico del puesto seleccionado.
*   Selecciona de forma automática la opción de "Postulación Interna" en los botones de radio.

### 2. Validaciones en Tiempo Real
*   **Filtro de Seguridad:** El formulario exige obligatoriamente un correo institucional con el dominio corporativo `@empresa.com`.
*   **Campos Obligatorios:** Verifica que el usuario elija un tipo de requerimiento antes de procesar el envío.

### 3. Diseño Profesional
*   Estructura limpia basada en tarjetas independientes para cada sección.
*   Efectos visuales interactivos (*hover*) en filas de tablas y botones de acción.

---

## 📦 Instrucciones de Despliegue en GitHub Pages

Para publicar este portal en tu cuenta de GitHub, sigue estos pasos:

1.  Crea un nuevo repositorio en tu cuenta de GitHub (ej. `portal-rrhh`).
2.  Sube el archivo principal renombrado exactamente como **`index.html`**.
3.  Sube este archivo **`README.md`** a la raíz del repositorio.
4.  Ve a la pestaña **Settings** (Configuración) de tu repositorio.
5.  En el menú izquierdo, busca la sección **Pages**.
6.  En *Build and deployment*, selecciona la rama **`main`** (o `master`) y la carpeta `/root`.
7.  Haz clic en **Save** (Guardar).
8.  Espera unos minutos y GitHub te proporcionará el enlace público de tu web.

---

## 📝 Licencia
Este proyecto es de código abierto y está disponible bajo la Licencia MIT. Siéntete libre de clonarlo y adaptarlo a las necesidades de tu organización.
