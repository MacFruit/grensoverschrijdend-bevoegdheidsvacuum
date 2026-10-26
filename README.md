# GRENSARBEID.ORG — Systeem-Audit
## Grensoverschrijdend bevoegdheidsvacuüm in de sociale zekerheid

> **Geen adviesloket en geen pleister op een vastgelopen formulier.** Deze site toont aan de hand van één volledig gedocumenteerd dossier (62 instanties, meer dan 680 handelingen) hoe de Belgische en Nederlandse systemen achter de schermen werkelijk op elkaar inwerken — waar ze blokkeren, waarom brieven elkaar tegenspreken, en welke hefbomen wél werken.

---

### Kerncijfers van het dossier

- **62 betrokken organisaties** (België, Nederland, Membraan/Grensoverschrijdend, Europese Unie)
- **682 geregistreerde interacties** in Document B (vanaf 10-03-2025 tot heden)
- **93% primair bron-gekoppeld (633 interacties)**: voorzien van verifieerbare primaire bewijsreferenties (`data-gmail-id` Message-ID's en `data-file-path` archiefstukken)
- **12 grote visuele architectuurplaten** in Document C: visuele beeldschema's van de fricties en datastromen
- **13 synthetische hoofdstukken** in Document D: incl. Deel XII (De AVG-stresstest en het EESSI-spook van 2030) en Deel XIII (De persoonlijke slotverklaring)
- **17 sociale rechten** geanalyseerd en gevolgd op actuele uitvoeringsstatus in Document E

---

### De zes documenten

| Document | Titel | Inhoud |
|---|---|---|
| **0** | Inleiding en leeswijzer | Biografisch essay over drie generaties grensarbeid, plus leesroutes |
| **A** | De narratieve audit | Het verhaal per organisatie, in doorlopende tekst (met directe kruisverwijzing naar Document B) |
| **B** | De data-matrix | Alle feiten: datums, referentienummers, correspondentie, tijdlijnen en interactieve bewijs-badges |
| **C** | De visuele architectuur | 12 visuele beeldschema's en datastromen — het bevoegdheidsvacuüm in één oogopslag |
| **D** | De synthese | 13 delen: patronen, paradoxen, de AVG-stresstest (Deel XII) en slotverklaring (Deel XIII) |
| **E** | Het rechtenoverzicht | Per recht: wat het is, wie het krijgt, waar het vastloopt, actuele status en financiële impact |

---

### Twee-Poorts Startportaal & Meertalige Architectuur

1. **Startportaal (`index.html`)**:
   - **Poort 1 (Nederland / België)**: Directe toegang tot de authentieke Nederlandstalige hoofdsite (`nl/home.html`) met alle 6 documenten inclusief officiële Word- (`.docx`) en PDF-downloads.
   - **Poort 2 (Europees & Internationaal Portaal)**: Directe toegang tot het Europese portaal (`home_int.html`) met live vertaling van alle 6 documenten.
2. **Ingebouwde Client-Side Vertaalengine**:
   - Automatische detectie van de browsertaal (`navigator.languages`).
   - Directe taalschakelaar bovenin de navigatiebalk voor 11+ talen (o.a. `NL`, `EN`, `DE`, `FR`, `IT`, `ES`, `PL`, `DA`, `SV`, `PT`, `RO`).
   - Behoudt de gekozen taal synchroon over alle pagina's en bij terugkeren met de browsergeschiedenis (`pageshow` / `sessionStorage`).
3. **Print / Opslaan als PDF**:
   - Geoptimaliseerde `@media print` A4-lay-out voor alle documenten in elke gekozen taal.
   - Vertaaldisclaimer blijft netjes bewaard bovenaan de afgedrukte PDF; donkere modus schakelt automatisch om naar helder wit papier.

---

### Forensische en interactieve functies

1. **Interactief Bronopvragings- en Contactvenster (Modal `#bm-modal`)**:
   - Elke bewijs-badge (`[Mail] #...` / `[Doc] ...`) in Document B is direct klikbaar.
   - Klikken op een badge extraheert automatisch de organisatie, datum, titel en referentiecodes, en opent een gestructureerd contactvenster.
   - Keuze uit vier perspectieven (*Lotgenoot/Grensarbeider*, *Wetenschap/Beleidsonderzoek*, *Journalistiek/Media*, *Juridisch/Toezichthouder*).
   - Direct versturen via e-mailprogramma (`mailto:systeemaudit@gmail.com`) of kopiëren naar het klembord met één klik.
   - Direct toegankelijk via de knop `📄 Bronstuk opvragen / Contact` in de navigatiebalk en footer van elk document.
2. **Forensische werkbalk in Document B**: Real-time filteren op trefwoord, datum, IN/UIT, kernfeiten, en directe sprong naar elk van de 62 organisaties.
3. **100% Responsief voor smartphone, tablet en desktop**:
   - Geoptimaliseerde typografie, touch-targets van minimaal 38px en horizontale swipe-containers voor brede tabellen.
   - Inputvelden afgestemd op iOS om ongewenst inzoomen te voorkomen (`font-size: 16px`).
   - Standaard voorzien van een hoogwaardige donkere modus (`Dark Mode`) met themageheugen (`localStorage`).

---

### Taalversies & Disclaimers

- **Nederlands (`nl/`)**: De enige authentieke brontaal van deze Systeem-Audit. In geval van twijfel of juridische interpretatie is uitsluitend de Nederlandse brontekst leidend en gezaghebbend.
- **Internationaal (`home_int.html`) & Vertaalde weergaven**: Bieden geautomatiseerde, live vertalingen van alle 6 documenten (`0`, `A`, `B`, `C`, `D`, `E`) om de gedocumenteerde grensoverschrijdende mechanismen pan-Europees toegankelijk te maken.

---

### Licentie & Auteursrecht

- **Tekst en SVG-schema's**: Creative Commons Naamsvermelding 4.0 Internationaal ([CC BY 4.0](LICENSE.txt)).
- Vrij te gebruiken voor journalistiek, wetenschappelijk onderzoek, beleidsanalyse en onderwijs mits correcte bronvermelding.
- **Auteur**: Eric Messa (in lopende teksten neutraal aangeduid in de 3e persoon: *de betrokkene*).

---

### Contact

Voor vragen over de onderliggende bewijsstukken, verificatie of inzage in brondossiers:
📧 **systeemaudit@gmail.com**
