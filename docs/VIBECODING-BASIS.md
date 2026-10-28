# Vibecoding basis — inhoud en uitvoering

Doelgroep: tweede en derde graad, alle finaliteiten; geen programmeerkennis.
Duur: ongeveer 70 minuten, buiten nulmeting en Smartschoolbevraging.

## Didactische afspraken

Eerst de behoefte (wat heb ik nodig om te leren?), daarna onderzoeken of en
hoe een digitaal hulpmiddel helpt. Bestaande hulpmiddelen kort onderzoeken;
zelf bouwen is niet altijd de beste oplossing. Bij een ongeschikte behoefte
keert de leerling terug om een andere te kiezen.

Vier inspiratiekeuzes: woorden/begrippen, oefeningen, mondeling, werkwijze.
Eigen gecontroleerde leerinhoud of passend startpakket, zonder persoonsgegevens.
AI mag inhoud voorstellen als de leerling die met bronnen kan controleren.
Een mondeling heeft controlepunten, geen automatisch oordeel over spraak.

Kennismaking: concrete situaties bij Engels en wiskunde, definitie, een
herkenningsvraag, optioneel historisch weetje en een aanklikbaar spectrum.
Van uitlegpagina naar oefenquiz, persoonlijke app en een escape game met
vrienden; het laatste vraagt extra techniek. Basis bouwt een kleine lokale
interactieve pagina, geen accounts, databank of publicatie.

De cyclus wordt benoemd als itereren en geoefend met Noor: beschrijven,
bouwen, testen, bijsturen en opnieuw testen. Slepen heeft een alternatief
met pijltjesknoppen voor het toetsenbord.

Een kort gesprek met AI gaat vóór het bouwen. Leerlingen controleren en
bewaren de samenvatting van hun bouwplan voor Smartschool. Vervolgens één
zelfstandig HTML-bestand downloaden en lokaal openen. De download- en
verbeterroute werd uitgeprobeerd met een Copilot-schoolaccount. Dezelfde
mogelijkheden zijn niet gegarandeerd voor alle leerlingen/accounts.

De testkaart bevat vier concrete onderdelen: basiswerking, leerinhoud,
onverwachte invoer en nut voor het leren. Daarna twee verbeterlussen: een
fout herstellen of leerondersteuning verbeteren, met tips per richting.
Geen fout vinden is geen reden om klaar te zijn. Elke wijziging opnieuw testen.

## Techniek

Eén MDX-module met 30 stappen in de bestaande stappenspeler. De modulegebonden
Vibe-islands delen alleen browsertoestand (`ai-leerlijn:vibecoding:werk`).
Geen backend of nieuwe externe diensten. Keuzes en tekst worden direct bewaard;
een volledige herstart gebruikt de bestaande bevestigingsdialoog en opslagwisser.
De nieuwe component is uitsluitend toegevoegd aan de MDX-componentenlijst;
bestaande modules en algemene samenvatting behouden hun werking.

De laatste stap genereert een downloadbaar A4-PDF-verslag lokaal met letterlijke
antwoorden en keuzes. Lege antwoorden worden gemeld met teruglinks; export blijft
mogelijk bij blokkades. PDF-pagina's zijn gerenderde afbeeldingen om Unicode te
behouden; de tekst is daardoor niet selecteerbaar. Een volledige tekstversie is
ook beschikbaar om te kopiëren (toegankelijk alternatief). HTML is een apart bestand.

## Nog niet in deze scope

Gevorderd: publiceren, databanken/accounts, diepere kwaliteitscontrole,
beveiliging, technische schuld. De Claude-instructies zijn niet geconverteerd.
Geen pull request of merge naar de gezamenlijke website zonder opdracht.


## Herwerking na leerlinggerichte review

De praktische start toont alle kaarten direct. Eerst een open eigen idee, daarna
optionele voorbeelden; een expliciet stappenoverzicht vervangt de oude losse
herkenningsvraag. Het spectrum opent bij binnenkomen steeds op het eerste voorbeeld.
Faselabels geven aan wat de leerling doet en waarom. De mini-quiz is een zichtbaar
apart oefenvoorbeeld. Eigen lesbestanden (PDF, PPT, Excel) gaan naar de AI-tool;
in het leerpad komt alleen een beschrijving van de gekozen leerstof. Canva Code
heeft eigen instructies voor bouwen en testen zonder HTML-download. PDF blijft
het verslag voor alle routes. De bestaande velden blijven behouden bij bijwerken.
