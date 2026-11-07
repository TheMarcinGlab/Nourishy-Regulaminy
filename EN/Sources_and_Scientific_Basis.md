# 🔬 Sources, Scientific Basis and Eligibility Criteria

**Application:** Nourishy (identifier: `com.nourishy.app`)  
**Last updated:** 7 November 2026

The Nourishy app supports healthy eating and meal planning, but **it does not replace professional medical care**. This document presents user eligibility criteria, the rationale behind combination blocks, and the scientific basis of the algorithms used.

All restrictions and safety rules in the app stem from a commitment to the user's health and comply with international guidelines of the World Health Organization (WHO), the National Institutes of Health (NIH), and the European Food Safety Authority (EFSA).

---

## 1. Sources and Bibliography

The sources listed below constitute the substantive foundation for the algorithms, thresholds, and classifications applied in the app. These are reference documents and databases of public institutions as well as peer-reviewed scientific publications.

### 1.1. Physical Activity Levels (PAL) and Energy Requirements (TDEE)

- **FAO/WHO/UNU (2004).** *Human energy requirements: Report of a Joint FAO/WHO/UNU Expert Consultation.* Rome, 17–24 October 2001. FAO Food and Nutrition Technical Report Series, No. 1. Chapter 5 covers adults.
  - 🔗 https://www.fao.org/3/y5686e/y5686e00.htm

### 1.2. BMI Classification

- **World Health Organization (WHO).** *BMI classification* — thresholds: < 18.5 underweight, 18.5–24.9 normal range, ≥ 25 overweight, ≥ 30 obesity.
  - 🔗 https://apps.who.int/nutrition/landscape/help.aspx?helpid=420

### 1.3. Food Composition and Macronutrient Data

- **USDA FoodData Central** — a public food composition database (CC0 licence).
  - 🔗 https://fdc.nal.usda.gov/

### 1.4. Methods of Measuring Resting Metabolic Rate (Academy of Nutrition and Dietetics)

- **Compher, C., Frankenfield, D., Keim, N., & Roth-Yousey, L. (2006).** *Best practice methods to apply to measurement of resting metabolic rate in adults: a systematic review.* Journal of the American Dietetic Association, 106(6), 881–903.
  - Basis for recognising the Mifflin-St Jeor equation as the reference method for BMR calculations (Academy of Nutrition and Dietetics).

### 1.5. National Institutes of Health (NIH)

- **NIH Office of Dietary Supplements (ODS)** — reliable information on nutrients and dietary supplements.
  - 🔗 https://ods.od.nih.gov
  
### 1.6. Publication Bibliography

1. **Mifflin, M. D., St Jeor, S. T., Hill, L. A., Scott, B. J., Daugherty, S. A., & Koh, Y. O. (1990).** *A new predictive equation for resting energy expenditure in healthy individuals.* The American Journal of Clinical Nutrition, 51(2), 241–247.
2. **World Health Organization (2000).** *Obesity: preventing and managing the global epidemic.* Report of a WHO consultation (WHO Technical Report Series, No. 894).
3. **European Food Safety Authority (EFSA) (2017).** *Dietary Reference Values for nutrients: Summary report.* EFSA Supporting Publications, 14(12).
4. **Compher, C., Frankenfield, D., Keim, N., & Roth-Yousey, L. (2006).** *Best practice methods to apply to measurement of resting metabolic rate in adults: a systematic review.* Journal of the American Dietetic Association, 106(6), 881–903.

---

## 2. Eligibility Criteria for Using the App

To safely use the nutritional recommendations and calculation algorithms, the user must meet the following criteria:

- **Age (≥ 18 years)** — Required range: 18 years and above — The app is not intended for minors. Energy and macronutrient requirements for individuals under 18 require individual pediatric assessment and cannot be calculated algorithmically.
- **Height (140–220 cm)** — Required range: 140–220 cm — Outside this range, the Mifflin-St Jeor equation loses statistical reliability and leads to inaccurate BMR estimates.
- **Weight (35–200 kg)** — Required range: 35–200 kg — Extreme values may indicate a condition requiring direct clinical care (anorexia, extreme obesity), where an algorithmic diet is contraindicated.
- **Body Mass Index BMI (16.0–45.0)** — Required range: 16.0–45.0 — Outside this range, clinical guidelines apply, requiring individual supervision by a physician and dietitian.
- **Anthropometric age (≤ 100 years back)** — Required range: up to 100 years — Upper applicability limit of validated metabolic formulas.

---

## 3. Who Is Not Eligible to Use the App

If any of the following situations apply to the user, **the app should not be used as a source for meal plans** — a medical or dietary consultation is required.

### 3.1. Individuals with a BMI Below 16.0 (Severe Underweight)

A BMI < 16 indicates severe underweight, which may be a symptom of eating disorders (anorexia, bulimia), chronic diseases, or hormonal imbalances. In such cases, algorithmic diet planning may exacerbate the health issue. Consultation with a physician or clinical dietitian is required.

### 3.2. Individuals with a BMI Above 45.0 (Extreme Obesity)

A BMI > 45 is associated with a high risk of comorbidities (type 2 diabetes, hypertension, heart disease). A nutritional plan must be managed under the direct supervision of a medical team.

### 3.3. Individuals Under 18 Years of Age

Energy and macronutrient requirements in children and adolescents depend on the growth phase, puberty, and individual developmental factors. The Mifflin-St Jeor equation is not applicable to this age group.

### 3.4. Pregnant and Breastfeeding Women

Caloric and macronutrient needs during pregnancy and lactation require individual adjustment by an attending physician. Standard formulas do not account for these conditions.

### 3.5. Individuals with Active Eating Disorders

Any tools for calorie counting, meal planning, and weight reduction can exacerbate the symptoms of eating disorders (anorexia, bulimia, orthorexia). In this state, specialised treatment is the priority, not an algorithmic diet.

### 3.6. Individuals with Chronic Diseases Requiring a Therapeutic Diet

Including:

- Type 1 and 2 diabetes
- Chronic kidney disease
- Liver failure
- Active phase thyroid diseases
- Autoimmune gastrointestinal diseases (celiac disease, Crohn's disease, ulcerative colitis)
- Cancer undergoing treatment
- Gestational diabetes

In these conditions, diet is a component of the medical treatment and must be determined by an attending physician or a clinical dietitian. Algorithmic planning can be dangerous.

---

## 4. Why Specific Setting Combinations Are Unavailable

Even if a user is eligible to use the app, some combinations of parameters are blocked:

- **Weight loss with BMI < 18.5:** The "weight loss" (lose_weight) goal is unavailable when BMI < 18.5. According to WHO guidelines, weight reduction in an underweight state risks metabolic complications. Safer choices are "maintain weight" or "build muscle mass".
- **Elimination diets with exclusion of all vegetables:** A vegan, vegetarian, Mediterranean, or ketogenic diet combined with the exclusion of all vegetables is blocked due to the risk of extreme micronutrient and fibre deficiencies.
- **Vegan diet + muscle building + ≥ 2 legume/nut allergies:** Blocked when there is simultaneous allergy to at least 2 groups: soy, tree nuts, peanuts, lupin. Safe balancing of high plant protein intake under these conditions requires dietitian supervision.
- **Maximum 6 allergens simultaneously:** Above 6 exclusions the product pool becomes too narrow to generate a balanced plan.

---

## 5. Calculation Methodology and Scientific Basis

The caloric and macronutrient requirement calculations in the Nourishy app are based on widely accepted clinical formulas:

- **Mifflin-St Jeor Equation:** Basal Metabolic Rate (BMR) is calculated using the standard formula recognised by the Academy of Nutrition and Dietetics:
  - Men: $BMR = (10 \times \text{weight [kg]}) + (6.25 \times \text{height [cm]}) - (5 \times \text{age}) + 5$
  - Women: $BMR = (10 \times \text{weight [kg]}) + (6.25 \times \text{height [cm]}) - (5 \times \text{age}) - 161$
- **Physical Activity Level coefficients (PAL):** Activity levels and Total Daily Energy Expenditure (TDEE) are calculated in accordance with FAO/WHO guidelines (see section 1.1).
- **BMI Classification:** Weight thresholds adopted directly from the official guidelines of the World Health Organization (WHO) (see section 1.2).

---

## 6. Contact and Support

If you have questions regarding eligibility to use the app or its scientific basis:

- Consult your primary care physician or a clinical dietitian.
- Write to us: 📧 **support@nourishy.eu**

---

**Disclaimer:** The above criteria and limitations are for informational and preventive purposes only. They do not replace a professional medical consultation. The Nourishy app is not a medical device and is not intended to diagnose, treat, or prevent any disease.
