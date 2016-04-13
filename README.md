# forum.pasja-informatyki.pl
## Developerskie środowisko

Grupa **CodersCommunity** postanowiła stworzyć środowisko developerskie naszego forum.

### Informacje:

To repozytorium zawiera skonfigurowaną wirtualną maszynę przygotowaną specjalnie do tego, aby nie dokonwyać zmian bezpośrednio na serwerze **produkcyjnym**

Repozytorium zawiera:
- Przygotowany "config" zawierający dane do bazy
- aktualny dump testowej bazy, zawierający tylko niezbędne dane takie jak:
  - Użytkownika testowego z loginem: `test` i hasłem `test`
  - Niezbędną konfigurację pluginow

- Kod strony, obecne Q2A wraz ze zmianami wprowadzonymi do szablonu strony. (Q2A jest na licencji GPL!!)
  - Kod strony nie zawiera: cache, avatarów, danych do bazy.
- specjalnie przygotowany plig `.gitignore`


#### Jak wyglądają zmiany?

Wszelkie poprawki dotyczące kodu strony podlegają CodeReview oraz testom.
Została włączona opcja blokady pushowania na branch `master`, dodatkowo tylko grupa **Owners** posiada prawa do mergowania, więc nie każdy kto chce będzie mógł te zmiany wprowadzać.

Więcej informacji na temat zasad współpracy można znaleźć w pliku CONTRIBUTING.md.

W momencie, gdy proces testowania zakonczy się, poprawki zostają wprowadzone na produkcję.

#### Dlaczego tak?

Chcemy pomóc Administracji.
Jedna osoba nie jest w stanie wprowadzić tylu zmian na raz. Żadne wrażliwe dane nie są tutaj ujawniane.
