## Číslo testu: TC102

## Názov:
Náhľad profilu maiteľa - ikonka "oko"

## Cieľ:
Overiť, že používateľ sa môže úspešne pozrieť na údaje o majiteľovi

## Predpoklady:
- Používateľ sa vie prihlásiť ako tester

## Testovacie kroky:

| Číslo kroku | Názov kroku                          | Dáta              | Očakávaný výsledok                                              |
|-------------|---------------------------------------|-------------------|-----------------------------------------------------------------|
| 1           | Prejdi na stránku Prihlasovanie       | https://www.veterinarik.sk | Zobrazí sa stránka www.veterinarik.sk                          |
| 2           | Používateľ sa prihlási ako "Tester"   |      | Používateľ je prihlásený ako "Tester"                                        |
| 3           | Klikni na ľubovoľnú ambulanciu|        | Otvorí sa stránka vybranej ambulancie |
| 4           | Klikni na záložku majitelia  |  | Otvorí sa stránka *Majitelia* |
| 5           | Vyber si majiteľa a v stĺpci "Akcie" klikni na tlačidlo "oko"  |  | Otvorí sa okno "Detaily majiteľa" |
| 6           | Klikni na tlačidlo "Zavrieť"  |  | Okno "Detaily majiteľa" sa zavrie |

## Očakávaný výsledok:
Tlačidlo "oko" funguje. Používateľ sa vie pozrieť na profil majiteľa.

## Závislé testy:
1. TC103 - Prihlásenie používateľa ako "Tester"

## Priorita:
normálna

## Poznámky:
- Tento scenár testuje len pozitívny prípad.


