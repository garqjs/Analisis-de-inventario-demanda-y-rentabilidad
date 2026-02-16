# Análisis de inventario: demanda y rentabilidad

# 📦 Optimización de Inventario: Demanda y Rentabilidad
[![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow.svg)](https://powerbi.microsoft.com/)
[![Supply Chain](https://img.shields.io/badge/Focus-Supply_Chain_Analytics-orange.svg)]()

## 🎯 Objetivo
Desarrollar un sistema de control de inventarios preciso para minimizar quiebres de stock y optimizar el capital de trabajo. El proyecto integra métricas de demanda semanal y una matriz de clasificación avanzada para priorizar productos según su impacto financiero y estabilidad de ventas.

---

## 📊 Indicadores Clave de Gestión (KPIs)
El dashboard se centra en la salud operativa del almacén:
* **Índice de Rotación:** Frecuencia de renovación del stock.
* **Valorización del Almacén:** Valor económico total de las existencias actuales.
* **Gestión de Reorden:** Cálculo automatizado de **Puntos de Reorden (ROP)** y **Stock de Seguridad** para mitigar la incertidumbre en el suministro.
* **Alertas de Stock Status:** Clasificación visual de productos en estado *Disponible*, *Bajo Punto de Reorden* o *Agotado*.



---

## 🔬 Metodología de Clasificación ABC-XYZ
Para una gestión eficiente, implementé una matriz de doble entrada que cruza la rentabilidad con la previsibilidad de la demanda:

### 1. Clasificación ABC (Impacto en Ingresos)
* **Clase A:** Productos críticos (Alta rentabilidad).
* **Clase B:** Importancia moderada.
* **Clase C:** Bajo impacto financiero.

### 2. Clasificación XYZ (Variabilidad de Demanda)
* **X (Estable):** Demanda constante y predecible.
* **Y (Moderada):** Sujeta a estacionalidad o ciclos.
* **Z (Errática):** Demanda impredecible, difícil de pronosticar.



---

## 💡 Estrategia de Priorización Logística
Basado en el cruce de variables, el sistema segmenta los esfuerzos de gestión:

| Segmento | Prioridad de Gestión | Estrategia Sugerida |
| :--- | :--- | :--- |
| **AX / DX** | 🔥 **Crítica** | Suministro continuo y revisión de stock diaria. |
| **BY** | ⚖️ **Moderada** | Planificación flexible y monitoreo de ciclos estacionales. |
| **CZ / FZ** | 🧊 **Baja** | Gestión simplificada; monitorear tendencias para evitar stock muerto. |

---

## 🛠️ Funcionalidades del Dashboard
1.  **Seguimiento de Flujo de Pedidos:** Visualización del ciclo completo desde el pedido hasta la entrega.
2.  **Cálculo de Demanda Semanal:** Análisis dinámico de pedidos por SKU para identificar tendencias de consumo.
3.  **Monitor de SKUs a Reordenar:** Lista de acción inmediata para el departamento de compras.



---

## 🚀 Conclusiones de Negocio
Este modelo de análisis permite:
* **Reducir costos de almacenamiento** al no sobre-stockear productos de baja rotación (Clase C).
* **Garantizar disponibilidad** de los productos "A" que generan la mayoría de los ingresos.
* **Mitigar riesgos** mediante el cálculo dinámico del stock de seguridad frente a fluctuaciones imprevistas de la demanda.

---
