# 🔬 Źródła naukowe, metodyka i kwalifikacja

**Aplikacja:** Nourishy (identyfikator: `com.nourishy.app`)  
**Data ostatniej aktualizacji:** 23 października 2026 r.

Aplikacja Nourishy wspiera zdrowe odżywianie i planowanie posiłków, ale **nie zastępuje profesjonalnej opieki medycznej**. Niniejszy dokument przedstawia kryteria kwalifikacji użytkowników, zasady blokad kombinacji oraz naukowe podstawy stosowanych algorytmów.

Wszelkie ograniczenia i reguły bezpieczeństwa w aplikacji wynikają z troski o zdrowie użytkownika i są zgodne z międzynarodowymi wytycznymi Światowej Organizacji Zdrowia (WHO), National Institutes of Health (NIH) oraz Europejskiego Urzędu ds. Bezpieczeństwa Żywności (EFSA).

---

## 1. Kryteria kwalifikacji do korzystania z aplikacji

Aby bezpiecznie korzystać z rekomendacji żywieniowych i algorytmów obliczeniowych, użytkownik musi spełniać poniższe kryteria:

- **Wiek (≥ 18 lat)** — zakres wymagany: 18 lat i więcej — Aplikacja przeznaczona jest wyłącznie dla osób pełnoletnich. Zapotrzebowanie energetyczne i makroskładnikowe u osób poniżej 18. roku życia wymaga indywidualnej oceny pediatrycznej i nie może być wyliczane algorytmicznie.
- **Wzrost (140–220 cm)** — zakres wymagany: 140–220 cm — Poza tym zakresem wzór metaboliczny Mifflin-St Jeor traci wiarygodność statystyczną i prowadzi do błędnych szacunków BMR.
- **Waga (35–200 kg)** — zakres wymagany: 35–200 kg — Wartości skrajne wskazują na stan wymagający bezpośredniej opieki klinicznej (anoreksja, skrajna otyłość), w którym dieta algorytmiczna jest przeciwwskazana.
- **Wskaźnik masy ciała BMI (16.0–45.0)** — zakres wymagany: 16.0–45.0 — Poza tym zakresem obowiązują wytyczne kliniczne wymagające indywidualnego nadzoru lekarza i dietetyka.
- **Wiek antropometryczny (≤ 100 lat wstecz)** — zakres wymagany: do 100 lat — Górna granica stosowalności zwalidowanych wzorów metabolicznych.

---

## 2. Kto nie kwalifikuje się do korzystania z aplikacji

Jeśli którakolwiek z poniższych sytuacji dotyczy użytkownika, **aplikacja nie powinna być używana jako źródło planów żywieniowych** — wymagana jest konsultacja lekarska lub dietetyczna.

### 2.1. Osoby z BMI poniżej 16.0 (niedowaga znaczna)

BMI < 16 wskazuje na niedowagę znaczną, która może być objawem zaburzeń odżywiania (anoreksja, bulimia), chorób przewlekłych lub zaburzeń hormonalnych. W takich przypadkach algorytmiczne planowanie diety może pogłębić problem zdrowotny. Wymagana jest konsultacja z lekarzem lub dietetykiem klinicznym.

### 2.2. Osoby z BMI powyżej 45.0 (otyłość olbrzymia)

BMI > 45 wiąże się z wysokim ryzykiem chorób współistniejących (cukrzyca typu 2, nadciśnienie, choroby serca). Plan żywieniowy musi być prowadzony pod bezpośrednim nadzorem zespołu medycznego.

### 2.3. Osoby poniżej 18. roku życia

Zapotrzebowanie energetyczne i makroskładnikowe u dzieci i młodzieży zależy od fazy wzrostu, dojrzewania i indywidualnych czynników rozwojowych. Wzory BMR nie mają zastosowania w tej grupie wiekowej.

### 2.4. Kobiety w ciąży i karmiące piersią

Zapotrzebowanie kaloryczne i makroskładnikowe w ciąży i podczas laktacji wymaga indywidualnego dostosowania przez lekarza prowadzącego. Standardowe wzory nie uwzględniają tych stanów.

### 2.5. Osoby z aktywnymi zaburzeniami odżywiania

Narzędzia do liczenia kalorii, planowania posiłków i redukcji masy ciała mogą nasilać objawy zaburzeń odżywiania (anoreksja, bulimia, ortoreksja). W tym stanie priorytetem jest leczenie specjalistyczne, nie dieta algorytmiczna.

### 2.6. Osoby z chorobami przewlekłymi wymagającymi diety leczniczej

W tym: cukrzyca typu 1 i 2, przewlekła choroba nerek, niewydolność wątroby, choroby tarczycy w fazie aktywnej, choroby autoimmunologiczne przewodu pokarmowego (celiakia, ChLC, WZJG) oraz nowotwory w trakcie leczenia. W tych stanach dieta jest elementem terapii i musi być ustalana przez lekarza specjalistę.

---

## 3. Dlaczego wybrane kombinacje ustawień są niedostępne

Nawet jeśli użytkownik kwalifikuje się do korzystania z aplikacji, niektóre kombinacje parametrów są blokowane:

- **Redukcja masy ciała przy BMI < 18.5:** Cel „redukcja masy ciała" (lose_weight) jest niedostępny, gdy BMI < 18.5. Zgodnie z wytycznymi WHO redukcja wagi w stanie niedowagi grozi powikłaniami metabolicznymi. Bezpiecznym wyborem jest „utrzymanie wagi" lub „budowa masy mięśniowej".
- **Diety eliminacyjne z wykluczeniem wszystkich warzyw:** Dieta wegańska, wegetariańska, śródziemnomorska lub ketogeniczna połączona z wykluczeniem wszystkich warzyw jest zablokowana z uwagi na ryzyko skrajnych niedoborów mikroskładników i błonnika.
- **Dieta wegańska + budowa mięśni + ≥ 2 alergie na strączki/orzechy:** Zablokowana przy jednoczesnej alergii na co najmniej 2 grupy: soja, orzechy, orzeszki ziemne, łubin. Bezpieczne zbilansowanie wysokiej podaży białka roślinnego w tych warunkach wymaga opieki dietetyka.
- **Maksymalnie 6 alergenów jednocześnie:** Powyżej 6 wykluczeń pula produktów staje się zbyt wąska, co uniemożliwia wygenerowanie zbilansowanego planu.

---

## 4. Metodyka obliczeń i podstawy naukowe

Wyliczenia zapotrzebowania kalorycznego i makroskładników w aplikacji Nourishy opierają się na powszechnie uznanych wzorach klinicznych:

- **Wzór Mifflin-St Jeor:** Podstawowa Przemiana Materii (BMR) wyliczana jest ze standardowego wzoru uznawanego przez Academy of Nutrition and Dietetics:
  - Mężczyźni: $BMR = (10 \times \text{waga [kg]}) + (6.25 \times \text{wzrost [cm]}) - (5 \times \text{wiek}) + 5$
  - Kobiety: $BMR = (10 \times \text{waga [kg]}) + (6.25 \times \text{wzrost [cm]}) - (5 \times \text{wiek}) - 161$
- **Współczynniki Aktywności Fizycznej (PAL):** Poziomy aktywności i Całkowite Zapotrzebowanie Energetyczne (TDEE) wyliczane są według wytycznych FAO/WHO.
- **Klasyfikacja BMI:** Progi masowe przyjęte bezpośrednio z oficjalnych wytycznych World Health Organization (WHO).

---

## 5. Oficjalna bibliografia medyczna

1. **Mifflin, M. D., St Jeor, S. T., Hill, L. A., Scott, B. J., Daugherty, S. A., & Koh, Y. O. (1990).** *A new predictive equation for resting energy expenditure in healthy individuals.* The American Journal of Clinical Nutrition, 51(2), 241–247.
2. **World Health Organization (2000).** *Obesity: preventing and managing the global epidemic.* Report of a WHO consultation (WHO Technical Report Series, No. 894).
3. **European Food Safety Authority (EFSA) (2017).** *Dietary Reference Values for nutrients: Summary report.* EFSA Supporting Publications, 14(12).

---

## 6. Kontakt i wsparcie

W razie pytań dotyczących kwalifikacji do korzystania z aplikacji lub podstaw naukowych:

- Skonsultuj się z lekarzem pierwszego kontaktu lub dietetykiem klinicznym.
- Napisz do nas: 📧 **support@nourishy.eu**

---

**Zastrzeżenie:** Powyższe kryteria i ograniczenia mają charakter informacyjny i profilaktyczny. Nie zastępują konsultacji medycznej. Aplikacja Nourishy nie jest wyrobem medycznym i nie służy do diagnozowania, leczenia ani zapobiegania jakimkolwiek chorobom.
