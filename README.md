Markdown

# Análisis de Viabilidad para Instalación Solar Fotovoltaica en Almacén Frigorífico

Este repositorio contiene un análisis de costes y viabilidad para implementar un sistema de energía solar fotovoltaica en un **almacén con cámara frigorífica industrial**.

---

## Contenido del Proyecto

* **`main.py`**: El script principal en Python. Aquí realizo los cálculos de dimensionamiento, los costes y la amortización para dos escenarios de instalación solar: **con y sin baterías**. Además, genera gráficas interactivas con Plotly Express para visualizar el desglose de costes y la línea de tiempo de amortización.
* **`memoria_proyecto.md`**: Un documento detallado que explica todo el proyecto, la metodología que seguí, los resultados obtenidos y mis conclusiones. También incluyo una reflexión personal sobre el proceso de investigación y las decisiones que tomé.

---

## Resumen del Proyecto

Mi objetivo principal con este proyecto era optimizar los elevados costes energéticos de mi cámara frigorífica. Después de explorar varias estrategias, la **instalación solar** se reveló como la solución más eficiente y prometedora.

El análisis propone un sistema de **40 kWp** capaz de generar **73.000 kWh/año**, lo que cubriría gran parte del consumo de la cámara. Evalué dos opciones principales:

1.  **Sin baterías:** Con un coste aproximado de **70.000 €**, este escenario ofrece una amortización de unos **4.55 años**.
2.  **Con baterías (50 kWh):** Esta opción, con un coste aproximado de **120.000 €**, se amortiza en unos **7.50 años**.

Aunque la opción con baterías implica una inversión inicial mayor, la considero la mejor debido a la **seguridad crítica que proporciona a la cámara frigorífica** (evitando pérdidas por cortes de luz) y a la **maximización del autoconsumo**.

---

## Cómo Ejecutar el Análisis

Para ejecutar el análisis en tu máquina, sigue estos sencillos pasos:

1.  **Clona este repositorio:**
    ```bash
    git clone [URL_del_repositorio]
    ```
    (Reemplaza `[URL_del_repositorio]` con la URL real de tu repositorio.)

2.  **Instala las dependencias necesarias:**
    ```bash
    pip install pandas plotly
    ```

3.  **Ejecuta el script principal:**
    ```bash
    python main.py
    ```
