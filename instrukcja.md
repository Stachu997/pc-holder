# Zawieszenie obudowy pod biurkiem

Wersja, która zostaje, to **wersja 2**: obudowa głębiej, więcej miejsca na nogi. Wersja 1 jest zapisana obok, gdyby jednak miała stanąć bliżej krawędzi.

Ceny są brutto, z 31 października 2026, bez wysyłki. Tam, gdzie podaję sklep, cena jest z jego strony. Płaskownik i paczka śrub M5 to widełki, nie konkretna aukcja.

## Pliki

| Plik | Co to jest |
| --- | --- |
| `pod-biurkiem-tyl.FCStd` | Wersja 2, do złożenia. Ten sam model co `pod-biurkiem.FCStd`. |
| `pod-biurkiem-przod.FCStd` | Wersja 1. |
| `desk-pc-holder-tyl.step` | Wersja 2 dla taty: blat, stelaż, obudowa i rama, osobne bryły. |
| `desk-pc-holder-przod.step` | Wersja 1, to samo. |
| `desk-pc-holder.step` | Kopia wersji 2. |
| `holder-2020.step` | Sama rama wersji 2, bez biurka i bez obudowy. |

STEP jest w milimetrach. Części da się ruszać osobno, nie ma w nim wiązań. Fusion: jak wpadną w jeden komponent, użyj Create Components from Bodies. Inventor otwiera ten plik. AutoCAD LT nie wczyta brył 3D.

Model stoi po lewej stronie biurka. Prawa strona byłaby lustrzana.

## Czym się różnią

Oś Y to głębokość blatu. Y = 0 to przednia krawędź, Y = 800 to tylna. Przód obudowy to szyba.

| | Wersja 1 | Wersja 2 |
| --- | --- | --- |
| Przód szyby od krawędzi blatu | 183 mm | 323 mm |
| Miejsce na nogi | mniej | 14 cm więcej |
| Tył obudowy | 617 mm, zostaje 183 mm do tylnej krawędzi | 757 mm, zostaje 43 mm |
| Belki boczne | 2 × 470 mm | 2 × 415 mm |
| Reszta cięć | ta sama | ta sama |

Te 43 mm z tyłu są na wtyczkę. Nad obudową, do spodu blatu, jest 72 mm, więc kabel idzie w górę i nie wystaje za biurko. Dosunięcie pod samą krawędź wyrzuca wtyczkę poza blat.

W wersji 2 środek ciężkości jest około 7 cm za tylną rurą stelaża. Tylna rura bierze trochę więcej niż wagę obudowy, a śruba przez przednią rurę trzyma ramę, żeby przód się nie unosił. Przy kilkunastu kilogramach profil 2020 i śruba M5 to udźwigną.

## Lista cięć

Profil: aluminiowy konstrukcyjny **20×20, rowek 6 mm** (zwykły T-slot, nie V-slot). Srebrny anodowany wystarczy, pod biurkiem go nie widać.

Kup **5 m**: dwa odcinki po 2 m i jeden po 1 m. Na piłę zostaje zapas. Z 4 m nie zejdzie, bo cięcia zjadają kilka milimetrów i końce trzeba wyrównać.

Wersja 2, ta do złożenia:

| Sztuk | Długość | Co to jest |
| --- | --- | --- |
| 4 | 420 mm | słupki |
| 4 | 355 mm | dwie belki górne pod rurami i dwie poprzeczki pod obudową |
| 2 | 415 mm | belki boczne, na dole, wzdłuż głębokości |

Plan z odcinków:

- 2 m: 420 + 420 + 420 + 420
- 2 m: 415 + 415 + 355 + 355
- 1 m: 355 + 355

Wersja 1 ma inne tylko belki boczne: **2 × 470 mm** zamiast 415 mm. Z tych samych 5 m:

- 2 m: 420 + 420 + 420 + 420
- 2 m: 470 + 470 + 355 + 355
- 1 m: 355 + 355

Tnij prostopadle, sfazuj ostrą krawędź, opisz kawałki od razu. Cztery belki 355 mm są wymienne.

## Co kupić

Razem około **230–250 zł** przy tańszym profilu, albo około **320 zł**, jak profil weźmiesz z EBMiA. Do tego przesyłka, zwykle 15–30 zł, druga tyle samo, jeśli profile i drobnica idą z dwóch sklepów.

| Część | Ile | Cena | Na co |
| --- | --- | --- | --- |
| Profil 20×20, rowek 6 mm, 2×200 cm i 1×100 cm | 5 m | 120 zł | v-slot.pl: 47,88 zł za 200 cm, 23,94 zł za 100 cm. U EBMiA ten sam profil wychodzi około 37 zł/m, czyli około 185 zł za 5 m |
| Płytka łącząca, 2 otwory, pod M5 | 8 | 39 zł | v-slot.pl, 4,90 zł/szt. Słupek do belki |
| Kątownik 20×20 z zestawem (śruby i nakrętki w środku) | 4 | 24–30 zł | Fleximo: zestaw 4,84 zł netto, około 6 zł brutto. Leanflex: 7,49 zł brutto. Końce poprzeczek |
| Nakrętka teowa M5 z kulką, rowek 6 mm | 20 | 13 zł | abc-rc.pl, 6,50 zł za 10 szt. Potrzeba 16, cztery zostają |
| Śruba imbusowa M5×10 | 20 | 8–15 zł | paczka. Do płytek idzie 16 |
| Płaskownik aluminiowy 40×3 mm | 0,5 m | 15–30 zł | z niego cztery płytki 40×62 mm na rury biurka |
| Śruba M5×30, nakrętka, dwie podkładki | 2 zestawy | 5–10 zł | na wylot przez rury |

Kątownik z zestawu Fleximo i Leanflex jest na **śruby M4**, nie M5. Śrub z zestawu nie wymieniaj na M5: otwór w kątowniku jest pod M4. Do płytek zostają M5. Potrzebne są dwa klucze imbusowe, 3 mm i 4 mm.

Na start wystarczy jedna płytka na narożnik słupka. Druga, z przeciwnej strony, usztywnia ramę: to kolejne 8 płytek, 16 nakrętek i 16 śrub, około 50 zł. Do pierwszej sztuki nie jest potrzebna.

Pasek do asekuracji obudowy to osobne kilka–kilkanaście złotych. Rama trzyma bez niego.

## Jak to jest skręcone

Słupek do belki schodzi się **płaską płytką**. Równek dochodzi do samego cięcia, więc płytka łapie równek słupka i równek belki: dwie nakrętki teowe, dwie śruby M5×10.

- U góry płytka jest na przedniej ściance przedniej belki i na tylnej ściance tylnej belki. Na bocznej ściance, od nogi i od środka biurka, widać ucięte czoło belki, a czoło rówka nie ma.
- Na dole płytka jest na zewnętrznej ściance: od nogi na lewych słupkach, od środka biurka na prawych.

Poprzeczki, na których stoi obudowa, siadają końcem na belce bocznej. Tu jest **kątownik**. Jedna półka w rowku poprzeczki, druga w zewnętrznym rowku belki bocznej, poniżej spodu obudowy. Góra poprzeczki zostaje płaska, obudowa stoi na profilu.

Nakrętki teowe z kulką wsuwasz w równek od czoła, zanim zaślepisz koniec drugą belką. Zwykła nakrętka bez kulki też wejdzie, tylko łatwiej spadnie przy składaniu.

## Kolejność

1. Potnij profile i oznacz je.
2. Wsuń nakrętki w rówki, w miejscach płytek i kątowników. Na każdy łącznik dwie.
3. Złóż dolny prostokąt. Dwie belki boczne, na nich dwie poprzeczki: jedna pod przednim cokołem obudowy, druga pod tylnymi stopami. Końce poprzeczek skręć kątownikami. Między poprzeczkami zostaw pustkę. Tamtędy obudowa bierze powietrze od dołu.
4. Postaw cztery słupki i skręć je z belkami bocznymi płytkami.
5. Połóż dwie belki górne na słupkach, pod miejsce rur biurka, i skręć płytkami.
6. Wywierć rury stelaża. Nic nie wierć w blacie. Otwór Ø5,5 mm przez rurę 40×20, w połowie jej wysokości, czyli 20 mm poniżej spodu blatu. Na modelu jest to 430 mm od lewej krawędzi blatu, w obu rurach lewej strony. To ma być pusty odcinek rury, przed miejscem, w które wchodzi profil 30×15. Tego miejsca nie mierzyliśmy, w modelu wkładka wchodzi około 100 mm. Przed wierceniem sprawdź, czy rura w tym punkcie jest pusta. Jak trafisz we wkładkę, przesuń otwór w stronę nogi.
7. Z czterech kawałków płaskownika zrób płytki 40×62 mm. Otwór Ø5,5 mm w osi szerokości, 20 mm od górnej krawędzi. Górna krawędź dosunięta do spodu blatu. Na każdą rurę dwie płytki, z przodu i z tyłu, i jedna śruba M5×30 na wylot. Belka górna ma wejść między dolne końce płytek, równo pod rurą.
8. Wsuń obudowę od przodu, między słupki, aż cokół siądzie na przedniej poprzeczce, a tylne stopy na tylnej. Po bokach zostaje około 10 mm. Obudowy nie przykręcasz.

Lewa strona na modelu to ta przy nodze. Jak wolna noga biurka jest po prawej, całość odbij lustrzanie: 430 mm licz wtedy od prawej krawędzi blatu.
