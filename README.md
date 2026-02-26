# 1. Título y Descripción
## Análisis de Desercion y Estrategia de Retención: Challenge Alura Latam Telecom X Parte 2
Este proyecto utiliza Machine Learning para predecir la deserción de clientes (Churn) e identificar los factores financieros y contractuales que impactan la permanencia de los usuarios de alto valor.

# 2. Contexto del Problema
La empresa enfrenta una fuga de clientes concentrada en servicios premium. El objetivo es identificar a los clientes en riesgo antes de que abandonen y cuantificar el impacto económico de estas pérdidas.

# 3. Stack Tecnológico
Python (Pandas, NumPy)

Scikit-Learn (Regresion Logistica, Random Forest)

Imbalanced-learn (SMOTE para balanceo de datos)

Matplotlib & Seaborn (Visualización de datos)

# 4.🏆 Conclusiones del Proyecto 

## 📊 Hallazgos Clave
El "Cáncer" del Contrato Mensual: El 88.6% de las bajas totales provienen de clientes con contrato Month-to-month. Este grupo tiene un riesgo de fuga del 41.3%, frente a solo el 2.8% en contratos de dos años.

<img width="913" height="344" alt="image" src="https://github.com/user-attachments/assets/719d53fc-1edf-42a6-9a9b-383055f24138" />

El Peso del Ticket Alto: Los clientes que contratan servicios de Streaming (TV, Películas o Ambas) y Fibra Óptica generan los cargos mensuales más altos, pero son los más propensos a irse si no están vinculados a un contrato de permanencia.
<img width="592" height="459" alt="image" src="https://github.com/user-attachments/assets/fa8d4f15-2fe7-400d-9e11-d4eddc5290c4" />

Impacto Financiero: La deserción no es solo un número de clientes; proyectando las pérdidas de los clientes fugados a un año, la empresa perdio un ingreso recurrente de $ 528.374, lo que justifica cualquier inversión en campañas de retención.

<img width="502" height="427" alt="image" src="https://github.com/user-attachments/assets/6bf51fa8-8d17-4dac-85bf-67c14691655c" />

A través de la segmentación por niveles de probabilidad, identificamos la existencia de riesgos de perdida financiera anualizada de $ 17.501,14, que puede ser rescatada mediante intervenciones preventivas antes de que su probabilidad de fuga aumente.
<img width="504" height="311" alt="image" src="https://github.com/user-attachments/assets/a170ce1c-564d-4894-91f3-8a3f742a4732" />

# 5. 🤖 Desempeño del Modelo
Se seleccionó la Regresión Logística por su alto Recall (0.72). En este caso de negocio, es preferible tener algunos "falsos positivos" que dejar escapar a un cliente que realmente se va a fugar.

<img width="252" height="184" alt="image" src="https://github.com/user-attachments/assets/4f162207-f317-4b83-b779-db110d697a52" />

Las variables con mayor peso predictivo fueron: Cargos Mensuales (impulsor de fuga) y Contrato de 2 años (retenedor principal).
<img width="555" height="351" alt="image" src="https://github.com/user-attachments/assets/03a24eef-dd56-41f4-92aa-d43eadcdf931" />

# 6. 💡 Recomendaciones Estratégicas
Conversión de Contrato: Crear una oferta "Premium Anual" dirigida a usuarios de streaming que actualmente están en plan mensual, ofreciendo un descuento por permanencia.

Al analizar las variables, observamos que los contratos de Uno y Dos años actúan como potentes reductores de riesgo en comparación con el plan mensual, siendo el contrato de dos años el que presenta la mayor fuerza de retención."

Alerta Temprana: Implementar el modelo en el sistema de atención al cliente para que los agentes reciban una alerta cuando un cliente de "alto riesgo" llame, permitiéndoles ofrecer incentivos de retención proactivos.

Revisión de Fibra Óptica: Investigar la calidad del servicio técnico en zonas de alta deserción con fibra, ya que es el servicio más costoso y volátil.


