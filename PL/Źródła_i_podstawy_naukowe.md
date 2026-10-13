# Kwalifikacja do aplikacji i ograniczenia

Aplikacja Nourishy wspiera zdrowe odżywianie, ale **nie zastępuje opieki medycznej**. Poniżej znajdują się kryteria kwalifikacji oraz wyjaśnienie, dlaczego część kombinacji ustawień jest niedostępna. Ograniczenia wynikają z troski o bezpieczeństwo zdrowotne użytkownika i są zgodne z międzynarodowymi wytycznymi (WHO, NIH, EFSA).

---

## 1. Kto może korzystać z aplikacji

Aby bezpiecznie korzystać z rekomendacji żywieniowych, użytkownik musi spełniać następujące warunki:

| Kryterium | Zakres akceptowany | Uzasadnienie |
|---|---|---|
| **Wiek** | ≥ 18 lat | Aplikacja nie jest przeznaczona dla osób niepełnoletnich. Zapotrzebowanie energetyczne i makroskładnikowe u osób poniżej 18. roku życia wymaga indywidualnej oceny pediatrycznej i nie może być wyliczane algorytmicznie. |
| **Wzrost** | 140–220 cm | Poza tym zakresem wzór Mifflin-St Jeor traci wiarygodność (skrajne wartości prowadzą do błędnych szacunków BMR). |
| **Waga** | 35–200 kg | Skrajne wartości mogą wskazywać na stan wymagający opieki specjalistycznej (anoreksja, skrajna otyłość), gdzie dieta algorytmiczna jest przeciwwskazana. |
| **BMI** | 16.0–45.0 | Poza tym zakresem obowiązują wytyczne kliniczne wymagające opieki lekarza i dietetyka. |
| **Data urodzenia** | ≤ 100 lat wstecz | Granica 100 lat odzwierciedla górną granicę stosowalności wzoru Mifflin-St Jeor. |

---

## 2. Kto nie kwalifikuje się do korzystania z aplikacji

Jeśli którakolwiek z poniższych sytuacji dotyczy użytkownika, **aplikacja nie powinna być używana jako źródło planów żywieniowych** — wymagana jest konsultacja lekarska lub dietetyczna.

### 2.1. Osoby z BMI poniżej 16.0 (niedowaga znaczna)

**Dlaczego wykluczone:**  
BMI < 16 wskazuje na niedowagę znaczną, która może być objawem zaburzeń odżywiania (anoreksja, bulimia), chorób przewlekłych lub zaburzeń hormonalnych. W takich przypadkach algorytmiczne planowanie diety może pogłębić problem zdrowotny.

**Co zrobić:**  
Konsultacja z lekarzem pierwszego kontaktu lub psychiatrą/dietetykiem klinicznym przed rozpoczęciem jakiejkolwiek diety.

### 2.2. Osoby z BMI powyżej 45.0 (otyłość olbrzymia)

**Dlaczego wykluczone:**  
BMI > 45 wiąże się z wysokim ryzykiem chorób współistniejących (cukrzyca typu 2, nadciśnienie, choroby serca). Plan żywieniowy musi być prowadzony pod nadzorem zespołu medycznego.

**Co zrobić:**  
Konsultacja z lekarzem, rozważenie programu odchudzania pod nadzorem specjalisty.

### 2.3. Osoby poniżej 18. roku życia

**Dlaczego wykluczone:**  
Zapotrzebowanie energetyczne i makroskładnikowe u dzieci i młodzieży zależy od fazy wzrostu, dojrzewania i indywidualnych czynników rozwojowych. Wzór Mifflin-St Jeor nie ma zastosowania w tej grupie wiekowej.

**Co zrobić:**  
Konsultacja z pediatrą lub dietetykiem dziecięcym.

### 2.4. Kobiety w ciąży i karmiące piersią

**Dlaczego wykluczone:**  
Zapotrzebowanie kaloryczne i makroskładnikowe w ciąży i podczas laktacji wymaga indywidualnego dostosowania przez lekarza prowadzącego. Standardowe wzory nie uwzględniają tych stanów.

**Co zrobić:**  
Konsultacja z ginekologiem-położnikiem lub dietetykiem specjalizującym się w ciąży.

### 2.5. Osoby z aktywnymi zaburzeniami odżywiania

**Dlaczego wykluczone:**  
Wszelkie narzędzia do liczenia kalorii, planowania posiłków i redukcji masy ciała mogą nasilać objawy zaburzeń odżywiania (anoreksja, bulimia, ortoreksja). W tym stanie priorytetem jest leczenie specjalistyczne, nie dieta.

**Co zrobić:**  
Konsultacja z psychiatrą, psychologiem lub specjalistycznym ośrodkiem leczenia zaburzeń odżywiania.

### 2.6. Osoby z chorobami przewlekłymi wymagającymi diety leczniczej

M.in.:
- Cukrzyca typu 1 i 2
- Przewlekła choroba nerek
- Niewydolność wątroby
- Choroby tarczycy w fazie aktywnej
- Choroby autoimmunologiczne przewodu pokarmowego (celiakia, choroba Leśniowskiego-Crohna, WZJG)
- Nowotwory w trakcie leczenia
- Cukrzyca ciążowa

**Dlaczego wykluczone:**  
W tych stanach dieta jest elementem leczenia i musi być ustalana przez lekarza prowadzącego lub dietetyka klinicznego. Planowanie algorytmiczne może być niebezpieczne.

**Co zrobić:**  
Konsultacja z lekarzem specjalistą lub dietetykiem klinicznym.

---

## 3. Dlaczego wybrane kombinacje ustawień są niedostępne

Nawet jeśli użytkownik kwalifikuje się do korzystania z aplikacji, niektóre kombinacje ustawień są blokowane. Poniżej wyjaśnienie dlaczego.

### 3.1. Redukcja masy ciała przy BMI < 18.5

**Reguła:**  
Cel „redukcja masy ciała" (lose_weight) jest **niedostępny**, gdy BMI < 18.5.

**Dlaczego:**  
BMI < 18.5 oznacza niedowagę (wg WHO). Redukcja masy ciała w tym stanie może prowadzić do:
- niedoborów żywieniowych (białko, żelazo, witaminy),
- zaburzeń hormonalnych (u kobiet — zaburzenia miesiączkowania),
- osłabienia układu odpornościowego,
- osteoporozy (u osób starszych).

**Co zrobić:**  
Wybór celu „utrzymanie wagi" lub „budowa masy mięśniowej" jest bezpieczniejszy. Jeśli niedowaga jest wynikiem choroby lub zaburzeń odżywiania — konsultacja lekarska.

### 3.2. Dieta wegańska + wykluczenie wszystkich warzyw

**Reguła:**  
Kombinacja jest **zablokowana**.

**Dlaczego:**  
Dieta wegańska opiera się na roślinach jako podstawowym źródle białka, żelaza, witamin i minerałów. Wykluczenie wszystkich warzyw prowadzi do skrajnych niedoborów żywieniowych i jest sprzeczne z samą definicją diety wegańskiej.

**Co zrobić:**  
Wybierz jedną z opcji: dieta wegańska **lub** wykluczenie wszystkich warzyw. Jeśli wykluczenie warzyw wynika z nietolerancji konkretnych produktów — skonsultuj się z dietetykiem, można wykluczyć konkretne warzywa, nie wszystkie.

### 3.3. Dieta wegetariańska / śródziemnomorska + wykluczenie wszystkich warzyw

**Reguła:**  
Kombinacja jest **zablokowana**.

**Dlaczego:**  
Te diety opierają warzywa jako podstawę. Wykluczenie wszystkich warzyw jest sprzeczne z ich założeniami i prowadzi do niedoborów.

### 3.4. Dieta ketogeniczna + wykluczenie wszystkich warzyw

**Reguła:**  
Kombinacja jest **zablokowana**.

**Dlaczego:**  
Dieta keto wymaga spożycia warzyw niskoskrobiowych (zielone warzywa liściaste, brokuły, cukinia) jako źródła błonnika, witamin i minerałów. Bez nich dieta staje się monotonna i prowadzi do niedoborów.

### 3.5. Dieta wegańska + budowa masy mięśniowej + ≥ 2 alergie roślinne

**Reguła:**  
Kombinacja jest **zablokowana**, gdy użytkownik ma ≥ 2 alergie z grupy: soja, orzechy, orzeszki ziemne, łubin.

**Dlaczego:**  
Budowa masy mięśniowej wymaga wysokiej podaży białka. W diecie wegańskiej główne źródła białka to rośliny strączkowe i orzechy. Jeśli użytkownik ma alergię na 2 lub więcej z tych grup, znalezienie bezpiecznych źródeł białka staje się nierealistyczne bez nadzoru dietetyka.

**Co zrobić:**  
Konsultacja z dietetykiem specjalizującym się w dietach roślinnych — możliwe że inne źródła (quinoa, ciecierzyca, pestki dyni, tempeh) będą wystarczające, ale wymaga to indywidualnego planu.

### 3.6. Więcej niż 6 alergenów jednocześnie

**Reguła:**  
Maksymalnie **6 alergenów** w profilu.

**Dlaczego:**  
Powyżej 6 wykluczeń jednocześnie pula dostępnych produktów staje się tak mała, że plany posiłków są nierealistyczne, monotonne i mogą prowadzić do niedoborów. Limit chroni przed planami, które nie będą możliwe do zrealizowania.

**Co zrobić:**  
Wybierz 6 alergenów o największym znaczeniu dla Twojego zdrowia. Pozostałe nietolerancje można zgłosić dietetykowi prowadzącemu.

---

## 4. Uwaga o danych profilowych

Wszystkie pola profilu (wzrost, waga, data urodzenia, płeć, aktywność fizyczna, cel, dieta, alergeny) podlegają walidacji **zarówno po stronie aplikacji, jak i serwera**. Oznacza to, że:

- nie da się zapisać profilu z danymi poza zakresem (np. wzrost 100 cm, waga 20 kg),
- nie da się ominąć blokad kombinacji przez manipulację żądaniami API,
- każda zmiana profilu jest weryfikowana tymi samymi regułami.

Reguły są identyczne dla wszystkich użytkowników i nie mogą być indywidualnie „poluzowane" — jeśli użytkownik nie kwalifikuje się do korzystania z aplikacji, wymagana jest konsultacja ze specjalistą.

---

## 5. Kiedy aplikacja może być nieodpowiednia — lista kontrolna

Przed rozpoczęciem korzystania z aplikacji zastanów się, czy któryś z poniższych punktów Cię dotyczy. Jeśli tak — **skonsultuj się z lekarzem lub dietetykiem przed użyciem aplikacji**:

- [ ] Mam mniej niż 18 lat
- [ ] Jestem w ciąży lub karmię piersią
- [ ] Mam BMI < 16 lub > 45
- [ ] Mam zdiagnozowane zaburzenia odżywiania (anoreksja, bulimia, ortoreksja)
- [ ] Mam cukrzycę typu 1 lub 2 wymagającą insulinoterapii
- [ ] Mam przewlekłą chorobę nerek, wątroby lub tarczycy
- [ ] Mam celiakię lub chorobę zapalną jelit
- [ ] Jestem w trakcie leczenia onkologicznego
- [ ] Przyjmuję leki wpływające na metabolizm (sterydy, hormony, leki psychiatryczne)
- [ ] Mam ≥ 2 alergie pokarmowe z grupy: soja, orzechy, orzeszki ziemne, łubin

Jeśli którykolwiek punkt jest zaznaczony — aplikacja może nie być odpowiednim narzędziem. To nie znaczy, że nie możesz jej używać, ale wymaga to **świadomej decyzji i konsultacji ze specjalistą**.

---

## 6. Kontakt i wsparcie

W razie wątpliwości dotyczących kwalifikacji do korzystania z aplikacji:

- Skonsultuj się z lekarzem pierwszego kontaktu lub dietetykiem
- Napisz do nas: [adres e-mail wsparcia]
- Zapoznaj się z sekcją „Źródła i podstawy naukowe" w aplikacji

---

**Zastrzeżenie:** Powyższe kryteria i ograniczenia mają charakter informacyjny i profilaktyczny. Nie zastępują konsultacji medycznej. Aplikacja Nourishy nie jest wyrobem medycznym i nie służy do diagnozowania, leczenia ani zapobiegania jakimkolwiek chorobom.