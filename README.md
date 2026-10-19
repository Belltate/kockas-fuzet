# Kockás Füzet

Gyakorló kvízek egy 10.-es tanév anyagához: **angol szavak, matematika, történelem, fizika és
számítógépes hálózatok**. Egyetlen HTML-fájl — nincs regisztráció, nincs telepítés, nincs
bejelentkezés. Megnyitod a linket, és mehet.

**→ https://belltate.github.io/kockas-fuzet/**

## Mi van benne

| Tantárgy | Tartalom |
|---|---|
| **Angol** | Pioneer B1+ szavak leckénként (Module 1–3), mindkét irányban kérdezve; írásbeli (begépelős) feladatsorok; Present Simple vs Progressive |
| **Matematika** | szögfüggvények méretarányos ábrákkal és számológéppel; fejszámolási trükkök magyarázó oldallal |
| **Történelem** | A középkori Magyar Királyság fénykora — témánkénti mappák, jegyzetlapok, évszám- és fogalomkvízek |
| **Fizika** | Newton törvényei, lendület, sűrűség, nehézségi erő és rugóerő — vektoros ábrákkal |
| **Hálózatok** | CCNA ITN Modul 1–2 szakaszonként, IOS-parancsokkal |

## Hogyan működik

- minden kérdés után **azonnal jön a magyarázat** — nem a végén derül ki, mit rontottál el
- a generált kvízek (szavak, évszámok, fogalmak, számolás) **minden indításkor más kérdéseket**
  adnak, és a válaszok sorrendje is keveredik
- a **haladásod a böngésződben** marad (localStorage): nem megy sehova, nem kell hozzá fiók,
  de ha törlöd a böngésződ adatait, elveszik
- világos és sötét témában is működik, telefonon is

## Technikai

Egyetlen önálló HTML-fájl, külső függőség nélkül (csak a betűtípusokat tölti a Google Fontsról).
Az `index.html` generált fájl: a forrásból egy build szkript készíti, amely a publikus változatból
kihagyja azokat a részeket, amelyek külön szolgáltatást igényelnének.

A kvízek tartalma iskolai tananyag alapján készült, tanulási célra.
