# 🏛️ Batería Oficial de Preguntas Tipo Test — OPE Ayuntamiento de Bilbao

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Desplegado-success?style=for-the-badge&logo=github)](https://ciciar85.github.io/Bateria-OPE-Bilbao/)
[![Preguntas](https://img.shields.io/badge/Preguntas-630%20Oficiales-blue?style=for-the-badge)](preguntas.json)
[![Temas](https://img.shields.io/badge/Temario%20General-18%20Temas-indigo?style=for-the-badge)](#-temario-oficial-18-temas)
[![React](https://img.shields.io/badge/React%2018-SPA%20Autocontenida-61dafb?style=for-the-badge&logo=react)](index.html)

Simulador interactivo, web test y banco estructurado con las **630 preguntas oficiales** publicadas por el **Ayuntamiento de Bilbao** para la **Parte General del Temario** (5ª edición oficial de los procesos selectivos de OPE).

---

## 📋 Temario Oficial (18 Temas)

El banco oficial abarca con exactitud 35 preguntas por tema para un total de 630 preguntas:

1. **Tema 1**: La Constitución Española de 1978. Principios generales. Derechos y deberes fundamentales *(Preguntas 1 a 35)*.
2. **Tema 2**: El Estatuto de Autonomía del País Vasco. Competencias exclusivas, de desarrollo legislativo y de ejecución *(Preguntas 36 a 70)*.
3. **Tema 3**: El Municipio. Organización municipal de municipios de gran población (Título X Ley 7/1985 LRBRL) *(Preguntas 71 a 105)*.
4. **Tema 4**: Organización del Ayuntamiento de Bilbao. Reglamentos Orgánicos *(Preguntas 106 a 140)*.
5. **Tema 5**: Ley 39/2015, de 1 de octubre, del Procedimiento Administrativo Común de las Administraciones Públicas *(Preguntas 141 a 175)*.
6. **Tema 6**: Ley 11/2022 de Empleo Público Vasco. Retribuciones, derechos, deberes, incompatibilidades y régimen disciplinario *(Preguntas 176 a 210)*.
7. **Tema 7**: Ley 10/1982 Básica de Normalización del Uso del Euskera *(Preguntas 211 a 245)*.
8. **Tema 8**: Ley 31/1995 de Prevención de Riesgos Laborales *(Preguntas 246 a 280)*.
9. **Tema 9**: Ley Orgánica 3/2018 (LOPDGDD) y Reglamento General de Protección de Datos (RGPD 2016/679) *(Preguntas 281 a 315)*.
10. **Tema 10**: Decreto Legislativo 1/2023 de Igualdad de Mujeres y Hombres y V Plan Municipal de Igualdad del Ayuntamiento de Bilbao *(Preguntas 316 a 350)*.
11. **Tema 11**: Contratación Administrativa. Clases, elementos, procedimientos de selección y formalización (LCSP Ley 9/2017) *(Preguntas 351 a 385)*.
12. **Tema 12**: Instrumentos reguladores de RRHH: Oferta Pública de Empleo, planes de empleo y ordenación (TREBEP) *(Preguntas 386 a 420)*.
13. **Tema 13**: Personal al servicio de entidades locales: clases, régimen jurídico, plantillas y RPT (TRRL y LRBRL) *(Preguntas 421 a 455)*.
14. **Tema 14**: Presupuesto general de entidades locales: estructura, elaboración, aprobación, prórroga y liquidación (TRLRHL) *(Preguntas 456 a 490)*.
15. **Tema 15**: Ordenanzas y reglamentos de las entidades locales *(Preguntas 491 a 525)*.
16. **Tema 16**: Las Cortes Generales. El Defensor del Pueblo. El Ararteko *(Preguntas 526 a 560)*.
17. **Tema 17**: Distribución de competencias Estado - CCAA en la Constitución y Estatuto de Gernika *(Preguntas 561 a 595)*.
18. **Tema 18**: El Poder Judicial. Administración de Justicia en el País Vasco. El Tribunal Superior de Justicia *(Preguntas 596 a 630)*.

---

## ⚡ Funcionalidades de la Web Test (`index.html`)

La aplicación es una Single Page Application (SPA) construida en React 18 precompilado y estilizada con Tailwind CSS. Carga de manera instantánea, sin tiempos de transpilación en el navegador:

1. 📖 **Modo Práctica / Estudio**:
   - Navegación pregunta a pregunta con botones o salto directo al número deseado (1 a 630).
   - Filtro directo por cualquiera de los **18 temas oficiales**.
   - Retroalimentación visual inmediata (verde para acierto, rojo para error).
   - Panel de solución y fundamentación jurídica con la cita normativa y la respuesta literal.
   - Sistema de **Marcadores / Favoritos** persistente en el dispositivo (`localStorage`).
   - Atajos de teclado para agilizar la práctica (flechas izquierda/derecha para navegar, 1-4 para responder).

2. ⏱️ **Modo Simulacro de Examen**:
   - Generación de exámenes aleatorios (configuración por defecto de 50 preguntas).
   - Cronómetro regresivo con límite de tiempo proporcional.
   - Rejilla interactiva para revisar preguntas respondidas y marcar preguntas dudosas.
   - Corrección oficial con cálculo de penalización estándar:
     $$\text{Puntuación} = \text{Aciertos} - \frac{\text{Fallos}}{3}$$
   - Pantalla de resultados con desglose de porcentaje, apto/no apto y revisión de todas las respuestas.

3. 🔍 **Modo Explorador & Búsqueda**:
   - Buscador en tiempo real por texto de pregunta, opciones o normativa aplicable.

4. 📊 **Modo Estadísticas de Rendimiento**:
   - Métricas globales de aciertos, fallos, tasa de precisión y progreso desglosado por tema.

5. 🌓 **Modo Oscuro / Claro**:
   - Selector de tema para estudio nocturno de alto contraste.

---

## 📁 Estructura del Repositorio

- [`index.html`](index.html): Aplicación web SPA completa, optimizada y lista para GitHub Pages.
- [`preguntas.json`](preguntas.json): Dataset estructurado en JSON con las 630 preguntas, temas, opciones y respuestas oficiales.
- [`Bateria_OPE_Bilbao.md`](Bateria_OPE_Bilbao.md): Batería íntegra en Markdown estructurado para consulta offline o impresión.
- [`.nojekyll`](.nojekyll): Configuración para omitir el procesado de Jekyll en GitHub Pages.
- [`README.md`](README.md): Documentación y guía del repositorio.

---

## 🚀 Publicación y Despliegue en GitHub Pages

Para desplegar o actualizar esta Web Test en GitHub Pages:

1. Ve a la pestaña **Settings** de tu repositorio `OPE-Bilbao`.
2. En el menú lateral izquierdo, haz clic en **Pages**.
3. En la sección **Build and deployment > Source**, selecciona **Deploy from a branch**.
4. En **Branch**, selecciona `main` y directorio `/ (root)`.
5. Haz clic en **Save**. En 1-2 minutos, la aplicación estará disponible en:
   ```
   https://<tu-usuario>.github.io/Bateria-OPE-Bilbao/
   ```
