#  Projektfeladat – Közösségi oldal felület készítése (HTML + CSS)

##  Feladat célja
Készítsetek egy modern, letisztult közösségi oldal (social media) felületet kizárólag **HTML és CSS** használatával!

>  JavaScript NEM használható.

Az oldal neve legyen például: **ConnectUs**

---

#  Elvárt funkciók és szerkezet

##  Oldalszerkezet (CSS Grid kötelező)

Az oldal 3 fő részből álljon:

- **Fejléc (header)**
- **Bal oldali menü (sidebar)**
- **Hírfolyam (feed)**
- (Opcionális) Jobb oldali információs panel

Az alap elrendezést **CSS Grid** segítségével kell kialakítani.

### Példa elrendezés:

```
-------------------------------------
|              HEADER               |
-------------------------------------
| SIDEBAR |         FEED           |
|         |                         |
-------------------------------------
```

📌 Kötelező:
- grid-template-areas használata
- Legalább 2 oszlopos grid
- Reszponzív viselkedés (mobilon egymás alá kerüljenek)

---

##  Fejléc (Flexbox kötelező)

A fejléc tartalmazza:

- Oldal logó (szöveg is lehet)
- Keresőmező
- Profilkép (kör alakú)
- Értesítési ikon (lehet emoji)

A fejléc elemeit **Flexbox** segítségével rendezzétek el.

📌 Kötelező:
- justify-content használata
- align-items használata
- Hover effekt a profilképen

---

##  Oldalsó menü (Flexbox)

Tartalmazzon legalább 5 menüpontot:

- Főoldal
- Profil
- Üzenetek
- Értesítések
- Beállítások

📌 Kötelező:
- Flexbox oszlop irányban
- Hover effekt (színváltás vagy háttérváltozás)
- Aktív menüpont kiemelése

---

##  Hírfolyam (Grid + Flex kombináció)

A feedben jelenjen meg legalább 3 bejegyzés (post).

Egy bejegyzés tartalmazza:

- Profilkép
- Név
- Dátum
- Szöveg
- Kép (opcionális)
- Like / Komment / Megosztás gombok

📌 Kötelező:
- A post fejléc Flexbox legyen
- A feed maga Grid legyen
- A gombok hover animációval rendelkezzenek

---

#  Animációs követelmények

Legalább 2 animáció szükséges.

### Példák:

###  Like gomb
- Hover esetén enyhe nagyítás (`transform: scale`)
- Színváltás

###  Új bejegyzés
- Oldal betöltésekor fade-in animáció

```css
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}
```

###  Menü elem
- Hover esetén enyhe jobbra csúszás

---

#  Reszponzivitás (kötelező)

600px alatt:

- A sidebar tűnjön el VAGY
- Kerüljön a feed fölé
- A grid alakuljon át 1 oszlopossá

Használjatok:

```css
@media (max-width: 600px)
```

---

#  Kötelező technikai elemek

- ✔ CSS Grid használata  
- ✔ Flexbox használata  
- ✔ Minimum 2 animáció  
- ✔ Hover effektek  
- ✔ Reszponzív viselkedés  
- ✔ Modern kinézet (színek, árnyékok, lekerekítés)

---

#  Extra pont (haladóknak)

- Dark mode kinézet
- Sticky header
- Smooth transition effektek
- Google Font használata
- Saját színpaletta tervezése

---

#  Beadandó

- `index.html`
- `style.css`
- képek (ha használtak)
- tömörítve `.zip` formátumban

---

#  Értékelési szempontok (100 pont)

| Szempont | Pont |
|----------|------|
| HTML szerkezet | 20 |
| Grid használat | 15 |
| Flexbox használat | 15 |
| Animációk | 15 |
| Reszponzivitás | 15 |
| Design igényesség | 10 |
| Kód rendezettség | 10 |

---

##  Tanári megjegyzés
A projekt célja a modern layout-megoldások (Grid és Flexbox) tudatos kombinálása, valamint az alap animációk gyakorlása valós felület szimulálásával.

