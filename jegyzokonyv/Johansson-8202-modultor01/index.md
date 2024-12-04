
# MÉRÉSI JEGYZŐKÖNYV

**A mérést végző neve:**  Horváth Martin és Csépke Péter

**A mérés tárgya:** Távközlési Technika        

**A mérés száma:** 01

**A mérés dátuma:**   2024.12.04 

**Évfolyam:** 13. E  

**Csoport:** GYAK 2  

**Helyszín:** V3. Labor

---

## 1. Mérés célja
Cél: A tanulók megismerjék a Johansson 8202 DVB-T modulátor működését, konfigurációs lehetőségeit, és méréseket végezzenek a METEK HD spektrum/jelszint analizátorral. A mérési eredményeket rögzítik jegyzőkönyv formájában.

---
## 2. Menete
1. Előkészítettük a megfelelő műszereket a mérés végzéséhez;
2. Összecsatlakoztattuk a METEK HD spektrum/jelszint analizátort a Johansson 8202 hdmi modulátorral;
3. Beállítottuk a Johansson 8202 hdmi modulátort az adott frekvencia sávokra;
4. A METEK HD analizátorral rááltunk a modulátorral létrehozott sávokra;
5. Egy adott frekvencián három féle moduláció típust használtunk a jelszint, bitsebesség, MER érték meghatározására;
6. A kapott adatokat egy táblázatban összegyűjtöttük.

---

## 2. Alkalmazott mérőeszközök és készülékek

| Műszer neve                         | Típus       | Gyártási szám | Kép |
| ----------------------------------- | ----------- | ------------- |-----|
| Johansson Hdmi modulátor            | 8202        | 2341010237504 |---------|
| METEK HD spektrum/jelszint analizátor| 240002     | ...           |--------|
| Laptop | HP       | ...    |-----|

---

## 3. Adattáblázat: 

| Mérési paraméter    | RF Frekvencia (MHz) | Moduláció típusai   | Sávszélesség (MHz)  |Jelszint (dBm) |Bitsebesség (Mbps) |MER érték (dB) |
|---------------------|---------------------|---------------------|---------------------|---------------|-------------------|---------------|
|Mérési eredmény 1    |   212               |     64 QAM          |           7         |     -29.6     |      15.8         |    38.3       |
|Mérési eredmény 2    |   212               |     16 QAM          |           7         |     -29.4     |      7.8          |    36.4       |
|Mérési eredmény 3    |   212               |      QPSK           |           7         |     -29.4     |      3.7          |    39.9       |
| |
|Mérési eredmény 1    |       474           |     64 QAM          |           8         |      -31      |      18           |    36.8       |
|Mérési eredmény 2    |       474           |     16 QAM          |           8         |      -30.7    |      9.1          |    35.3       |      
|Mérési eredmény 3    |       474           |       QPSK          |           8         |      -30.4    |      4.2          |    39.4       |    
| |
|Mérési eredmény 1    |       546           |     16 QAM          |           8         |      -30.3    |      18.3         |    36.1       | 
|Mérési eredmény 2    |       546           |     16 QAM          |           8         |      -30.2    |      9.2          |    35.8       |
|Mérési eredmény 3    |       546           |      QPSK           |           8         |      -31      |      4.3          |    39.9       |



---

## 4. Mérések többféle modulációval:


---

## 5. Következtetések:

A mérések alapján megállapítható, hogy a 64-QAM moduláció a legmagasabb adatsebességet biztosít, viszont a jelkódolás minősége (MER) alacsonyabb, mint a kisebb modulációs rendeknél, mint például a 16-QAM és a QPSK. Ezzel szemben a QPSK moduláció kiváló MER értékeket mutatott, de a bitsebessége jelentősen alacsonyabb volt.

---


