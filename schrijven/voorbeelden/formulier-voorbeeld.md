# Example: formulier invullen

**Situation**: Je meldt je aan voor een cursus Nederlands bij een taalschool. Vul het
inschrijfformulier in.

**Model (filled fields)**

| Veld | Invulling |
|---|---|
| Achternaam | De Vries |
| Voornaam | Anna |
| Geboortedatum | 15-01-1995 |
| Geboorteplaats | Warschau, Polen |
| Adres | Voorbeeldstraat 12 |
| Postcode / Woonplaats | 1234 AB, Amsterdam |
| Telefoonnummer | 06-12345678 |
| E-mailadres | a.devries@voorbeeld.nl |
| Datum | 19-08-2026 |
| Handtekening | A. de Vries |

**Reden van aanvraag (free-text box)**

> Ik vraag deze cursus aan omdat ik mijn Nederlands wil verbeteren voor mijn
> inburgeringsexamen. Ik hoop dat u mijn aanvraag snel kunt behandelen.

**Why this works**: every field answered directly (no blanks), reden box uses the fixed
mini-template from `zinnen.md`, date format matches Dutch convention (DD-MM-YYYY).
