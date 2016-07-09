# Contributing

Jest to drugi najważniejszy plik po README w projekcie. Dotyczy on osób, które chcą w sposób aktywny wpłynąć na rozwój naszego forum.

# Tworzenie `issue`

Jeśli znalazłeś błąd w projekcie (i nie wiesz jak go naprawić), masz pytanie odnośnie działania danej funkcjonalności lub chcesz powiedzieć nam, czego brakuje na forum - stwórz `Issue`. Jest to trwały sposób na przekazanie nam Twojego pomysłu lub problemu. 

## Wskazówki odnośnie `issue`

 * **Sprawdź czy już ktoś wystawił podobne `issue`** do Twojego. Nie ma sensu duplikować tych samych informacji (zgodnie z zasadą DRY), ponieważ wprowadza to niepotrzebny zamęt. Jeśli już istnieje zamknięte `issue`, a Ty dalej nie masz rozwiązania tego problemu - nic nie szkodzi. Zawsze możesz je ponownie otworzyć. 
 * **Bądź dokładny** w opisywaniu problemu lub nowej funkcjonalności. Jakiego zachowania się spodziewałeś, jakie otrzymałeś? A może wiesz jak rozwiazać ten problem? W takim razie napisz nam w jaki sposób można to zrobić. 
 * **Podeślij nam linki do `demo`** - jeśli naprawiłeś buga w naszym forum, jeśli stworzyłeś jakąś funkcjonalność - podeślij właśnie w tym issue demo działania lub zrzuty ekranu.
 * **Podaj informacje o swoim systemie i środowisku**, takie jak nazwa i wersja przeglądarki, system operacyjny - cokolwiek, co pozwoli nam się skupić na danym problemie.
 * **Dołącz treść błędu** jeśli taką otrzymujesz.
 
# Pull Requests
 
 * **Forkuj lub sklonuj projekt** na swój lokalny komputer. Instalację forum przeprowadź zgodnie z plikiem README.md
 * **Utwórz `branch`**, czyli gałąź. Zasady branchowania i workflow poniżej. 
 * **Opisz dokładnie zmiany wprowadzone** przez Ciebie. Niech każdy, kto spojrzy na dany PR będzie świadomy o jego przydatności i funkcjonowaniu.
 * **Najlepiej pokaż nam testy** gdy piszesz testy, utwórz **ze swojego brancha, już utworzonego** kolejny branch z dopiskiem `-tests` na końcu. Na nim możesz trzymać swoje testy, a my możemy przejrzeć ich działanie. 
 * **Dołącz zrzuty ekranu** obrazujące to, co stworzyłeś lub naprawiłeś (przed/po)
 
# Tworzenie branchy

Proszę się pilnie zapoznać: [Git-Flow Workflow](http://danielkummer.github.io/git-flow-cheatsheet/)

# Tworzenie commit'ów

Proszę się zapoznać: [How to write a Git Commit Message](http://chris.beams.io/posts/git-commit/)

W skrócie:

* Oddziel temat od ciała wiadomości za pomocą entera
* Ogranicz tytuł commita do 50 znaków
* Linię z tytułem zaczynamy Wielką literą
* Tytuł, tak jak w podstawówce uczono, nie posiada na końcu kropki
* Tytuł powinien być zapisany z wykorzystaniem bezokoliczników (używamy form: REFACTOR, UPDATE, REMOVE, RELEASE, MERGE, FIX)
* Użyj ciała commita, aby wyjaśnić WWH - What Why How