# Logius Standaard Vastgestelde versie (datum )

> [<span class="underline">Overzicht
> standaarden</span>](https://publicatie.centrumvoorstandaarden.nl/)
> 
> **Deze versie:**
> 
> **Laatst gepubliceerde versie:**
> 
> **Vul link naar betreffende website of document**

**Laatste werkversie:**

> **Vul link naar betreffende website of document**

### Redacteurs:

### Vul hier redacteurs naam en bedrijfsnaam

### 

### Doe mee:

> [<span class="underline">Dien een melding
> in</span>](https://github.com/Logius-standaarden/ADR-Beheermodel/issues/)
> 
> [<span class="underline">Revisiehistorie</span>](https://github.com/Logius-standaarden/ADR-Beheermodel/)
> [<span class="underline">Pull
> requests</span>](https://github.com/Logius-standaarden/ADR-Beheermodel/pulls/)
> 
> This document is also available in this non-normative format:
> [pdf](file://localhost/home/runner/work/ADR-Beheermodel/ADR-Beheermodel/ADR-Beheermodel.pdf)
> 
> This document is licensed under a [<span class="underline">Creative
> Commons Attribution 4.0
> License</span>](https://creativecommons.org/licenses/by/4.0/).

# Samenvatting

> Dit document beschrijft het Beheermodel van: (vul naam standaard in)

# Status van dit document

> Dit is de definitieve versie van de standaard. Wijzigingen naar
> aanleiding van consultaties zijn doorgevoerd.

Het xxx heeft op advies van xxx deze versie vastgesteld.

# Inhoudsopgave

> **Samenvatting**
> 
> **Status van dit document**

1.  **Inleiding**
    
    1.  Leeswijzer 1.2 naam xxxx
        
        1.  Nut
        
        2.  Werking
        
        3.  Status

> 1.3 Bomos

2.  ### Strategie
    
    1.  > Visie
    
    2.  > Governance
        
        1.  Governancestructuur
        
        2.  Besluitvorming
        
        3.  Deelname
    
    3.  > Financering

3.  ### Tactiek
    
    1.  > Community
    
    2.  > Architectuur
        
        1.  Internationale, Europese en nationale
            standaardisatiegemeenschap
        
        2.  Samenwerking met andere beheerorganisaties

> 3.2.2.1 Kennisplatform/community

3.  Nederlandse Overheid Referentie Architectuur (NORA)

4.  Overige belangrijke vermeldingen (zoals overlap met andere
    standaarden)

<!-- end list -->

3.  > Rechtenbeleid

4.  > Kwaliteitsbeleid en benchmarking

5.  > Adoptie en erkenning

<!-- end list -->

4.  ### Operationeel
    
    1.  > Initiatie
    
    2.  > Wensen en Eisen
    
    3.  > Uitvoering en ontwikkeling (Wijzigingsproces)
    
    4.  > Status van de standaard
    
    5.  > Documentatie

5.  ### Implementatieondersteuning
    
    1.  > Opleiding en advies
    
    2.  > Helpdesk
    
    3.  > Validatie & Certificatie

6.  ### Communicatie
    
    1.  > Promotie
    
    2.  > Publicatie
    
    3.  > Klachtenafhandeling

<!-- end list -->

1.  # Inleiding
    
    1.  Leeswijzer

> Dit document beschrijft hoe Logius, afdeling Standaarden (hierna:
> Logius) xxxxx standaard beheert en hoe de bijbehorende governance is
> ingericht.

2.  > (Vul naam van de standaard hier in)

Beschrijf hier de standaard

Voorbeeld:

> De xxx standaard omvat een set van normatieve ontwerpafspraken voor
> het structureren en documenteren. De standaard heeft tot doel om
> betere, uniforme en ontwikkelaar vriendelijke API’s te ontwikkelen die
> makkelijk te implementeren zijn. De set van afspraken bestaat uit
> breed toepasbare en ondubbelzinnige richtlijnen. Deze helpen
> organisaties die nieuwe API’s ontwikkelen voor Nederlandse overheden
> (Rijk, provincies, gemeenten en waterschappen) en instellingen uit de
> (semi-) publieke sector. Het Nut en de werking van de standaard zijn
> reeds goed beschreven door het Forum Standaardisatie en voor de
> eenduidigheid hieronder integraal
> opgenomen [<span class="underline">zie
> link</span>](https://www.forumstandaardisatie.nl/open-standaarden/rest-api-design-rules):
> 
> van de standaard zijn reeds goed beschreven door het Forum
> Standaardisatie en voor de eenduidigheid hieronder integraal opgenomen
> [<span class="underline">zie
> link</span>](https://www.forumstandaardisatie.nl/open-standaarden/rest-api-design-rules):

### Nut

> Beschrijf hier de nut van de standaard
> 
> Voorbeeld:
> 
> De overheid ontsluit gegevens en applicaties steeds vaker met
> standaarden. Voorbeelden hiervan zijn te zien op de website
> developer.overheid.nl, in Common Ground, Haal Centraal en het Digitaal
> Stelsel Omgevingswet.
> 
> Representational state transfer (REST) is een ontwerpprincipe dat
> wereldwijd veel gebruikt wordt voor het bouwen van
> programmeerinterfaces over het web (API's). REST is geen standaard
> maar een ontwerpprincipe, en laat nog veel vrijheid in het
> structureren van API's.
> 
> De standaard REST-API Design Rules geeft een verzameling basisregels
> voor structuur en naamgeving waarmee de overheid op een uniforme en
> eenduidige manier REST-API's aanbiedt. Dit maakt het voor
> ontwikkelaars gemakkelijker om betrouwbare applicaties met te
> ontwikkelen met API's van de overheid. Bron: Forum standaardisatie

### Werking

> Beschrijf hier de werking van de standaard

Voorbeeld:

> Een application programming interface (API) is een gestructureerd en
> gedocumenteerd koppelvlak voor communicatie tussen applicaties. Zo
> lang er computers zijn, bestaan er API's en worden er verschillende
> API technologieën gebruikt. In de laatste 10 jaar heeft
> Representational state transfer (REST) zich ontwikkeld tot een
> bepalend principe voor het realiseren van API's. Zogenaamde
> ‘REST-API's’ doen voor applicaties wat websites voor mensen doen.
> Websites presenteren informatie aan mensen, REST-API's maken
> applicaties en gegevens over het Internet beschikbaar voor andere
> applicaties. De technologie achter websites en REST-API's heeft daarom
> veel gemeen.
> 
> De overheid gebruikt REST-API's voor koppelingen met andere overheden,
> bedrijven en indirect ook met burgers, bijvoorbeeld via mobiele apps
> en webapps die aangeboden worden door bedrijven of overheden zelf.
> Ontwikkelaars kunnen deze REST-API's bevragen vanuit de gangbare
> programmeertalen en frameworks zoals Python, Java, Microsoft C\#, PHP.

<span class="underline">[Bron: Forum
standaardisati](https://www.forumstandaardisatie.nl/open-standaarden/rest-api-design-rules)e</span>

### Status

> Beschrijf hier de status van de standaard
> 
> Voorbeeld:
> 
> De actuele versie van de ADR-standaard is 1.0. Deze versie is op
> 09-07-2020 door het OBDO vastgesteld op advies van het Forum
> Standaardisatie.
> 
> De status van de ADR-standaard is ‘Verplicht (pas toe leg uit)’. Dit
> houdt kort gezegd in dat Nederlandse overheden en instellingen uit de
> (semi) publieke sector verplicht zijn deze standaard toe te passen op
> het moment dat zij REST API’s gaan gebruiken voor het ontsluiten van
> overheidsinformatie en/of functionaliteit. (Zie voor meer informatie
> over het [<span class="underline">pas toe of leg uit
> beleid</span>.](https://www.forumstandaardisatie.nl/node/229))

Voorbeeld:

> De verplichting is gepubliceerd door het Forum Standaardisatie op:
> 
> [<span class="underline">forumstandaardisatie.nl/open-standaarden/rest-api-design-rules</span>](https://www.forumstandaardisatie.nl/open-standaarden/rest-api-design-rules)
> Versie 1.0 van de xxx is gepubliceerd op:
> 
> [<span class="underline">publicatie.centrumvoorstandaarden.nl/api/adr/1.0</span>](https://publicatie.centrumvoorstandaarden.nl/api/adr/1.0)

## ![](./media/image1.png)![](./media/image1.png)![](./media/image2.png)Bomos

> ![](./media/image3.png)Logius richt de beheerorganisatie in conform
> het Beheer en Ontwikkel Model voor Open Standaarden (BOMOS). Ook het
> beheer van de xxxxx is op basis van BOMOS ingericht. Voor de
> beheerorganisatie heeft Logius een generiek beheermodel opgezet, waar
> het beheerplan van xxx is afgeleid.

![](./media/image1.png)

> *Figuur 1 Bomos model*
> 
> ![](./media/image5.png)Voor meer informatie over BOMOS zie ook:

[<span class="underline">BOMOS, het
fundament</span>](https://gitdocumentatie.logius.nl/publicatie/bomos/fundament/)

[<span class="underline">BOMOS, de
verdieping</span>](https://gitdocumentatie.logius.nl/publicatie/bomos/verdieping/)

[<span class="underline">'Publicatie-BOMOS-2i.pdf'</span>](https://www.forumstandaardisatie.nl/sites/default/files/BFS/4-basisinformatie/publicaties/Publicatie-BOMOS-2i.pdf)

> BOMOS onderscheidt verschillende levenscyclusfases waarin een
> standaard zich kan bevinden. Deze fase bepaalt mede op welke
> beheeronderdelen meer of minder wordt ingezet. De verschillende fases
> zijn:

1.  Creatie/ontwikkeling

2.  Introductie

3.  Implementatie/groei

4.  Volwaardige toepassing

5.  Uitfaseren

> ![](./media/image7.png)![](./media/image8.png)Adoptie

![](./media/image10.png)

> Tijd
> 
> *Figuur 2 Bomos levenscyclus*
> 
> De xxx bevindt zich in de xxx fase. De eerste versie van de standaard
> is xxx aangemeld bij het Forum Standaardisatie en op xxx op de lijst
> van verplichte standaarden opgenomen. Vanuit het xxx en Logius
> afdeling Standaarden wordt momenteel nog volop aan de xxx gewerkt en
> de verwachting is dat de standaard nog de nodige ontwikkelingen door
> gaat maken.
> 
> Daarom is er komende tijd vooral aandacht voor:
> 
> Het in de praktijk bestendigen van het beheer van de standaard;
> Gestaag doorontwikkeling van de specificaties zelf;
> 
> Bouwen en aanbieden ondersteunende tooling; Groei in het aantal
> toepassingen van de standaard; Monitoring van het gebruik van de
> standaard; Groei van de community rond de standaard.

# Strategie

> De strategische activiteiten van BOMOS bestaan uit de onderdelen
> Visie, Govenance en Financiering. Deze onderdelen en hun toepassing op
> het beheer van xxxx worden hieronder beschreven.

## Visie

> Met de xxx standaard wil de Nederlandse overheid interoperabiliteit
> bevorderen. Dit komt erop neer dat overheden dezelfde standaard in
> vergelijkbare situaties toepassen. Dit maakt uiteindelijk dat
> componenten en systemen onderling effectief gegevens uit kunnen
> wisselen. Zowel horizontaal in één voorziening binnen één situatie als
> verticaal tussen voorzieningen in verschillende situaties en tussen
> organisaties. Deze doelstelling wordt onderschreven door een breed
> scala aan partijen die deelnemen aan het xxx Kennisplatform, waar de
> ontwikkeling van de standaard zijn oorsprong heeft, en is bestendigd
> door Forum
> 
> Standaardisatie en het OverheidsBrede Beleidsoverhed Digitale Overheid
> (OBDO), die xxxx standaard hebben opgenomen op de zogenaamde ‘pas toe
> of leg uit’-lijst met andere standaarden die interoperabiliteit
> bevorderen [<span class="underline">zie ook de basisinformatie van het
> Forum
> Standaardisatie</span>](https://www.forumstandaardisatie.nl/basisinformatie).

De toetsingsprocedure voor opname van een standaard op pas toe of leg
uit’-lijst bestaat uit de volgende

stappen:

1\. Aanmelding

2\. Intake

> 3\. Expertonderzoek

4\. Openbare consultatie

5\. Advisering door het Forum Standaardisatie

6\. Vaststelling door het Overheidsbreed Beleidsoverleg Digitale
Overheid

> Deze criteria staan op: [Toetsingsprocedure en criteria voor lijsten
> met open standaarden
> (forumstandaardisatie.nl)](https://www.forumstandaardisatie.nl/sites/default/files/BFS/3-lijsten/standaarden-aanmelden/toetsen/Toetsingsprocedure-en-criteria-22_0.pdf)
> 
> De afdeling Standaarden van Logius werkt samen met het Forum
> Standaardisatie aan de promotie van open standaarden via
> kennisplatforms, bijeenkomsten en seminars. De standaarden die Logius
> beheert, zijn verplichte standaarden voor overheidsorganisaties en
> staan op de 'Pas toe of leg uit'-lijst van het Forum of zijn verplicht
> via wetgeving.

2.  ## Governance
    
    1.  ### Governancestructuur

> Bij het beheer van een open standaard hoort een open governance en een
> open procedure voor belanghebbenden om te kunnen participeren in het
> beheer. xxx neemt hierin de rol van onafhankelijke, duurzame
> beheerpartij en facilitator. Bij het beheer van de xxx worden
> verschillende gremia onderscheiden die gezamenlijk invulling geven aan
> de governance op de standaard:

1.  xxx-community (Interesse Groep - IG)

> Dit is het meest operationele gremium waarin iedere
> belangstellende/belanghebbende vragen kan stellen over de
> xxx-standaard en suggesties kan doen voor de doorontwikkeling van de
> standaard. Dergelijke vragen en suggesties worden door xxx verzameld
> en voorgelegd aan het Technisch Overleg en als issue geregistreerd bij
> de werkgroep xxx van het kennisplatform xxx

2.  Technisch Overleg (Technische Architectuur Groep – TAG)

> Het Technisch Overleg is een periodieke bijeenkomst van de Technische
> Architectuur Groep (TAG) waarbij de vragen en doorontwikkelwensen
> m.b.t. de xxx worden doorgenomen, geprioriteerd en worden uitgewerkt.
> Daarnaast wordt door de leden de releaseplanning en de roadmap
> opgesteld. Deelname aan de TAG is vrij voor eenieder die een belang
> heeft bij de standaard (overheid, wetenschap en markt)

3.  Tactisch overleg xxx

> Dit gremium is verantwoordelijk voor het vaststellen van de
> doorontwikkel-roadmap, het vaststellen van minor releases van de
> standaard en dient als het voorportaal van het
> strategisch/besluitvormende gremium: het OBDO.

4.  Het Overheidsbrede Beleidsoverleg Digitale Overheid (OBDO)

> Dit is het hoogst ambtelijke gremium dat besluit over major releases
> van de standaard, het beheermodel van de standaard en externe
> publicaties over releases en van het standaardenbeleid. Op dit moment
> wordt het OBDO louter ‘gevoed’ door Forum Standaardisatie en is de
> focus voornamelijk het bestendigen van major releases van de
> standaard. Op het moment dat het tactische gremium is ingevuld, zal
> het OBDO waarschijnlijk een breder scala aan onderwerpen langs krijgen
> ter bestendiging.
> 
> De MIDO structuur kan ook de mogelijkheid bieden om de
> Programmeringsraad GDI te laten besluiten over de standaarden.
> Wijzigingen worden dan ter informatie aan het OBDO voorgelegd.
> 
> Het strategisch overleg neemt besluiten op basis van adviezen van de
> tactisch en strategische overleggen en het advies van de
> beheerorganisatie. Daarnaast kan het strategisch overleg een
> richtinggevend besluit nemen wat aan de beheerorganisatie voorgelegd
> wordt. Bijvoorbeeld een ingrijpende wijziging zoals het overgaan naar
> een nieuwe (onderliggende) standaard kan in het strategisch overleg
> besloten worden.
> 
> In tabelvorm:

<table>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Gremium</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Accent</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Rol participant</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Ondersteuning door beheerder (Logius)</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p><strong>Xxx Community</strong></p>
<p>(omvang onbeperkt)</p>
</blockquote></td>
<td><blockquote>
<p>Inhoud – delen</p>
</blockquote></td>
<td><blockquote>
<p>Samen met alle leden van de Interesse Groep (IG):</p>
</blockquote>
<ol type="1">
<li><p>Volgen van ontwikkelingen.</p></li>
<li><blockquote>
<p>Leveren van input voor de doorontwikkeling van de standaard.</p>
</blockquote></li>
</ol></td>
<td><ol type="1">
<li><p>Informatie m.b.t. specificaties en beheer open delen met community.</p></li>
<li><p>Deelnemen aan stuurgroep en werkgroepen van</p></li>
</ol>
<blockquote>
<p>Kennisplatform xxx</p>
</blockquote></td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Gremium</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Accent</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Rol participant</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Ondersteuning door beheerder (Logius)</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p><strong>xxxTechnisch Overleg</strong> (Operationeel, 4x per jaar)</p>
</blockquote></td>
<td><blockquote>
<p>Inhoud - afstemmen</p>
</blockquote></td>
<td><blockquote>
<p>Samen met andere experts van de Technische Architectuur Groep (TAG):</p>
</blockquote>
<ol type="1">
<li><p>Inhoudelijk ontwikkelen van standaard onderdelen en bijbehorende documentatie.</p></li>
<li><p>Voorbereiden van de release- planning.</p></li>
<li><p>Prioriteiten stellen voor de ontwikkeling, roadmap van nieuwe releases van de standaarden.</p></li>
<li><p>Goedkeuring van aanpassingen op de standaard.</p></li>
</ol></td>
<td><ol type="1">
<li><p>Analyseren, ontwerpen en uitwerken van specificaties.</p></li>
<li><p>Volgen en beïnvloeden van aanpalende standaarden.</p></li>
<li><blockquote>
<p>Organiseren bijeenkomsten.</p>
</blockquote></li>
<li><p>Opstellen en verspreiden notulen.</p></li>
<li><p>Beschikbaar stellen specificaties.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><blockquote>
<p><strong>Tactisch/Strategisch</strong></p>
<p>(4x per jaar)</p>
</blockquote></td>
<td><blockquote>
<p>Prioritering proces en uitwerken strategisch advies</p>
</blockquote></td>
<td><blockquote>
<p>Samen met andere participanten:</p>
</blockquote>
<ol type="1">
<li><p>Vaststellen roadmap van de standaard.</p></li>
<li><blockquote>
<p>Voorportaal OBDO</p>
</blockquote></li>
<li><p>Vaststellen minor releases van de standaard.</p></li>
</ol></td>
<td><blockquote>
<p>1. Analyseren, ontwerpen en uitwerken van beleidszaken, (release)planning.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p><strong>OBDO</strong></p>
<p>(Strategisch besluitvormend, 2x per jaar)</p>
</blockquote></td>
<td><blockquote>
<p>Bestuurlijk besluit</p>
</blockquote></td>
<td><blockquote>
<p>Samen met andere bestuurders:</p>
</blockquote>
<ol type="1">
<li><p>Vaststellen major releases van de standaard.</p></li>
<li><p>Vaststellen beheermodel van de standaard.</p></li>
<li><blockquote>
<p>Vaststellen externe publicaties over</p>
</blockquote></li>
</ol>
<blockquote>
<p>het standaardenbeleid en releases.</p>
</blockquote></td>
<td><ol type="1">
<li><p>Begeleiding van de Adviesraad en inbreng via secretariaat OBDO.</p></li>
<li><p>Publiceren standaarden en andere Standaard-informatie.</p></li>
</ol></td>
</tr>
</tbody>
</table>

### Besluitvorming

> In alle overleggremia vindt besluitvorming plaats op basis van
> consensus. Mocht consensus niet mogelijk zijn, dan gaat het vraagstuk
> met een weergave van de verschillende standpunten door naar het
> eerstvolgend-hoger gelegen-gremium. Indien in het hoogste gremium (het
> OBDO) geen consensus bereikt kan worden, heeft de voorzitter van het
> OBDO (min. BZK) de beslissende stem.

### Deelname

> Uitbreidingen en aanpassingen in de xxx standaard komen tot stand door
> participatie van de verschillende belanghebbenden. Belanghebbenden
> kunnen op vier manieren participeren aan het wijzigings- en
> besluitvormingsproces:

1.  Als lid van de xxx Community van het Kennisplatform / de Interesse
    Groep (IG)

2.  Als lid van de Technische Architectuur Groep (TAG)

3.  Als lid van het Tactisch overleg

4.  Als lid van het MIDO of OBDO

> *Ad 1) Deelname aan de xxx-Community staat open voor alle
> belanghebbenden; Ad 2) Invulling van het Tactisch overleg volgt, zodra
> bekend is welk gremium dit is;*
> 
> *[Ad 3) Het OBDO kent een vaste vertegenwoordiging
> .<span class="underline">Zie voor meer informatie de governance
> van</span> <span class="underline">Digitaleoverheid.nl
> </span>](https://www.digitaleoverheid.nl/governance-digitale-overheid/)*
> 
> *Ad 4) Aangezien het overleg van de Technische Architectuur Groep (het
> Technisch Overleg) het eerste besluitvormende gremium is van de
> standaard, en besluitvorming in dit gremium plaatsvindt op basis van
> consensus, stelt Logius een aantal voorwaarden aan deelname:*

1.  Leden van het technisch overleg dienen een aantoonbaar belang te
    hebben bij de standaard.

2.  De omvang en samenstelling moet een goede vertegenwoordiging
    bevatten van de verschillende belangen rond de standaard. We gaan
    uit van 1 deelnemer per organisatie.

3.  Het belang van de Nederlandse overheid dient voldoende geborgd te
    zijn in het technisch overleg.

> Personen/partijen die willen deelnemen aan het technisch overleg
> kunnen een mail sturen aan xxxx waarin zij aangeven wat hun belang is
> bij de standaard. Met inachtneming van bovenstaande punten, beoordeeld
> Logius de aanvraag.

## Financering

> Het beheer van de xxx standaard wordt gefinancierd door min. BZK voor
> een initiële periode van tenminste drie jaar (2020-2023) om gebruikers
> het vertrouwen te geven dat er geen desinvesteringen worden gedaan bij
> het implementeren van de standaard. Na drie jaar wordt de financiering
> verlengd als blijkt dat het nut van en de behoefte aan de standaard
> nog aanwezig is.

3.  # Tactiek
    
    1.  ## Community

> De xxx community/ Interesse Groep bestaat uit eenieder die
> belanghebbende of belangstellende is m.b.t. de standaard. Deelname aan
> de community kent geen drempels of restricties. Leden van de community
> kunnen alle informatie m.b.t. de standaard en het beheer daarvan
> inzien via de website en via verschillende kanalen issues of RFC's
> melden. Daarnaast kunnen community leden reageren op openbare
> consultaties en onder bepaalde voorwaarden deelnemen aan de Technische
> Architectuur Groep (zie paragraaf
> <span class="underline">deelname</span>).

## Architectuur

> De xxx standaard is een op zichzelf staande standaard en geen
> onderdeel van een bovenliggende standaard. Wel wordt er in de ADR
> verwezen naar verschillende andere (internationale) standaarden.

### Internationale, Europese en nationale standaardisatiegemeenschap

> De xxx volgt de ontwikkeling van internationale standaarden (zoals
> bijvoorbeeld de HTTP standaarden van het IETF) in het algemeen. Meer
> specifiek volgen de specialisten van Logius en de leden van de TAG de
> standaarden waarnaar wordt gerefereerd in de standaard en bespreken
> deze ontwikkelingen ook in het Technisch Overleg. Indien relevant
> worden op basis van de internationale ontwikkelingen rfc's opgesteld
> om de xxx standaard aan te passen, verbeteren of actualiseren.

### Samenwerking met andere beheerorganisaties

> *3.2.2.1 Kennisplatform/community <span class="underline">
> xxxx</span>*
> 
> Kennisplatform of community xxx is een initiatief van xxx, xxx, en
> Logius. Het doel van het Kennisplatform is om de kennis over het
> toepassen van xxx uit te wisselen en de aanpak bij verschillende
> organisaties op elkaar af te stemmen en waar nodig te standaardiseren.
> In het kennisplatform/community wordt gezamenlijk gekeken naar
> strategische en tactische vraagstukken rond het ontwikkelen van de
> standaard xxx door de overheid en gebruik van de standaard xxx buiten
> en binnen de overheid. Dit vanuit de gedachte dat we in een digitale
> samenleving eenvoudig met elkaar moeten kunnen samenwerken.
> 
> De xxx standaard komt voort uit xxx die beheerd wordt door het
> Kennisplatform/community xxx en is door het kennisplatform/community
> ontwikkeld. Op het moment dat er in het kennisplatform consensus was
> over de kwaliteit van de xxx standaard en de wenselijkheid deze via
> het 'pas toe of leg uit' -principe normatief te laten verklaren is de
> standaard voorgedragen aan Forum Standaardisatie voor het verkrijgen
> van de voor overheden verplichte 'pas toe of leg uit' status en heeft
> Logius het beheer van dit normatieve deel op zich genomen.

### Nederlandse Overheid Referentie Architectuur (NORA)

> De xxx standaard volgt de principes van de Nederlandse Overheid
> Referentie Architectuur. Zie voor meer informatie:
> [<span class="underline">https://www.noraonline.nl/wiki/NORA\_online</span>](https://www.noraonline.nl/wiki/NORA_online)

4.  ### 
    
    1.  
    2.  
## Rechtenbeleid

> [De xxx Standaard zelf en dit beheermodel vallen onder de Creative
> Commons licentie (<span class="underline">Creative Commons</span>
> <span class="underline">Attribution 4.0 License</span>) Dit houdt in
> dat het is toegestaan om deze documenten te gebruiken, verder
> te](https://creativecommons.org/licenses/by/4.0/) verspreiden en aan
> te passen. Dit werk en de specificaties van de xxx standaard worden
> royaltee-free ter beschikking gesteld. Organisaties en personen die
> bijdragen aan de ADR dienen dit onder dezelfde voorwaarden te doen als
> bij het originele werk. Door bij te dragen aan de ADR verklaren zij
> hiermee in te stemmen.
> 
> Uitgesloten van alle bovenstaande zijn rechten verbonden aan de
> standaarden, profielen en andere onderdelen waar de xxx gebruik van
> maakt. Hierop zijn de rechten van de betreffende standaarden,
> profielen en andere onderdelen zelf van toepassing. Dit zijn in geval
> van de xxx allemaal open standaarden.

## Kwaliteitsbeleid en benchmarking

> Zoals gezegd wordt het beheer van de xxx standaard volledig open
> ingevuld (zie ook de paragraaf <span class="underline">Bomos</span> en
> <span class="underline">Governance</span>) Dit borgt dat zoveel
> mogelijk belangstellenden en belanghebbenden betrokken zijn bij
> wijzigingen en besluitvorming die wijzigingen.

## Adoptie en erkenning

> De xxx standaard heeft de 'pas toe of leg uit' -status van Forum
> Standaardisatie. Dit betekent kort gezegd dat Nederlandse
> overheidspartijen en partijen uit de (semi) publieke sector deze
> standaard dienen toe te passen op het moment dat zij hun informatie
> met behulp van xxx standaard willen ontsluiten. Zie hoofdstuk 1 voor
> meer informatie.

4.  # Operationeel
    
    1.  ## Initiatie

<!-- end list -->

1.  Uitbreidingen en aanpassingen in de xxx standaarden komen tot stand
    door participatie van de verschillende belanghebbenden.

2.  Belanghebbenden kunnen op vier manieren participeren: als lid van de
    xxx Community en/of de Technische Architectuur Groep en/of als lid
    van de Adviesraad of als lid van het OBDO.
    
    1.  ## Wensen en Eisen

> RFC's kunnen binnen komen via verschillende kanalen:

1.  Rechtstreeks bij Logius, tijdens overleggen, via de website of mail

2.  Bij de werkgroep xxx van de standaard en tijdens overleggen, via de
    website of mail

> RFC's worden als issue's geregistreerd in de repository van het
> kennisplatform/community op Github: voorbeeld:
> <https://github.com/Geonovum/KP-APIs/issues>
> 
> Om te voorkomen dat er verschillende lijsten met issues en verzoeken
> ontstaan, is met het kennisplatform/community afgesproken dat ieder
> issue en verzoek als eerste wordt beoordeeld door de werkgroep van xxx
> standaard. Dit voorkomt het ontstaan van verschillende stromen met
> RFC's en geeft de werkgroep de gelegenheid om in te schatten of de RFC
> betrekking heeft op de xxx standaard die Logius beheert, of dat er
> sprake is van een verzoek dat het best kan landen in één van de (niet
> normatieve) extensies die het kennisplatform/community beheert.
> 
> Dit houdt concreet in dat RFC's die rechtstreeks bij Logius worden
> neergelegd, door Logius worden doorgespeeld aan de werkgroep van de
> xxx standaard zodat daar de eerste beoordeling kan plaatsvinden.
> 
> ![](./media/image11.png)*Figuur 3 ADR RFC Procesmodel*

## Uitvoering en ontwikkeling (Wijzigingsproces)

> De procedure van RCF naar daadwerkelijke wijziging ziet er als volgt
> uit:
> 
> Issues die in behandeling worden genomen worden als RFC gelabeld RFC's
> worden besproken en uitgewerkt in de Werkgroep xxx
> 
> RFC's worden vastgesteld in Technisch Overleg (TO) RFC worden na
> vaststelling in het TO Openbaar geconsulteerd
> 
> Na vaststelling volgt publicatie van de nieuwe versie van standaard
> 
> N.B. Zolang de afdeling Standaarden van Logius nog geen predicaat
> "Uitstekend beheer" heeft ontvangen van Forum Standaardisatie, zullen
> nieuwe versies na vaststelling in het TO aan Forum Standaardisatie
> worden voorgelegd ter beoordeling.
> 
> N.B.2. Het technisch overleg is momenteel samengevoegd met het
> structurele overleg van de werkgroep ADR van het Kennisplatform
> 
> Dit is schematisch weergegeven in het onderstaande ADR Governance
> model:
> 
> *Figuur 4 ADR Governance model*

## Status van de standaard

> Logius, afdeling standaarden onderscheid vier statussen die de xxx
> standaard kan hebben:

<table>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Afkorting</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Status van de standaard</strong></p>
</blockquote></th>
<th><blockquote>
<p><strong>Beschrijving van de status</strong></p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><blockquote>
<p>IO</p>
</blockquote></td>
<td><blockquote>
<p>In Ontwikkeling</p>
</blockquote></td>
<td><blockquote>
<p>Een nieuwe release van de standaard is "In Ontwikkeling" wanneer er met medeweten en medewerking van participanten aan gewerkt wordt en wanneer dit onderdeel of deze release nog niet voor de buitenwereld is gepubliceerd.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>IG</p>
</blockquote></td>
<td><blockquote>
<p>In Gebruik</p>
</blockquote></td>
<td><blockquote>
<p>Als een nieuwe release van de standaard gereed is, en is bestendigd door Forum Standaardisatie, stelt het Technisch Overleg de status 'In Gebruik' vast. Door deze vaststelling worden gebruikers en ICT-leveranciers opgeroepen deze nieuwe release op te nemen in software en in gebruik te nemen.</p>
</blockquote></td>
</tr>
<tr class="odd">
<td><blockquote>
<p>EO</p>
</blockquote></td>
<td><blockquote>
<p>Einde Ondersteuning</p>
</blockquote></td>
<td><blockquote>
<p>De standaardversie met de status "Einde ondersteuning" wordt niet meer ondersteund door de beheerder. De kennis en informatie voor vragen en support is bij de beheerder niet langer beschikbaar.</p>
</blockquote></td>
</tr>
<tr class="even">
<td><blockquote>
<p>TG</p>
</blockquote></td>
<td><blockquote>
<p>Teruggetrokken</p>
</blockquote></td>
<td><blockquote>
<p>De standaard krijgt de status "Teruggetrokken" indien een release van de standaard niet bruikbaar blijkt (bijv. vanwege implementatieproblemen).</p>
</blockquote></td>
</tr>
</tbody>
</table>

## Documentatie

> Alle documenten m.b.t. de standaard en het beheer van de standaard
> worden openbaar en zonder drempels voor gebruik, gepubliceerd op
> logius.nl en onze Github pagina's. Logius publiceert tenminste de
> volgende documenten:
> 
> Dit beheermodel
> 
> De vergaderstukken van het Technisch overleg en overige
> besluitvormende gremia.
> 
> De specificaties van de standaard
> 
> De voorlopige specificaties van de nieuwe versie van de standaard.
> 
> Versie xx van de xx is gepubliceerd op:
> 
> voorbeeld:
> [<span class="underline">https://publicatie.centrumvoorstandaarden.nl/api/adr/1.0</span>](https://publicatie.centrumvoorstandaarden.nl/api/adr/1.0)
> De

5.  # Implementatieondersteuning
    
    1.  ## Opleiding en advies

> Voorbeeld tekst: Logius biedt momenteel geen opleiding aan, maar borgt
> dat de informatie m.b.t. de standaard altijd, zonder drempels,
> toegankelijk is. Bovendien kunnen geïnteresseerden via verschillende
> kanalen contact opnemen met Logius in geval van vragen of opmerkingen.
> Zie hiervoor 5.2 Helpdesk.
> 
> Aanvullend organiseert het Kennisplatform/community regelmatig
> overleggen en seminars m.b.t. de xxx standaard.

## Helpdesk

> Logius biedt ondersteuning en advies via verschillende kanalen:
> 
> Online: als reactie op issue's in de Github van het Kennisplatform:
> 
> xxxxx
> 
> Per mail: <span class="underline">[xx](mailto:api@logius.nl)x</span>
> 
> Telefonisch: xxxx
> 
> Per post: xxxx

## Validatie & Certificatie

> Voorbeeld tekst: Met xxx worden standaardisatiecommunities ondersteund
> en geïnspireerd bij het structureel vormgeven van het beheer en
> verdere ontwikkelingen van standaarden. xxx is niet verplicht en is
> ook geen conformiteitsbeoordeling.

xxx kan op verschillende manieren gebruikt worden:

  - voor het opzetten van beheer van standaarden of stelsels

  - als hulpmiddel voor verdere ontwikkeling van beheerorganisaties

  - als richtlijn om aan te voldoen

  - als onderbouwing voor het aanvragen van de status ‘Uitstekend
    Beheer’ van uw standaard bij Forum Standaardisatie

  - als inspirerend naslagwerk

> Voorbeeld tekst:
> 
> Certificatie van xxx is op dit moment niet mogelijk. Wel is het
> mogelijk xxx te valideren en te testen met behulp van xxx tools welke
> beschikbaar zijn op:

  - [voorbeeld](https://developer.overheid.nl/) &

  - [voorbeeld](https://api-test.nl/)

> Na validatie met de API-test tool is het mogelijk een badge te
> genereren waarmee aangetoond wordt dat de API voldoet aan alle test
> voorwaarden.

6.  # Communicatie
    
    1.  ## Promotie

> De xxx-standaard wordt via verschillende kanalen gepromoot. Ten eerste
> via het Kennisplatform/community. Naast communicatie op de website van
> het kennisplatform/community, organiseert het platform regelmatig vrij
> toegankelijke bijeenkomsten.
> 
> Daarnaast heeft de standaard de zogenaamde 'pas toe of leg uit'
> -status van Forum Standaardisatie. Dit betekent dat Forum
> Standaardisatie het gebruik van deze standaard niet alleen actief
> promoot, maar in veel gevallen zelfs hard voorschrijft.
> 
> Tot slot is Logius promotor van de standaard. Zowel intern voor de
> toepassing van de standaard in Logius voorzieningen als extern, door
> andere partijen te informeren en adviseren over de mogelijkheden van
> de standaard.

## Publicatie

> Als een nieuwe versie van de xxx standaard de status "In Gebruik"
> heeft, worden verschillende zaken gepubliceerd.
> 
> Logius publiceert altijd de volledige specificatie van de standaard op
> een deel van zijn website. Daarnaast wordt een persbericht uitgegeven,
> waarin de publicatie van de nieuwe release van de standaard wordt
> aangekondigd. Aanvullend publiceert Logius alle genoemde documentatie
> zoals genoemd bij<span class="underline">Documentatie</span>.

## Klachtenafhandeling

> Klachten over de opzet of de uitvoering van het beheerproces kunnen
> ingediend worden bij Logius. Dit kan in principe via alle beschikbare
> kanalen (zie bij 5.2). De indiener van de klacht krijgt zo spoedig
> mogelijk en altijd terugkoppeling over de voortgang van en beslissing
> over zijn klacht.
> 
> De volledige klachtenprocedure is terug te vinden in het generieke
> beheermodel van Logius, afdeling standaarden. (volgt)
> 
> <span class="underline">↑</span>
