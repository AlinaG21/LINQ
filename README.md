# LINQ
1. LINQ - Language-Integrated Query is a powerful query language introduced with .Net 3.5 & Visual Studio 2008. LINQ can be used with C# or Visual Basic to query different data sources.
2. mida tähendab märk: => - Anonüümse funktsiooni loomiseks kasutate lambda väljendit. Kasutage lambda deklaratsiooni operaatorit =>, et eraldada lambda parameetrite loend selle kehast.
3. Where - Üldise definitsiooni klausel kus määrab piirangud tüüpidele, mida kasutatakse tüübi parameetrite argumendina üldise tüübi, meetodi, delegeerija või kohaliku funktsiooni korral. Piirangud võivad määrata liidesed, baasklassid või nõuda, et üldine tüüp oleks viide, väärtus või haldamata tüüp. Nad deklareerivad võimeid, mis tüübi argumendil peavad olema.
4. OfType - Operatsiooni kasutatakse väljundjärjestuse koostamiseks, mis sisaldab ainult neid elemente, mida saab edukalt teisendada määratud tüübiks.
5. ThenBy - Operatsioon ThenBy võimaldab teil tellida sisestusjärjestuse tüübi IOrderedEnumerable <T>, mis põhineb võtme väärtuse tagastaval keySelector meetodil. Tulemuseks on järjestatud tüüp IOrderedEnumerable <T>.
6. GroupBy, ToLookUp - Grupeerimis Operatsioonid aitavad järjestuse üksusi ühise võtme abil ühendada. Operatsiooni GroupBy kasutatakse sisend järjestuse elementide rühmitamiseks.
7. Join - Operatsioon teostab kahe järjestuse sisemise samaväärsuse ühendamise nende järjestuste igast elemendist eraldatud võtmete põhjal.
8. GroupJoin - Operatsioon teostab kahe järjestuse hulgi ühendus, mis põhineb järjestuste igast elemendist eraldatud võtmetel.
9. Select - Toimingut kasutatakse ühte tüüpi elementide väljund järjestuse loomiseks teist tüüpi elementide sisend järjestusest. Need tüübid ei pea olema ühesugused.
10. All, Any - Operatsioon tagastatakse tõesena, kui mõni sisendada elementidest vastab tingimusele.
11. Contains - Toiming tagastatakse tõene, kui sisend järjestuse mõni element vastab määratud väärtusele.
12. Aggregate - Operatsioon täidab sisestatud jada iga elemendi jaoks kasutaja määratud funktsiooni, edastades selle funktsiooni tagastatud väärtuse eelmise elemendi jaoks ja tagastades selle väärtuse viimase elemendi jaoks.
13. Average - Operatsioon tagastab sisend jada elementide arv väärtuste aritmeetilise keskmise.
14. Count - Toiming tagastab sisend järjestuses olevate elementide arvu.
15. Max - Toiming tagastab sisend järjestusest maksimaalse väärtuse.
16. Sum - Operatsioon tagastab jada elementides sisalduvate arvväärtuste summa.
17. ElementAt, ElementAtOrdefault - Operatsioon tagastab määratud indeksis oleva elemendi algsest järjestusest ja operatsioon tagastab algsest järjestusest elemendi määratud asukoha indeksis
18. First, FirstOrDefault - Operatsioon tagastab predikaadile vastava jada esimese elemendi või järjestuse esimese elemendi, sõltuvalt kasutatud prototüübist ja toiming sarnaneb kõigega kõigiga, välja arvatud käitumine, kui elementi ei leita.
19. Last, LastOrDefault - Operatsioon tagastab jada viimase või predikaadile vastava elemendi, sõltuvalt kasutatud prototüübist ja operatsioon LastOrDefault on igas mõttes sarnane Last, välja arvatud käitumine, kui üksust ei leita.
20. Single, SingleOrDefault - Operatsioon tagastab predikaadile vastava järjestuse ühe elemendi või järjestuse ühe elemendi, sõltuvalt kasutatud prototüübist ja operatsioon SingleOrDefault sarnaneb Single-ga, kuid käitub teistsugusel viisil, kui üksust ei leita.
21. SequenceEqual - Operatsioon määrab, kas kaks sisend järjestust on samaväärsed.
22. Concat - Toiming ühendab kaks sisend järjestust ja annab ühe väljundi järjestuse.
23. Default Empty - Operatsioon tagastab vaikelementi sisaldava järjestuse, kui sisend järjestus on tühi.
24. Empty, Range, Repeat - Toiming Range genereerib täisarvude jada ja toiming Repeat genereerib järjestuse, korrates määratud elementi mitu korda ja toiming Empty genereerib määratud tüüpi tühja jada.
25. Distinct - Operatsioon eemaldab duplikaat elemendid sisend järjestusest.
26. Except - Toiming tagastab jada, mis sisaldab kõiki esimese jada elemente, mis pole teises jadas.
27. Intersect - Operatsioon tagastab kahe algse järjestuse komplektide ristumiskoha.
28. Union - Operatsioon tagastab hulga ühenduse kahest algest järjestusest.
29. Skip, SkipWhile - Toiming jätab sisestatud järjestusest määratud arvu elemente vahele, alustades selle algusest, ja ülejäänud osa prinditakse ja operatsioon SkipWhile töötleb sisend järjestust, jättes elemendid vahele, kuni tingimus on tõene, ja väljastab seejärel ülejäänud osa väljund järjestusse.
30. Take, TakeWhile - Toiming tagastab sisestatud järjestusest määratud arvu elemente, alustades algusest ja tagastab elemendid sisend järjestusest seni, kuni mõni tingimus on tõene, alustades jada algusest. Ülejäänud sisend elemendid jäetakse vahele.

