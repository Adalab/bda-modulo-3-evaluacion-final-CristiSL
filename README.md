# ✈️ Evaluación Final Módulo 3 — Análisis del programa de lealtad de una aerolínea

## 📌 Descripción
Análisis exploratorio de datos sobre el comportamiento de clientes dentro de un programa de lealtad de una aerolínea canadiense. El proyecto cubre limpieza de datos, estadística descriptiva, visualización y evaluación de diferencias entre grupos.

## 📁 Estructura del repositorio
├── files/

│   ├── Customer_Flight_Activity.csv

│   └── Customer_Loyalty_History.csv

├── evaluacion-final.ipynb

└── evaluacion-final.pdf

## 🗂️ Datos
Los datos consisten en dos datasets complementarios:
- **Customer_Flight_Activity.csv**: actividad mensual de vuelo por cliente (vuelos reservados, distancia, puntos acumulados y redimidos).
- **Customer_Loyalty_History.csv**: perfil demográfico de los clientes (ubicación, nivel educativo, salario, tipo de tarjeta, estado de membresía).

## 🔍 Fases del análisis
1. **Exploración y limpieza**: detección y eliminación de duplicados, tratamiento de valores nulos y negativos en `Salary`, creación de la columna `Membership Status`.
2. **Estadística descriptiva**: análisis de variables numéricas y categóricas, identificación de outliers mediante IQR y análisis de correlación.
3. **Visualización**: gráficas de distribución, relaciones entre variables y comparativas por segmento.
4. **Evaluación por nivel educativo**: análisis descriptivo de vuelos reservados según el nivel educativo de los clientes.

## 📊 Conclusiones principales
- La mayoría de clientes no vuela habitualmente: las medianas de vuelos reservados, distancia y puntos acumulados son 0 ó 1, lo que indica una base de miembros mayoritariamente inactiva mensualmente.
- El salario no está relacionado con la actividad de vuelo. El poder adquisitivo no determina la frecuencia de vuelo en este programa.
- La actividad de reservas sigue un patrón estacional claro: pico en verano (junio-agosto) y repunte en diciembre, coincidiendo con periodos vacacionales.
- El programa mantiene una tasa de retención del 87.7%: la gran mayoría de miembros permanece activa.
- El nivel educativo no influye en el número de vuelos reservados: todos los grupos presentan medias prácticamente idénticas.

## ⚙️ Requisitos
```bash
pip install pandas numpy matplotlib seaborn
```

## 👩‍💻 Autora
Cristina Sáenz Llorente