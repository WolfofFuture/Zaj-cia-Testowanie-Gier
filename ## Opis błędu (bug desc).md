## Opis błędu (bug desc)
[Functional]
    Gracz jest w stanie dostać się do strefy, która zmienia się w strefę niedozwoloną. Musi przejść przez korytarz w ogrodzeniu, żeby przejść dalej. Po skoku w czasie, w przejściu pojawia się niewidzialna bariera, za którą gracz może utknąć, jeśli przejdzie w czasie, będąc w korytarzu. Do tego nie otrzymuje obrażeń od prądu.
## Kroki do reprodukjcji (steps to reproduce)
1. Uruchomienie aplikacji
2. Uruchomienie poziomu
3. Przejdź na drugą stronę ogrodzenia, za pomocą portalu
4. Po zejściu na dół, obok lampy skocz w przeszłość
5. Wejdź w korytarz
6. Powróć do przyszłości
7. Spróbuj wyjść z korytarza
8. Gracz jest w miejscu utknięcia

## Oczekiwany rezultat (expected result)
    Postać powinna otrzymywać obrażenia, żeby odstraszyć gracza od niepożądanego działania.
## Rzeczywisty rezultat (actual result)
    Postać nie otrzymuje obrażeń oraz będąc w przyszłości nie może wyjść z korytarza
## Dane debugowania
- **Pozycja gracza (Vector3):** X:1840,43; Y: 608.97, Z:95.150
- funkcja skoku w czasie
- 

## Załączniki (Attachments)
 - [zrzuty ekranu niżej] Zrzut ekranu
 - [brak] Wideo
 - [brak] Logi
 - [ ] Patch notes