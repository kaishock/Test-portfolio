# Szablon dla przypadku testowego
**TEST - _Tytuł testu_**

**ŚRODOWISKO TESTOWE**

**URZĄDZENIA I APLIKACJE TESTOWE**

**WARUNKI TESTOWE**

**DANE TESTOWE**

**KROKI TESTOWE**

**OCZEKIWANY REZULTAT**

**RZECZYWISTY REZULTAT**

**PODSUMOWANIE**

**WYNIK TESTU**

**ZAŁĄCZNIKI**


## Przykładowy przypadek testowy na podstawie www.wikipedia.pl

**TEST - _pole "Przeszukaj Wikipedię" pozwala na wyszukanie wskazanego hasła_**

**ŚRODOWISKO TESTOWE**
  - https://pl.wikipedia.org

**URZĄDZENIA I APLIKACJE TESTOWE**
  - Przeglądarka Google Chrome v. 106

**WARUNKI TESTOWE**:
  - Użytkownik posiada dostęp do internetu

**DANE TESTOWE**:
  - Hasło do wyszukania: "Testowanie oprogramowania"

**KROKI TESTOWE**:
  1. Uruchom przeglądarkę
  2. Przejdź do strony Wikipedia
  3. W polu "Przeszukaj Wikipedię" wprowadź dane testowe

**OCZEKIWANY REZULTAT**:
  - Po wyszukaniu danych testowych, Użytkownik zostaje przeniesiony na podstronę https://pl.wikipedia.org/wiki/Testowanie_oprogramowania

**RZECZYWISTY REZULTAT**:

PT1 - Wyszukanie hasła "Testowanie oprogramowania"
  - Użytkownik zostaje przeniesiony na podstronę "Testowanie oprogramowania"
  - Adres URL podstrony jest zgodny z oczekiwanym rezultatem

PT2 - Wyszukanie hasła wpisanego tylko małymi literami "testowanie oprogramowania"
  - Użytkownik zostaje przeniesiony na podstronę "Testowanie oprogramowania"
  - Adres URL podstrony jest zgodny z oczekiwanym rezultatem

PT3 - Wyszukanie hasła wpisanego tylko wielkimi literami "TESTOWANIE OPROGRAMOWANIA"
  - Użytkownik zostaje przeniesiony na podstronę "Testowanie oprogramowania"
  - Adres URL podstrony jest zgodny z oczekiwanym rezultatem

**PODSUMOWANIE**:
  - Weryfikacja pola input "Przeszukaj Wikipedię" zakończona zgodnie z oczekiwanym rezultatem. 

**WYNIK TESTU**:
  - **Test zaliczony**

**ZAŁĄCZNIKI**:

![tc_input_wikipedia](https://user-images.githubusercontent.com/72787034/193466758-413b20a6-31e0-44dc-b137-379488838891.PNG)
