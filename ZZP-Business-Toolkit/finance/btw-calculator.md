# BTW Calculator (VAT Calculator)

## Doel
Een overzicht van je BTW-aangifte per periode (maand of kwartaal).
Gebruik dit in Google Sheets of Excel om te berekenen hoeveel BTW je moet betalen of terugkrijgt.

---

## Invoervelden (wat je invult)

| Veld | Beschrijving | Voorbeeld |
|------|--------------|-----------|
| **Periode** | Maand of kwartaal | [Q1 2025 (jan-feb-mrt)] |
| **Omzet excl. btw** | Totale omzet uit facturen (zonder BTW) | € [10.000,00] |
| **BTW-percentage** | Standaard 21% (of 9% / 0% indien van toepassing) | [21%] |
| **Voorbelasting** | Totaal BTW betaald op zakelijke kosten | € [500,00] |

---

## Berekening (logica)

1. **BTW verschuldigd** = Omzet excl. btw × BTW-percentage  
   Voorbeeld: € 10.000,00 × 21% = € 2.100,00

2. **BTW terug te vorderen** = Voorbelasting (BTW op kosten)  
   Voorbeeld: € 500,00

3. **BTW te betalen of te ontvangen** = BTW verschuldigd − BTW terug te vorderen  
   Voorbeeld: € 2.100,00 − € 500,00 = **€ 1.600,00 te betalen**

---

## Uitvoervelden (wat je ziet)

| Veld | Bedrag |
|------|--------|
| **BTW verschuldigd** | € [2.100,00] |
| **BTW terug te vorderen** | € [500,00] |
| **BTW te betalen** | **€ [1.600,00]** |

*Als het bedrag negatief is, krijg je BTW terug van de Belastingdienst.*

---

## Voorbeeld – Volledige berekening

### Periode: Q1 2025 (januari – maart)

| Invoer | |
|--------|---------|
| Omzet excl. btw | € 15.000,00 |
| BTW-percentage | 21% |
| Voorbelasting (kosten) | € 750,00 |

| Berekening | |
|------------|---------|
| BTW verschuldigd | € 15.000,00 × 21% = € 3.150,00 |
| BTW terug te vorderen | € 750,00 |
| **BTW te betalen** | **€ 3.150,00 − € 750,00 = € 2.400,00** |

---

## Notities

- **Dit is een overzichtstool, geen fiscaal advies**
- Controleer altijd je gegevens voordat je de BTW-aangifte doet
- Bewaar je data per kwartaal (Q1, Q2, Q3, Q4)
- Zorg dat je voorbelasting alleen zakelijke kosten bevat
- Bij twijfel: raadpleeg een boekhouder of de Belastingdienst

---

## Aangifte per kwartaal

In Nederland doen de meeste ZZP'ers BTW-aangifte per kwartaal:

| Kwartaal | Periode | Aangifte deadline |
|----------|---------|-------------------|
| Q1 | jan – mrt | [30 april] |
| Q2 | apr – jun | [31 juli] |
| Q3 | jul – sep | [31 oktober] |
| Q4 | okt – dec | [31 januari] |

*Check altijd de actuele deadlines op belastingdienst.nl*

---

## Tips

- Gebruik de expense-tracker.md om je voorbelasting automatisch bij te houden
- Doe je berekening vooraf, zodat je geen verrassingen krijgt
- Bewaar alle facturen (in- en uitgaand) digitaal voor minimaal 7 jaar
- Bij grote bedragen: reserveer geld op een aparte rekening voor de BTW
