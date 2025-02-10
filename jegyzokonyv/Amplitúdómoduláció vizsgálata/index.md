# Jegyzőkönyv: Amplitúdómoduláció (AM) vizsgálata a GRF-1300A trénerrel
**Vizsgázó neve**: Horváth Martin   
**Dátum**: 2025.02.03   
**Vizsga helyszín**: V3  
**Időtartam**: 60 perc  

---

## Feladat:
A cél az amplitúdómoduláció (AM) előállítása a GRF-1300A RF és kommunikációs tréner használatával. A vizsgálat során beállítjuk a megfelelő RF vivőfrekvenciát, moduláló jelet, majd megvizsgáljuk az AM jel spektrumát, mérjük a jelszintet, a sávszélességet és a modulációs mélységet.

---

## Használt eszközök:
- **GRF-1300A RF és kommunikációs tréner**  
- **GSP-730 Spektrumanalizátor (a tréner része)**    

- **Jelgenerátor (moduláló jel előállításához)**

<details> 
   <summary>Képek</summary>
   <img src="https://martinez7200.github.io/tavkozles/jegyzokonyv/Amplitúdómoduláció vizsgálata/grf-1300a.jpg"/>
   <img src="https://martinez7200.github.io/tavkozles/jegyzokonyv/Amplitúdómoduláció vizsgálata/hmo1002-hero-1200x735-White-b.jpg"/>
</details> 

---

## Beállítások:

1. **Vivőfrekvencia beállítása:**
   - A GRF-1300A tréneren beállítottuk az RF vivőfrekvenciát elöször : **880 MHz**,**900 MHz**.
     
2. **Moduláló jel beállítása:**
   - Állítsuk be a moduláló jelet, amely egy **1 kHz szinuszjel** lesz.

3. **Jelgenerátor csatlakoztatása:**
   - A jelgenerátor segítségével biztosítsuk, hogy a moduláló jel (1 kHz szinuszjel) a GRF-1300A tréner bemenetére kerüljön.

4. **Moduláció beállítása:**
   - Aktiváljuk az amplitúdómoduláció (AM) üzemmódot a tréneren, és csatlakoztassuk a moduláló jelet.

5. **Spektrumanalizátor csatlakoztatása:**
   - A GRF-1300A RF kimenetét csatlakoztassuk a spektrumanalizátorhoz, hogy megfigyelhessük a generált AM jel spektrumát.

---

## Mérések és elemzés:

1. **Jelszint mérése:**
   - Mérjük meg a generált AM jel jelszintjét a spektrumanalizátor segítségével. A spektrumon figyeljük meg a vivőfrekvenciát és a mellékcsúcsokat.
   - A jelszintet dB-ben mérjük, és rögzítjük a spektrumanalizátor kijelzőjén található értéket.

2. **Spektrumkép mentése és kiértékelése:**
   - A spektrumanalizátor segítségével készítsünk egy spektrumképet a mérésről, amely tartalmazza a vivőfrekvenciát, a mellékcsúcsokat, és a modulált jel viselkedését.
   - Mentjük el a spektrumképet, majd elemezzük a következőket:
     - Vivőfrekvencia helyzete.
     - Mellékcsúcsok helyzete és azok erősségei.

3. **Modulációs mélység meghatározása:**
   - A modulációs mélység meghatározása az amplitúdómodulált jel hullámformájának és a vivője közötti amplitúdóváltozáson alapul.
   - Mérjük meg a legnagyobb és a legkisebb amplitúdó értékeket, majd számoljuk ki a modulációs mélységet a következő képlettel:
     \[
     \text{Modulációs mélység} = \frac{A_{max} - A_{min}}{A_{max} + A_{min}} \times 100 \%
     \]
     ahol \( A_{max} \) és \( A_{min} \) a maximális és minimális amplitúdó értékek.

4. **Sávszélesség meghatározása:**
   - A sávszélességet a spektrumkép alapján mérhetjük. A modulált jel sávszélessége a mellékcsúcsok közötti távolság alapján meghatározható.
   - A mérés során figyeljük meg a két első mellékcsúcs közötti frekvenciát, és ennek alapján számoljuk ki a sávszélességet.

---

## Összegzés:
A kísérlet során sikerült előállítani az amplitúdómodulált jelet a GRF-1300A tréner segítségével, és megvizsgáltuk annak spektrumát. A jelszintet, modulációs mélységet és sávszélességet mérve részletes információkat kaptunk az AM jel viselkedéséről. A mérési adatok alapján meghatároztuk a modulációs mélységet és a sávszélességet, amely segít a moduláció hatékonyságának kiértékelésében.

---

## Mérési adatok:
- **Vivőfrekvencia:** 900 MHz
- **Moduláló jel:** 1 kHz szinuszjel
- **Jelszint:** [érték]
- **Modulációs mélység:** [érték] %
- **Sávszélesség:** [érték] Hz

---

A mérési feladatok sikeresen elvégezve, a kísérlet eredményei alapján az AM moduláció jellemzői egyértelműen meghatározhatók.

