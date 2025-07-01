## Číslo testu: TC101

## Názov:
Pridaj majiteľa

## Cieľ:
Overiť, či je možné správne vytvoriť nového majiteľa

## Predpoklady:
 -  Používateľ sa musí prihlásiť ako - *Tester*
 -  *Tester* - musí mať vytvorené ambulancie

## Testovacie kroky:

| Číslo kroku | Názov kroku                          | Dáta              | Očakávaný výsledok                                              |
|-------------|---------------------------------------|-------------------|-----------------------------------------------------------------|
| 1           | Prejdi na stránku Prihlasovanie       | https://www.veterinarik.sk | Zobrazí sa stránka www.veterinarik.sk                          |
| 2           | V časti *"Testovaci useri"* klikni na tlačidlo *Tester*  |   | Otvorí sa stránka *Moje ambulancie*, so zoznamom ambulancií                                        |
| 3           | Klikni na tlačidlo ľubovoľnej ambulancie   |        | Otvorí sa stránka *Správa veterinárnych záznamov*                            |
| 4           | Klikni na záložku *Majitelia* |     | Zobrazí sa modul *Majitelia*, obsahujúca tabuľku s údajmi o majiteľoch
| 5           | Klikni na tlačidlo *Pridaj maijiteľa* |     | Zobrazí sa okno s názvom *Pridaj majiteľa*, na vytvorenie profilu nového majiteľa
| 6           | Vyplň údaje: Meno (povinná položka), Telefón, Email, Popis. Klikni na tlačidlo "Uložiť" |     | Majiteľ je úspešne vytvorený. Kliknutím na tlačidlo "oko" viem skontrolovať jeho údaje

## Očakávaný výsledok:
Majiteľ je úspešne vytvorený. Kliknutím na tlačidlo "oko" viem skontrolovať jeho údaje

## Závislé testy:
1. TC0002 - Registrácia používateľa
2. TC003 - Prihlásenie používateľa

## Priorita:
vysoká

## Poznámky:
- Tento scenár testuje len pozitívny prípad.
- Negatívne prípady budú v scenároch TC002 a TC003.

