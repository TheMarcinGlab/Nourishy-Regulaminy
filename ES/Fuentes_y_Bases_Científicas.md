# 🔬 Fuentes, Bases Científicas y Criterios de Elegibilidad

**Aplicación:** Nourishy (identificador: `com.nourishy.app`)  
**Última actualización:** 7 de noviembre de 2026

La aplicación Nourishy apoya la alimentación saludable y la planificación de comidas, pero **no sustituye la atención médica profesional**. El presente documento expone los criterios de elegibilidad de los usuarios, la justificación de los bloqueos de combinaciones y las bases científicas de los algoritmos utilizados.

Todas las restricciones y reglas de seguridad de la aplicación surgen del compromiso con la salud del usuario y cumplen con las directrices internacionales de la Organización Mundial de la Salud (OMS), los Institutos Nacionales de Salud (NIH) y la Autoridad Europea de Seguridad Alimentaria (EFSA).

---

## 1. Fuentes y bibliografía

Las fuentes que se indican a continuación constituyen la base sustantiva de los algoritmos, umbrales y clasificaciones aplicados en la aplicación. Se trata de documentos y bases de referencia de instituciones públicas, así como de publicaciones científicas revisadas por pares.

### 1.1. Coeficientes de nivel de actividad física (NAF) y necesidades energéticas (GETD)

- **FAO/OMS/UNU (2004).** *Human energy requirements: Report of a Joint FAO/WHO/UNU Expert Consultation.* Roma, 17–24 de octubre de 2001. FAO Food and Nutrition Technical Report Series, n.º 1. El capítulo 5 se refiere a los adultos.
  - 🔗 https://www.fao.org/3/y5686e/y5686e00.htm

### 1.2. Clasificación del IMC

- **Organización Mundial de la Salud (OMS).** *BMI classification* — umbrales: < 18.5 bajo peso, 18.5–24.9 intervalo normal, ≥ 25 sobrepeso, ≥ 30 obesidad.
  - 🔗 https://apps.who.int/nutrition/landscape/help.aspx?helpid=420

### 1.3. Datos sobre composición de los alimentos y macronutrientes

- **USDA FoodData Central** — base de datos pública sobre composición de los alimentos (licencia CC0).
  - 🔗 https://fdc.nal.usda.gov/

### 1.4. Métodos de medición del gasto metabólico en reposo (Academy of Nutrition and Dietetics)

- **Compher, C., Frankenfield, D., Keim, N., & Roth-Yousey, L. (2006).** *Best practice methods to apply to measurement of resting metabolic rate in adults: a systematic review.* Journal of the American Dietetic Association, 106(6), 881–903.
  - Justificación del reconocimiento de la ecuación de Mifflin-St Jeor como método de referencia para el cálculo de la TMB (Academy of Nutrition and Dietetics).

### 1.5. National Institutes of Health (NIH)

- **NIH Office of Dietary Supplements (ODS)** — información fiable sobre nutrientes y complementos alimenticios.
  - 🔗 https://ods.od.nih.gov

### 1.6. Bibliografía de publicaciones

1. **Mifflin, M. D., St Jeor, S. T., Hill, L. A., Scott, B. J., Daugherty, S. A., & Koh, Y. O. (1990).** *A new predictive equation for resting energy expenditure in healthy individuals.* The American Journal of Clinical Nutrition, 51(2), 241–247.
2. **World Health Organization (2000).** *Obesity: preventing and managing the global epidemic.* Report of a WHO consultation (WHO Technical Report Series, No. 894).
3. **European Food Safety Authority (EFSA) (2017).** *Dietary Reference Values for nutrients: Summary report.* EFSA Supporting Publications, 14(12).
4. **Compher, C., Frankenfield, D., Keim, N., & Roth-Yousey, L. (2006).** *Best practice methods to apply to measurement of resting metabolic rate in adults: a systematic review.* Journal of the American Dietetic Association, 106(6), 881–903.

---

## 2. Criterios de elegibilidad para el uso de la aplicación

Para utilizar de forma segura las recomendaciones nutricionales y los algoritmos de cálculo, el usuario debe cumplir los siguientes criterios:

- **Edad (≥ 18 años)** — Rango requerido: 18 años y más — La aplicación no está destinada a menores de edad. Las necesidades energéticas y de macronutrientes en personas menores de 18 años requieren una evaluación pediátrica individual y no pueden calcularse de forma algorítmica.
- **Estatura (140–220 cm)** — Rango requerido: 140–220 cm — Fuera de este rango, la ecuación de Mifflin-St Jeor pierde fiabilidad estadística y conduce a estimaciones inexactas de la TMB.
- **Peso (35–200 kg)** — Rango requerido: 35–200 kg — Los valores extremos pueden indicar una condición que requiere atención clínica directa (anorexia, obesidad extrema), donde una dieta algorítmica está contraindicada.
- **Índice de masa corporal IMC (16.0–45.0)** — Rango requerido: 16.0–45.0 — Fuera de este rango, se aplican las directrices clínicas que requieren supervisión individual de un médico y un dietista.
- **Edad antropométrica (≤ 100 años atrás)** — Rango requerido: hasta 100 años — Límite superior de aplicabilidad de las fórmulas metabólicas validadas.

---

## 3. Quién no es elegible para utilizar la aplicación

Si alguna de las siguientes situaciones se aplica al usuario, **la aplicación no debe utilizarse como fuente de planes de alimentación** — se requiere una consulta médica o nutricional.

### 3.1. Personas con un IMC inferior a 16.0 (Bajo peso severo)

Un IMC < 16 indica un bajo peso severo, que puede ser síntoma de trastornos de la conducta alimentaria (anorexia, bulimia), enfermedades crónicas o desequilibrios hormonales. En tales casos, la planificación dietética algorítmica puede agravar el problema de salud. Se requiere consulta con un médico o un dietista clínico.

### 3.2. Personas con un IMC superior a 45.0 (Obesidad extrema)

Un IMC > 45 está asociado a un alto riesgo de comorbilidades (diabetes tipo 2, hipertensión, enfermedades cardíacas). Un plan nutricional debe llevarse a cabo bajo la supervisión directa de un equipo médico.

### 3.3. Personas menores de 18 años

Las necesidades energéticas y de macronutrientes en niños y adolescentes dependen de la fase de crecimiento, la pubertad y factores de desarrollo individuales. La ecuación de Mifflin-St Jeor no es aplicable a este grupo de edad.

### 3.4. Mujeres embarazadas y en período de lactancia

Las necesidades calóricas y de macronutrientes durante el embarazo y la lactancia requieren un ajuste individual por parte de un médico tratante. Las fórmulas estándar no tienen en cuenta estas condiciones.

### 3.5. Personas con trastornos de la conducta alimentaria activos

Cualquier herramienta para contar calorías, planificar comidas y reducir peso puede agravar los síntomas de los trastornos alimentarios (anorexia, bulimia, ortorexia). En esta condición, la prioridad es el tratamiento especializado, no una dieta algorítmica.

### 3.6. Personas con enfermedades crónicas que requieren una dieta terapéutica

Incluyendo:

- Diabetes tipo 1 y 2
- Enfermedad renal crónica
- Insuficiencia hepática
- Enfermedades de la tiroides en fase activa
- Enfermedades gastrointestinales autoinmunes (enfermedad celíaca, enfermedad de Crohn, colitis ulcerosa)
- Cáncer en tratamiento
- Diabetes gestacional

En estas condiciones, la dieta es parte del tratamiento médico y debe ser determinada por un médico tratante o un nutricionista clínico. La planificación algorítmica puede ser peligrosa.

---

## 4. Por qué no están disponibles ciertas combinaciones de ajustes

Incluso si un usuario es elegible para usar la aplicación, algunas combinaciones de parámetros están bloqueadas:

- **Pérdida de peso con IMC < 18.5:** El objetivo de "pérdida de peso" (lose_weight) no está disponible cuando el IMC < 18.5. Según las directrices de la OMS, la reducción de peso en estado de bajo peso conlleva riesgo de complicaciones metabólicas. Las opciones más seguras son "mantener el peso" o "desarrollar masa muscular".
- **Dietas de eliminación con exclusión de todas las verduras:** Una dieta vegana, vegetariana, mediterránea o cetogénica combinada con la exclusión de todas las verduras está bloqueada por el riesgo de deficiencias extremas de micronutrientes y fibra.
- **Dieta vegana + desarrollo de masa muscular + ≥ 2 alergias a legumbres/frutos secos:** Bloqueada cuando existe alergia simultánea a al menos 2 grupos: soja, frutos secos, cacahuetes, altramuz. El equilibrio seguro de una ingesta alta de proteínas vegetales bajo estas condiciones requiere la supervisión de un dietista.
- **Máximo 6 alérgenos simultáneamente:** Por encima de 6 exclusiones, el conjunto de productos disponibles se vuelve demasiado reducido para generar un plan equilibrado.

---

## 5. Metodología de cálculo y bases científicas

Los cálculos de las necesidades calóricas y de macronutrientes en la aplicación Nourishy se basan en fórmulas clínicas ampliamente reconocidas:

- **Ecuación de Mifflin-St Jeor:** La Tasa Metabólica Basal (TMB) se calcula con la fórmula estándar reconocida por la Academy of Nutrition and Dietetics:
  - Hombres: $TMB = (10 \times \text{peso [kg]}) + (6.25 \times \text{estatura [cm]}) - (5 \times \text{edad}) + 5$
  - Mujeres: $TMB = (10 \times \text{peso [kg]}) + (6.25 \times \text{estatura [cm]}) - (5 \times \text{edad}) - 161$
- **Coeficientes de Nivel de Actividad Física (NAF):** Los niveles de actividad y el Gasto Energético Total Diario (GETD) se calculan según las directrices de la FAO/OMS (véase la sección 1.1).
- **Clasificación del IMC:** Los umbrales de peso se adoptan directamente de las directrices oficiales de la Organización Mundial de la Salud (OMS) (véase la sección 1.2).

---

## 6. Contacto y soporte

En caso de dudas sobre la elegibilidad para usar la aplicación o sus bases científicas:

- Consulte a su médico de atención primaria o a un dietista clínico.
- Escríbanos: 📧 **support@nourishy.eu**

---

**Descargo de responsabilidad:** Los criterios y limitaciones anteriores tienen fines informativos y preventivos únicamente. No sustituyen una consulta médica profesional. La aplicación Nourishy no es un dispositivo médico y no está destinada a diagnosticar, tratar ni prevenir ninguna enfermedad.
