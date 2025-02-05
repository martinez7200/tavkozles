# Digitális TV Vételi Rendszer Kiépítése - Jegyzőkönyv

**Vizsgázó neve**: Horváth Martin   
**Dátum**: 2025.02.03   
**Vizsga helyszín**: V3  
**Időtartam**: 120 perc  

---

## 1. Előkészületek
- **Eszközök ellenőrzése**:
  - Antenna: [Iscar UHF TV Antenna P-2845, kültéri]
  - Fejállomás: LEMCO SCL-824CT 8 × DVB-S/S2/T/T2/C to 4 × DVB-T/C & IP (FTA)
  - Set-top box: MAG IPTV
  - Hálózati eszköz: IGMP támogatású és DHCP képes router (Tp link archer c7)  
  - Mérőműszer: METEK HDD digitális TV jelmérő
  - Koaxiális kábelek, csatlakozók, jelosztó, UTP kábelek
  - Szerelési eszközök: csavarhúzó, villáskulcs, kábelvágó, iránytű, dőlésszögmérő

- **Multiplex keresés**:  
  Az Avasi adótoronyból elérhető multiplexek és adatok lekérdezése az internetes adatbázisból:  
  - **Frekvencia**: [634 MHz]  
  - **Teljesítmény**: [megadott teljesítmény]  
  - **Polarizáció**: DNY: 234°  
  - **Adás típusa**: DVB-T

---

## 2. Antenna felszerelése és beállítása

- **Antenna kiválasztása**:  
  - [Beltéri vagy kültéri antenna választása]
  - **Kültéri antenna rögzítése**:  
    Stabil rögzítés tripodra.
  - **Beltéri antenna elhelyezése**:  
    Helyes pozíció kiválasztása az optimális vétel érdekében.

- **Antenna beállítása**:  
  - Használt eszközök: iránytű, dőlésszögmérő.
  - A megfelelő irányba történő beállítás (Avasi adótoronyra).
  - **Finomhangolás**:  
    METEK HDD mérőműszerrel.

---

## 3. Kábelezés és mérési pontok kialakítása

- **Koaxiális kábelezés**:  
  Csatlakoztatás az antennához és a fejállomáshoz.
- **Jelosztó beépítése**:  
  Helyes elosztás biztosítása a fejállomás bemeneti jeleihez.
- **Mérés és elosztás**:  
  A különböző multiplexek megfelelő bemenetekhez rendelése a fejállomásban.

---

## 4. Fejállomás beállítása és IPTV stream konfigurálása

- **Fejállomás konfigurálása**:  
  - Minden bemenetre multiplex hozzárendelése.  
  - DVB-T jelek szabadon fogható (FTA) módon történő feldolgozása és IP streamre konvertálása.
  - **Multicast IP tartomány beállítása**:  
    A megfelelő IP tartomány kiválasztása az IPTV csatornákhoz.

- **IPTV Set-top-box konfigurálása**:  
  - DHCP szerver és IGMP konfigurálása a routeren.
  - Multicast IP címek hozzáadása a csatornalistához.
  - **IPTV stream keresése**:  
    A Set-top-box csatornakeresése és ellenőrzése.

---

## 5. Jelszintmérés és dokumentáció

- **Antenna mérése**:
  - **Spektrum analizátor**: Kép rögzítése.
  - **Jelszint és jelminőség mérés**:  
    - **Jelerősség (dBμV)**: [51dB]  
    - **Jel-zaj viszony (SNR - dB)**: [érték]  
    - **Bit Error Rate (BER)**: [érték]  
    - **Modulation Error Ratio (MER - dB)**: [25dB]  
    - **Csillapítás (dB)**: [érték]
  - **Antenna pozíciók és szögek**:  
    - **Polarizáció**: [DNY:234°]
  - **Időjárási körülmények**:  
    - Hőmérséklet: [5°C]  
    - Szélsebesség: [3,2m/s]  
    - Egyéb megjegyzések: [ha releváns]

- **Fejállomás mérése**:  
  - **IPTV stream stabilitása**:  
    - Multicast IP címek ellenőrzése.
    - **Hálózati késleltetés és csomagvesztés**:  
      - **Ping teszt**: [eredmény]  
      - **Traceroute**: [eredmény]
    - **Wireshark és TShark elemzés**:  
      A stream elemzése, csomagvesztés vizsgálata.
      - **FFmpeg elemzés**:  
        - Bitráta, késleltetés, csomagvesztés mérése.
          <details>
          <img src="https://martinez7200.github.io/tavkozles/jegyzokonyv/iptv/Képernyőkép 2025-02-04 084129.png"/>
          <img src="https://martinez7200.github.io/tavkozles/jegyzokonyv/iptv/Képernyőkép 2025-02-04 084154.png"/>
          </details> 
---

## 6. Eredmények és Jegyzőkönyv

- **Mérések dokumentálása**:  
  A mérési eredmények és az eszközök beállításainak rögzítése a jegyzőkönyvben:
  - Jelerősség (dBμV): [érték]
  - Jel-zaj viszony (SNR - dB): [érték]
  - Bit Error Rate (BER): [érték]
  - Modulation Error Ratio (MER - dB): [érték]
  - Csillapítás (dB): [érték]
  - Lock állapot: [ ] Igen [ ] Nem
  - Hőmérséklet és időjárási körülmények: [értékek]
  - Multiplex adatok és frekvenciák: [értékek]

---
| Programs | Input   | Program title            | OriginalService ID | LCN1..1023 | Encrypted | TS Output | OutputService ID | IP address  | IP port | Protocol |
|----------|---------|--------------------------|--------------------|------------|-----------|-----------|------------------|-------------|---------|----------|
| 1        | Input 1 | M1 HD                    | 100                | 0          | FTA       | 1         | 100              | 239.1.1.1   | 10001   | UDP      |
| 2        | Input 1 | M4 Sport HD              | 101                | 0          | FTA       | 1         | 101              | 239.1.1.1   | 10002   | UDP      |
| 3        | Input 1 | Duna HD                  | 102                | 0          | FTA       | 1         | 102              | 239.1.1.1   | 10003   | UDP      |
| 4        | Input 1 | DunaW/M4Sport+           | 103                | 0          | FTA       | 2         | 103              | 239.1.1.1   | 10004   | UDP      |
| 5        | Input 1 | Kossuth Radio            | 130                | 0          | FTA       | 4         | 130              | 239.1.1.1   | 10005   | UDP      |
| 6        | Input 1 | Petofi Radio             | 131                | 0          | FTA       | 4         | 131              | 239.1.1.1   | 10006   | UDP      |
| 7        | Input 1 | Bartok Radio             | 132                | 0          | FTA       | 4         | 132              | 239.1.1.1   | 10007   | UDP      |
| 8        | Input 1 | Danko Radio              | 133                | 0          | FTA       | 4         | 133              | 239.1.1.1   | 10008   | UDP      |
| 10       | Input 2 | M2 HD                    | 200                | 0          | FTA       | 1         | 200              | 239.1.1.1   | 10009   | UDP      |
| 11       | Input 2 | M5 HD                    | 201                | 0          | FTA       | 2         | 201              | 239.1.1.1   | 10010   | UDP      |
| 12       | Input 2 | TV2                      | 202                | 0          | FTA       | 1         | 202              | 239.1.1.1   | 10011   | UDP      |
| 13       | Input 2 | RTL                      | 203                | 0          | FTA       | 1         | 203              | 239.1.1.1   | 10012   | UDP      |
| 14       | Input 2 | MAX4                     | 206                | 0          | FTA       | 2         | 206              | 239.1.1.1   | 10013   | UDP      |
| 15       | Input 2 | Spektrum Home +          | 207                | 0          | FTA       | 2         | 207              | 239.1.1.1   | 10014   | UDP      |
| 16       | Input 2 | MinDig TV Plusz Info     | 208                | 0          | FTA       | 2         | 208              | 239.1.1.1   | 10015   | UDP      |
| 37       | Input 3 | HEVC teszt               | 524                | 0          | FTA       | 2         | 524              | 239.1.1.1   | 10016   | UDP      |
| 39       | Input 4 | Miskolc TV               | 1000               | 0          | FTA       | 2         | 1000             | 239.1.1.1   | 10017   | UDP      |

- **Jegyzőkönyv aláírása**:  
  A jegyzőkönyv aláírása és véglegesítése a mérési eredmények alapján.

---

Ez a jegyzőkönyv segíti a digitális TV vételi rendszer kiépítését, és biztosítja, hogy minden szükséges mérés és konfigurálás dokumentálásra kerüljön a rendszer megfelelő működésének érdekében.
