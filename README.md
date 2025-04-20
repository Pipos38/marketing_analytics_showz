# marketing_analytics_showz

# 📊 Análisis de Rentabilidad en Marketing – Caso Showz

Este proyecto simula un caso real de análisis de negocio en la empresa ficticia **Showz**, una plataforma de venta de entradas. El objetivo fue ayudar al equipo de marketing a **optimizar los gastos publicitarios y evaluar la rentabilidad de cada fuente de adquisición**.

---

## 🎯 Objetivo

- Comprender cómo los usuarios interactúan con la plataforma (visitas, sesiones, retorno).
- Medir el rendimiento de las campañas de marketing.
- Calcular KPIs clave: CAC, LTV, ROMI.
- Recomendar las fuentes más rentables para invertir presupuesto.

---

## 📁 Dataset utilizado

El análisis se realizó con datos ficticios proporcionados por TripleTen, incluyendo:

- **visits_log_us.csv** – Registros de sesiones por usuario  
- **orders_log_us.csv** – Detalles de pedidos y revenue  
- **costs_us.csv** – Inversión en publicidad por fuente

---

## 🛠️ Tecnologías utilizadas

- Python  
- Pandas, NumPy  
- Matplotlib, Plotly  
- Jupyter Notebook

---

## 📊 Análisis realizado

✔️ Limpieza y tipado de datos  
✔️ Cálculo de usuarios únicos diarios, semanales y mensuales  
✔️ Métricas de marketing:
- CAC (Costo de adquisición por fuente)
- LTV (Lifetime Value por cohortes)
- ROMI (Return on Marketing Investment)
✔️ Análisis de comportamiento del usuario  
✔️ Gráficos por fuente, cohorte y dispositivo  

---

## 📝 Conclusión

Se identificaron las fuentes con mejor rentabilidad, justificando en base a métricas clave. Se recomendó la redistribución del presupuesto en favor de las fuentes con mayor ROMI y LTV positivos, priorizando las que convertían más rápido.

---

## 📂 Estructura del repositorio

marketing_analytics_showz/ │ ├── showz_marketing_analysis.ipynb # Análisis completo ├── datasets/ │ ├── visits_log_us.csv │ ├── orders_log_us.csv │ └── costs_us.csv ├── README.md └── requirements.txt
