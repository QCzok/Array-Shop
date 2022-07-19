# Array-Shop

Unsere Seite ist ein Automobilklub mit 18 Mitgliedern.

Aus Datenschutzgründen darf ein Nutzer nicht die Liste aller anderen registrierten Nutzer sehen können.

Er soll aber die Möglichkeit haben, einen Nutzer zu finden.

Eine solche Suche wollen wir implementieren.

## Aufbau
Wir benötigen eine `index.html`, eine `style.css` und eine `index.js`.

Verbinde die Dateien miteinander.

## HTML

Deine HTML besteht aus folgenden Elementen:
* Ein Input Formular für den Benutzernamen
* Ein Button zum Suchen.

## Style
Verleihe deiner Seite ein schlichtes Design.

### JavaScript

In einem Array speicherst du alle 18 Nutzer ab. Dies sind:
* Berry
* Don
* Henry
* Gerry
* Gal
* Freddy 
* Paul
* Lilly 
* Sammy
* Lis
* Ann
* Elizabeth
* Otto
* Betsy
* Noamie
* Peterson
* Annabelle
* Francesca

### Teil 2

Nun geht es um die Suche.

Wenn ein Nutzer einen Namen eingegeben hat und auf die Suche klickt, soll er erfahren können, ob ein solcher Nutzer unter diesem Namen registriert ist.

Unter Umständen hilft dir die Methode `includes`.

Beispiel:
```
const fruits = ["Banana", "Orange", "Apple", "Mango"];
fruits.includes("Mango");
```

## Teil 3
Nun musst du noch das Ergebnis an den Nutzer übergeben.

Benutze `innerHTML`.

## Test
Teste deine Seite mit unterschiedlichen Werten.
