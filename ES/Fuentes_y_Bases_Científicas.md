# Elegibilidad para la aplicación y limitaciones

La aplicación Nourishy apoya la alimentación saludable, pero **no sustituye la atención médica**. A continuación, se detallan los criterios de elegibilidad y una explicación de por qué algunas combinaciones de ajustes no están disponibles. Las limitaciones surgen del compromiso con la seguridad de la salud del usuario y cumplen con las directrices internacionales (OMS, NIH, EFSA).

---

## 1. Quién puede utilizar la aplicación

Para utilizar de forma segura las recomendaciones nutricionales, el usuario debe cumplir las siguientes condiciones:

| Criterio | Rango Aceptado | Justificación |
|---|---|---|
| **Edad** | ≥ 18 años | La aplicación no está destinada a menores de edad. Las necesidades energéticas y de macronutrientes en personas menores de 18 años requieren una evaluación pediátrica individual y no pueden calcularse de forma algorítmica. |
| **Estatura** | 140–220 cm | Fuera de este rango, la ecuación de Mifflin-St Jeor pierde fiabilidad (los valores extremos conducen a estimaciones inexactas de la TMB). |
| **Peso** | 35–200 kg | Los valores extremos pueden indicar una condición que requiere atención especializada (anorexia, obesidad extrema), donde una dieta algorítmica está contraindicada. |
| **IMC** | 16.0–45.0 | Fuera de este rango, se aplican las directrices clínicas que requieren la atención de un médico y un nutricionista. |
| **Fecha de nacimiento** | ≤ 100 años atrás | El límite de 100 años refleja el límite superior de aplicabilidad de la ecuación de Mifflin-St Jeor. |

---

## 2. Quién no es elegible para utilizar la aplicación

Si alguna de las siguientes situaciones se aplica al usuario, **la aplicación no debe utilizarse como fuente de planes de alimentación**; se requiere una consulta médica o nutricional.

### 2.1. Personas con un IMC inferior a 16.0 (Bajo peso severo)

**Por qué se excluye:**  
Un IMC < 16 indica un bajo peso severo, que puede ser síntoma de trastornos de la conducta alimentaria (anorexia, bulimia), enfermedades crónicas o desequilibrios hormonales. En tales casos, la planificación dietética algorítmica puede agravar el problema de salud.

**Qué hacer:**  
Consultar a un médico de atención primaria o a un psiquiatra/nutricionista clínico antes de iniciar cualquier dieta.

### 2.2. Personas con un IMC superior a 45.0 (Obesidad extrema)

**Por qué se excluye:**  
Un IMC > 45 está asociado a un alto riesgo de comorbilidades (diabetes tipo 2, hipertensión, enfermedades cardíacas). Un plan nutricional debe llevarse a cabo bajo la supervisión de un equipo médico.

**Qué hacer:**  
Consultar a un médico, considerar un programa de pérdida de peso bajo la supervisión de un especialista.

### 2.3. Personas menores de 18 años

**Por qué se excluye:**  
Las necesidades energéticas y de macronutrientes en niños y adolescentes dependen de la fase de crecimiento, la pubertad y factores de desarrollo individuales. La ecuación de Mifflin-St Jeor no es aplicable a este grupo de edad.

**Qué hacer:**  
Consultar a un pediatra o a un nutricionista pediátrico.

### 2.4. Mujeres embarazadas y en período de lactancia

**Por qué se excluye:**  
Las necesidades calóricas y de macronutrientes durante el embarazo y la lactancia requieren un ajuste individual por parte de un médico tratante. Las fórmulas estándar no tienen en cuenta estas condiciones.

**Qué hacer:**  
Consultar a un ginecoobstetra o a un nutricionista especializado en embarazo.

### 2.5. Personas con trastornos de la conducta alimentaria activos

**Por qué se excluye:**  
Cualquier herramienta para contar calorías, planificar comidas y reducir peso puede agravar los síntomas de los trastornos alimentarios (anorexia, bulimia, ortorexia). En esta condición, la prioridad es el tratamiento especializado, no una dieta.

**Qué hacer:**  
Consultar a un psiquiatra, a un psicólogo o a un centro especializado en el tratamiento de trastornos alimentarios.

### 2.6. Personas con enfermedades crónicas que requieren una dieta terapéutica

Incluyendo:
- Diabetes tipo 1 y 2
- Enfermedad renal crónica
- Insuficiencia hepática
- Enfermedades de la tiroides en fase activa
- Enfermedades gastrointestinales autoinmunes (enfermedad celíaca, enfermedad de Crohn, colitis ulcerosa)
- Cáncer en tratamiento
- Diabetes gestacional

**Por qué se excluye:**  
En estas condiciones, la dieta es parte del tratamiento médico y debe ser determinada por un médico tratante o un nutricionista clínico. La planificación algorítmica puede ser peligrosa.

**Qué hacer:**  
Consultar a un médico especialista o a un nutricionista clínico.

---

## 3. Por qué no están disponibles ciertas combinaciones de ajustes

Incluso si un usuario es elegible para usar la aplicación, algunas combinaciones de ajustes están bloqueadas. A continuación, se explica el porqué.

### 3.1. Pérdida de peso con un IMC < 18.5

**Regla:**  
El objetivo de "pérdida de peso" (lose_weight) **no está disponible** cuando el IMC < 18.5.

**Por qué:**  
Un IMC < 18.5 indica bajo peso (según la OMS). La reducción de peso en este estado puede provocar:
- deficiencias nutricionales (proteínas, hierro, vitaminas),
- alteraciones hormonales (en mujeres, trastornos menstruales),
- debilitamiento del sistema inmunológico,
- osteoporosis (en adultos mayores).

**Qué hacer:**  
Elegir el objetivo de "mantener el peso" o "desarrollar masa muscular" es más seguro. Si el bajo peso es resultado de una enfermedad o de un trastorno alimentario, busque una consulta médica.

### 3.2. Dieta vegana + exclusión de todas las verduras

**Regla:**  
Esta combinación está **bloqueada**.

**Por qué:**  
La dieta vegana se basa en las plantas como fuente principal de proteínas, hierro, vitaminas y minerales. Excluir todas las verduras conduce a deficiencias nutricionales extremas y contradice la propia definición de una dieta vegana.

**Qué hacer:**  
Elija una de las opciones: dieta vegana **o** exclusión de todas las verduras. Si la exclusión de verduras se debe a la intolerancia a productos específicos, consulte a un nutricionista; es posible excluir verduras específicas, pero no todas.

### 3.3. Dieta vegetariana / mediterránea + exclusión de todas las verduras

**Regla:**  
Esta combinación está **bloqueada**.

**Por qué:**  
Estas dietas se basan en las verduras como fundamento. Excluir todas las verduras contradice sus principios fundamentales y conduce a deficiencias.

### 3.4. Dieta cetogénica + exclusión de todas las verduras

**Regla:**  
Esta combinación está **bloqueada**.

**Por qué:**  
La dieta keto requiere el consumo de verduras bajas en almidón (verduras de hoja verde, brócoli, calabacín) como fuente de fibra, vitaminas y minerales. Sin ellas, la dieta se vuelve monótona y conduce a deficiencias.

### 3.5. Dieta vegana + desarrollo de masa muscular + ≥ 2 alergias a plantas

**Regla:**  
Esta combinación está **bloqueada** cuando el usuario tiene ≥ 2 alergias del grupo: soja, frutos secos, cacahuetes, altramuz.

**Por qué:**  
El desarrollo de masa muscular requiere una alta ingesta de proteínas. En una dieta vegana, las principales fuentes de proteínas son las legumbres y los frutos secos. Si el usuario es alérgico a 2 o más de estos grupos, encontrar fuentes de proteínas seguras resulta poco realista sin la supervisión de un nutricionista.

**Qué hacer:**  
Consultar a un nutricionista especializado en dietas basadas en plantas; es posible que otras fuentes (quinoa, garbanzos, semillas de calabaza, tempeh) sean suficientes, pero esto requiere un plan altamente individualizado.

### 3.6. Más de 6 alérgenos simultáneamente

**Regla:**  
Se permite un máximo de **6 alérgenos** en el perfil.

**Por qué:**  
Por encima de 6 exclusiones simultáneas, el conjunto de productos disponibles se vuelve tan pequeño que los planes de alimentación resultan poco realistas, monótonos y pueden provocar deficiencias. Este límite protege contra planes que serían imposibles de ejecutar.

**Qué hacer:**  
Elija los 6 alérgenos de mayor importancia para su salud. Otras intolerancias pueden ser comunicadas a su nutricionista tratante.

---

## 4. Nota sobre los datos del perfil

Todos los campos del perfil (estatura, peso, fecha de nacimiento, sexo, actividad física, objetivo, dieta, alérgenos) están sujetos a validación **tanto del lado de la aplicación como del servidor**. Esto significa que:

- es imposible guardar un perfil con datos fuera de rango (por ejemplo, estatura 100 cm, peso 20 kg),
- no se pueden eludir los bloqueos de combinaciones manipulando las solicitudes a la API,
- cada cambio de perfil se verifica exactamente con las mismas reglas.

Las reglas son idénticas para todos los usuarios y no se pueden "flexibilizar" de manera individual; si un usuario no es elegible para usar la aplicación, se requiere una consulta con un especialista.

---

## 5. Cuándo la aplicación puede no ser adecuada: Lista de verificación

Antes de comenzar a usar la aplicación, considere si alguno de los siguientes puntos se aplica a usted. Si es así, **consulte a un médico o nutricionista antes de utilizar la aplicación**:

- [ ] Tengo menos de 18 años
- [ ] Estoy embarazada o en período de lactancia
- [ ] Tengo un IMC < 16 o > 45
- [ ] Tengo diagnosticados trastornos de la conducta alimentaria (anorexia, bulimia, ortorexia)
- [ ] Tengo diabetes tipo 1 o 2 que requiere insulinoterapia
- [ ] Tengo enfermedad crónica del riñón, del hígado o de la tiroides
- [ ] Tengo enfermedad celíaca o enfermedad inflamatoria intestinal
- [ ] Estoy en tratamiento oncológico
- [ ] Tomo medicamentos que afectan el metabolismo (esteroides, hormonas, fármacos psiquiátricos)
- [ ] Tengo ≥ 2 alergias alimentarias del grupo: soja, frutos secos, cacahuetes, altramuz

Si algún punto está marcado, la aplicación puede no ser una herramienta adecuada para usted. Esto no significa que no pueda usarla en absoluto, pero requiere una **decisión informada y una consulta con un especialista**.

---

## 6. Contacto y soporte

En caso de dudas sobre su elegibilidad para usar la aplicación:

- Consulte a su médico de atención primaria o a un nutricionista
- Escríbanos a: [dirección de correo electrónico de soporte]
- Consulte la sección "Fuentes y bases científicas" en la aplicación

---

**Descargo de responsabilidad:** Los criterios y limitaciones anteriores tienen fines informativos y preventivos únicamente. No sustituyen una consulta médica profesional. La aplicación Nourishy no es un dispositivo médico y no está destinada a diagnosticar, tratar ni prevenir ninguna enfermedad.