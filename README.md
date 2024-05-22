# Geoptimaliseerd ontwerp

*Projectteam: Noah Menschaert; luca Poppe*

*Datum 20/5/2024*

## De hiërarchische taakanalyse

<p>
  <img src="Screenshot 2024-05-22 104533.png" width="1200" 
     height="auto" />

</p>

> De rood omlijnde vakken in de hiërarchische taakanalyse zijn degenen die we in ons concept hebben aangepast/geoptimaliseerd.

## De test
We hebben 1 systeem voor de test personen gezet. In de eerste fase voerden ze een opdrachten uit wanneer de auto zogezegd stilstaat(dit betekend dat ze het bedieningspaneel centraal kunnen gebruiken. In de tweede fase voerden ze tests uit terwijl de auto zogezegd in beweging is. De test moest meer kennis geven over het gebruik van voice activition, draaiknoppen, HUD als navigatie. We wouden te weten komen of deze funties effectief minder afleidend zijn tijdens het rijden. Ook wouden we weten of het geoptimaliseerd kan worden en of ze het systeem in het echt zouden gebruiken.


#### De opdrachten die ze moesten uitvoeren per prototype:
- Plan een route naar <bestemming> via google maps.
- Maak de rit die vooraf voor jou is vastgelegd
- Gebruik de knoppen om de temperatuur aan te passen en het volume van de liedjes
- Ga naar liedje spotify en leg het derde nummer op via google home
- Probeer tijdens het rijden toch nog te kijken naar het afgedekt(gepolariseerd scherm) en toch nog de auto proberen te besturen.


## prototype

<p>
  <img src="https://github.com/Noahmen2004/Deelopdracht-4-develop-2-Expert-tests/blob/main/Screenshot%202024-05-21%20143533.png" width="500" 
     height="auto" />

</p>

> - Polaristiefilm interface
> - Vanaf dat ze rijden komt er een film over het scherm die ervoor zorgt dat de chauffeur het scherm niet kan zien

<p>
  <img src="https://github.com/Noahmen2004/Deelopdracht-4-develop-2-Expert-tests/blob/main/Screenshot%202024-05-21%20143758.png" width="500" 
     height="auto" />

</p>

> - Draaiende interface
> - Vanaf dat ze rijden draait het scherm naar de medepassgier zoadat de chauffeur het scherm niet kan zien


## Evaluatie van test

#### Pluspunten:

- Duidelijke navigatie-indicatie via HUD.
- Eenvoudig en intuïtief gebruik van de draaiknoppen.
- Verminderde stress door duidelijke aanwijzingen.
  
#### Minpunten:

- Afleiding van de verkeerslichten in de simulatie.
- Nood aan duidelijke indicaties voor de draaiknoppen (wat is hun functie) en alarm signalen voor ongewenst gedrag.

#### Conclusies
- Veiligheid: Het systeem heeft potentieel om de veiligheid te verbeteren door minder afleidend te zijn dan traditionele schermen.
- Gebruiksgemak: De draaiknoppen werden als zeer gebruiksvriendelijk en intuïtief ervaren.
- Effectiviteit van HUD: De HUD biedt duidelijke navigatie en instructies, wat de bestuurder helpt om de blik op de weg te houden.
- Aanpassingen Nodig: Implementatie van waarschuwingen voor gevaar en afstand, en alarmsignalen voor het ongewenst kijken naar het centrale scherm.
  
#### Aanbevelingen
- Reële Testomstandigheden: Voer verdere tests uit in echte rijomstandigheden om de effectiviteit en veiligheid van het systeem te valideren. Want simulatie had nog verschillen met het effeectief gebruik van een auto.
- Waarschuwingen en Signalen: Implementeer duidelijke waarschuwingen voor gevaar en alarmsignalen om ongewenst gedrag te corrigeren(zoals indicaties als er dichtbij de auto een ongevval gaat gebeuren).
- Indicatielabels: Voorzie duidelijke labels of visuele aanwijzingen voor de functies van de draaiknoppen.
- Verbeterde Simulaties: Optimaliseer de simulatieomgeving om beter de werkelijkheid na te bootsen en mogelijke afleidingen beter te testen.
- Proberen ook eens te testen of een gewone pijl indicatie zoals bij een gps ook even goed werkt.
  <p>
  <img src="Screenshot 2024-05-22 112655.png" width="400" 
     height="auto" />

</p>

> In rood de pijl navigatie die ook eens getest zou moeten worden op de HUD.

## Designrequirements

#### Zijdelingse Verplaatsing:
- Het scherm moet volledig buiten het gezichtsveld van de bestuurder kunnen verschuiven wanneer de auto in beweging is, zodat afleiding geminimaliseerd wordt.

#### Foutenherkenning en -herstel:
- Ingebouwde mechanismen voor het herkennen en herstellen van fouten, zoals pop-up meldingen of geluidssignalen wanneer de bestuurder probeert het scherm te gebruiken tijdens het rijden.
  
#### Minimalistisch Design:
- Vermijd overmatige visuele elementen en houd de interface strak en overzichtelijk om afleiding te minimaliseren.

#### Error Prevention:
- Zorg voor error prevention door eventueel een melding te geven als je toch naar het centraal touchscreen probeert te kijken.
  
## Ontwerpbeslissingen

#### 1. HUD (Heads-Up Display)
- Blauwe Navigatielijnen: De HUD moet duidelijke, goed zichtbare navigatielijnen bevatten om de bestuurder effectief te begeleiden.
- Waarschuwingspictogrammen: Het is nodig om pictogrammen toe te voegen voor gevaren, zoals een uitroepteken, en afstandsindicaties om de bestuurder te waarschuwen voor grote risico's. Alleen grote risicos anders te veel aan het gebeuren op de HUD.
- 
#### 2. Draaiknoppen
- Blindelings Bedienbaar: De draaiknoppen moeten zo ontworpen worden dat ze eenvoudig en intuïtief te gebruiken zijn zonder dat de bestuurder ernaar hoeft te kijken. Dit kan worden bereikt door texturen of vormverschillen aan de knoppen toe te voegen.
- Duidelijke Labels: Er moeten duidelijke visuele indicaties en labels bij de knoppen zijn om hun functies meteen duidelijk te maken.
- 
#### 3. Centrale Scherm
- Polarisatie: Het centrale scherm moet een polarisatiefilm hebben dat zichtbaar is voor de passagier en niet voor de bestuurder tijdens het rijden.
- Alarm Signaal: Een alarm signaal moet worden toegevoegd dat afgaat als de bestuurder probeert naar het centrale scherm te kijken tijdens het rijden.

#### 4. Verhoogde Interactie
- Gebruik van Google Home en Spotify: Gebruiksvriendelijke interfaces zoals Google Home en Spotify moeten geïntegreerd worden, die makkelijk via de HUD of spraak bediend kunnen worden.
- Temperatuur en Volume Aanpassingen: Temperatuur- en volume-aanpassingen moeten eenvoudig via de draaiknoppen bediend kunnen worden zonder afleiding.

## Bijlagen
Protocol: https://docs.google.com/document/d/1Q-Gr13mFpRs562zWZIK_h5xHHILlJB6Ak3FmDEnZr0A/edit <br>
Videos tests: - https://youtu.be/LqED6phG2a4<br>
              - https://youtu.be/_Iaf5eOsnbs <br>



