## RAMriders – Hálózati vizsgaremek

Ez a repó a RAMriders csapat hálózati vizsgaremekéhez készült anyagokat tartalmazza.  
A projekt célja egy valós cég (CseGe Kft) hálózati infrastruktúrájának megtervezése, dokumentálása és Cisco Packet Tracer prototípus elkészítése.

## Branch-ek felépítése

- **main**:  
  - Áttekintő dokumentumok, prezentációk és a vizsgaremekhez kapcsolódó végleges anyagok.

- **documentations**:  
  - Részletes dokumentációk (DOCX, PPTX, XLSX, TXT), például:  
    - `Dokumentáció_Ramriders.docx` – a hálózati megoldás teljes leírása  
    - `Hálózat tesztelési séma.xlsx` – tesztterv és verifikáció  
    - `Konfigurációk.docx` – eszközkonfigurációk összegzése  
    - `CseGe Kft prototype.pptx` és `CseGe Kft prototype angol.pptx` – bemutató anyagok  
    - `Csegekft videó.txt` – a kísérő videóhoz kapcsolódó információk

- **cisco_prototype**:  
  - A Cisco Packet Tracer hálózati topológia fájl:  
    - `RAMriders CsegeKft prototype.pkt`

## Projekt áttekintés

- **Cél**: egy skálázható, biztonságos és jól dokumentált vállalati hálózat megtervezése CseGe Kft számára.  
- **Fő elemek**:
  - Topológia tervezés (routerek, switchek, VLAN-ok, IP-címzés)
  - Cisco Packet Tracer prototípus megvalósítás
  - Konfigurációk és tesztelési lépések részletes dokumentálása
  - Prezentációk és vizsgára kész anyagok elkészítése

## Használat

1. **Dokumentációk megtekintése**  
   - Válts a `documentations` branchre:  
     - `git checkout documentations`
   - Nyisd meg a számodra releváns DOCX, PPTX, XLSX vagy TXT fájlokat.

2. **Cisco hálózati prototípus megnyitása**  
   - Válts a `cisco_prototype` branchre:  
     - `git checkout cisco_prototype`
   - Nyisd meg a `RAMriders CsegeKft prototype.pkt` fájlt Cisco Packet Tracerben.

3. **Összefoglaló / prezentáció**  
   - A vizsgán bemutatáshoz használd a `documentations` branch prezentációs fájljait.

## Közreműködés

Ez a repó vizsgaremekhez készült, ezért a branch-struktúra és a fájlnevek szándékosan tükrözik a leadott anyagokat.  
Módosítás esetén érdemes:
- Új verzióról rövid leírást tenni a commit üzenetbe  
- A megfelelő branchet használni (`documentations` – dokumentáció, `cisco_prototype` – hálózati prototípus)
