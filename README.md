# Dashboard del Balance de Pagos Internacional

Este proyecto presenta un **análisis interactivo del balance de pagos de distintos países** utilizando Python y Plotly. Permite explorar la evolución de la **cuenta corriente** y otros tipos de cuentas a nivel global.

---

## 📊 Objetivos del Proyecto

- Visualizar la evolución de la cuenta corriente por país.
- Comparar los balances de los principales países por año.
- Explorar el balance de pagos geográficamente mediante un mapa interactivo.
- Ofrecer un dashboard interactivo con dropdowns para seleccionar años y tipos de cuenta.

---

## 🧾 Descripción de los Gráficos

### 1️⃣ Gráfico de Líneas por País
- **Propósito:** Mostrar la evolución histórica de la **cuenta corriente** de cada país.
- **Datos:** Año vs Balance (millones USD), con un color distinto por país.
- **Interactividad:** Posibilidad de seleccionar un país mediante dropdown en la versión interactiva.

### 2️⃣ Gráfico de Barras por Año
- **Propósito:** Comparar los **top países** según el valor absoluto del balance en cada año.
- **Datos:** País vs Balance (millones USD), mostrando solo los países más relevantes para evitar saturación.
- **Interactividad:** Dropdown para cambiar el año y actualizar el gráfico.

### 3️⃣ Mapa Geográfico del Balance
- **Propósito:** Visualizar la distribución geográfica de los balances por **tipo de cuenta**.
- **Datos:** Países con burbujas proporcionales al valor absoluto del balance, diferenciando entre **Current account** y **Capital account**.
- **Interactividad:** Hover para ver detalles de cada país y tipo de cuenta.

---

## ⚙️ Requisitos

- Python 3.10+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

Instalación de dependencias:
```bash
pip install -r requirements.txt


