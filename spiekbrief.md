# Spiekbrief Git en GitHub, versie van mijn laptop

## 1. Clone, commit, push en pull

Met clone zet je een kopie van een repository van GitHub op je eigen computer. Met commit leg je je wijzigingen vast als een momentopname, die voorlopig alleen op je eigen computer bewaard wordt. Met push stuur je die commits van je computer naar GitHub, zodat ze online in je repository staan. Met pull haal je nieuwe wijzigingen van GitHub naar je computer, zodat je lokale map weer up-to-date is.

## 2. Een goed commitbericht

Goed voorbeeld: Spiekbrief: uitleg over clone, commit, push en pull

Slecht voorbeeld: aanpassing

Het eerste bericht is beter omdat je er meteen aan ziet wat er veranderd is. Bij het tweede weet je niets, en dat is vervelend als je later in de geschiedenis iets wilt terugvinden.

## 3. Gitignore

Een .gitignore-bestand zegt aan Git welke bestanden het moet negeren, zodat ze niet per ongeluk in je repository terechtkomen.

## 4. Pull

Ik heb de README online op GitHub aangepast en daarna met pull die wijziging naar mijn computer gehaald. Je pullt aan het begin van elke les eerst, zodat je lokale map up-to-date is en je niet met een oude versie verder werkt.

## 5. Terugdraaien

Een revert verwijdert de foute commit niet, maar maakt een nieuwe commit die de wijziging ongedaan maakt. De geschiedenis blijft daardoor volledig bewaard: je ziet wat er gebeurd is en wanneer, en het terugdraaien staat er zelf als aparte commit bij.

## 6. Branches en pull requests

Een branch is een aparte werkversie van je project, waarin je wijzigingen kunt maken zonder de rest aan te raken. Main blijft daardoor altijd de werkende versie, want half afgewerkt werk komt pas in main als het klaar en nagekeken is. Een pull request is een voorstel om de wijzigingen van een branch in main te zetten, zodat anderen ze eerst kunnen bekijken en bespreken.