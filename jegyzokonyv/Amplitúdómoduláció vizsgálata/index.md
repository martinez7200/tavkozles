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
  <br><img width="200" src="https://martinez7200.github.io/tavkozles/jegyzokonyv/Amplitúdómoduláció vizsgálata/grf-1300a.jpg"/>
- **GSP-730 Spektrumanalizátor (a tréner része)**
  <br><img width="200" src="https://martinez7200.github.io/tavkozles/jegyzokonyv/Amplitúdómoduláció vizsgálata/hmo1002-hero-1200x735-White-b.jpg"/>
- **Jelgenerátor (moduláló jel előállításához)**
   
  


---

## Beállítások:
## Első mérés

1. **Vivőfrekvencia beállítása:**
   - A GRF-1300A tréneren beállítottuk az RF vivőfrekvenciát elöször :**880 MHz**
                                                                      
2. **Moduláló jel beállítása:**
   - Állítsuk be a moduláló jelet, amely egy **100 kHz szinuszjel** lesz.
     
3. **Modulációs mélység:**  
   - 100% modulácós mélységet beállítottuk 63%-ra.

## Második mérés
1. **Vivőfrekvencia beállítása:**
   - A GRF-1300A tréneren beállítottuk az RF vivőfrekvenciát elöször :**880 MHz**
                                                                      
2. **Moduláló jel beállítása:**
   - Állítsuk be a moduláló jelet, amely egy **100 kHz szinuszjel** lesz.
     
3. **Modulációs mélység:**  
   - 100% modulácós mélységet beállítottuk 63%-ra.



---
## Eredmények
**880 MHz-nél**  

<img width="500" src="https://martinez7200.github.io/tavkozles/jegyzokonyv/Amplitúdómoduláció vizsgálata/SCR00.BMP"/>

<img width="500" src="https://martinez7200.github.io/tavkozles/jegyzokonyv/Amplitúdómoduláció vizsgálata/TA01.PNG"/>

**900 MHz-nél**  

<img width="500" src="https://martinez7200.github.io/tavkozles/jegyzokonyv/Amplitúdómoduláció vizsgálata/SCR01.BMP"/>

<img width="500" src="https://martinez7200.github.io/tavkozles/jegyzokonyv/Amplitúdómoduláció vizsgálata/TA02.PNG"/>




---

## Mérések és elemzés:
<details>

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
   - A mérés során figyeljük meg a két első mellékcsúcs közötti frekvenciát, és ennek alapján számoljuk ki a sávszélességet.</details>

---

## Összegzés:
A kísérlet során sikerült előállítani az amplitúdómodulált jelet a GRF-1300A tréner segítségével, és megvizsgáltuk annak spektrumát. A jelszintet, modulációs mélységet és sávszélességet mérve részletes információkat kaptunk az AM jel viselkedéséről. A mérési adatok alapján meghatároztuk a modulációs mélységet és a sávszélességet, amely segít a moduláció hatékonyságának kiértékelésében.

---

## Mérési adatok:
- **Vivőfrekvencia:** 880 MHz
- **Moduláló jel:** 100 kHz szinuszjel
- **Jelszint:** [érték]
- **Modulációs mélység:** 6 dB
- **Sávszélesség:**  30 KHz
- **Span:** 5 MHz
- **Vpp:** 1.24V
  
- **Vivőfrekvencia:** 900 MHz
- **Moduláló jel:** 500 kHz szinuszjel
- **Jelszint:** [érték]
- **Modulációs mélység:** 10 dB
- **Sávszélesség:** 30 KHz
- **Span:** 5 MHz
- **Vpp:** 1.19V

---

A mérési feladatok sikeresen elvégezve, a kísérlet eredményei alapján az AM moduláció jellemzői egyértelműen meghatározhatók.

