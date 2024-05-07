# Ontwerp theorie
Er zijn veel verschillende visies op wat ontwerpen "is". Een mogelijke manier om naar ontwerpen te kijken is te kijken naar de rol die ontwerpen als activiteit heeft: waarom ontwerpen mensen?

1. Ontwerpen als vormgeving. De vraag die beantwoord wordt is: "Hoe moet iets eruit zien?". Dit is het soort "ontwerpen" dat vaak (ten onrechte) met 'design' wordt aangeduid. Bijvoorbeeld: de vorm van een opvallende (kunstzinnige?) stoel.
2. Ontwerpen als verkenning. De vraag die beantwoord wordt is: "wat kan er allemaal?". Dit is het soort ontwerpen dat geassocieerd wordt met 'visie'. Bij dit soort ontwerpen worden dingen (producten, toekomsten) ontworpen die nooit daadwerkelijk gemaakt (kunnen) gaan worden, maar daar gaat het niet om. Het gaat hier om een richting aangeven. Bijvoorbeeld: concept cars.
3. Ontwerpen als oplossing. Ontwerpen als activitiet om efficient en gestructureerd een oplossing voor een gegeven probleem te kiezen en implementeren. Dit is het soort ontwerpen waarbij het probleem in grote lijnen bekend is en de kunst is om uit alle verschillende mogelijke oplossingen er één te kiezen die goed genoeg is. De kernwoorden zijn hier 'efficient' en 'gestructureerd'.

Bij Design Engineering voor Fysici focussen we op de laatste categorie en voegen we daaraan toe: met gebruik van je natuurkunde kennis. Zo komen alle drie de woorden uit de titel van het vak samen: we leren je ontwerpen (design) en maken (engineering) gebruik makend van je natuurkunde kennis (fysica). 

## De ontwerpcyclus
Er zijn veel manieren om je werk als ontwerper (of, zie hierboven: oplossing-bedenker) gestructureerd in te richten. Als je gaat zoeken kom je vele ontwerp-methodes tegen zoals *Agile*, *design thinking*, *ontwerpcyclus* en vele andere. Deze termen zijn vaak erg vakgebied specifiek (vaak zonder te expliciet te noemen!). Zo is *agile* een methodiek die ontwikkeld is om teams van programmeurs zo snel mogelijk een bestaand stuk software beter te laten maken. Ontwerp-methodes zijn (vaak) tegenstrijdig: wat de één zegt is vaak strijdig met wat een ander zegt. Dat is geen probleem: verschillende ontwerp-methodes zijn ontwordpen voor verschillende toepassingen / deelgebieden en wat voor (bijvoorbeeld) software engineering van een klimaat-model geldt, geldt niet per se voor het ontwerpen en bouwen van een kern-reactor.

Bij DEF gebruiken we de ontwerpcyclus van [insert ref]. Zie de Delft Design Guide [insert ref], een boek met verschillende ontwerpmethodes dat in de opleiding Industrieel Ontwerpen veel gebruikt wordt, voor meer ontwerpmethodes. 

```{figure} ../figures/ontwerpcyclus.png
---
height: 300px
name: ontwerpcycluse
---
De ontwerpcyclus van Roozenburg & Eekels
```

Hoewel deze methode *ontwerpcyclus* heet, is het belangrijk in te zien dat het meer een verzameling van activiteiten is. De volgorde waarin de activiteiten voorkomen volgen vaak, maar niet altijd, de cyclus. Als ontwerper is het zaak om voordat je aan de slag gaat met de inhoud van je ontwerp na te denken over hoe de randvoorwaarden van je ontwerpopracht impact hebben op de activiteiten in de ontwerpcyclus. Bijvoorbeeld: bij software ontwerp zijn de kosten van een iteratie doorlopen verwaarloosbaar en is het dus slimmer om niet te lang te blijven hangen in synthese en evaluatie, maar om bij het eerste het beste idee snel uit te werken of het werkt. Als het niet werkt doe je snel een iteratie en ga je terug naar synthese voor het volgende idee. Bij het ontwerpen van een raket naar Mars zijn de kosten van een iteratie te hoog en ga je dus bij synthese alle mogelijke opties af die je bij evaluatie uitwerkt, voordat je kiest welke je uiteindelijke oplossing wordt.

Elke activiteit heeft een duidelijk gedefineerd doel binnen ontwerpen en eigenschappen die deze activiteit onderscheit van andere activiteiten. Er zijn altijd verschillende voorbeelden van werkzaamheden die kunnen vallen onder een activiteit. Hieronder behandellen we de verschillende activiteiten.

### Analyse
In de analyse activiteit wordt bepaald wat er ontworpen moet worden. Soms wordt de analyse gegeven door een opdrachtgever, soms wordt de analyse gedaan samen met een opdrachtgever en soms doen de ontwerpers de analyse zelf. Bij analyse denk je na over welk probleem je wilt oplossen en baken je dat af. De uitkomst van een goede analyse fase is een duidelijk omschreven probleem dat opgelost gaat worden. 

Bijvoorbeeld:

* We gaan een oplossing ontwerpen waardoor mensen deze rivier kunnen oversteken terwijl scheepvaart niet gehindert wordt. 
* We gaan een oplossing ontwerpen die beter is voor het klimaat dan de huidige kartonnen koffie-bekers
* We gaan een meet-apparaat ontwerpen dat in staat is om een zwaartekracht golf te detecteren

Het is belangrijk om in de analyse fase niet al de volgende stappen van de ontwerp-cyclus in te vullen. bij het eerste voorbeeld hierboven kan de opdracht zijn: "ontwerp een brug over de Rijn". Echter: een brug is al een oplossing voor een probleem en bij analyse gaat het om het probleem scherp krijgen. Het goede antwoord naar de opdrachtgever bij dit voorbeeld zou dan ook zijn: "waarom een brug? Wat is het onderliggende probleem dat we moeten oplossen?" Door de juiste vragen te stellen krijg je het probleem helder, in dit geval: er moeten mensen naar de andere kant van de rivier.

Belangrijke eigenschap van de analyse fase is dat je *in algemene termen* je probleem omschrijft. De specificering van je probleem in (natuurkundige) quantitatieve termen vindt plaats in de volgende stap: criteria.

### Criteria
Criteria zijn de vertaling van de analyse naar harde eisen waar het ontwerp aan moet voldoen om als succesvol (geslaagd) gezien te worden. In een ontwerp-project met een opdrachtgever is het verstandig om na de analyse de criteria terug te leggen bij de opdrachtgever met de vraag: "dus als de ontworpen oplossing aan deze criteria voldoet, dan is het een succes? / kan ik een factuur sturen? / krijg ik de studiepunten?"

Bij de criteria komen vaak voor het eerst in de ontwerpcyclus natuurkundige eenheden langs: het is handig om in natuurkundige termen uit te drukken wat het criteria is. Dus niet: "De brug moet sterk genoeg zijn voor een normale vrachtauto", maar: "de brug moet een rijdende colone van 15 vrachtwagens met een lengte van 12 meter per vrachtwagen en met een asdruk van maximaal 12 ton per vrachtwagen kunnen ondersteunen zonder problemen." 

Bij het opstelling van criteria gebruiken we de **SMART** afkorting die oorspronkelijk uit project-management komt, maar hier ook goed inzetbaar is. **SMART** staat voor: 

* **S**pecifiek
* **M**eetbaar
* **A**ctionable
* **R**elevant
* **T**ijdsgebonden

Er zit enige overlap tussen de verschillende termen, maar het helpt als denk-middel om te kijken of criteria goed geformuleerd zijn.

#### Specifiek
Het criterium moet eenduidelig zijn. Als twee mensen die het criterium lezen een verschillend beeld kunnen hebben bij het criterium, dan is het niet specifiek. Vermijd daarom subjectieve termen als: goed genoeg, sterk genoeg of 'niet te groot' en vervang deze door specifieke getallen of grenzen. Geef bij getallen waar nodig ook een domein aan, bijvoorbeeld: De koorts-thermometer die we gaan ontwerpen moet in het bereik van 30 tot 45 graden de lichaamstemperatuur van een persoon met een nauwkeurigheid lager dan 0.1 graad Celcius vaststellen. 

#### Meetbaar
Het moet meetbaar zijn of een oplossing aan het criterium voldoet. Wanneer het niet objectief meetbaar is of een criterium gehaald is, is niet vast te stellen of daadwerkelijk aan het criterium voldaan is. Vaak overlapt dit criterium met Specifiek, maar het is ook mogelijk om een criterium wel specifiek op te stellen, maar dat het fysisch, technichs of financieel niet mogelijk is om te meten of aan het wel specifieik geformuleerde criterium is voldaan.

#### Actionable
De ontwerper / maker moet binnen de grenzen van de opdracht invloed hebben op het criterium. Als de ontwerper niets kan veranderen aan het wel of niet halen van het criterium met een ontworpen oplossing, dan is het een slecht criterium.

#### Relevant
Het criterium moet gaan over de in de analyse geformuleerde probleem en bijdragen aan de oplossing. Als de uitkomst van de analyse fase is: "er moet een oplossing gemaakt worden om mensen over de rivier te verplaatsen", dan is het criterium: "de oplossing moet blauw zijn" niet relevant.  

#### Tijdsgebonden
Het criterium moet binnen een normale tijd te halen zijn en/of aantoonbaar zijn. Als de oplossing een bepaalde verandering moet teweegbrengen, dan moet aangegeven worden wanneer deze verandering bewerkstelligt is. Bijvoorbeeld: "de opstelling moet een drankje van maximaal 200 ml met een begin temperatuur van maximaal 40 graden af kunnen koelen naar 10 graden celcius *binnen 2 minuten*."

### Synthese
In de synthese fase worden oplossingen verzonnen die **mogelijk** voldoen aan de criteria. Of er in de synthese fase één of meerdere oplossingen verzonnen worden hangt af van hoe de ontwerpcyclus ingericht is, wat weer afhangt van de randvoorwaarde van de ontwerpopdracht. In sommige gevallen is het beter om één oplossing te verzinnen en deze snel te testen in de evaluatie stap (zie hieronder), in andere gevallen is het beter om in de synthese stap meerdere oplossingen te verzinnen. 

Of een idee daadwerkelijk aan de criteria voldoet wordt in de stappen simulatie en evaluatie beoordeeld. In synthese worden enkel de ideeen verzamelt. Wel is het natuurlijk zo dat ervaren ontwerpers in de synthese fase eerder met ideeen komen die aan de criteria gaan voldoen terwijl minder ervaren ontwerpers nog veel ideeen verzinnen die later blijken niet aan de criteria te (kunnen) voldoen. Een valkuil voor onervaren ontwerpers in het algemeen en natuurkundige in het bijzonder is om zich in de synthese fase te snel te richten op één idee en niet langer na te denken over mogelijke alternatieven. 

Er zijn vele methodes en hulpmiddelen bedacht om ontwerpers te helpen om in de synthese fase tot goede ideeen te komen. Voor een overzicht daarvan verwijzen we naar de Delft Design Guide, een leerboek dat bij de opleiding Industrieel Ontwerpen veelvuldig gebruikt wordt [citation needed]. Één van deze methodes: de morfologische kaart wordt uitgelegd in het tweedejaars vak Design Engineering voor Fysici 2 (DEF2, TN2003). Voor DEF1 (dit vak) is het voldoende om te weten dat je in de synthese fase ideeen bedenkt die mogelijk aan de ontwerpopdracht voldoen.  

### Simulatie
In de simulatie fase doe je activiteiten die het mogelijk maken om te testen of je idee uit de synthese fase voldoet aan de criteria. Die activiteiten kunnen heel verschillende zijn. Het woord *simulatie* kan verwarrend zijn omdat het buiten de context van ontwerpen vooral gebruikt wordt voor *digitale* similaties. Binnen de context van ontwerpen is simulatie echter breder: alles wat je doet om te later te kunnen toetsen of je idee aan de criteria voldoet. Een (niet uitputtende!) lijst van mogelijke activiteiten die goed onder Simulatie kunnen vallen:

* Het analytisch doorreken van het idee. Dit kan een berekening op de achterkant van een envelop (of bierviltje) zijn, maar kan ook meerdere pagina's aan afleidingen en afschattingen zijn. Dit is een activiteit die binnen de opdrachten van DEF veel voorkomt als Simulatie stap.
* Het opstellen en doorrekenen van een nummeriek model dat (een deel van) het idee simuleert. 
* Het uitwerken van schetsen of digitale (3D) representaties van het idee, of het maken van een (schaal-)model, maquette (3D geprint of anders). Dit is onderdeel van simulatie omdat het gebruikt kan worden  om criteria te toetsen die gaan over hoe het ontwerp eruit moet zien. Dit kan zowel esthetisch zijn als technisch, bijvoorbeeld: 

  * Uit een lijst van 10 ideeen moet dit idee door een steekproef van 10 klanten als *mooiste* worden betiteld. (esthetisch) 
  * het ontwerp van een cubesat sateliet moet in een volume van 10 x 10 x 10 cm passen. (technisch)
  * Het ontwerp voor de DEF eindopdracht moet door een deur heen kunnen (technisch)
   
*  Het volledig bouwen van het idee. In sommige ontwerpen is het direct maken van het volledige idee de enige manier om te testen. Dit is vaak het geval bij het ontwerpen van software.
*  Logisch nadenken over het idee. Dit klinkt flauw, maar sommige ideeen kan je door logisch na te denken direct beoordelen (zie evaluatie hieronder). Als je gevraagd wordt een oplossing te verzinnen om 100 vrachtautos per uur over grote rivier te verplaatsen en een teamlid suggereert in de synthese fase een schans waarmee de autos naar de overkant springen dan kan je direct in Simulatie mentaal voorstellen wat er gebeurd met een auto een auto die aan de overkant neerkomt. In de volgende fase, evaluatie, ga je dan beoordelen of het "auto moet heel blijven" criteria gehaald wordt. Realiseer je dus dat de stappen synthese -> simulatie -> evaluatie vaak heel snel en onbewust gaan. Maar bij grote projecten worden deze stappen vaak expliciet gescheiden en zelfs door verschillende afdelingen binnen een bedrijf gedaan.

### Evaluatie

In de evaluatie fase leg je de uitkomst van de simulatie naast de criteria en beoordeel je of het idee voldoet aan de criteria. Bij kleine projecten kan dat heel snel en vaak onbewust gebeuren. Bijvoorbeeld bij het ontwerpen van een algoritme in software is het runnen van je code (synthese) en dan tegen een error aanlopen een evaulatie van de eis: "software moet werken". Bij grote projecten wordt de evaluatie systematischer gepland en worden hele evaluatie rapporten opgesteld in deze fase. Als beginnend ontwerper is het verstandig om je bewust te zijn van wanneer je een evaulatie doet en dit te documenteren: in notulen van een overleg, of in een ontwerp-journaal, zodat je later kan terugzien wanneer je welke ideeen wel of niet hebt goedgekeurd en om welke redenen.

Het is belangrijk om bij evaluatie niet te droog te kijken naar alleen de criteria, maar ook terug te kijken naar de analyse en te beoordelen of de criteria wel goed genoeg gedefinieerd zijn. Vaak wordt pas bij evaluatie duidelijk dat een essentieel criteria vergeten is. (bijvoorbeeld de personen in de auto die over de rivier verplaatst wordt moet het overleven...) Het gebeurd (helaas) regelmatig dat een ontwerp opgeleverd wordt dat technisch gezien wel aan de criteria voldoet maar niet het probleem van de analyse oplost. 

### Iteratie

Itereren is het proces van terugstappen naar een eerdere fase in de ontwerpcyclus omdat de uitkomst van evaluatie is dat een of meer criteria van het ontwerp nog niet in orde zijn. De ontwerpcyclus doorlopen tot en met evaluatie noemen we *één iteratie*. Het is zeer onwaarschijnlijk dat een ontwerpproces slechts één iteratie doorloopt. 

Als uitkomst van evaluatie kan de beslissing zijn om terug te gaan naar synthese en daar meer ideeen uit te werken, of bestaande ideeen te veranderen. De uitkomst van evaluatie kan ook zijn om terug te gaan naar het opstellen van (extra, betere) criteria omdat duidelijk werd bij evaluatie dat de criteria niet (volledig) de probleem omschrijving uit Analyse dekken.

### Productie
De laatste fase is het daadwerkelijk produceren van het ontwerp. Voor natuurkundige betekend dit vaak dat het ontwerp uit handen gegeven wordt en door vakmensen gefabriceerd wordt. Maar bijvoorbeeld in het geval van het ontwerpen van een meet-opstelling voor (afstudeer-)onderzoek zijn het vaak de natuurkundige die ook hier een belangrijke, of de enige, rol spelen. Als het hele ontwerp-proces goed is gegaan, komen er in het productie-proces geen verrassingen meer boven. In sommige gevallen zoals het maken van software is er geen sprake van een ontwerp-proces omdat de software al iteratief gemaakt is in de simulatie-fase.

## Inrichten ontwerpcyclus

De ontwerpcyclus kan gezien worden als een beschrijving van wat (ervaren) ontwerpers doen om tot een succesvol ontwerp te komen. Maar je kan de ontwerpcyclus ook zien als een stuk gereedschap om voordat je met een ontwerp begint na te denken over hoe je je ontwerp gaat aanpakken: hoeveel tijd en aandacht ga je aan de verschillende fases van de ontwerpcyclus besteden. Vooral voor beginnende ontwerpers biedt de ontwerpcyclus houvast om gestructureerd te werk te gaan en efficient tot een succesvol ontwerp te komen. Hoe je de ontwerpcyclus inricht kan je vastleggen in een ontwerp-journaal. Keuzes die je daarin vastlegt zijn (bijvoorbeeld)

* Wie is verantwoordelijk voor het uitvoeren van welke fase van de ontwerpcyclus? En wie is verantwoordelijk voor het controleren of deze fast goed is verlopen en goed is gedocumenteerd? Voor kleine projecten kan dit altijd dezelfde persoon zijn, maar bij het ontwerpen van een nieuw vliegtuig kan dit door verschillende bedrijven gebeuren. 
* Worden de criteria met de opdrachtgever afgestemd? Hoe wordt dit vastgelegd?
* Hoeveel verschillende ideeen worden uitgewerkt voordat de stap naar simulatie gemaakt wordt? 
* Hoeveel van de ideeen uit synthese worden in simulatie uitgewerkt? Hoe wordt de keuze gemaakt?
* Wat voor (type) simulatie activiteiten worden gedaan? Worden onderdelen van de simulatie uitbesteed?
* Wordt het aantal iteraties vooraf afgesproken of beperkt tot een maximum? Of mag oneindig vaak geittereerd worden tot de tijd op is? Als de kosten van de simulatie-fase hoog zijn, bijvoorbeeld doordat er duur productie materiaal gebruikt wordt, of er veel uren werk in gaat zitten, dan kan je beslissen om heel zuinig te zijn met iteraties. Dan moet je dus goed nadenken over hoe je na synthese het meest kansrijke idee verder uit gaat werken.

Realiseer je goed dat je vaak (onbewust) een kleinere ontwerpcyclus doorloopt binnen een fase van de gehele ontwerpcyclus. Het inrichten van de ontwerpcyclus is een ontwerp op zich. Dit is een [turtles all the way down](https://en.wikipedia.org/wiki/Turtles_all_the_way_down) probleem. Een risico is dat er teveel tijd wordt besteed aan het inrichten van het ontwerp-proces en niet genoeg tijd aan het ontwerpen zelf. Beoordeel dus altijd goed of wat je inricht niet overkill is voor een gegeven opdracht. Voor beginnende ontwerpers is het advies om heel expliciet de ontwerpcyclus in te richten en te documenteren. Met ervaring kan beter besloten worden om bepaalde documentatie te minimaliseren.