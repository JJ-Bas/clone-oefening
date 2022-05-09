# Opdrachtbeschrijving

Tijd om te experimenteren met de kracht van pseudo-elementen. Je gaat onderstaande webpagina van een aantal handige trucjes voorzien.

![Screenshot](./assets/screenshot.png)

Bestudeer eerst de opbouw van het HTML-document goed voordat je aan de slag gaat. Let op: Je mag niets veranderen in de HTML behalve het eventueel toevoegen van `class`- of `id`-attributen.

## Opdracht 1: symbolen bijvoegen
De maker van deze webpagina licht iedere maand andere inspirerende complimenten uit in de blauwe blokken op de homepagina. Deze quotes staan er nu _hardcoded_ in, maar zullen in de toekomst worden opgehaald uit een database. Om duidelijk te maken dat het om quotes gaat, plaatsen we er op de webpagina aanhalingstekens (`" "`) omheen. Deze tekens willen we echter niet hoeven opslaan in de database. Daarom voegen we deze speciale tekens in, doormiddel van pseudo-elementen.

### Aanhalingstekens
Zorg ervoor dat de `<article class="compliment">`-tags worden voorzien van aanhalingstekens, door gebruik te maken van een `before` en `after` pseudo-element. Gebruik voor de aanhalingstekens de juiste [content-code](https://css-tricks.com/snippets/html/glyphs/#aa-special-characters):

![Glyph overview](./assets/content-code-css-tricks-table.png)
<sub>Bron: [CSS Tricks](https://css-tricks.com/snippets/html/glyphs/#aa-special-characters) </sub>

### Copyright
Zorg ervoor dat de tekst in de footer word voorzien van een copyright-teken. Gebruik hier een pseudo-element voor. Ben je opzoek naar de content-code? Deze kun je [hier](https://css-tricks.com/snippets/html/glyphs/#aa-latin-1-entity-set-for-html) opzoeken.


## Opdracht 2: tooltip
Maak met behulp van pseudo-elementen een tooltip (een soort praatwolkje) met daarin de tekst `Dit is een latijns woord`. Deze tooltip moet precies in het midden van de `<span class="highlight">`-tag zweven. De tooltip mag alleen verschijnen als de gebruiker met de muis over het woord beweegt. Tip: zorg ervoor dat de tooltip ook in het midden van het woord zal blijven staan als het woord ineens twee keer zo lang blijkt te zijn, zoals `hottentottententententoonstelling`.
