# 2-uzduotis

**Programa, skaičiuojanti studentų galutinį balą pagal jų namų darbų vidurkius arba medianas ir egzaminą; juos suskirsto į "kietus" ir "minkštus" pagal jų galutinį balą.**

**Norint paleisti programą, reikia:** 
  * atsisiųsti **main.cpp**, **func.cpp**, **header.hpp** ir **Makefile**
  * paleisti programą, kompiliuojančią kodą (Visual Studio, Visual Studio Code ir t.t.)
  * per **terminal**'ą nukeliauti su **cd** komanda į aplanką, kuriame yra atsiųstas failas
  * **terminal**'e parašyti "**mingw32-make**"
  * **terminal**'e parašyti "**./ats**"
  
**Programos veikimas:**
  * Pasirinkti ar norima, kad duomenų failai būtų sugeneruoti
  * Pasirinkti ar skaityti duomenis iš failo (jei taip, tai nurodyti failą ir keliauti į paskutinį žingsnį)
  * Pasirinkti ar balus generuoti atsitiktinai
  * Įrašyti studento vardą ir pavardę
  * Jei balai negeneruojami atsitiktinai, tai juos įrašyti
  * Pasirinkti ar pridėti naują studentą (jei taip, tai viskas kartojasi nuo 2 žingsnio)
  * Pasirinkti ar skaičiuoti vidurkį ar medianą

### Duomenų generavimo laikai
| Studentų sk.       | 1000    | 10,000  | 100,000   | 1,000,000  | 10,000,000 |
| :----------    | :------ | :------ | :-------- | :--------- | :--------- |
| Laikas (s)  | 0.0165 | 0.0505 | 0.48   | 4.8615    | 42.248    |
### Duomenų skaitymo laikai
| Studentų sk.       | 1000    | 10,000  | 100,000   | 1,000,000  | 10,000,000 |
| :----------    | :------ | :------ | :-------- | :--------- | :--------- |
| Laikas (s)  | 0.003 | 0.023 | 0.2235   | 2.207    | 12.2178    |
### Studentų rūšiavimo laikai
| Studentų sk.       | 1000    | 10,000  | 100,000   | 1,000,000  | 10,000,000 |
| :----------    | :------ | :------ | :-------- | :--------- | :--------- |
| Laikas (s)  | 0.0005 | 0.005 | 0.0455   | 0.519   | 2.48    |
### Studentų išvedimo laikai
| Studentų sk.       | 1000    | 10,000  | 100,000   | 1,000,000  | 10,000,000 |
| :----------    | :------ | :------ | :-------- | :--------- | :--------- |
| Laikas (s)  | 0.02 | 0.0496 | 0.4155   | 3.766    |37.2447   |

---

[v0.4](https://github.com/MatasValiunas/2-uzduotis/tree/v0.4) - pridėta galimybė generuoti duomenų failus, studentai pagal savo galutinį balą skirstomi į 2 grupes, matuojamas tam tikrų operacijų atlikimo laikas.

[v0.3](https://github.com/MatasValiunas/2-uzduotis/tree/v0.3) - sukurti header, Makefile ir kiti cpp failai dėl paprastesnio naudojimo. Pridėtas failo skaitymo tikrinimas (try, catch).

[v0.2](https://github.com/MatasValiunas/2-uzduotis/tree/v0.2) - galima rinktis ar duomenis vesti ranka, ar skaityti iš failo. Skaitant iš failo, programa automatiškai apskaičiuoja kiek yra namų darbų. Taip pat yra išvedimas į failą. Yra vardų rūšiavimas.

[v0.1](https://github.com/MatasValiunas/2-uzduotis) - galima skaičiuoti vidurkius ir medianas tiek su masyvais (mas.cpp), tiek su vektoriais (vekt.cpp). Yra atsitiktinių skaičių generavimas.
