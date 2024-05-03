# Ontwerp theorie
Er zijn veel verschillende visies op wat ontwerpen "is". Een mogelijke manier om naar ontwerpen te kijken is te kijken naar de rol die ontwerpen als activiteit heeft: waarom ontwerpen mensen?

1. Ontwerpen als vormgeving. De vraag die beantwoord wordt is: "Hoe moet iets eruit zien?". Dit is het soort "ontwerpen" dat vaak (ten onrechte) met 'design' wordt aangeduid. Bijvoorbeeld: de vorm van een opvallende (kunstzinnige?) stoel.
2. Ontwerpen als verkenning. De vraag die beantwoord wordt is: "wat kan er allemaal?". Dit is het soort ontwerpen dat geassocieerd wordt met 'visie'. Bij dit soort ontwerpen worden dingen (producten, toekomsten) ontworpen die nooit daadwerkelijk gemaakt (kunnen) gaan worden, maar daar gaat het niet om. Het gaat hier om een richting aangeven. Bijvoorbeeld: concept cars.
3. Ontwerpen als oplossing. Ontwerpen als activitiet om efficient en gestructureerd een oplossing voor een gegeven probleem te kiezen en implementeren. Dit is het soort ontwerpen waarbij het probleem in grote lijnen bekend is en de kunst is om uit alle verschillende mogelijke oplossingen er één te kiezen die goed genoeg is. De kernwoorden zijn hier 'efficient' en 'gestructureerd'.

Bij `Design Engineering voor Fysici` focussen we op de laatste categorie en voegen we daaraan toe: met gebruik van je natuurkunde kennis. Zo komen alle drie de woorden uit de titel van het vak samen: we leren je ontwerpen (design) en maken (engineering) gebruik makend van je natuurkunde kennis (fysica). 

## De ontwerpcyclus
Er zijn veel manieren om je werk als ontwerper (of, zie hierboven: oplossing-bedenker) gestructureerd in te richten. Als je gaat zoeken kom je vele ontwerp-methodes tegen zoals *Agile*, *design thinking*, *ontwerpcyclus* en vele andere. Deze termen zijn vaak erg vakgebied specifiek (vaak zonder te expliciet te noemen!). Zo is *agile* een methodiek die ontwikkeld is om teams van programmeurs zo snel mogelijk een bestaand stuk software beter te laten maken. Ontwerp-methodes zijn (vaak) tegenstrijdig: wat de één zegt is vaak strijdig met wat een ander zegt. Dat is geen probleem: verschillende ontwerp-methodes zijn ontwordpen voor verschillende toepassingen / deelgebieden en wat voor (bijvoorbeeld) software engineering van een klimaat-model geldt, geldt niet per se voor het ontwerpen en bouwen van een kern-reactor.

Bij DEF gebruiken we de ontwerpcyclus van [insert ref]. Zie de Delft Design Guide [insert ref], een boek met verschillende ontwerpmethodes dat in de opleiding Industrieel Ontwerpen veel gebruikt wordt, voor meer ontwerpmethodes. 

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
tekst

### Evaluatie

tekst

### Iteratie

### Productie