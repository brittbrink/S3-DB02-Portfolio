# S3-DB02-Portfolio

 
![alt text](https://pro2-bar-s3-cdn-cf.myportfolio.com/63f9ca06-04f8-40d6-9254-e23a34a31357/b8774d32-34ee-4fe4-a5d8-d987fc625211.gif?h=035b5a45a3474d1696c4524d788f6716)



# Inhoudsopgave:

  + [Leeruitkomst 1: Web applicatie](#leeruitkomst-1-web-applicatie)
  + [Leeruiktomst 2: Software kwaliteit](#leeruitkomst-2-software-kwaliteit)
  + [Leeruitkomst 3: Agile methode](#leeruitkomst-3-agile-methode)
  + [Leeruitkomst 4: CI/CD](#leeruitkomst-4-ci-cd)
  + [Leeruitkomst 5: Culturele verschillen en ethiek](#leeruitkomst-5-culturele-verschillen-en-ethiek)
  + [Leeruitkomst 6: Vereisten en ontwerp](#leeruitkomst-6-vereisten-en-ontwerp)
  + [Leeruitkomst 7: Business processen](#leeruitkomst-7-business-processen)
  + [Leeruitkomst 8: Professioneel](#leeruitkomst-8-professioneel)

## Leeruitkomst 1: Web applicatie

  **Leeruitkomst**: Je ontwerpt en bouwt **gebruiksvriendelijke**, **full-stack** webapplicaties. 

  **Gebruiksvriendelijk**: Je past basistechnieken voor het testen en ontwikkelen van gebruikerservaringen toe. 

  **Full-stack**: Je ontwerpt en bouwt een full-stack applicatie met behulp van algemeen geaccepteerde front-end (Javascript-gebaseerd raamwerk) en back-end technieken (bijv. Object Relational Mapping) waarbij relevante communicatieprotocollen worden gekozen en geïmplementeerd en asynchrone communicatieproblemen worden aangepakt.

  
  <details>
  <summary><h4> Mijn webapplicatie </h4></summary>

*Productbeschrijving:* </br>
Met mijn webapplicatie kun je je verbrandde calorieën ingeven en worden er vervolgens recepten opgehaald die deze calorieën bevatten. Zo eet je de calorieën die je verbrand hebt via een maaltijd. Daarnaast kun je inloggen om je favorieten te bekijken die je hebt aangeklikt en krijg je een historie te zien met de recepten die je al is hebt gezien. Hierdoor worden deze recepten niet meer voor jou gegenereerd, zodat er variatie blijft.

*Frontend taal:* </br>
Voor de frontend heb ik de taal React gekozen, dit omdat het makkelijker te leren is[^1]. Ik heb zelf nog maar een jaartje ervaring met coderen in C# (backend) en voor de frontend html/css. Ik wilde niet een te grootte stap vooruit nemen en mezelf in de war laten komen door alle talen. Ook kan ik vanauit React snel overswitchen naar een mobile app maken, zo kan ik mezelf uitdagen binnen de taal React. Ook is React door de meeste developers gebruikt[^2]. 


*Backend taal:* </br>
Voor de backend heb ik de taal Java Springboot gekozen. In ons groepsproject hebben wij besloten dit te gaan doen, ik wilde ervoor zorgen dat ik extra ervaring op kon doen binnen Java Springboot en heb daarom ook in mijn individuele project ervoor gekozen om in Java Springboot te werken. Ook developers kiezen Java Springboot als meest gebruikte programmeer taal.[^2][^3]


[^1]: [bron: alidaschool](https://www.alidaschool.com/blog/react-vue-or-angular-the-best-javascript-framework-to-learn-to-get-a-front-end-job#:~:text=If%20you're%20a%20beginner%20developer%20or%20junior%20developer%2C%20I,native%20to%20build%20mobile%20apps.)
[^2]: [bron: stackoverflow survey](https://insights.stackoverflow.com/survey/2021#technology-most-popular-technologies)
[^3]: [bron: hackr.io](https://hackr.io/blog/c-sharp-vs-java#:~:text=Java%20is%20class%2Dbased%20and,oriented%20languages%20with%20strong%20communities.)

 ```
  DOT framework method:
  - Survey
  - Focus group
  ```
</details>


<details>
  <summary><h4> Op welke manier kan een ORM de security van mijn web applicatie verbeteren? </h4></summary>

Doormiddel van een forms die we hebben gekregen via Jean-Paul, ben ik erachter gekomen dat ik onderzoek moest gaan doen naar ORM's. Ik wist nog niet goed wat dit was, maar heb er wel van geleerd nadat ik de forms teruggekoppeld kreeg. Zo heb ik uit de forms de functie van een ORM weten te halen.

 <h5> Wat is een ORM? </h5>
 Een ORM staat voor Object Relational Mapping. Dit houdt in dat er via code een database gegenereert kan worden en andersom. Ik heb dit nog bevestigt door research te doen op het internet. Een ORM convert gegevens tussen systemen met behulp van programmeertalen[^10]. Bij objectgeoriënteerd programmeren kun je gebruik maken van een ORM library, dit zorgt ervoor dat je bijvoorbeeld niet je hele query hoeft uittetypen met SQL en dus tijd bespaart[^11]. 
 
 Er zijn verschillende ORM libraries voor verschillende programmeertalen, elke programmeertaal heeft een bijpassende ORM library: 
 
- Java: Hibernate
- C#: NHibernate of Entity Framework
- Python: SQLAlchemy[^11]

<h5> Waar dient een ORM voor? </h5>

 <h5> Welke verschillende Java ORM's zijn er? </h5>
 
<h5> Wat zijn de voor en nadelen van een ORM op basis van security? </h5>

<h5> Prototyping? </h5>

Er zijn meerdere technieken die ervoor zorgen dat ORM-code net zo goed presteert als met de hand gecodeerde code. Moderne ORM's bevatten namelijk technieken zoals gretig laden en batchgewijs updaten die ingewikkeld zijn om te implementeren met hand gecodeerde code. Doordat de ORM-code net zo goed presteert als met de hand gecodeerde code maak je geen kosten aan het beheersen en onderhouden van complexe SQL en handgeschreven code[^12].

Een probleem bij grotere projecten, is dat de omvang van het databasemodel erg groot is (veel relaties tussen veel modellen). Om 1 gigantische query te doen en dan alles in 1 stap op te halen is niet sneller, zeker niet als je niet altijd alle informatie nodig hebt. De verleiding is groot bij een JDBC-benadering om één gigantische query te gebruiken, omdat het aanzienlijk langer (en meer werk) is om N queries te doen. Met ORM is het een beetje het tegenovergestelde, standaard zijn N queries makkelijker te doen. Alleen kan je hier tegen het N+1 probleem aanlopen, die je wilt vermijden, dit kan je oplossen door de techniek gretig laden toe te passen, die moderne ORM's bevatten[^13][^14]. Echter is het eenvoudiger om het aantal queries te verminderen door tabellen samen te voegen in plaats van queries te splitsen, ORM-prestatieoptimalisatie voelt natuurlijker aan[^12].

 <h5> Conclusie: </h5>
 Door verschillende technieken presteert ORM-code net zo goed als code die met de hand is gecodeerd. Maar het nadeel van hand gecodeerde code en het schrijven van SQL queries is dat 1 gigantische query, die alles in 1 keer ophaalt, er lang over doet. Een ORM daarintegen gebruikt N queries, waarmee je tegen een N+1 probleem aanloopt. Maar om dit op te lossen bevat een ORM een techniek die dit kan verhelpen. Dit is makkelijker en geeft minimale kosten dan de SQL uit elkaar te pluizen op fouten en de grote van de query, om de performance te maximaliseren. 
 <br></br>
 
```
  DOT framework method:
  - Survey
  - Literature study
  ```
  
 [^10]: [bron: stackoverflow ORM](https://stackoverflow.com/questions/1279613/what-is-an-orm-how-does-it-work-and-how-should-i-use-one.) </br>
 [^11]: [bron: wikipedia ORM](https://en.wikipedia.org/wiki/Object%E2%80%93relational_mapping.) </br>
 [^12]: [bron: infoq](https://www.infoq.com/articles/optimizing-orm-performance/) </br>
 [^13]: [bron: inspector](https://inspector.dev/make-your-application-scalable-optimizing-the-orm-performance/) </br>
 [^14]: [bron: chase the devil](https://chasethedevil.github.io/post/use-orm-for-better-performance/) </br>

  </details>
    
## Leeruitkomst 2: Software kwaliteit

 **Leeruitkomst**: Je gebruikt **softwaretooling en -methodiek** die de softwarekwaliteit tijdens de softwareontwikkeling continu bewaakt en verbetert. </br>

  **Tooling en methodiek**: Uitvoeren, bewaken en rapporteren over unit integratie, regressie en systeemtesten, met aandacht voor security en performance aspecten,
  netzoals het toepassen van statische code analyse en code reviews.

   <details>
   <summary><h4> Code quality </h4></summary>
 
 ![image](https://user-images.githubusercontent.com/99249005/205012992-ea99146b-94a3-4493-89b9-f0999a280c6b.png) [^15]
  
 ![image](https://user-images.githubusercontent.com/99249005/205012912-1e261373-2df8-4a82-81ea-53eb7b61fc19.png) 

![image](https://user-images.githubusercontent.com/99249005/205012755-4f9a41b9-d291-4cde-9fc2-1966ea9d2618.png)

 ![image](https://user-images.githubusercontent.com/99249005/205013808-05278258-0967-4387-b31b-9d0a3234d32c.png)

![image](https://user-images.githubusercontent.com/99249005/205015760-3bcdc85a-6ac6-436f-b388-88041de73dac.png) [^16]
toegevoegd aan settings.xml file
 
![image](https://user-images.githubusercontent.com/99249005/205019103-4fe79830-cce3-4eff-af0d-a106cb9fe133.png)

 ![image](https://user-images.githubusercontent.com/99249005/205019207-d88c13fd-c6ef-46da-845f-930a34335c09.png)

 ![image](https://user-images.githubusercontent.com/99249005/205020863-8c5f140c-c790-4dd5-a4a2-e7df88e2d04b.png)
geprobeerd omdat ik building failed kreeg
 ![image](https://user-images.githubusercontent.com/99249005/205021343-b023a3c9-90f2-49ed-a623-9e3b2e1e32ac.png)
maar werkt niet
 
 mvn clean verify sonar:sonar   -Dsonar.projectKey=projectSemester3   -Dsonar.host.url=http://localhost:9000   -Dsonar.login=sqp_f117f63345b04852876bc112ccfebadf139ac331 dit gerund en nu doet ie het wel.
 
 ![image](https://user-images.githubusercontent.com/99249005/205022109-54d47570-42c8-4d66-9c31-8e30d74bbe9b.png)

 De warnings die aangegeven stonden, waren omdat ik mijn recipecontroller nog niet had gepusht naar Git, nadat ik dit heb gedaan kreeg ik geen warnings meer.
 
 ![image](https://user-images.githubusercontent.com/99249005/205023630-d4ed66a0-d7f1-46ce-8558-8e7adfb7a423.png)

 ![image](https://user-images.githubusercontent.com/99249005/205028198-345ab478-cafb-4af1-b14f-960e99483c85.png)

 ![image](https://user-images.githubusercontent.com/99249005/205029177-ec007d95-447e-481a-81c7-8442efeef76d.png) [^20]

 ![image](https://user-images.githubusercontent.com/99249005/205031379-3b194f68-7886-43d2-a7d6-ba9d9a7d91ba.png)

 ![image](https://user-images.githubusercontent.com/99249005/205031521-811d0b45-927e-4e60-9570-e00df19dfc24.png)

 
 [^15]: [bron: SonarQube opzetten](https://docs.sonarqube.org/latest/setup/get-started-2-minutes/) </br>
 [^16]: [bron: SonarQube settings.xml](http://localhost:9000/documentation/analysis/scan/sonarscanner-for-maven/) </br>
 
 [^20]: [bron: Quality gate](http://localhost:9000/quality_gates/show/AYTNM-CN-fACkukBFFLB) </br>
 
   </details>
   
## Leeruitkomst 3: Agile methode

   **Leeruitkomst**: Je **kiest** en implementeert de meest geschikte agile software ontwikkelmethode voor jouw softwareproject. 

   **Kies**: Je bent op de hoogte van de meest populaire agile methoden en hun onderliggende agile principes. 
   Je keuze voor een methode is gemotiveerd en gebaseerd op welomschreven selectiecriteria en contextanalyses.

   <details>
   <summary><h4> Wat is agile? </h4></summary>
  
  [![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/Z9QbYZh1YXY/0.jpg)](https://www.youtube.com/watch?v=Z9QbYZh1YXY)
  
  ```
  DOT framework method:
  - Community research
  ```
  
*Agile* = Een verzameling van waarden en principes. Op de agile methode werken is elke beslissing nemen op basis van de principes en waarden die het team heeft besloten te volgen[^15]. Je levert je eindproduct stapsgewijs op, elke keer verbeter je je product door kleine releases[^16]. Het project wordt opgebouwd doormiddel van sprints, hierbij kun je veranderingen creëren en erop reageren[^17]. 

Beter software ontwikkelen door de items aan de linkerkant meer te waarderen dan de items aan de rechterkant:
  + Individuen en interacties boven processen en tools
  + Werkende software boven uitgebreide documentatie
  + Klantsamenwerking boven contractonderhandeling
  + Reageren op verandering boven het volgen van een plan[^18]
  
Er zijn 12 principes die de waarden ondersteunen:
  1. Onze hoogste prioriteit is om de klant tevreden te stellen door vroege en continue levering van waardevolle software.
  2. Verwelkom veranderende vereisten, zelfs in de late ontwikkeling. Agile processen benutten verandering voor het concurrentievoordeel van de klant.
  3. Regelmatig werkende software leveren, van een paar weken tot een paar maanden, met een voorkeur voor de kortere termijn.
  4. Ondernemers en ontwikkelaars moeten gedurende het hele project dagelijks samenwerken.
  5. Bouw projecten rond gemotiveerde individuen. Geef ze de omgeving en ondersteuning die ze nodig hebben en vertrouw erop dat ze de klus klaren.
  6. De meest efficiënte en effectieve methode om informatie naar en binnen een ontwikkelteam over te brengen, is een face-to-face gesprek.
  7. Werkende software is de belangrijkste maatstaf voor vooruitgang.
  8. Agile processen bevorderen duurzame ontwikkeling. De sponsors, ontwikkelaars en gebruikers moeten in staat zijn om voor onbepaalde tijd een constant tempo aan te houden.
  9. Continu aandacht voor technische uitmuntendheid en een goed ontwerp verbetert de wendbaarheid.
  10. Eenvoud - de kunst van het maximaliseren van de hoeveelheid niet gedaan werk - is essentieel.
  11. De beste architecturen, vereisten en ontwerpen komen voort uit zelforganiserende teams.
  12. Met regelmatige tussenpozen denkt het team na over hoe het effectiever kan, stemt het vervolgens af en past hun gedrag daarop aan.
  
  
    
  [^15]: [bron: agile.org](https://www.agilealliance.org/agile101/) </br>
  [^16]: [bron: HDI](https://www.thinkhdi.com/library/supportworld/2021/define-agile-in-simple-terms.aspx) </br> 
  [^17]: [bron: jigsaw](https://www.jigsawacademy.com/blogs/product-management/types-of-agile-methodology/#:~:text=The%20agile%20method%20is%20an,thereby%20encouraging%20flexibility%20to%20changes.) </br>
  [^18]: [bron: wikipedia agile](https://en.wikipedia.org/wiki/Agile_software_development) </br>
  
  
  <!-- image -->
  ![alt text](https://targettrend.com/wp-content/uploads/2021/03/Agile-Methodology-1.png) [^19]
 [^19]: [bron: agile methodology picture](https://targettrend.com/agile-methodology-meaning-advantages-disadvantages-more/)
  
   </details>
   <details>
   <summary><h4> Welke agile methodes zijn er? </h4></summary>
   
 Met verschillende methodes kan je op de agile manier werken. Ik heb 8 verschillende agile methodes gevonden:
 1. Scrum
 2. Kanban
 3. Extreme Programming (XP)
 4. Crystal
 5. Dynamic Systems Development Method (DSDM)
 6. Feature Driven Development (FDD)
 7. Lean Software Development
 8. Scaled Agile Framework (SAFe)
 
 Ik heb hieronder 3 methodes uitgewerkt[^17]:
 
 - <h5>Kanban</h5>
De letterlijke vertaling van het woord 'Kanban'uit het Japans is "visual bord of signboard". Bij Kanban gaat het erom om et project "just in time" in te leveren. Dit gebeurt met behulp van een Kanban-board, dat in kolommen is verdeeld om het proces van de software ontwikkeling te laten zien. Zo ziet het team elke ontwikkelingsfase en kunnen zo hun voortgang inschatten om de taken "just in time" in te leveren. Scrum werkt hierbij op dezelfde manier maar dan leveren ze op in sprints.
 
 - <h5>Extreme Programming (XP) </h5>
 Extreme Programming is een methode die de nadruk legt op teamwork, communicatie en feedback. Het richt zich op constante ontwikkeling en klanttevredenheid. Net als scrum maakt deze methode ook gebruik van sprints, dit zorgt voor een productief team en zeer efficiënte omgeving. Dit helpt de ontwikkelaars om veranderingen in de eisen van de klant te accepteren. Bij Extreme Programming wordt het project vanaf de beginfase getest door feedback te verzamelen die de output van het systeem bevordert. Dit biedt ook opties om gemakkelijk eventuele klantvereisten te implementeren.
 
 - <h5>Lean Software Development</h5>
 Deze agile methode werkt met 7 principes:
 
 1. Verwijderen wat er niet toe doet -> Alles wat geen waarde toevoegt, wordt uit het project verwijderd.
2. Kwaliteitsontwikkeling -> De discipline en controle van het aantal gecreëerde reststoffen zijn essentieel voor kwaliteitsontwikkeling.
3. Kenniscreatie -> Het team is gedreven om de gehele infrastructuur te documenteren om deze waarde in de toekomst te behouden.
4. Verbintenissen uitstellen -> Dit punt moedigt het team aan om zich minder te concentreren op het plannen en anticiperen op ideeën zonder eerst een voorafgaand en volledig begrip van de zakelijke vereisten te hebben.
5. Snelle levering -> Zo snel mogelijk waarde bieden aan de klant.
6. Het team respecteren -> twee essentiële punten zijn communicatie en conflicthantering.
7. Optimaliseer het geheel -> Om een stroom van echte waarde te creëren, moet de ontwikkelingsvolgorde voldoende geperfectioneerd zijn om fouten uit de code te verwijderen.
 
 Met behulp van deze lean-methodologie worden ontwikkeltijd en middelen geoptimaliseerd. Deze methode is eenvoudig schaalbaar en aanpasbaar aan projecten van elke omvang.

 <h5> Conclusie: </h5>
 Op mijn individuele project ga ik de principes toepassen van de agile methode Lean Software Development, zo blijft de kwaliteit van het product goed en kan ik rekening houden met een team en mogelijke klanten. Deze principes zijn vooral ook handig als ik straks in een team moet werken, waar ik niemand ken. Zo zorg ik ervoor dat ik mezelf al kan openstellen en mezelf kan voorbereiden op wat er verwacht wordt van mij.
 
 Voor ons groepsproject werken wij op de scrum methode maar gebruiken wij ook Extreme Programming. We zorgen ervoor dat we de feedback die we terugkrijgen van de klant meteen verwerken zodat we up-to-date blijven met de klant en aan hn eisen blijven voldoen. Ook werken we in sprints die beide methodes toepassen. Onze user stories staan in ons Jira board. Elk persoon heeft een user story toegeëigend gekregen, hier gaat hij/zij aan werken. Elke sprint heeft hier user stories toegekend gekregen waar we in die sprint aan gaan werken, zoals in de afbeelding te zien is:
   
   [![2022-11-14.png](https://i.postimg.cc/zDK4gvzw/2022-11-14.png)](https://postimg.cc/grcM9Y6r)
   
   </details>
    
## Leeruitkomst 4: CI-CD
**Leeruitkomst**: Je **ontwerpt en implementeert** een (semi)automatisch software release proces dat aansluit bij de behoeften van de projectcontext. 

**Ontwerpen en implementeren**: Je ontwerpt een releaseproces en implementeert een continu integratie- en implementatieoplossing (met behulp van o.a. Gitlab CI en Docker).
   
   <details>
   <summary><h4> yes </h4></summary>
   

   </details>

## Leeruitkomst 5: Culturele verschillen en ethiek
**Leeruitkomst**: Je **herkent en houdt rekening met** culturele verschillen tussen project stakeholders en ethische aspecten bij softwareontwikkeling.

**Herkennen**: Erkenning is gebaseerd op theoretisch onderbouwd bewustzijn van culturele verschillen en ethische aspecten in software engineering.

**Houd rekening met**: Pas je communicatie-, werk- en gedragsstijlen aan om de belanghebbenden van het project uit verschillende culturen te weerspiegelen; Behandel een van de standaard Programming Ethical Guidelines (bijv. ACM Code of Ethics and Professional Conduct) in je werk.

   
   <details>
   <summary><h4> whoo </h4></summary>
   

   </details>
   
## Leeruitkomst 6: Vereisten en ontwerp
**Leeruitkomst**: Je analyseert (niet-functionele) eisen, werkt (bouwkundige) ontwerpen uit en valideert deze met behulp van **meerdere soorten testtechnieken**.

**Meerdere soorten testtechnieken**: Je past gebruikersacceptatietesten en feedback van belanghebbenden toe om de kwaliteit van de vereisten te valideren. Je evalueert de kwaliteit van het ontwerp (bijvoorbeeld door testen of prototyping) rekening houdend met de geformuleerde kwaliteitseigenschappen zoals veiligheid en prestaties.
   
   <details>
  <summary><h4> Designs en wireframe </h4></summary>


De kleuren geel en rood doen ons vooral denken aan eten en wekken eetlust op[^4][^5]. Ik ben daarom voor de kleur oranje gegaan, want geel en rood gemengd maakt oranje.

Ik heb onderzoek gedaan bij verschillende websites die recepten laten zien. Hierdoor heb ik inspiratie opgedaan voor mijn eigen website. Ik heb zelf gekeken naar wat ik mooi vind en wat ik handig/makkelijk vind.

#### Leuke recepten
Leukerecepten.nl heeft als je over een plaatje heen hovert dat er dan informatie wordt gegeven over het recept, ikwilde het zelf wat meer simpel houden en deze informatie pas laten zien als je echt het recept wilt aanklikken.
![2022-11-23 (1)](https://user-images.githubusercontent.com/99249005/203744947-2badad85-a047-438c-9fed-cb69c4e5e2f4.png) [^6]

#### Jumbo
Van jumbo.com heb ik inspiratie opgedaan om het recept te laten zien als je erop klikt, dan is je plaatje niet volledig aan de background maar heeft ie nog een soort lijst, als bij een schilderij, eromheen. Als je dus op een recept klikt krijg je het plaatje zo te zien.
![2022-11-23 (2)](https://user-images.githubusercontent.com/99249005/203751547-1a2d3b8d-200d-461a-888c-08c14a8b2b5e.png) [^7]

#### Albert Heijn
Bij de ah.nl vond ik het erg leuk hoe ze op de beginpagina laten zien hoeveel kcal er in het recept zitten en voor hoeveel personen het gerecht is. Dit heb ik zelf ook toegevoegd in die rand die ze hebben gebruikt. Ik vond dit erg aantrekkelijk en belangrijk om te laten zien omdat je zelf de calorieën invult in het begin.
![2022-11-23](https://user-images.githubusercontent.com/99249005/203758347-93996266-f594-4964-89a6-2f40ddc9157d.png)[^8]

#### 24kitchen
Bij 24kitchen.nl zag ik dat je recepten kon favorieten en dat vond ik een leuke en handige toevoeging in mijn applicatie. Zo kun je alleen maar favorieten aanklikken als je ingelogd bent.
![2022-11-23 (3)](https://user-images.githubusercontent.com/99249005/203759485-bfe6db77-1a09-45a8-b1e0-a872903f9e14.png) [^9]

[^4]: [bron: intereno](https://www.intereno.nl/artikelen/kleurenpsychologie-in-de-keuken/)
[^5]: [bron: fitgirls](https://fitgirls.nl/deze-kleuren-hebben-effect-op-jouw-eetlust/)
[^6]: [bron: leukerecepten](https://www.leukerecepten.nl/)
[^7]: [bron: jumbo recepten](https://www.jumbo.com/recepten)
[^8]: [bron: ah recepten](https://www.ah.nl/allerhande)
[^9]: [bron: 24kitchen recepten](https://www.24kitchen.nl/recepten)


 Hiernaast is mijn interactieve UI-design te zien:         
<img src="https://user-images.githubusercontent.com/99249005/203734556-c2214dca-fc0b-4634-9f64-25dea693f12a.gif"  width="500" height="350"/> </br>
En hier is mijn interactieve wireframe te zien: </br>
<img src="https://user-images.githubusercontent.com/99249005/203734605-253748b1-2c3b-44cf-b365-b61791af0920.gif"  width="500" height="350"/>

  <!-- gifje -->
  ![alt text](https://media1.giphy.com/media/4bjIKBOWUnVPICCzJc/200.gif)


</details>

<details>
   <summary><h4> Modellen </h4></summary>
   
   #### Conceptueel model
   ![conceptueel model semester3 drawio](https://user-images.githubusercontent.com/99249005/203935216-41b5f61e-de59-4460-9d0e-38718c992735.png)

   #### C2 model
   ![c2 model drawio](https://user-images.githubusercontent.com/99249005/203966746-67eb1fc8-fe63-466a-a65b-8976f74a5b66.png)

</details>
   
## Leeruitkomst 7: Business processen
**Leeruitkomst**: Je analyseert en beschrijft **eenvoudige** bedrijfsprocessen die **gerelateerd** zijn aan jouw project.

**Eenvoudig**: Betrokkenheid van belanghebbenden, overwegend opeenvolgende processen met een of twee alternatieve paden.

**Gerelateerd**: Bedrijfsprocessen waarbij de software die u ontwikkelt gebruikt gaat worden (bedrijfsprocessen die de software moet ondersteunen door deze geheel of gedeeltelijk te automatiseren) of bedrijfsprocessen die nodig zijn voor het succes van uw softwareontwikkelingsproject (bijv. productrelease, marktrelease, financiële zekerheid).
   
   <details>
   <summary><h4> Business process </h4></summary>
   
   <h5> Business process zonder onze app </h5>
  <a href='https://postimg.cc/cgSpZmNz' target='_blank'><img src='https://i.postimg.cc/cgSpZmNz/S3groepsproject-bedrijfsproceswithoutapp.jpg' border='0' alt='S3groepsproject-bedrijfsproceswithoutapp' width="300"/></a>
  
   <h5> Business process met onze app </h5>
   <a href='https://postimg.cc/2LjgLSyF' target='_blank'><img src='https://i.postimg.cc/2LjgLSyF/S3groepsproject-bedrijfsproceswithapp.jpg' border='0' alt='S3groepsproject-bedrijfsproceswithapp' width="300"/></a>
   
   (Klik op de afbeelding voor scherp beeld)

   
   </details>
   
## Leeruitkomst 8: Professioneel
**Leeruitkomst**: Je handelt op een **professionele manier** tijdens het ontwikkelen en leren van software.

**Professionele manier**: Je vraagt en past actief feedback van stakeholders toe en adviseert hen over de meest optimale technische en ontwerp (bouwkundige) oplossingen. Je kiest en onderbouwt oplossingen voor een bepaald probleem.
   
   
   <details>
   <summary><h4> ait </h4></summary>
   

   </details>
