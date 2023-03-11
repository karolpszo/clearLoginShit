-------------------------------------------------------------------------------------------------------------------------------------------

# notificationsBeGONE dla macOS
+ notificationsBeGONE to bardzo lekki :feather: program AppleScript, który eliminuje wszystkie wyskakujące powiadomienia na macOS jednym kliknięciem.
+ Ten program jest przeznaczony dla tych, którzy doświadczają błędu popupu LoginItems lub którzy mają zbyt wiele powiadomień na swoich komputerach Mac.
+ Możesz uruchomić ten program z Programów za pomocą Aplikacje/Applications, Spotlight, lub możesz dodać go do Login Items systemu macOS, aby działał zaraz po zalogowaniu.
### Zostaw gwiazdkę :star: na tym repozytorium, jeśli spełnia wszystkie twoje potrzeby.
![applogo](https://i.imgur.com/mnm2GrD.png)

-------------------------------------------------------------------------------------------------------------------------------------------
## Główne problemy, zagadnienia i zadania do zrobienia:
- [x] :green_square: :hammer: Oprogramowanie nie zamyka powiadomień na macOS z ustawionym językiem polskim (Issue #1)
- [x] :green_square: :hammer: Zmień słowo "Schlie§en" na "Schließen" w notificationsbegone.scpt i notificationsBeGONE.app (Issue #2)
- [ ] :pen: Dodaj więcej języków 
-------------------------------------------------------------------------------------------------------------------------------------------

## Ważne wiadomości :gazeta: :ostrzeżenie:
> Gdy spojrzysz :oczy: do pliku notificationsbegone.scpt, w line 8:
```
if description of _action is in {"Schließen", "Alle entfernen", "Zamknij", "Close", "Clear All"} then
```
> Zobaczysz, że ten program działa tylko w 3 językach systemu macOS: **Niemieckim, Polskim i Angielskim.** Chcę udostępnić to oprogramowanie dla całej społeczności GitHuba i Maca, więc jeśli chcesz pomóc w tłumaczeniu oprogramowania, otwórz "Issue" ze swoją poprawką.
### Co więc potrzebuję? Jedyną rzeczą, której potrzebuję, jest tłumaczenie słowa, które zamyka powiadomienia.
![a](https://user-images.githubusercontent.com/111112623/224505336-015febd8-0c16-4b8d-810a-3369b2ed8e2b.png) 
#### W języku angielskim :gb:, jest to **Close**, w polskim :poland: - **Zamknij**, a w niemieckim :de: - **Schließen**.
-------------------------------------------------------------------------------------------------------------------------------------------
### Wesprzyj pracę nad programem! :black_heart:
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://paypal.com/karolpszo)
