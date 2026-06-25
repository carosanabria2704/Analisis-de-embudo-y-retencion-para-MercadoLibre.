📱Informe ejecutivo (C → F → I)

🧠Preparé un Informe ejecutivo con formato C → F → I contestando a cada una de las preguntas del Negocio :

▶️1. Contexto: Qué proceso se analizó y qué periodo abarca.
▶️2. Hallazgos: Señalar los cohortes con las mejores y peores retenciones.
▶️3. Implicaciones: Acciones concretas (p. ej. optimizar onboarding, notificaciones o recompensas).

▶️4. Análisis personal:
¿Qué etapa mejoraría primero?
¿Qué se evidenció sobre el comportamiento del usuario?


📊Objetivos del proyecto:

▶️1. Construir embudos multietapa en SQL usando CTEs.
▶️2. Calcular tasas de conversión entre pasos y detectar caídas.
▶️3. Analizar la retención de usuarios por cohortes.
▶️4. Simular mejoras en conversión o retención.
▶️5. Validar resultados y comunicar hallazgos ejecutivos.


📱Contexto del negocio
La dirección de producto busca responder:

¿En qué etapa se pierden más usuarios?

🔹 Entre el [01/01/2025] y el [08/31/2025], ¿cuál es la tasa de conversión entre cada etapa clave del embudo?.

🔹 ¿En qué paso se observa la mayor caída porcentual de usuarios?

🔹 ¿Cómo varía esta pérdida por país (country)?

Métricas clave:

Tasa de conversión por etapa
Agrupación de eventos por device_category y referral_source
¿Qué tan bien retenemos a los usuarios a lo largo del tiempo?

🔹 Para los usuarios que se registraron entre el [01/01/2025] y el [06/01/2025], ¿cuál es la tasa de retención en D7, D14, D21, D28?

🔹 ¿Cómo se comporta la retención por país (country)?

Métrica clave: Retención por cohorte (D7, D14, D21, D28)

📂CONTEXTO:

Se analizó la retención de usuarios tomando como base cohortes mensuales de registro entre el periodo 01/01/25 y el 08/31/2025 , midiendo el porcentaje de usuarios activos a los 7,14,21 y 28 días desde su registro inicial por otro lado segmentamos por país y así identificar el comportamiento en general entre etapas para cada uno de los mercados.

<img width="752" height="452" alt="image" src="https://github.com/user-attachments/assets/2b2d45da-fc56-4c7e-a85b-59f00837f668" />

<img width="751" height="452" alt="image" src="https://github.com/user-attachments/assets/27e3ea33-ddff-4e69-83de-e895d8622220" />


📊PRINCIPALES HALLAZGOS:

- Se evidencia el mayor porcentaje de caida entre select_item y add_to_cart en todos los paises del grupo sin embargo Uruguay muestra mejores resultados sobre el resto al mantener el porcentaje de retención de usuarios desde el checking hasta el purchase.
- La mayor perdida de usuarios ocurre antes del día 7la experiencia temprana del usuario no es homogénea entre países y que factores locales como medios de pago, expectativas del usuario etc..) influyen directamente en la permanencia.

  <img width="751" height="452" alt="image" src="https://github.com/user-attachments/assets/e7d0f818-ee2b-4335-85ca-dfd422f271b7" />

  IMPLICACIONES

 ▶️ 1. Optimizar la experiencia del usuario durante los primeros 7 días.
     
 ▶️ 2. Supervisar los cohortes de forma continua para implementar practicas o validar que cambios afectan negativamente la permanencia del usuario entre las etapas del proceso de compra
     
  ▶️3. Diseñar estrategias de retención temprana para los usuarios      


 🧠ANÁLISIS PERSONAL:

 ¿Qué etapa mejoraría primero?

El foco debería estar en el onboarding inicial entre las primeras 2 semanas
 
¿Qué se evidenció sobre el comportamiento del usuario?

El resultado de la perdida gradual entre cada etapa del proceso no siempre está relacionada con el sistema en algunos casos el cliente selecciona el producto pero no está 100% convencido de comprarlo , por otro lado no todos los mercados se comportan de la misma manera.

🛠️ Tecnologías utilizadas
Python

Pandas: Manipulación y limpieza de datos.

Matplotlib & Seaborn: Visualización de distribuciones y detección de outliers (Boxplots).

NumPy: Lógica de segmentación y operaciones matemáticas.

 

  






