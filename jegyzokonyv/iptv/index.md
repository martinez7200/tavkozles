# Digitális TV Vételi Rendszer Kiépítése - Jegyzőkönyv

**Vizsgázó neve**: [Neved]  
**Dátum**: [Dátum]  
**Vizsga helyszín**: [Helyszín]  
**Időtartam**: 120 perc

---

## 1. Előkészületek
- **Eszközök ellenőrzése**:
  - Antenna: [Megadott típus, pl. beltéri/kültéri]
  - Fejállomás: LEMCO SCL-824CT 8 × DVB-S/S2/T/T2/C to 4 × DVB-T/C & IP (FTA)
  - Set-top box: MAG IPTV
  - Hálózati eszköz: IGMP támogatású és DHCP képes router
  - Mérőműszer: METEK HDD digitális TV jelmérő
  - Koaxiális kábelek, csatlakozók, jelosztó, UTP kábelek
  - Szerelési eszközök: csavarhúzó, villáskulcs, kábelvágó, iránytű, dőlésszögmérő

- **Multiplex keresés**:  
  Az Avasi adótoronyból elérhető multiplexek és adatok lekérdezése az internetes adatbázisból:  
  - **Frekvencia**: [megadott frekvencia]  
  - **Teljesítmény**: [megadott teljesítmény]  
  - **Polarizáció**: [megadott polarizáció]  
  - **Adás típusa**: [DVB-T, stb.]

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
    - **Jelerősség (dBμV)**: [érték]  
    - **Jel-zaj viszony (SNR - dB)**: [érték]  
    - **Bit Error Rate (BER)**: [érték]  
    - **Modulation Error Ratio (MER - dB)**: [érték]  
    - **Csillapítás (dB)**: [érték]
  - **Antenna pozíciók és szögek**:  
    - **Polarizáció**: [érték]
  - **Időjárási körülmények**:  
    - Hőmérséklet: [érték]  
    - Szélsebesség: [érték]  
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

- **Jegyzőkönyv aláírása**:  
  A jegyzőkönyv aláírása és véglegesítése a mérési eredmények alapján.

---

Ez a jegyzőkönyv segíti a digitális TV vételi rendszer kiépítését, és biztosítja, hogy minden szükséges mérés és konfigurálás dokumentálásra kerüljön a rendszer megfelelő működésének érdekében.
