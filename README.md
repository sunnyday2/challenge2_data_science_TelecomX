# Challenge ONE Data Science – Telecom X (parte 1)
## 📊 Análisis de Evasión de Clientes

Este proyecto analiza datos de una empresa de telecomunicaciones para identificar los factores que influyen en la evasión de clientes. Se utilizaron herramientas de ciencia de datos para visualizar, cuantificar y predecir comportamientos de abandono, con el objetivo de proponer estrategias de retención.

---

## 🧠 Objetivo del Proyecto

- Investigar los factores que inciden en la decisión de un cliente de cancelar el servicio.
- Detectar patrones de evasión según edad, método de pago, permanencia y monto pagado.
- Entregar visualizaciones claras y conclusiones accionables para el área de retención.

---

## 📸 Visualizaciones

### Comparación por categorías (género, contrato, método de pago)
![Comparación por categoría](./permanencia_por_categoria.png)

---

### Evasión según monto pagado y edad
![Evasión por total pagado](./evasiones_pagos_edad.png)

---

### Evasión según permanencia y edad
![Evasión por permanencia](./evasiones_permanencia_edad.png)

---

Este proyecto requiere Python 3.8+ y las siguientes bibliotecas:
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- notebook (para ejecutar archivos .ipynb localmente) o un entorno virtual
  
## ⚙️ Instalación y dependencias en el entorno virtual

```bash
pip install pandas numpy matplotlib seaborn plotly


# 🧰 ¿Qué necesitas para ejecutar .ipynb localmente?
# ✅ 1. Tener Python instalado
# - Puedes descargarlo desde python.org.
# - Asegúrate de marcar “Add Python to PATH” durante la instalación.

### ✅ 2. Instalar Jupyter Notebook o JupyterLab
# - Lo más cómodo es hacerlo dentro de un entorno virtual:

# Crear entorno virtual (solo la primera vez)
python -m venv venv

# Activar el entorno
# En Windows:
venv\Scripts\activate

# En macOS/Linux:
source venv/bin/activate

# Instalar Jupyter y librerías necesarias
pip install notebook pandas matplotlib seaborn plotly

# ✅ 3. Ejecutar Jupyter Notebook
jupyter notebook
