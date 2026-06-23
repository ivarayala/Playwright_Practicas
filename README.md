# Playwright Automation Labs & Practices 🧪✨

Este repositorio funciona como mi laboratorio de pruebas y espacio de práctica continua con **Playwright**. En él recopilo diversos escenarios, scripts y desafíos técnicos automatizados que me permiten dominar la herramienta a fondo y mantener un flujo de aprendizaje constante.

El enfoque aquí es la resolución de retos comunes de automatización, manejo de elementos dinámicos en la UI y la correcta estructuración de suites de prueba.

---

## 📂 Estructura del Proyecto (Main Branch)

Al explorar la rama principal (`main`), encontrarás una estructura limpia y estandarizada para proyectos de automatización:

*   **`tests/`**: Contiene los archivos de prueba (`.spec.ts` / `.spec.js`) organizados por escenarios (formularios, logins, flujos E2E).
*   **`playwright.config.ts`**: Archivo central de configuración donde gestiono los entornos, navegadores (Chromium, Firefox, WebKit), reintentos y reporteros.
*   **`package.json`**: Gestión de dependencias y scripts automatizados de ejecución rápida.

---

## 🛠️ Stack Tecnológico y Enfoque

*   **Core Tool:** Playwright
*   **Estrategia:** Creación de scripts independientes y suites de prueba diseñadas para validar flujos de usuario finales (E2E).
*   **Buenas Prácticas:** Implementación de esperas automáticas (*auto-waiting*) y uso de localizadores robustos recomendados por Playwright (`getByRole`, `getByText`) para evitar tests inestables (*flaky*).

---

## 📌 Escenarios Automatizados en este Laboratorio

A través de las prácticas en este repositorio, abordo situaciones reales del día a día de un QA Automation:

*   **Interacciones Complejas de UI:** Automatización de formularios, manejo de elementos dinámicos, dropdowns, modales y navegación entre múltiples páginas.
*   **Asincronía y Sincronización:** Control eficiente de tiempos de carga y respuestas del servidor sin recurrir a esperas forzadas (*hardcoded sleeps*).
*   **Análisis de Resultados:** Configuración y lectura de reportes HTML integrados para identificar fallos de manera rápida.

---

## 🚀 Cómo Ejecutar las Prácticas Localmente

1. **Clonar el proyecto:**
```bash
   git clone [https://github.com/ivarayala/Playwright_Practicas.git](https://github.com/ivarayala/Playwright_Practicas.git)
   cd Playwright_Practicas
