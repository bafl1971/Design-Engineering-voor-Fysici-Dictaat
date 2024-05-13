# onzekerheids analyse en toleranties

## Doel:
Het bij hij het ontwerpen van een fysisch experiment nadenken over, en voldoen aan, de
gewenste nauwkeurigheid van het experiment.

## Aanvullende literatuur
De materie die hier behandeld wordt herhaald wat in {cite:t}`pols_NP` behandeld is. Voor verdere verdieping verwijzen we naar {cite:t}`Hughes_Hase`

## Enkele belangrijke zaken die behandeld zijn in TN1405-P Introductie tot experimenteren
* Het resultaat van een fysische meting is pas zinvol als de meet-onzekerheid gekwantificeerd en
gerapporteerd is.
* De nauwkeurigheid van een (wetenschappelijk) meetinstrument wordt gespecificeerd door de
fabrikant.
* De precisie van een (correct gerapporteerde!) literatuurwaarde (indien geen onzekerheid is
opgegeven) is $\pm$ 1 in de laatste decimaal.
* De nauwkeurigheid wordt negatief beïnvloed door systematische fouten, zoals defecte of verkeerd
gecalibreerde meetinstrumenten, fouten in de meetmethode, niet in rekening gebrachte verstoringen
etc.
* Wanneer een correct experiment (juiste meetmethode, correcte meetapparatuur) N maal herhaald is,
dan: Geven we de uitkomst van de meetserie aan als $x=\mu \pm \frac{\sigma}{\sqrt{N}}$ met $\mu$ het gemiddelde van $N$ de metingen, en $\sigma$ de standaardafwijking van de $N$ metingen.
* De standaardafwijking $\sigma$ is gedefinieerd als $\sigma = \left[ \frac{1}{N-1} \sum_{i=1}^{N} (x_i -\mu )^2  \right]^\frac{1}{2}$
* Op de meeste wetenschappelijke rekenmachines en in bijvoorbeeld Excel zijn standaardfuncties
beschikbaar om $\mu$ en $\sigma$ te berekenen.
* De onzekerheid $\frac{\sigma}{\sqrt{N}}$ wordt meestal slechts in 1 significant cijfer gerapporteerd. Bij $N>10^4$ kan de onzekerheid in 2 significante cijfers worden gerapporteerd.
* Het aantal significante cijfers in $\mu$ wordt bepaald door de grootte van de onzekerheid.

##### afleiding onzekerheidsformules
Stel een fysische grootheid Z hangt af van de fysische grootheden A , B en C: 

$$
Z=Z\left(A,B,C\right)
$$

A, B en C kunnen direct worden gemeten, met een onzekerheid $u(A)$ , $u(B)$ en $u\left(C\right)$, dan wordt de onzekerheid in $Z$ volgens de “calculus based approach” gegeven door

$$
U\left(Z\right)=\left[ \left( \frac{\partial Z}{\partial A}\right)^2 U(A)^2 + \left( \frac{\partial Z}{\partial B}\right)^2 U(B)^2 + \left( \frac{\partial Z}{\partial C}\right)^2 U(C)^2 \right] ^\frac{1}{2}
$$

Of volgende "functional approach":

$$
U(Z)=\left[\left[ Z(A+u(A),B,C)-Z(A,B,C) \right]^2 + [\left[ Z(A,B+u(B),C)-Z(A,B,C) \right]^2 + [\left[ Z(A,B,C+u(C))-Z(A,B,C) \right]^2 \right]^\frac{1}{2}
$$

Als Z het resultaat is van uitsluitend vermenigvuldigingen en delingen van machten van A, B en C, dus bijvoorbeeld $Z = A^\alpha B^\beta C^{-\gamma}$, dan vinden we met behulp van de calculus based approach:


\begin{eqnarray}
\left( \frac{u(Z)}{Z} \right) ^2 &=& \frac{\left[ \left( \frac{\partial Z}{\partial A}\right)^2 U(A)^2 + \left( \frac{\partial Z}{\partial B}\right)^2 U(B)^2 + \left( \frac{\partial Z}{\partial C}\right)^2 U(C)^2 \right]}{Z^2}
\\
&=& \frac{\left[ \left( \alpha A^{\alpha-1} B^{\beta} C^{-\gamma} \right)^2 U(A)^2 + \left(  A^{\alpha} \beta B^{\beta-1} C^{-\gamma} \right)^2 U(B)^2  +  \left( -A^{\alpha} B^{\beta} \gamma C^{-\gamma-1} \right)^2 U(C)^2 \right]}{\left( A^\alpha B^\beta C^{-\gamma} \right)^2}
\\
&=& \left( \left( \alpha A^-1 \right)^2 u(A)^2 + \left( \beta B^-1 \right)^2 u(B)^2 + \left( \gamma C^-1 \right)^2 u(C)^2 \right) 
\\
&=& \left( \left( \alpha \frac{U(A)}{A} \right)^2 +  \left( \beta \frac{U(B)}{B} \right)^2 +  \left( \gamma \frac{U(C)}{C} \right)^2 
\right) 
\end{eqnarray}


## Verschil onzekerheid bij practicum en ontwerpen
Bij het natuurkundig practicum was de uitdaging om bij een gegeven opstelling te bepalen wat de (on)nauwkeurigheid in het gene was dat gemeten was. Ook wordt bij het practicum al een belangrijke stap naar het ontwerpen van experimenten gedaan door uit te rekenen hoe vaak een experiment herhaald moet worden om met gegeven apperatuur een gewenste nauwkeurigheid te halen.

Bij het ontwerpen van een meet-apparaat of een meet-opstelling worden dezelfde vergelijkingen gebruikt om een ander probleem op te lossen, namelijk: hoe nauwkeurig moeten onderdelen van mijn oplossing zijn om een gewenste nauwkeurigheid te behalen. De maximaal toegelaten nauwkeurigheid ($U\left( Z\right)$ in bovenstaande vergelijkingen) is dan gegeven. De op te lossen vraag is welke combinatie van ontwerpkeuzes ervoor zorgt dat de opstelling aan dit criteria gaat voldoen. Realiseer je daarbij dat een opstelling relatief nauwkeuriger maken vaak zowel kan door $U\left( A\right)$ te verlagen als door $A$ te vergroten.

