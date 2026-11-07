# Nieuwe versies publiceren

Voor de beheerder van deze downloadrepository.

1. Geef een gewijzigde spelversie een nieuw nummer en een eigen tag, bijvoorbeeld `v1.3.3`. Behoud bestaande releases zodat een testverslag altijd aan één versie gekoppeld blijft.
2. Controleer code, vragen, beelden, opslag en spelverloop volgens de ontwikkelcontroles. Leg vast op welke systemen de app echt is gestart en welke alleen op pakketstructuur zijn gecontroleerd.
3. Werk de startgids, installatiehandleiding en versiegeschiedenis bij. Leg noodzakelijke wijzigingen in opgeslagen voortgang uit. Genereer de offline HTML en voeg de handleidingen toe aan alle pakketten.
4. Maak een **draft release** met tag, titel, wijzigingsnotities en beperkingen. Kies **pre-release** zolang het om proefversies gaat. Publiceer geen volledige ontwikkelmap via Upload files.
5. Voeg de drie platform-ZIP-bestanden, de handleidingen-ZIP en `SHA256SUMS.txt` als **release assets** toe. Grote spelbestanden horen bij Releases, niet tussen de repositorybestanden.
6. Controleer op iedere ZIP: volledig uitpakken, documentatie aanwezig, juiste architectuur, exact dezelfde app als de geteste build. Start ten minste de Windows-x64-download vanuit de uitgepakte map met een tijdelijk testprofiel. Voor Mac: controleer de Intel/ARM-code, appstructuur en uitvoerrechten; beschrijf de afwezige praktijkcontrole als die er nog niet is.
7. Publiceer de release en controleer dat de downloads zonder aanmelding bereikbaar zijn. Deel aan proefpersonen de releasepagina, niet alleen één willekeurig ZIP-bestand en ook niet de Source code-knop.
8. Controleer na een nieuwe Windows-oplevering dat zowel de startlink als de standaard spelmap werkelijk dezelfde nieuwe app bevatten. Een nog draaiende app kan vervangen blokkeren; meld dat expliciet. Een gewijzigde link vernieuwt een al draaiend spel niet.

De huidige game gebruikt eigen anatomische schema's en heeft licenties en herkomstinformatie in de spelpakketten. Verspreid het oorspronkelijke aangeleverde PDF-brondocument, lokale spelerbestanden, echte klaslijsten en onderzoeksverslagen niet via deze openbare repository.

## Bij een probleem in een gepubliceerde versie

Laat de oorspronkelijke release intact en vermeld een bekende fout bij die versie. Publiceer een herstelversie onder een nieuw nummer. Bewaar de koppeling tussen vraagcode, versie en melding. Geef bij een installatieblokkade een concreet alternatief; vraag proefpersonen niet om hun beveiliging breed uit te schakelen.
