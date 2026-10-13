# Application Eligibility and Limitations

The Nourishy app supports healthy eating, but **it does not replace medical care**. Below are the eligibility criteria and an explanation of why certain combinations of settings are unavailable. These limitations stem from a commitment to the user's health and safety and comply with international guidelines (WHO, NIH, EFSA).

---

## 1. Who Can Use the App

To safely use the nutritional recommendations, the user must meet the following conditions:

| Criterion | Accepted Range | Justification |
|---|---|---|
| **Age** | ≥ 18 years | The app is not intended for minors. Energy and macronutrient requirements for individuals under 18 require individual pediatric assessment and cannot be calculated algorithmically. |
| **Height** | 140–220 cm | Outside this range, the Mifflin-St Jeor equation loses its reliability (extreme values lead to inaccurate BMR estimates). |
| **Weight** | 35–200 kg | Extreme values may indicate a condition requiring specialized care (anorexia, extreme obesity), where an algorithmic diet is contraindicated. |
| **BMI** | 16.0–45.0 | Outside this range, clinical guidelines apply, requiring the care of a physician and a dietitian. |
| **Date of Birth** | ≤ 100 years ago | The 100-year limit reflects the upper boundary of applicability for the Mifflin-St Jeor equation. |

---

## 2. Who Is Not Eligible to Use the App

If any of the following situations apply to the user, **the app should not be used as a source for meal plans** — a medical or dietary consultation is required.

### 2.1. Individuals with a BMI Below 16.0 (Severe Underweight)

**Why excluded:**  
A BMI < 16 indicates severe underweight, which may be a symptom of eating disorders (anorexia, bulimia), chronic diseases, or hormonal imbalances. In such cases, algorithmic diet planning may exacerbate the health issue.

**What to do:**  
Consult a primary care physician, psychiatrist, or clinical dietitian before starting any diet.

### 2.2. Individuals with a BMI Above 45.0 (Extreme Obesity)

**Why excluded:**  
A BMI > 45 is associated with a high risk of comorbidities (type 2 diabetes, hypertension, heart disease). A nutritional plan must be managed under the supervision of a medical team.

**What to do:**  
Consult a doctor and consider a weight-loss program under specialist supervision.

### 2.3. Individuals Under 18 Years of Age

**Why excluded:**  
Energy and macronutrient requirements in children and adolescents depend on the growth phase, puberty, and individual developmental factors. The Mifflin-St Jeor equation is not applicable to this age group.

**What to do:**  
Consult a pediatrician or a pediatric dietitian.

### 2.4. Pregnant and Breastfeeding Women

**Why excluded:**  
Caloric and macronutrient needs during pregnancy and lactation require individual adjustment by an attending physician. Standard formulas do not account for these conditions.

**What to do:**  
Consult an obstetrician-gynecologist or a dietitian specializing in pregnancy.

### 2.5. Individuals with Active Eating Disorders

**Why excluded:**  
Any tools for calorie counting, meal planning, and weight reduction can exacerbate the symptoms of eating disorders (anorexia, bulimia, orthorexia). In this state, specialized treatment is the priority, not a diet.

**What to do:**  
Consult a psychiatrist, psychologist, or a specialized eating disorder treatment center.

### 2.6. Individuals with Chronic Diseases Requiring a Therapeutic Diet

Including:
- Type 1 and 2 diabetes
- Chronic kidney disease
- Liver failure
- Active phase thyroid diseases
- Autoimmune gastrointestinal diseases (celiac disease, Crohn's disease, ulcerative colitis)
- Cancer undergoing treatment
- Gestational diabetes

**Why excluded:**  
In these conditions, diet is a component of the medical treatment and must be determined by an attending physician or a clinical dietitian. Algorithmic planning can be dangerous.

**What to do:**  
Consult a medical specialist or a clinical dietitian.

---

## 3. Why Specific Settings Combinations Are Unavailable

Even if a user is eligible to use the app, some combinations of settings are blocked. Below is an explanation of why.

### 3.1. Weight Loss with a BMI < 18.5

**Rule:**  
The "weight loss" (lose_weight) goal is **unavailable** when BMI < 18.5.

**Why:**  
A BMI < 18.5 indicates underweight (according to the WHO). Weight reduction in this state can lead to:
- nutritional deficiencies (protein, iron, vitamins),
- hormonal imbalances (in women — menstrual disorders),
- weakened immune system,
- osteoporosis (in older adults).

**What to do:**  
Choosing the "maintain weight" or "build muscle mass" goal is safer. If the underweight condition is the result of an illness or an eating disorder — seek a medical consultation.

### 3.2. Vegan Diet + Exclusion of All Vegetables

**Rule:**  
This combination is **blocked**.

**Why:**  
A vegan diet relies on plants as the primary source of protein, iron, vitamins, and minerals. Excluding all vegetables leads to extreme nutritional deficiencies and contradicts the very definition of a vegan diet.

**What to do:**  
Choose one of the options: vegan diet **or** exclusion of all vegetables. If the exclusion of vegetables is due to an intolerance to specific products — consult a dietitian; it is possible to exclude specific vegetables, not all of them.

### 3.3. Vegetarian / Mediterranean Diet + Exclusion of All Vegetables

**Rule:**  
This combination is **blocked**.

**Why:**  
These diets rely on vegetables as a foundation. Excluding all vegetables contradicts their core principles and leads to deficiencies.

### 3.4. Ketogenic Diet + Exclusion of All Vegetables

**Rule:**  
This combination is **blocked**.

**Why:**  
The keto diet requires the consumption of low-starch vegetables (leafy greens, broccoli, zucchini) as a source of fiber, vitamins, and minerals. Without them, the diet becomes monotonous and leads to deficiencies.

### 3.5. Vegan Diet + Muscle Building + ≥ 2 Plant Allergies

**Rule:**  
This combination is **blocked** when the user has ≥ 2 allergies from the following group: soy, tree nuts, peanuts, lupin.

**Why:**  
Building muscle mass requires a high protein intake. In a vegan diet, the main sources of protein are legumes and nuts. If the user is allergic to 2 or more of these groups, finding safe protein sources becomes unrealistic without the supervision of a dietitian.

**What to do:**  
Consult a dietitian specializing in plant-based diets — it is possible that other sources (quinoa, chickpeas, pumpkin seeds, tempeh) will be sufficient, but this requires a highly individualized plan.

### 3.6. More Than 6 Allergens Simultaneously

**Rule:**  
A maximum of **6 allergens** is permitted in the profile.

**Why:**  
With more than 6 simultaneous exclusions, the pool of available products becomes so small that meal plans turn unrealistic, monotonous, and can lead to deficiencies. This limit protects against plans that would be impossible to execute.

**What to do:**  
Select the 6 allergens of greatest importance to your health. Any additional intolerances can be reported to your attending dietitian.

---

## 4. Note on Profile Data

All profile fields (height, weight, date of birth, gender, physical activity, goal, diet, allergens) are subject to validation **on both the app and server sides**. This means that:

- it is impossible to save a profile with out-of-range data (e.g., height 100 cm, weight 20 kg),
- combination blocks cannot be bypassed by manipulating API requests,
- every profile change is verified using the exact same rules.

The rules are identical for all users and cannot be individually "relaxed" — if a user is not eligible to use the app, a consultation with a specialist is required.

---

## 5. When the App May Be Unsuitable — Checklist

Before using the app, consider whether any of the following points apply to you. If so — **consult a doctor or a dietitian before using the app**:

- [ ] I am under 18 years old
- [ ] I am pregnant or breastfeeding
- [ ] I have a BMI < 16 or > 45
- [ ] I have diagnosed eating disorders (anorexia, bulimia, orthorexia)
- [ ] I have type 1 or 2 diabetes requiring insulin therapy
- [ ] I have chronic kidney, liver, or thyroid disease
- [ ] I have celiac disease or inflammatory bowel disease
- [ ] I am undergoing oncological treatment
- [ ] I am taking medications that affect metabolism (steroids, hormones, psychiatric drugs)
- [ ] I have ≥ 2 food allergies from the group: soy, tree nuts, peanuts, lupin

If any box is checked — the app may not be a suitable tool for you. This does not mean you absolutely cannot use it, but it requires an **informed decision and consultation with a specialist**.

---

## 6. Contact and Support

In case of any doubts regarding your eligibility to use the app:

- Consult your primary care physician or a dietitian
- Write to us: [support email address]
- Refer to the "Sources and scientific basis" section in the app

---

**Disclaimer:** The above criteria and limitations are for informational and preventive purposes only. They do not replace a professional medical consultation. The Nourishy app is not a medical device and is not intended to diagnose, treat, or prevent any disease.