## Opis błędu (bug desc)
[Functional]
    Gracz jest w stanie utknąć w podłodze, jeśli jeden portal jest niżej od tego, do którego wskakuje od dołu, uniemożliwiając mu kontynuację rozgrywki.
## Kroki do reprodukjcji (steps to reproduce)

1. Uruchomienie aplikacji
2. Uruchomienie poziomu
3. Wyjdź z pierwszego pokoju
4. Postaw portal na wysokiej ścianie, wyżej od siebie
5. Stojąc pod portalem, wskocz w niego
6. Gracz utknął lub wpadł pod ziemię

## Oczekiwany rezultat (expected result)
    Postać powinna niewskakiwać w portal, wrócić do poprzedniej pozycji lub przejść na drugą stronę portalu
## Rzeczywisty rezultat (actual result)
    Postać utyka w podłodze lub spada pod ziemię
## Dane debugowania
- **Pozycja gracza (Vector3):** (X=-798.300942,Y=890.617337,Z=95.150007)
- 

## Załączniki (Attachments)
 - [brak] Zrzut ekranu
 - [ ] Wideo
 - [brak] Logi
 - [brak] Patch notes