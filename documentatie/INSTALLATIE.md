# Installeren en starten

**Voor proefpersonen · spelversie 1.4.1 · 10 november 2026**

## Vooraf

Download alleen via de door Dennis gedeelde link naar de officiële release. De pakketten zijn zelfstandige proefversies. Er is geen installatieprogramma, account of spelabonnement nodig. Een internetverbinding is nodig voor downloaden en het teruggeven van feedback; tijdens het spelen werkt de app offline. Een toetsenbord is nodig voor de horrorroute en voor vragen waarbij je typt. Het spelvenster heeft minimaal 960 × 600 beeldpunten nodig.

## Windows: welk pakket heb ik nodig?

Ga naar **Instellingen → Systeem → Info** en bekijk **Type systeem**. Bij een x64-processor kies je **Windows-x64**; bij een ARM-processor kies je **Windows-ARM64**. Er is geen 32-bits versie. Controleer bij twijfel samen met Dennis. Windows 11 is de aanbevolen testomgeving; een werkende installatie op alle Windows-computers is nog niet aangetoond.

### Uitpakken en openen

1. Download `Overleven-in-het-Anatomielokaal-v141-Windows-x64.zip` of `Overleven-in-het-Anatomielokaal-v141-Windows-ARM64.zip`.
2. Klik met rechts op het ZIP-bestand en kies **Alles uitpakken**. Kies een eigen map, bijvoorbeeld Documenten/Anatomiespel-1.4.1.
3. Open de uitgepakte map **Windows-x64-v141** of **Windows-ARM64-v141**.
4. Dubbelklik op **Overleven-in-het-Anatomielokaal.exe**. Laat de andere bestanden en mappen erbij staan.
5. Controleer op het welkomstscherm dat **1.4.1** wordt vermeld.

### Een beveiligingsmelding?

Deze proefversie heeft geen uitgevershandtekening. Windows kan daarom een onbekende uitgever of onbekende app melden. Dit is op zichzelf geen bewijs dat een bestand veilig of onveilig is. Controleer eerst de herkomst en exacte bestandsnaam. Alleen bij de gewone SmartScreen-melding **Je pc wordt beschermd** kun je, als je het officiële pakket vertrouwt, via **Meer informatie → Toch uitvoeren** toestemming geven aan deze app, als Windows die optie biedt.

Bij een expliciete virus-/malwaremelding, een beheerdersblokkade, Smart App Control, S-modus of een ontbrekende knop: stop en stuur de melding aan Dennis. Schakel antivirus of andere beveiliging niet uit. Op een beheerde schoolcomputer kan toestemming van ICT nodig zijn; gebruik zo nodig een andere toegestane computer. Je hoeft voor deze proef niet uit S-modus over te stappen.

## Mac: één download voor Intel en Apple Silicon

Het **macOS-Universal**-pakket bevat zowel Intel- als Apple-Silicon-code. Er is geen Windows-programma of Windows-emulator nodig. De export is ingesteld op macOS 12 of nieuwer. Op een echte Mac is deze release nog niet getest. Reken dus op mogelijke installatieproblemen en meld die ook als je niet aan spelen toekomt.

### Uitpakken en openen

1. Download `Overleven-in-het-Anatomielokaal-v141-macOS-Universal.zip`.
2. Open Finder → Downloads en dubbelklik op het ZIP-bestand.
3. Bewaar de uitgepakte app **Overleven-in-het-Anatomielokaal.app** en de documentatie samen in een eigen map. Als Finder ze los uitpakt, maak daarvoor bijvoorbeeld Documenten/Anatomiespel-1.4.1 aan. Verplaats de app niet via een Windows-computer of een dienst die appbestanden verandert.
4. Dubbelklik op de app. macOS kan de extensie `.app` verbergen.
5. Controleer op het welkomstscherm dat **1.4.1** wordt vermeld. Het venster of de bestandsinformatie kan nog oudere interne versiegegevens tonen; noteer een verschil in je verslag.

### macOS kent de ontwikkelaar niet

De proefversie is niet met een Apple Developer-certificaat ondertekend en niet door Apple genotariseerd. macOS kan de ontwikkelaar daarom niet verifiëren. Als het de gewone melding over een onbekende ontwikkelaar betreft en je de officiële download vertrouwt:

1. Probeer de app één keer te openen en sluit de melding.
2. Open **Apple-menu → Systeeminstellingen → Privacy en beveiliging**. Op oudere macOS-versies heet dit **Systeemvoorkeuren → Beveiliging en privacy**.
3. Zoek de blokkade van deze app en kies **Open toch**, als die optie aanwezig is. Bevestig het openen van deze specifieke app als macOS daarom vraagt.

Bij **beschadigd**, **malware**, **zal je computer beschadigen**, een ontbrekende uitzondering of een bedrijfsblokkade: stop, maak een screenshot en meld dit. Verwijder geen beveiligingskenmerken met Terminal-opdrachten en schakel Gatekeeper niet uit. De huidige ongetekende Mac-export kan op jouw systeem onbruikbaar blijken; dat is een relevante testuitkomst.

## Eerste start en bediening

Gebruik een testcode of verzonnen naam en kies een leerroute. Bij **Rustig oefenen → Kies je opgaven** kun je antwoordvormen en onderwerpen aanvinken. Begin bijvoorbeeld met meerkeuze en spiernamen. Hints zijn toegestaan; meld of de uitleg helpt.

De standaardbediening van het horrorverhaal is:

| Actie | Toets |
| --- | --- |
| Lopen: vooruit, links, achteruit, rechts | W, A, S, D |
| Uithaal naar links / rechts | J / L |
| Uithaal schuin naar linksonder / rechtsonder | U / O |
| Uithaal recht omlaag | I |
| Trappen | Spatie |
| Pauzeren | Escape of de knop Pauze |
| Terug naar het keuzescherm | Het huisje / Naar Home |

In **Instellingen → Toetsen** kun je de bediening wijzigen. De toets die het spel toont is leidend. Hoog/laag wisselen is uitgeschakeld. Na de verhaalintro en toetsenborduitleg oefen je **vijf slagrichtingen zonder anatomievragen**. Een teller toont de voortgang. Na de training kies je **Start level 1 / met anatomievragen**. Pas dan volgt na een rake slag een opgave. Een BOSS vraagt meerdere treffers en komt tussendoor terug.

## Voortgang, privacy en updates

Het spel bewaart spelersnamen, antwoorden, instellingen en sessies lokaal. Er is geen ingebouwde upload van spelresultaten naar de onderzoeker. De horrorroute en rustige route hebben elk een opgeslagen sessie. **Naar Home** bewaart je actieve voortgang. Heropen dezelfde route en kies hervatten om verder te gaan. Gebruik dezelfde spelersnaam op dezelfde computer. Je voortgang verhuist niet vanzelf mee naar een andere computer.

De gegevensmap is op Windows `%APPDATA%\DEADLINE` en op Mac `~/Library/Application Support/DEADLINE`. Het profielbestand heet `deadline-profiles-v03.json`; er kunnen reservekopieën en register-notities naast staan. Je hoeft deze map voor het testen niet te openen. Deel het profielbestand alleen als Dennis dat voor het onderzoek met je heeft afgesproken; het bevat je lokaal bewaarde speelgegevens. Deel geen persoonsgegevens of profielen via openbare GitHub-issues.

Bij een nieuwe versie: sluit de oude app volledig, download en pak het nieuwe pakket uit in een **nieuwe map**, open de app uit die map en controleer het versienummer. Opgeslagen voortgang staat buiten de spelmap; verwijder die gegevensmap niet bij een update. Compatibiliteit van voortgang tussen toekomstige versies moet per release worden gecontroleerd. Als iets niet klopt, bewaar de oude versie en neem contact op.

## Problemen die je kunt melden

- **Geen anatomievraag na hakken:** tijdens de vijf oefenslagen is dit de bedoeling. Noteer het als er na **Start level 1 / met anatomievragen** nog steeds geen opgave komt.
- **Een brede uitleg bedekt de zombie:** controleer dat je echt 1.4.1 hebt geopend; de training heeft hierin een compact vak links.
- **Lege oefenselectie:** vink minstens één antwoordvorm én één inhoudscategorie aan. Een foutenfilter kan leeg zijn als je nog geen fouten hebt gemaakt.
- **Traag beeld of geen geluid:** probeer de instellingen voor beeldkwaliteit, geluid en volume. Noteer wat je verandert en of dat helpt.
- **Vastloper of afsluiting:** noteer wat je net deed, de vraagcode, je systeem en de exacte melding. Start opnieuw; probeer hervatten. Verwijder of bewerk geen profielbestand om verder te komen.

## Officiële hulp bij systeemmeldingen

Geraadpleegd op 10 november 2026. Menuwoorden verschillen per taal en systeemversie.

- [Apple: apps veilig openen en onbekende ontwikkelaars](https://support.apple.com/102445)
- [Microsoft: 32-bits/64-bits en het systeemtype vinden](https://support.microsoft.com/en-au/windows/experience/compatibility/32-bit-and-64-bit-windows-frequently-asked-questions)
- [Microsoft: ARM herkennen bij Type systeem](https://support.microsoft.com/en-us/windows/hardware/printer/help-with-installing-printers-on-arm-pcs)
- [Microsoft: Smart App Control en niet-ondertekende apps](https://support.microsoft.com/en-gb/windows/security/threat-malware-protection/smart-app-control-frequently-asked-questions)
- [Microsoft: SmartScreen bij nieuwe apps en de eerste start](https://learn.microsoft.com/da-dk/windows/apps/package-and-deploy/publish-first-app)
