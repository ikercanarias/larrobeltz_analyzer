# 📊 Financial Dashboard

Dashboard web interactivo para analizar **ingresos y gastos a partir de ficheros Excel**.

Permite importar movimientos bancarios, aplicar filtros avanzados, agrupar conceptos, crear categorías y reglas personalizadas y visualizar la información mediante gráficos interactivos.

> Una herramienta ligera y privada para convertir un Excel de movimientos financieros en un dashboard de análisis.

---

## ✨ Características

### 📥 Importación de Excel

Carga directamente tus ficheros:

* `.xls`
* `.xlsx`

La aplicación detecta automáticamente:

* Hoja de datos
* Cabeceras
* Fecha
* Concepto
* Fecha valor
* Importe
* Saldo

Si el formato del Excel es diferente, permite realizar el mapeo de columnas manualmente.

---

### 📈 Dashboard financiero

Visualiza de un vistazo:

* 💰 Ingresos totales
* 💸 Gastos totales
* 📊 Balance
* 🏦 Saldo actual
* 🔢 Número de movimientos

Todos los indicadores se actualizan automáticamente al aplicar filtros.

---

### 📊 Gráficos interactivos

Genera gráficos dinámicamente en función de los criterios seleccionados.

Puedes analizar:

* Ingresos
* Gastos
* Balance
* Ingresos y gastos
* Número de movimientos
* Evolución del saldo

Y agrupar la información por:

* Día
* Semana
* Mes
* Trimestre
* Año
* Concepto
* Categoría
* Grupo

Tipos de gráficos disponibles:

* Línea
* Barras
* Barras apiladas
* Área
* Dona
* Circular
* Combinado

---

## 🔎 Filtros avanzados

Filtra los movimientos por diferentes criterios.

### Fecha

* Desde / hasta
* Este mes
* Mes anterior
* Últimos 30 días
* Últimos 90 días
* Este año
* Año anterior

### Tipo de movimiento

* Todos
* Ingresos
* Gastos
* Neutros

### Concepto

Búsqueda por texto con diferentes operadores:

* Contiene
* No contiene
* Empieza por
* Termina por
* Igual a
* Distinto de

Por ejemplo:

```text
Concepto contiene "FEDERACION"
```

permitirá localizar todos los movimientos relacionados con una federación aunque el texto completo del concepto sea diferente.

---

## 🗂️ Agrupación de conceptos

Una de las principales funcionalidades de la aplicación es la posibilidad de **agrupar movimientos independientemente del concepto original**.

Por ejemplo:

```text
TRANSF. VIRGINIA ARTOLA RIVAS
TRANSF. MIRIAM CORREA SARACHAGA
TRANSF. SERGIO GARCIA
```

pueden agruparse dentro de:

```text
Transferencias personales
```

También pueden crearse grupos mediante reglas:

```text
Contiene "CUOTA"
→ Cuotas

Contiene "FEDERACION"
→ Federación

Contiene "COMISION"
→ Comisiones bancarias
```

Los grupos son configurables por el usuario y no modifican los datos originales.

---

## 🏷️ Categorías y reglas

Permite crear catego
