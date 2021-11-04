
# Rapportage webtoegankelijkheid-test voor de OBA
*Dit document is een template voor een webtoegankelijkheid-test volgens de Web Content Accessibility Guidelines (WCAG). Een consistente rapportage helpt bij het uitvoeren van een evaluatie en zorgt er voor dat verschilelnde tests kunnen worden vergeleken.*
Datum webtoegankelijkheid-test: {datum}
Webtoegankelijkheid-test uitgevoerd door: Nandita en Emona.

## Inhoudsopgave
* [Samenvatting](#samenvatting)
* [Achtergrond bij de evaluatie](#achtergrond-bij-de-evaluatie)
* [Afbakening](#afbakening)
* [Beoordelaars](#beoordelaars)
* [Beoordelingsproces](#beoordelingsproces)
* [Testresultaten en aanbevelingen](#testresultaten-en-aanbevelingen)
* [Referenties](#referenties)
* [Bijlagen](#bijlagen)
* [Licentie](#licentie)

## Samenvatting
In dit rapport wordt er beschreven in hoeverre de website OBA gelijkloopt met de Web Content Accessibility Guidelines (WCAG) van het W3C. Zo wordt er gekeken naar accessibility checklist. Die checklist bestaat ook wel uit het bekijken van de content, global code en keyboard etc. Elke item van de checklist heeft een bijbehorende WCAG- succescriterium. Gedetailleerde resultaten en aanbevelingen zijn verderop in dit document beschikbaar en in de referenties vindt u bronnen voor eventuele vervolgstudie. Wij stellen feedback op deze evaluatie zeer op prijs. Beoordelaars, beoordelingsproces en testresulltaten worden beschreven na de achtergrondinformatie en afbakening van de test. Als einduitkomst van deze test luidt dat de OBA website dichtbij voldoet aan de WCAG 2.1, op niveau AA. Gedetailleerde resultaten en aanbevelingen zijn verderop in dit document beschikbaar en in de referenties vindt u bronnen voor eventuele vervolgstudie. Wij stellen feedback op deze evaluatie zeer op prijs.
## Achtergrond bij de evaluatie
De webtoegankelijkheid-test vereist een combinatie van semi-geautomatiseerde en handmatig uitgevoerde evaluatie tools door een ervaren beoordelaar. De beoordelingsresultaten in dit rapport zijn gebaseerd op een beoordeling welke is uitgevoerd op {datum}. De website kan ondertussen aangepast zijn.

## Afbakening
[huidige activiteiten landingspagina](https://www.oba.nl/activiteiten.html)
![alt text](https://github.com/beaupd/oba-activiteitenhub-a11y-audit-autonomous/blob/activiteiten/oba-screen1.png "header oba activiteiten")
Het doel van deze pagina is om de gebruiker de aangboden activitieten te laten zien. wij testen daarom alleen de landingspagina en maken hier bij gebruik van
[lighthouse](https://developers.google.com/web/tools/lighthouse), [a11y checklist](https://www.a11yproject.com/checklist/) en eye tracking. De meeste testen hebben plaatsgevonden op 01-11-2021. OBA heeft als taal standaard Nederlands maar heeft ook een engelse versie van de site.
Activiteiten
Ben je op zoek naar een leuk uitje in Amsterdam? Bij de OBA worden jaarlijks duizenden activiteiten voor kinderen en volwassenen georganiseerd. Van literaire lezing tot voorleesuurtje. Er zit voor ...



## Beoordelaars
De Beoordelaars van de OBA website zijn wij Emona en Nandita. Ook wel de studenten van FDND hebben de opdracht gekregen de accesibiliteit van de OBA website te testen. Zo hebben we gekeken naar de landingspagina van de activiteiten.  Het doel van de beoordelaars waren het testen van de accesibility van de website OBA. Hierbij hebben we testen gehouden waaruit we de uitslagen hebben gedocumenteerd.

## Beoordelingsproces
De beoordeling is uitgevoerd op AA level. Hierbij maken wij bij gebruik van
[lighthouse](https://developers.google.com/web/tools/lighthouse), [a11y checklist](https://www.a11yproject.com/checklist/) en usability eye tracking test

## Testresultaten en aanbevelingen
aan de hand van de testen die wij uitgevoerd hebben, is gebleken dat de oba activiteiten pagina dicht bij AA level voldoet. Tijdens het testen met een screenreader zijn wij erachter gekomen dat sommige beschrijvingen van activiteiten niet gescant worden. Ook is de header afbeelding niet goed voor mensen die alleen door een gaatje kunnen zien( hier hebben wij gebruik gemaakt van de straw test). De oba logo is rood op een witte achtergrond en heeft daarom een contrast verhouding van 4:1, om AA level te halen moet de contastverhouding boven de 4:3:1 zijn. Op mobiel hebben alle clickbare links en buttons een te kleine touch range waardoor het moeilijker is om het aan klikken. 

### Sterke punten
   - Tab navigatie werkt goed. 
-	Behalve het logo, hindert de design van de website niet veel. 
-	Vertaling optie Engels.


### Ontoegankelijke punten
  - Html semantiek
-	Header afbeelding
-	Screen reader slaat dingen over
-	

### Checklist
{Beschijf de resultaten van de hele test op basis van de A11Y Project-Checklist}
##### Content
De Inhoud is het belangrijkste onderdeel van de OBA site. Te zien aan de OBA website zie je dat er goed gebruikt wordt gemaakt van duidelijke taal en het vermijden van de stijlfiguren, uitdrukkingen en ingewikkelde metaforen. Elementen als de button zien er duidelijk uit. De gebruiker hoeft ook niet horizontaal te scrollen om een regel tekst op een scherm. Ten conclusie beoordeel ik de inhoud voldoende.
##### Global code
De Globale code die van invloed is op uw hele website of webapp. Het geven van unieke titels aan de activiteieten zou verbeteringen aanbieden voor de accessibility. het zou makkelijker zijn de activiteit te begrijpen en herkennen.
##### Keyboard
Het belang dat uw interface en inhoud kunnen worden bediend en genavigeerd met behulp van een toetsenbord is te zien. Het controleren van de focusvolgorde van het toetsenbord met de visuele lay-out zou wel van toepassing moeten worden uitgevoert. (link keyboard)
##### Images
De afbeeldingen zijn een veel veelverkomend onderdeel van de meeste websites. De website OBA zou verbetert kunnen werden met wat leukere afbeelingen van de activiteueten zelf. Afbeeldingen spelen een belangrijke rol. Zij helpen mee om ervoor te zorgen dat iedereen ervan kan genieten. Het tekstalternatief voor complexe afbeeldingen zou beter aangeboden moeten worden. (link afbeeldingen). De alt heeft in de huidige site geen tekst. 
##### Headings
Het introduceren van de kopelementen staan er niet voldoende op. Als je zo kijk naar de main afbeelding merk je dat de heading kopelemenmten niet goed benoemd worden. Kopelementen zouden in een logische volgorde moeten worden geschreven. En sla geen kopnieveaus over. Er zou goed gekeken moeten worden naar de headings.
##### Lists
Beter gebruik van de lijstelementen voor inhoud zou van toepassing worden moeten gemaakt.
##### Controls
De buttons worden niet als a element gebruikt. De links zijn wel herkenbaar doordat ze onderstreept en uitgedrukt zijn. Het identificeren van links die openenen in een nieuwe tabblad of venster zou handig zijn.
##### Tables
No tables element.
##### Forms
[All inputs in a form are associated with a corresponding label element.](https://www.a11yproject.com/checklist/#all-inputs-in-a-form-are-associated-with-a-corresponding-label-element)

[Make sure that form input errors are displayed in list above the form after submission.](https://www.a11yproject.com/checklist/#make-sure-that-form-input-errors-are-displayed-in-list-above-the-form-after-submission)

##### Media
No Media
##### Video
No video
##### Audio
No audio
##### Appearance
[Double-check that good proximity between content is maintained.](https://www.a11yproject.com/checklist/#double-check-that-good-proximity-between-content-is-maintained)

##### Animation
no animation

##### Color contrast
[Check the contrast for all icons.](https://www.a11yproject.com/checklist/#check-the-contrast-of-borders-for-input-elements-text-input-radio-buttons-checkboxes-etc)

##### Mobile and touch
[Ensure that button and link icons can be activated with ease.](https://www.a11yproject.com/checklist/#ensure-that-button-and-link-icons-can-be-activated-with-ease)

### Resultaten Usability test
![alt text](https://github.com/beaupd/oba-activiteitenhub-a11y-audit-autonomous/blob/activiteiten/heatmap-oba%20-activiteiten.png "heatmap eye tracking oba activiteiten")
![alt text](https://github.com/beaupd/oba-activiteitenhub-a11y-audit-autonomous/blob/activiteiten/graph-oba%20-activiteiten.png "graph eye tracking oba activiteiten")

## Referenties
Referenties welke gebruikt zijn bij de webtoegankelijkheid-test. Deze referenties zijn allen in het Engels:
- [Overzicht en introductie van de Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/intro/wcag)
- [De complete Web Content Accessibility Guidelines 2.1 (WCAG)](https://www.w3.org/TR/WCAG21/)
- [Technieken voor WCAG 2.1](https://www.w3.org/WAI/WCAG21/Techniques/)
- [Bronnen voor beoordeling van webtoegankelijkheidsevaluatie ](http://www.w3.org/WAI/eval/)
- [Tools lijst voor semi-geautomatiseerde beoordeling van webtoegankelijkheid](https://www.w3.org/WAI/ER/tools/)
- [Informatie over het gebruik van gecombineerde expertise voor het evalueren van webtoegankelijkheid](https://www.w3.org/WAI/eval/reviewteams)
- [A11Y Project Checklist](https://www.a11yproject.com/checklist/)
{Vul aan waar nodig, haal weg wat niet relevant is}
## Bijlagen
![alt text](https://github.com/beaupd/oba-activiteitenhub-a11y-audit-autonomous/blob/activiteiten/oba-lighthouse.png "lighthouse score oba activiteiten")
lighthouse score kan verbeterd worden door de aangeven punten te fixen

## Licentie
![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)
This work is licensed under [GNU GPLv3](./LICENSE).


