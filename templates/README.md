# ZZP Starter Kit – Gebruikshandleiding
Deze handleiding legt stap voor stap uit hoe je de templates in dit pakket gebruikt.
Geen technische kennis nodig.

---

## Wat zit er in dit pakket?
Dit ZZP Starter Kit bevat praktische tools om je administratie en communicatie professioneel te regelen:

- Invoice templates (NL / EN)
- Offerte template
- Expense & BTW trackers
- Client tracker
- AI prompts voor e-mails, offertes en prijsafspraken

Alles is ontworpen voor ZZP'ers in Nederland.

---

## Hoe dit pakket te gebruiken

### Stap 1: Pak de ZIP uit
- Download het volledige ZZP Starter Kit
- Klik met rechtermuisknop en kies "Uitpakken" of "Extract"
- Bewaar de map op een vaste plek (bijv. Documenten/ZZP-Kit)

### Stap 2: Kies je werkwijze
Je hebt twee opties:
1. **Google Docs/Sheets** (online, automatisch opgeslagen)
2. **Microsoft Word/Excel** (lokaal op je computer)

Beide werken prima. Kies wat je prettig vindt.

---

## 1) Facturen maken (Invoices)
**Map:** `templates/invoices/`

### Stap voor stap:

#### A) Open de template
- Google: Upload naar Google Drive → Open met Google Docs
- Word: Dubbelklik op het bestand

#### B) Vul jouw bedrijfsgegevens in (eenmalig)
- Bedrijfsnaam
- KvK-nummer
- BTW-nummer (als je BTW-plichtig bent)
- Adres
- IBAN
- E-mail en telefoon

💡 **Tip:** Sla deze versie op als "Factuur Template - [Jouw Naam].docx"
Zo kun je hem steeds hergebruiken.

#### C) Vul per factuur in:
- **Factuurnummer** (bijv. 2025-001, 2025-002, etc.)
  - Houd een doorlopend nummer bij
  - Elk jaar opnieuw beginnen mag
- **Factuurdatum** (datum van vandaag)
- **Vervaldatum** (meestal +14 dagen)
- **Klantgegevens:**
  - Naam + bedrijf
  - Adres
  - KvK (als het een bedrijf is)
- **Omschrijving diensten:**
  - Wat heb je geleverd?
  - Per regel: omschrijving + aantal uur/stuks + tarief
- **Totaalbedrag:**
  - Subtotaal (excl. BTW)
  - BTW (21% voor de meeste diensten)
  - Totaal (incl. BTW)

#### D) Controleer voor je verstuurt:
- [ ] Facturnummer klopt en is uniek
- [ ] IBAN is correct
- [ ] Vervaldatum staat erbij
- [ ] BTW is goed berekend (21% in Nederland, tenzij vrijgesteld)
- [ ] Alle bedragen kloppen

#### E) Opslaan en versturen:
- Opslaan als PDF: Bestand → Exporteren als PDF (of Downloaden als PDF)
- Stuur de PDF naar je klant via e-mail
- Bewaar een kopie in je administratie (zie verderop)

---

## 2) Offertes maken (Quotations)
**Map:** `templates/offertes/`

### Stap voor stap:

#### A) Open de offerte template
- Zelfde werkwijze als bij facturen

#### B) Vul jouw gegevens in (eenmalig)
- Net als bij de factuur template

#### C) Vul de offerte in:
- **Offertenummer** (bijv. OFF-2025-001)
- **Datum**
- **Klantgegevens**
- **Projectnaam** (korte titel)
- **Omschrijving:**
  - Wat ga je doen?
  - Wat levert het op?
  - Hoe lang duurt het?
- **Scope (wat zit erin):**
  - Lijst met deliverables
  - Bijvoorbeeld: "2 ontwerpen, 1 revisieronde, oplevering in PDF"
- **Scope (wat zit er NIET in):**
  - Dit is belangrijk om miscommunicatie te voorkomen
  - Bijvoorbeeld: "Hosting en domeinnaam niet inbegrepen"
- **Planning:**
  - Startdatum
  - Opleveringsdatum
  - Eventuele mijlpalen
- **Prijs:**
  - Totaalprijs (excl. BTW)
  - BTW (indien van toepassing)
  - Totaal (incl. BTW)
- **Betaalvoorwaarden:**
  - Betaaltermijn (meestal 14 dagen)
  - Aanbetaling (optioneel, bijv. 50% vooraf)
- **Geldigheid:** Hoelang is de offerte geldig? (meestal 14 dagen)

#### D) Controleer:
- [ ] Scope is helder (wat wel/niet)
- [ ] Planning is realistisch
- [ ] Prijs is compleet (incl. BTW-berekening)
- [ ] Betaalvoorwaarden staan erbij

#### E) Versturen:
- Opslaan als PDF
- Stuur naar klant
- Bewaar een kopie

---

## 3) Uitgaven en BTW bijhouden (Expense & VAT Tracker)
**Map:** `templates/trackers/`

### Waarom belangrijk?
Als ZZP'er moet je:
- Je kosten bijhouden (voor belastingaangifte)
- BTW terugvragen op zakelijke uitgaven

Dit kan met een simpele spreadsheet.

### Stap voor stap:

#### A) Open de Expense Tracker
- Google Sheets of Excel

#### B) Vul per uitgave in:
- **Datum** (wanneer betaald)
- **Leverancier** (waar gekocht)
- **Omschrijving** (wat was het)
- **Bedrag excl. BTW**
- **BTW bedrag**
- **Bedrag incl. BTW**
- **Categorie** (bijv. kantoorbenodigdheden, software, reiskosten)
- **BTW-tarief** (21%, 9%, of 0%)

#### C) Bewaar bonnetjes
- Maak een foto of scan
- Bewaar digitaal in een map: "Bonnetjes 2025"
- Je moet bonnetjes 7 jaar bewaren (fiscale regel)

#### D) Update wekelijks of maandelijks
- Zo vergeet je niks
- Voor BTW-aangifte heb je alles op een rij

💡 **Tip:** Koppel je zakelijke bankrekening aan een boekhoudtool (bijv. Moneybird, Informer) om dit automatisch te laten gaan.

---

## 4) Klanten bijhouden (Client Tracker)
**Map:** `templates/trackers/`

### Stap voor stap:

#### A) Open de Client Tracker
- Spreadsheet met overzicht van al je klanten

#### B) Vul per klant in:
- **Naam klant / bedrijf**
- **Contactpersoon** (naam + functie)
- **E-mail en telefoon**
- **KvK-nummer** (voor facturen)
- **Eerste opdracht** (datum)
- **Laatste contact** (datum)
- **Status:**
  - Actief (lopend project)
  - Afgerond (project klaar)
  - Terugkerend (vaste klant)
  - Inactief (lang geen contact)
- **Totale omzet** (hoeveel hebben ze betaald)
- **Notities** (bijv. betalingsgedrag, voorkeuren)

#### C) Update regelmatig
- Na elk project
- Helpt om te zien: wie zijn je beste klanten?

💡 **Tip:** Check elke 3 maanden wie je lang niet hebt gesproken. Stuur een vriendelijke check-in mail (zie AI prompts).

---

## 5) AI Prompts gebruiken
**Map:** `ai-prompts/`

Dit zijn kant-en-klare prompts voor ChatGPT, Copilot of andere AI-tools.

### Hoe te gebruiken:

#### A) Kies een prompt
Bijvoorbeeld: "Eerste e-mail naar potentiële klant"

#### B) Kopieer de prompt
- Inclusief alle instructies

#### C) Vul placeholders in
- Alles tussen [ ] moet je aanpassen
- Bijvoorbeeld: [branche] → "webdesign"

#### D) Plak in ChatGPT/Copilot
- Klik op "Verzenden"
- AI schrijft een concept e-mail

#### E) Pas aan naar jouw stijl
- AI geeft een basis
- Maak het persoonlijk
- Controleer of het klopt

💡 **Waar vind je AI-tools:**
- ChatGPT: chat.openai.com (gratis versie beschikbaar)
- Microsoft Copilot: copilot.microsoft.com
- Claude: claude.ai

---

## 6) Administratie organiseren (Best Practices)

### Mappenstructuur (voorbeeld):
```
📁 ZZP Administratie 2025/
  📁 Facturen/
    📁 Verzonden/
    📁 Betaald/
    📁 Openstaand/
  📁 Offertes/
    📁 Verstuurd/
    📁 Akkoord/
    📁 Afgewezen/
  📁 Bonnetjes/
  📁 Contracten/
  📁 Klanten/
```

### Bewaartermijnen (Nederland):
- **Facturen:** 7 jaar
- **Bonnetjes:** 7 jaar
- **Contracten:** 7 jaar na einde contract
- **BTW-aangiftes:** 7 jaar

### Back-up:
- Bewaar alles digitaal (PDF + origineel)
- Maak back-ups (Google Drive, Dropbox, of externe harde schijf)
- Doe dit minimaal eens per maand

---

## 7) Veelgestelde vragen

### Moet ik BTW rekenen?
- Ja, als je omzet > € 20.000 per jaar (2025)
- Anders ben je "kleine onderneming" en mag je kiezen
- Check Belastingdienst.nl voor actuele regels

### Wat als ik geen BTW reken?
- Gebruik de factuur template zonder BTW-regel
- Vermeld op de factuur: "Geen BTW verschuldigd (kleine onderneming)"

### Hoe bepaal ik mijn uurtarief?
- Check de AI prompt: "ai-prompts/offertes-and-pricing.md"
- Prompt 1.1 helpt je een realistisch tarief te berekenen

### Wat als een klant niet betaalt?
- Check de AI prompts: "ai-prompts/client-emails.md"
- Prompts 6.1, 6.2, 6.3 voor betalingsherinneringen
- Na 3 herinneringen: overweeg incassobureau of rechtsbijstand

### Kan ik deze templates doorverkopen?
- Nee, dit is een commercieel product voor eigen gebruik
- Redistribution is niet toegestaan (zie LICENSE.md)

---

## Hulp nodig?
- Check de AI prompts voor specifieke situaties
- Raadpleeg Belastingdienst.nl voor fiscale vragen
- Overweeg een boekhouder in te schakelen voor het eerste jaar

**Succes met je ZZP-onderneming! 🚀**
