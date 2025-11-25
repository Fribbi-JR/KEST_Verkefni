## 1. Hvað gera eftirfarandi Linux skipanir?
**cd** – fer í aðra möppu (change directory).  
**ls** – sýnir skrár og möppur þar sem þú ert staddur.  
**pwd** – sýnir slóðina að möppunni sem þú ert í (print working directory).  
**mkdir** – býr til nýja möppu.

## 2. Hvað gera eftirfarandi Git skipanir?
**git clone** – afritar Git geymslu á nýtt vinnusvæði, allar skráningar fylgja með.
**git status** – Sýnir stöðu HEAD, td. hvaða skrár eru óskráðar (untracked), hvaða skrám hefur verið breytt eða eytt. Eftir að hafa sviðsett (add to stage) skrárnar þarf að skrá þær (commit) í vinnuskrána (Working Directory). 
**git diff** – Sýnir breytingar sem þú ert að vinna í frá síðustu skráningu (commit).

## 3. Hvað gera eftirfarandi skipanir saman og af hverju eru þær gagnlegar?
**git log** – Sýnir lista yfir allar skráningar (commit) sem gerðar hafa verið í greininni sem HEAD bendir á.
**git checkout** – Fylgist með stöðunni og skráir í vinnuskrána.  
**git branch** – Sýnir lista yfir allar staðtengdar (local) greinar.

**Gagn:** Þær leyfa að skoða útgáfusögu, hoppa í eldri útgáfur, vinna á greinum og skipuleggja verkefnið án þess að skemma main.

## 4. Hvað er útgáfustýring (Version Control)?
Kerfi sem geymir breytingar á skrám yfir tíma, gerir mörgum kleift að vinna saman og leyfir að fara til baka ef mistök gerast.

## 5. Helstu kostir við Git:
- Heldur utan um alla sögu breytinga.  
- Auðvelt að vinna margir saman.  
- Auðvelt að búa til greinar og prófa hluti.  
- Hægt að fara til baka í eldri útgáfur.  
- Öruggt þegar ýtt er á GitHub.

## 6. Hversu oft á að gera commit?
Mjög oft — í hvert skipti sem þú gerir breytingu.  

## 7. Hvað er “Working Directory” og “Staging Area” í Git?
**Working Directory:** Þar sem þú ert að vinna í skránum á tölvunni.  
**Staging Area:** Staðurinn sem skrár fara í þegar þú notar *git add* áður en þær eru commit-aðar.

