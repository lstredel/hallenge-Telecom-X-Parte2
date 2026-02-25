# 1. Título y Descripción
Análisis de Desercion y Estrategia de Retención: Challenge Alura Latam Telecom X Parte 2
Este proyecto utiliza Machine Learning para predecir la deserción de clientes (Churn) e identificar los factores financieros y contractuales que impactan la permanencia de los usuarios de alto valor.

2. Contexto del Problema
La empresa enfrenta una fuga de clientes concentrada en servicios premium. El objetivo es identificar a los clientes en riesgo antes de que abandonen y cuantificar el impacto económico de estas pérdidas.

3. Stack Tecnológico
Python (Pandas, NumPy)

Scikit-Learn (Logistic Regression, Random Forest)

Imbalanced-learn (SMOTE para balanceo de datos)

Matplotlib & Seaborn (Visualización de datos)

🏆 Conclusiones del Proyecto (Para tu reporte final)
Estas conclusiones resumen toda nuestra conversación y tus descubrimientos:

📊 Hallazgos Clave
El "Cáncer" del Contrato Mensual: El 88.6% de las bajas totales provienen de clientes con contrato Month-to-month. Este grupo tiene un riesgo de fuga del 41.3%, frente a solo el 2.8% en contratos de dos años.

El Peso del Ticket Alto: Los clientes que contratan servicios de Streaming (TV y Películas) y Fibra Óptica generan los cargos mensuales más altos, pero son los más propensos a irse si no están vinculados a un contrato de permanencia.

Impacto Financiero: La deserción no es solo un número de clientes; proyectando las pérdidas de los clientes fugados a un año, la empresa pierde un ingreso recurrente de $[Insertar tu cifra aquí], lo que justifica cualquier inversión en campañas de retención.

🤖 Desempeño del Modelo
Se seleccionó la Regresión Logística por su alto Recall (0.72). En este caso de negocio, es preferible tener algunos "falsos positivos" que dejar escapar a un cliente que realmente se va a fugar.

Las variables con mayor peso predictivo fueron: Cargos Mensuales (impulsor de fuga) y Contrato de 2 años (retenedor principal).

💡 Recomendaciones Estratégicas
Conversión de Contrato: Crear una oferta "Premium Anual" dirigida a usuarios de streaming que actualmente están en plan mensual, ofreciendo un descuento por permanencia.

Alerta Temprana: Implementar el modelo en el sistema de atención al cliente para que los agentes reciban una alerta cuando un cliente de "alto riesgo" llame, permitiéndoles ofrecer incentivos de retención proactivos.

Revisión de Fibra Óptica: Investigar la calidad del servicio técnico en zonas de alta deserción con fibra, ya que es el servicio más costoso y volátil.

🚀 ¿Qué sigue?
Si vas a subir esto a GitHub o enviarlo para el Challenge:

Limpia el código: Elimina celdas vacías o con errores.

Guarda el modelo: Usa el código de joblib que te pasé antes para incluir el archivo .pkl.

Capturas de pantalla: Agrega al README el gráfico de Importancia de Variables y el de Riesgo por Contrato, son tus visualizaciones más potentes.

¿Te gustaría que te ayude a redactar alguna sección más específica o crees que con esto ya tienes el "10" asegurado? ¡Éxito en tu entrega!
