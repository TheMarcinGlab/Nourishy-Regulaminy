# 🛡️ Polityka Prywatności Aplikacji Mobilnej Nourishy

**Data ostatniej aktualizacji:** 4 sierpnia 2026 r.

---

## 1. Postanowienia ogólne i Administrator Danych

* **1.1.** Niniejsza Polityka Prywatności określa zasady, cele, podstawy prawne oraz czas przetwarzania danych osobowych użytkowników aplikacji mobilnej Nourishy (identyfikator aplikacji: `com.nourishy.app`), zwanej dalej **„Aplikacją”**.
* **1.2.** Administratorem danych osobowych jest osoba fizyczna nieprowadząca zarejestrowanej działalności gospodarczej (działalność nierejestrowana w rozumieniu polskiej ustawy Prawo przedsiębiorców): Marcin Głąb, zwany dalej „Administratorem”.
* **1.3.** Kontakt z Administratorem jest możliwy pod adresem e-mail: support@nourishy.eu
* **1.4.** Administrator deklaruje, że przetwarza dane osobowe użytkowników zgodnie z rozporządzeniem Parlamentu Europejskiego i Rady (UE) 2016/679 z dnia 27 kwietnia 2016 r. (RODO), polską ustawą o ochronie danych osobowych oraz ustawą o świadczeniu usług drogą elektroniczną.
* **1.5. Ograniczenie wiekowe:** Aplikacja przeznaczona jest wyłącznie dla osób pełnoletnich, które ukończyły **18 rok życia**. Administrator nie zbiera w sposób świadomy, nie przetwarza ani nie przechowuje danych osobowych, w tym danych o zdrowiu, osób poniżej 18 roku życia. Jeżeli Administrator poweźmie informację, że doszło do rejestracji konta przez osobę niepełnoletnią, konto takie wraz ze wszystkimi powiązanymi danymi zostanie natychmiastowo i bezpowrotnie usunięte z systemów produkcyjnych w czasie rzeczywistym.

---

## 📊 2. Kategorie i zakres zbieranych danych osobowych

W celu umożliwienia korzystania ze wszystkich zaawansowanych funkcji Aplikacji, Administrator zbiera i przetwarza następujące kategorie danych osobowych:

* **2.1. Dane rejestracyjne i autentykacyjne:** adres e-mail, identyfikator użytkownika generowany przez system Auth0.
* **2.2. Dane profilowe oraz informacje o zdrowiu (Dane szczególnej kategorii – Art. 9 RODO):** waga, wzrost, wiek, płeć, poziom aktywności fizycznej, preferencje smakowe, wybrane kuchnie świata, cele żywieniowe (np. redukcja masy, budowanie mięśni) oraz przede wszystkim **alergie pokarmowe, nietolerancje i wykluczenia dietetyczne**.
  > 🧬 **Uwaga prawna:** Dane te stanowią dane dotyczące zdrowia w rozumieniu art. 9 ust. 1 RODO. Ich przetwarzanie odbywa się wyłącznie na podstawie wyraźnej, oddzielnej i świadomej zgody użytkownika zebranej podczas procesu onboardingowego.
* **2.3. Treści użytkownika:** zdjęcia posiłków przesłane w celu analizy przez AI są przetwarzane wyłącznie w czasie rzeczywistym na potrzeby realizacji zapytania. Administrator nie wykorzystuje prywatnych zdjęć użytkowników do trenowania publicznych modeli AI. (szczegóły w [Regulaminie Serwisu](Regulamin_Serwisu_Nourishy.md), § 4.2).
* **2.4. Dane o użytkowaniu i zawartości aplikacji:** informacje wprowadzane w ramach funkcji wirtualnej lodówki (posiadane produkty), listy zakupów, historia wygenerowanych planów posiłków, preferencje oceniane metodą "swipe" oraz statystyki spożycia makroskładników.
* **2.5. Dane techniczne i lokalizacyjne:** adres IP, model urządzenia mobilnego, wersja systemu operacyjnego (iOS/Android), unikalny identyfikator urządzenia (IDFA/GAID), język systemu, unikalny token powiadomień push oraz geolokalizacja (w celu synchronizacji rynku, waluty i kraju użytkownika).
* **2.6. Dane transakcyjne i zakupowe:** status subskrypcji Premium (np. wersja próbna, subskrypcja miesięczna, roczna), data zakupu, data wygaśnięcia oraz identyfikator transakcji wygenerowany przez system RevenueCat i sklep mobilny.
  > 💳 **Ważne:** Administrator nie zbiera, nie przetwarza ani nie widzi danych kart płatniczych ani szczegółowych danych bankowych użytkownika – płatności są obsługiwane w całości przez Apple App Store lub Google Play.

---

## ⚖️ 3. Cele i podstawy prawne przetwarzania danych (RODO)

Dane osobowe użytkowników są przetwarzane przez Administratora w następujących celach, na podstawie wskazanych przepisów RODO:

* **3.1. Świadczenie usług drogą elektroniczną (Art. 6 ust. 1 lit. b RODO):** Przetwarzanie jest niezbędne do wykonania umowy o świadczenie usług (akceptacja Regulaminu). Obejmuje to rejestrację konta, utrzymanie sesji (Auth0), działanie funkcji wirtualnej lodówki, koszyka zakupowego, skanera kodów kreskowych oraz synchronizację językową i rynkową na podstawie geolokalizacji.
* **3.2. Przetwarzanie danych o zdrowiu (Art. 9 ust. 2 lit. a RODO):** Przetwarzanie danych profilowych dotyczących zdrowia, parametrów fizycznych, alergii i celów dietetycznych odbywa się na podstawie wyraźnej zgody Użytkownika, wyrażanej podczas rejestracji/onboardingu. Podanie tych danych i wyrażenie zgody jest dobrowolne, lecz **stanowi warunek konieczny (niezbędny) do świadczenia usług Aplikacji**. Odmowa wyrażenia zgody uniemożliwia utworzenie konta i korzystanie z Aplikacji. Wycofanie zgody w dowolnym momencie jest równe z brakiem możliwości dalszego świadczenia usług przez Administratora i wiąże się z koniecznością usunięcia Konta Użytkownika.
* **3.3. Wysyłka powiadomień push i lokalnych (Art. 6 ust. 1 lit. a RODO):** Przetwarzanie tokenów urządzeń w celu wysyłania powiadomień przypominających o posiłkach, zakupach lub powiadomień systemowych (widżety ekranu głównego) na podstawie zgody użytkownika wyrażonej w ustawieniach systemu operacyjnego urządzenia.
* **3.4. Prawnie uzasadniony interes Administratora (Art. 6 ust. 1 lit. f RODO):** Przetwarzanie danych technicznych i analitycznych w celu zapewnienia bezpieczeństwa teleinformatycznego Aplikacji, wykrywania błędów i awarii (_crash reporting_), optymalizacji działania systemu, prowadzenia anonimowych statystyk, a także obrony przed ewentualnymi roszczeniami prawnymi (w szczególności związanych z wyłączeniem odpowiedzialności medycznej) lub ich dochodzenia.

---

## 🤝 4. Odbiorcy danych i powierzenie przetwarzania (W tym moduły AI)

Dla zapewnienia prawidłowego i stabilnego funkcjonowania Aplikacji, Administrator korzysta z usług wyspecjalizowanych dostawców zewnętrznych. Dane użytkowników są powierzane na podstawie rygorystycznych umów powierzenia przetwarzania danych (DPA) lub udostępniane następującym podmiotom:

* **4.1. Auth0 (Okta, Inc.):** Podmiot obsługujący proces bezpiecznej rejestracji, logowania, autentykacji oraz zarządzania sesjami użytkowników.
* **4.2. Railway (Railway Corp.):** Podmiot dostarczający bezpieczną infrastrukturę chmurową oraz bazy danych, na których hostowane jest API Aplikacji oraz na których przechowywane są zaszyfrowane dane użytkowników.
* **4.3. Google LLC (Firebase / Firebase Cloud Messaging):** Narzędzia analityczne, crash reporting, optymalizacja UX oraz infrastruktura służąca do wysyłania powiadomień push i obsługi widżetów ekranu głównego.
* **4.4. RevenueCat, Inc.:** Podmiot dostarczający infrastrukturę techniczną do zarządzania subskrypcjami Premium, walidacji paragonów oraz weryfikacji statusu płatności z Apple App Store i Google Play.
* **4.5. Apple Inc. (App Store) & Google LLC (Google Play):** Operatorzy platform dystrybucyjnych, którzy przetwarzają dane transakcyjne i płatnicze użytkowników w celu realizacji zakupu subskrypcji Premium.
* **4.6. Zewnętrzni dostawcy modeli AI w chmurze (np. OpenAI, Anthropic):** W celu analizy obrazu (zdjęć potraw, produktów spożywczych oraz paragonów) przesyłanych przez Użytkownika, spseudonimizowane dane obrazowe są przesyłane do zewnętrznych dostawców modeli AI.
  > 🤖 **Bezpieczeństwo AI:** Dane przesyłane do zewnętrznych dostawców AI w celu analizy zdjęcia są **spseudonimizowane** (nie zawierają adresu e-mail, imienia ani nazwiska Użytkownika). Zewnętrzni dostawcy przetwarzają przesyłane obrazy wyłącznie w czasie rzeczywistym na potrzeby realizacji zapytania i nie wykorzystują ich do trenowania własnych modeli publicznych.

---

## 🌐 5. Przekazywanie danych poza Europejski Obszar Gospodarczy (EOG)

* **5.1.** Ze względu na korzystanie z usług globalnych dostawców technologii zlokalizowanych w Stanach Zjednoczonych (USA), dane osobowe użytkowników mogą być przekazywane i przechowywane poza EOG.
* **5.2.** Administrator dba o to, aby transfer danych odbywał się w sposób całkowicie legalny i bezpieczny. Podmioty zlokalizowane w USA, z których usług korzysta Administrator (w tym Okta/Auth0, Google, RevenueCat, OpenAI), uczestniczą w programie *EU-U.S. Data Privacy Framework* (Ramy Ochrony Danych), co oznacza, że stopień ochrony danych w tych przedsiębiorstwach został uznany przez Komisję Europejską za odpowiedni i bezpieczny.
* **5.3.** W przypadkach, gdy program *Data Privacy Framework* nie ma zastosowania, podstawą transferu są Standardowe Klauzule Umowne (SCC) zatwierdzone przez Komisję Europejską, uzupełnione o zaawansowane środki techniczne (szyfrowanie danych w spoczynku i w transmisji).

---

## ⏱️ 6. Okres przechowywania danych osobowych

* **6.1.** Dane osobowe powiązane z Kontem Użytkownika są przetwarzane przez cały okres aktywności konta, tj. przez czas trwania umowy o świadczenie usług drogą elektroniczną.
* **6.2.** W wypadku podjęcia przez użytkownika decyzji o usunięciu konta (poprzez opcję w sekcji Profil -> Ustawienia -> Usuń konto), jego dane osobowe są trwale i bezpowrotnie usuwane w czasie rzeczywistym z produkcyjnej bazy danych.
* **6.3.** Po usunięciu konta, Administrator zastrzega sobie prawo do przechowywania wyłącznie ściśle ograniczonego i zanonimizowanego zakresu danych (np. identyfikator transakcji RevenueCat, data logowania) wyłącznie w celu obrony przed ewentualnymi roszczeniami prawnymi lub podatkowymi, przez okres przedawnienia roszczeń wynikający z przepisów polskiego Kodeksu cywilnego (maksymalnie 6 lat).
* **6.4.** Dane przetwarzane na podstawie zgody (np. dane o zdrowiu i alergiach, powiadomienia push) są usuwane natychmiast po wycofaniu tej zgody przez użytkownika lub usunięciu konta.

---

## 🔑 7. Prawa użytkownika na gruncie RODO

Każdemu użytkownikowi Aplikacji przysługują pełne prawa wynikające z przepisów RODO, realizowane poprzez kontakt pod adresem **support@nourishy.eu**:

* **7.1. Prawo dostępu do danych oraz otrzymania ich kopii (Art. 15 RODO).**
* **7.2. Prawo do sprostowania i poprawiania danych (Art. 16 RODO).**
* **7.3. Prawo do usunięcia danych / „prawo do bycia zapomnianym” (Art. 17 RODO).**
* **7.4. Prawo do ograniczenia przetwarzania danych (Art. 18 RODO).**
* **7.5. Prawo do przenoszenia danych w formacie strukturyzowanym (Art. 20 RODO).**
* **7.6. Prawo do sprzeciwu wobec przetwarzania opartego na prawnie uzasadnionym interesie (Art. 21 RODO).**
* **7.7. Prawo do cofnięcia zgody na przetwarzanie danych wrażliwych (Art. 9) w dowolnym momencie, bez wpływu na zgodność z prawem przetwarzania przed jej cofnięciem.**
* **7.8. Prawo do wniesienia skargi do organu nadzorczego.** W Polsce organem tym jest **Prezes Urzędu Ochrony Danych Osobowych (PUODO)**, ul. Stawki 2, 00-193 Warszawa.

---

## ⚙️ 8. Procedura usunięcia konta a Subskrypcje

* **8.1.** Uruchomienie procedury usunięcia konta w aplikacji powoduje automatyczne, natychmiastowe i bezpowrotne usunięcie adresu e-mail, danych profilowych (w tym alergii i parametrów zdrowotnych), historii planów posiłków oraz zdjęć z serwerów i baz danych powiązanych z Aplikacją.
* **8.2.**
  > ⚠️ **Kluczowa informacja konsumencka:** Samodzielne usunięcie konta w Aplikacji **nie powoduje automatycznego anulowania aktywnej subskrypcji Premium** w Apple App Store lub Google Play. Ze względów technicznych i prawnych zależnych od operatorów sklepów mobilnych, użytkownik ma bezwzględny obowiązek anulować subskrypcję samodzielnie w ustawieniach swojego urządzenia przed usunięciem konta. W przeciwnym wypadku opłaty będą nadal naliczane przez Apple/Google. Aby zapobiec automatycznemu odnowieniu subskrypcji na urządzeniach iOS, należy przejść do: Ustawienia systemu iOS -> [Twoje Imię i Nazwisko / Apple ID] -> Subskrypcje -> Nourishy -> Anuluj subskrypcję, co najmniej 24 godziny przed końcem bieżącego okresu rozliczeniowego.

---

## 🔒 9. Bezpieczeństwo danych osobowych

* **9.1.** Administrator stosuje zaawansowane środki techniczne i organizacyjne, aby zapewnić stopień bezpieczeństwa odpowiadający ryzyku naruszenia praw lub wolności użytkowników.
* **9.2.** Cała komunikacja pomiędzy Aplikacją mobilną a infrastrukturą serwerową (API hostowane na Railway) jest w pełni szyfrowana przy użyciu nowoczesnego protokołu SSL/TLS (HTTPS).
* **9.3.** Procesy uwierzytelniania, rejestracji i logowania są odizolowane i w pełni zabezpieczone przez dedykowaną platformę Auth0, co uniemożliwia nieautoryzowany dostęp do kont użytkowników.
* **9.4.** Dane dotyczące zdrowia (alergie, waga, wzrost) podlegają dodatkowej pseudonimizacji wewnątrz bazy danych, a dostęp do nich posiadają wyłącznie upoważnione osoby związane obowiązkiem zachowania pełnej poufności.

---

## 🔄 10. Zmiany Polityki Prywatności

* **10.1.** Niniejsza Polityka Prywatności może być okresowo aktualizowana w celu dostosowania jej do zmian technologicznych, nowych funkcji Aplikacji (np. aktualizacji modeli AI), zmian u dostawców usług chmurowych lub zmian w przepisach prawa międzynarodowego (w tym nadchodzącego EU AI Act).
* **10.2.** O wszelkich istotnych modyfikacjach Polityki Prywatności użytkownicy zostaną powiadomieni bezpośrednio wewnątrz Aplikacji (poprzez dedykowany komunikat) lub za pośrednictwem wiadomości e-mail.
* **10.3.** Korzystanie z Aplikacji po wejściu w życie zmian oznacza ich pełną akceptację. W przypadku braku zgody na nową treść polityki, użytkownik powinien zaprzestać korzystania z Aplikacji i usunąć konto.
