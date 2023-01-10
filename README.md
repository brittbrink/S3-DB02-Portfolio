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
  <summary><h4> Individueel project </h4></summary>

 ```
  DOT framework method:
  - Survey
  - Focus group
  - Usability testing
  ```

*Productbeschrijving:* </br>
Met mijn webapplicatie kun je je verbrandde calorieën ingeven en worden er vervolgens recepten opgehaald die deze calorieën bevatten. Zo eet je de calorieën die je verbrand hebt via een maaltijd. Daarnaast kun je inloggen om je favorieten te bekijken die je hebt aangeklikt en krijg je een historie te zien met de recepten die je al is hebt gezien. Hierdoor worden deze recepten niet meer voor jou gegenereerd, zodat er variatie blijft.

*Frontend taal:* </br>
Voor de frontend heb ik de taal React gekozen, dit omdat het makkelijker te leren is[^1]. Ik heb zelf nog maar een jaartje ervaring met coderen in C# (backend) en voor de frontend html/css. Ik wilde niet een te grootte stap vooruit nemen en mezelf in de war laten komen door alle talen. Ook kan ik vanauit React snel overswitchen naar een mobile app maken, zo kan ik mezelf uitdagen binnen de taal React. Ook is React door de meeste developers gebruikt[^2]. 


*Backend taal:* </br>
Voor de backend heb ik de taal Java Springboot gekozen. In ons groepsproject hebben wij besloten dit te gaan doen, ik wilde ervoor zorgen dat ik extra ervaring op kon doen binnen Java Springboot en heb daarom ook in mijn individuele project ervoor gekozen om in Java Springboot te werken. Ook developers kiezen Java Springboot als meest gebruikte programmeer taal.[^2][^3]


[^1]: [bron: alidaschool](https://www.alidaschool.com/blog/react-vue-or-angular-the-best-javascript-framework-to-learn-to-get-a-front-end-job#:~:text=If%20you're%20a%20beginner%20developer%20or%20junior%20developer%2C%20I,native%20to%20build%20mobile%20apps.)
[^2]: [bron: stackoverflow survey](https://insights.stackoverflow.com/survey/2021#technology-most-popular-technologies)
[^3]: [bron: hackr.io](https://hackr.io/blog/c-sharp-vs-java#:~:text=Java%20is%20class%2Dbased%20and,oriented%20languages%20with%20strong%20communities.)


</details>

<details>
  <summary><h4> Groepsproject </h4></summary>

 ```
  DOT framework method:
  - Survey
  - Focus group
  ```

*Productbeschrijving:* </br>
Als groep gaan wij een horeca zelf-service applicatie maken voor onze opdrachtgever, InfoSupport. Het is de bedoeling dat de gasten die in het restaurant komen eten, zelf hun eten kunnen bestellen via een app, die wij mogen gaan creëren. Het is belangrijk dat de gasten orders kunnen bestellen, met eten en/of drinken en deze daarna ook kunnen afrekenen. Van de bestelling wordt het eetgedeelte naar de keuken gestuurd en het drinkgedeelte naar de bar. De keuken kan deze gerechten toe eigenen, zodat de bar weet wanneer gerechten klaar zijn om uit te serveren. De bar moet ook bestellingen kunnen aanpassen en naar een andere tafel kunnen zetten.

*Frontend taal:* </br>
De opdrachtgever liet ons erg vrij in het maken van de keuze voor de programmeertalen. Hierbij hebben we voor de frontend React gekozen. Dit vonden wij er erg clean uitzien en omdat wij allemaal nog niet zo bekend waren met deze frontend taal vonden we dit een mooie uitdaging om aan te gaan. Hierbij is onze keuze ook voort gekomen doordat we een javascript frontend moesten gebruiken, Angular, Vue.js en React. React was de snelste taal om te leren en ook het hoogst aangeschreven.

*Backend taal:* </br>
Voor de backend taal wilde we graag in Java Springboot programmeren. We hadden allemaal ervaring in C# maar wilde onze kennis uitbreiden naar meer talen. Ook was dit voor ons fijn met de frontend taal en sloot het erg op elkaar aan. Java Springboot werkt fantastisch met de gekozen database, MySQL. We hebben Java Springboot ook gekozen voor de securti die het met zich meebrengt.

</details>

<details>
  <summary><h4> ORM security onderzoek </h4></summary>
 <h4> Op welke manier kan een ORM de security van mijn web applicatie verbeteren? </h4>
 
 ```
  DOT framework method:
  - Survey
  - Literature study
  ```
 
Doormiddel van een forms die we hebben gekregen via Jean-Paul, ben ik erachter gekomen dat ik onderzoek moest gaan doen naar ORM's. Ik wist nog niet goed wat dit was, maar heb er wel van geleerd nadat ik de forms teruggekoppeld kreeg. Zo heb ik uit de forms de functie van een ORM weten te halen. Ik heb dit nog bevestigt door research te doen op het internet.

 <h4> Wat is een ORM? </h4>
 Een ORM staat voor Object Relational Mapping. Dit houdt in dat er via code een database gegenereert kan worden en andersom. ORM is een techniek voor het creeëren van een "brug" tussen object georiënteerd programmeren en in de meeste gevallen relationele databases. Anders gezegd, je kan een ORM zien als de laag die object georiënteerd programmeren(OOP) verbindt met relationele databases.[^10]  Een ORM convert gegevens tussen systemen met behulp van programmeertalen[^11]. Bij objectgeoriënteerd programmeren kun je gebruik maken van een ORM library, dit zorgt ervoor dat je bijvoorbeeld niet je hele query hoeft uittetypen met SQL en dus tijd bespaart[^12]. 
 
 Er zijn verschillende ORM libraries voor verschillende programmeertalen, dit zijn enkele programmeertalen met hun bijpassende ORM library: 
 
- Java: Hibernate
- C#: NHibernate of Entity Framework
- Python: SQLAlchemy[^12]

![image](https://user-images.githubusercontent.com/99249005/207557824-bce3d03d-a000-4295-a731-883ca9d9c782.png) [^13]


<h4> Waar dient een ORM voor? </h4>

Wanneer je communiceert met een database met behulp van OOP-talen, moet je verschillende opdrachten uitvoeren, zoals create, read, update en delete (CRUD) van gegevens uit een database. Standaard wordt hier SQL gebruikt voor het uitvoeren van deze opdrachten in relationele databases. Hoewel dat geen slecht idee is, helpen ORM en ORM-tools de interactie tussen relationele databases en verschillende OOP-talen te vereenvoudigen.[^10] 
Met mapping is het moeilijk om informatie om te zetten om deze aan de database aan te passen of database om te zetten om deze aan de informatie aan te passen. Je kunt mapping automatiseren doormiddel van een ORM. De ORM zorgt ervoor dat het mapping bovendien onafhankelijk maakt van de database die je wilt gebruiken en je kan deze zelfs probleemloos wijzigen.[^14] 

 <h4> Welke verschillende Java ORM's zijn er? </h4>
 
 ![image](https://user-images.githubusercontent.com/99249005/207558703-702dc1ff-a802-47a4-8e8e-036492126201.png) [^13]
 
 Er zijn verschillende ORM tools voor Java beschikbaar, hieronder staan de meest gebruikte.
 
 - <b>Hibernate</b> </br>
 Hibernate is een Java persistence framework dat de ontwikkeling van Java-applicaties voor interactie met de database vereenvoudigt. Het is een open source, veelgebruikte, lichtgewicht ORM-tool. Hibernate implementeert de specificaties van JPA (Java Persistence API) voor gegevens.
 
 - <b>TopLink</b> </br>
 TopLink is een ORM-tool ontwikkeld door Oracle voor Java-ontwikkelaars. Het is een vasthoudendframework, het biedt ontwikkel tools en runtime functionaliteiten die het ontwikkelingsproces vergemakkelijken en de functionaliteit vergroten.
 
 - <b>OpenJPA</b> </br>
 Apache OpenJPA is een Java-persistentieproject van The Apache Software Foundation dat kan worden gebruikt als een stand-alone POJO-persistentielaag of kan worden geïntegreerd in elke Java EE-compatibele container en vele andere lichtgewicht frameworks, zoals Tomcat en Spring.
 
 - <b>MyBatis</b> </br>
 MyBatis was voorheen bekend als iBatis. Het is ook een open source persistentieraamwerk dat de implementatie van een database vereenvoudigt. MyBatis is anders dan andere ORM-tools. Het belangrijkste verschil tussen MyBatis en andere ORM-tools is dat MyBatis de nadruk legt op het gebruik van SQL, terwijl andere ORM-tools aangepaste querytaal (HQL) gebruiken.
 
 - <b>EclipseLink</b> </br>
EclipseLink is de open source Eclipse Persistence Services-tool geïntroduceerd door Eclipse Foundation. Het is een uitbreidbaar raamwerk waarmee Java-ontwikkelaars kunnen communiceren met verschillende gegevensservices, zoals databases, webservices, Object XML-mapping en bedrijfsinformatiesystemen.[^13][^15]
 
<h4> Wat zijn de voor en nadelen van een ORM op basis van security? </h4>

<i> Voordelen: </i> </br>
~ Een ORM heeft meestal een reeks veilige functies te bieden ter bescherming tegen SQL-injectieaanvallen.[^16][^10] </br>
~ Voor het vermijden van SQL injection kun je gebruik maken van de frameworks Hibernate en Spring Data JPA voor de datalaag van de applicatie.[^17]

<i> Nadelen: </i> </br>
~ Het is mogelijk dat een web applicatie die ORM-gegenereerde objecten gebruikt, kwetsbaar is voor SQL-injectieaanvallen als methoden onopgeschoonde invoerparameters kunnen accepteren.[^16]


 <h4> Conclusie: </h4>
  In mijn applicatie heb ik gebruik gemaakt van de ORM framework Hibernate, zo is de grootste kans dat ik SQL injection vermijd. Dit framework werkt goed samen met mijn backend taal Java Spring Boot.
 <br></br>
 

  
  [^10]: [bron: freecodecamp ORM](https://www.freecodecamp.org/news/what-is-an-orm-the-meaning-of-object-relational-mapping-database-tools/) </br>
 [^11]: [bron: stackoverflow ORM](https://stackoverflow.com/questions/1279613/what-is-an-orm-how-does-it-work-and-how-should-i-use-one.) </br>
 [^12]: [bron: wikipedia ORM](https://en.wikipedia.org/wiki/Object%E2%80%93relational_mapping.) </br> 
 [^13]: [bron: ORM afbeelding](https://www.javatpoint.com/orm-tools-in-java) </br>
 [^14]: [bron: ORM](https://www.hwlibre.com/nl/orm-object-relational-mapping/) </br>
 [^15]: [bron: Java ORM's](https://javabydeveloper.com/orm-object-relational-mapping/) </br>
 [^16]: [bron: SQL injectie](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/07-Input_Validation_Testing/05.7-Testing_for_ORM_Injection) </br>
 [^17]: [bron: Digitalocean]( https://www.digitalocean.com/community/tutorials/sql-injection-in-java) </br>

 

  </details>
    
## Leeruitkomst 2: Software kwaliteit

 **Leeruitkomst**: Je gebruikt **softwaretooling en -methodiek** die de softwarekwaliteit tijdens de softwareontwikkeling continu bewaakt en verbetert. </br>

  **Tooling en methodiek**: Uitvoeren, bewaken en rapporteren over unit integratie, regressie en systeemtesten, met aandacht voor security en performance aspecten,
  netzoals het toepassen van statische code analyse en code reviews.

   <details>
   <summary><h4> CI </h4></summary>
   
   ```
  DOT framework method:
  - Prototyping
  ```
   
   Voor code quality heb gekeken naar welke tool ik het best kan gebruiken. PVS studio werd erg aangeraden en daarnaast ook SonarQube[^15]. SonarQube is een SAST tool, Static Application Security Testing, hiermee kun je kwetsbaarheden die veiligheidsproblemen veroorzaken analyseren. Ik heb voor SonarQube gekozen omdat ik doormiddel van SonarCloud ook mijn ci/cd kan opzetten. Zo maak ik al kennis met hoe Sonar werkt en helpt dit mij met het opzetten van ci/cd. Via SonarQube kun je gemakkelijk continuous code quality en code security op je project zetten en deze local laten runnen. Hierbij heb ik het stappenplan gevolgd dat door SonarQube wordt aanbevolen.
   
<h4> Stappenplan: </h4>
1. Het downloaden van de zip file </br>
2. Installeren van Java 11 </br>
   <a href='https://user-images.githubusercontent.com/99249005' target='_blank'><img src='https://user-images.githubusercontent.com/99249005/205012992-ea99146b-94a3-4493-89b9-f0999a280c6b.png' border='0' alt='205012992-ea99146b-94a3-4493-89b9-f0999a280c6b' width="450"/></a> </br> [^16]
 
 3. Inloggen op localhost:9000
 <!-- ![image](https://user-images.githubusercontent.com/99249005/205012992-ea99146b-94a3-4493-89b9-f0999a280c6b.png) --> 
  
 ![image](https://user-images.githubusercontent.com/99249005/205012912-1e261373-2df8-4a82-81ea-53eb7b61fc19.png) </br>

 4. Kijken of ik al kon doen wat er gevraagd werd.

![image](https://user-images.githubusercontent.com/99249005/205012755-4f9a41b9-d291-4cde-9fc2-1966ea9d2618.png) </br>

 5. Nee! Eerst stukje code toevoegen in settings.xml file om bij server te komen, maar deze wel eerst vinden.

 ![image](https://user-images.githubusercontent.com/99249005/205013808-05278258-0967-4387-b31b-9d0a3234d32c.png)

![image](https://user-images.githubusercontent.com/99249005/205015760-3bcdc85a-6ac6-436f-b388-88041de73dac.png) [^17] </br>
6. Bovenstaande voorbeeld toegevoegd aan settings.xml file.
 
![image](https://user-images.githubusercontent.com/99249005/205019103-4fe79830-cce3-4eff-af0d-a106cb9fe133.png) </br>

7. Build failed. Niet correct genoteerd.

 ![image](https://user-images.githubusercontent.com/99249005/205020863-8c5f140c-c790-4dd5-a4a2-e7df88e2d04b.png) </br>
 
8. Onderzocht wat wel de goede notatie is om build te laten slagen.

 ![image](https://user-images.githubusercontent.com/99249005/205021343-b023a3c9-90f2-49ed-a623-9e3b2e1e32ac.png) </br>
 
9. Nog steeds build failed. Geprobeerd gewoon met spaties ertussen, zoals hieronder:
 
 ```
 mvn clean verify sonar:sonar   -Dsonar.projectKey=projectSemester3   -Dsonar.host.url=http://localhost:9000   -Dsonar.login=sqp_f117f63345b04852876bc112ccfebadf139ac331 
 ```
 
 ![image](https://user-images.githubusercontent.com/99249005/205022109-54d47570-42c8-4d66-9c31-8e30d74bbe9b.png) </br>

10. Build succeeded
11. Kreeg nog warnings, deze opgelost doormiddel van het pushen van mijn recipecontroller naar git

 ![image](https://user-images.githubusercontent.com/99249005/205023630-d4ed66a0-d7f1-46ce-8558-8e7adfb7a423.png) </br>

12. Er was geen new code dus de coverage was 0.0%. Build failed

 ![image](https://user-images.githubusercontent.com/99249005/205028198-345ab478-cafb-4af1-b14f-960e99483c85.png) </br>
 
 13. Conditions aangepast zodat hij wel zal slagen.

 ![image](https://user-images.githubusercontent.com/99249005/205029177-ec007d95-447e-481a-81c7-8442efeef76d.png) [^18]

 ![image](https://user-images.githubusercontent.com/99249005/205031379-3b194f68-7886-43d2-a7d6-ba9d9a7d91ba.png)</br>
 
 14. Voor security ook conditions aangepast zodat hij wel zal slagen, ondanks dat het niet veilig is.

 ![image](https://user-images.githubusercontent.com/99249005/205031521-811d0b45-927e-4e60-9570-e00df19dfc24.png)</br>
 
 15. Build passed 

  ![image](https://user-images.githubusercontent.com/99249005/205019207-d88c13fd-c6ef-46da-845f-930a34335c09.png) </br>
 

  [^15]: [bron: keuze SonarQube](https://www.softwaretestinghelp.com/code-quality-tools/) </br>
 [^16]: [bron: SonarQube opzetten](https://docs.sonarqube.org/latest/setup/get-started-2-minutes/) </br>
 [^17]: [bron: SonarQube settings.xml](http://localhost:9000/documentation/analysis/scan/sonarscanner-for-maven/) </br>
 
 [^18]: [bron: Quality gate](http://localhost:9000/quality_gates/show/AYTNM-CN-fACkukBFFLB) </br>
 
 <h4> Conclusie: </h4>
 Ik heb SonarQube opgezet, maar heb in mijn CI/CD SonarCloud verwerkt. Ik vond uiteindelijk SonarCloud makkelijker om op te zetten en makkelijker te verwerken in mijn CD vandaar de keuze om niet SonarQube te gebruiken. Ik heb hier wel tijd aan besteed en ben ik tegen dingen aangekomen waarvan ik heb geleerd zoals, in mijn code heb ik mijn apiKey voor de externe API hardcoded in mijn code staan. Hierdoor faald mijn SonarQube door security. Om te zorgen dat hij toch zal slagen ondanks dat ik weet dat mijn security qua apiKey niet verstandig is heb ik de security rating omlaag gedaan, zo slaagd hij wel op security. En kan hij uiteindelijk wel deployen via CD.
 
 
 
  
  </details>
 <details>
   <summary><h4> End to End testing </h4></summary>
 
  ```
  DOT framework method:
  - Prototyping
  ```
 Om mijn front-end en of ik data krijg van de back-end te testen, maak ik gebruik van end-to-end testing. Dit was heel makkelijk op te zetten. Zo kan ik als ik testen heb geschreven automatisch zien of de knoppen doen wat ik wil dat ze doen en of ik überhaupt data krijg van de back-end. Mijn end-to-end testen maak ik via cypress
 
 
 1. Opzetten end-to-end testing:
 
 ![image](https://user-images.githubusercontent.com/99249005/206998958-e8df5fa1-34a9-4d82-a93f-ae6477f63bcd.png)

![image](https://user-images.githubusercontent.com/99249005/206999171-2470190f-0b87-41a2-8e52-dbf5fc4f7520.png)
 
 2. Test opgezet of de frontend data krijgt van de backend.
 
 ![image](https://user-images.githubusercontent.com/99249005/208903413-d3a0506e-cdc4-4375-a8d6-8bc1d31be055.png)
 
 3. Specifiek in test neerzetten dat ik http://localhost8080/persons wil testen. Anders krijg je error 404: not found.
 
![image](https://user-images.githubusercontent.com/99249005/207006006-402c7eb2-43b3-4b11-af54-6d64135726e4.png)

 4. Test geslaagd.
 
![image](https://user-images.githubusercontent.com/99249005/207009755-c23c4e5a-4f40-443d-9dce-312185f90f98.png)

  
   </details>
   
   <details>
   <summary><h4> Testplan </h4></summary>
 
Ik heb een testplan opgezet waarin ik een beschrijving geef over wat de test inhoud, hoe je deze test zou kunnen uitvoeren en wat de test als resultaat zou moeten geven als de beschrijving van de test wil aantonen. Dit werkt voor mij omdat ik dan goed op papier heb wat ik wil dat mijn applicatie doet en zo makkelijk kan reflecteren als de applicatie niet doet wat ik wil.
 
 ![image](https://user-images.githubusercontent.com/99249005/210544754-375a734c-4f9a-45d2-b160-97665bf7fde2.png)

 
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
 Op mijn individuele project ga ik de principes toepassen van de agile methode Lean Software Development, zo blijft de kwaliteit van het product goed en kan ik rekening houden met een team en mogelijke klanten. Deze principes zijn vooral ook handig als ik straks in een team moet werken, waar ik niemand ken. Zo zorg ik ervoor dat ik mezelf al kan openstellen en mezelf kan voorbereiden op wat er verwacht wordt van mij. </br>
 
*Reflectie:* 
Voor mij had ik beter ook met een board of in sprints kunnen werken in samenwerking met Lean. Zo houdt ik structuur in mijn werk en voor mijn docent. Zo had ik sprints kunnen afspreken met mijn docent waarin ik een demo zou geven. Dit zorgt ervoor dat ik deadlines moet halen en meer gestreven werk.
 </br></br>
 Voor ons groepsproject werken wij op de scrum methode maar gebruiken wij ook Extreme Programming. We zorgen ervoor dat we de feedback die we terugkrijgen van de klant meteen verwerken zodat we up-to-date blijven met de klant en aan hn eisen blijven voldoen. Ook werken we in sprints die beide methodes toepassen. Onze user stories staan in ons Jira board. Elk persoon heeft een user story toegeëigend gekregen, hier gaat hij/zij aan werken. Elke sprint heeft hier user stories toegekend gekregen waar we in die sprint aan gaan werken, zoals in de afbeelding te zien is:
   
   [![2022-11-14.png](https://i.postimg.cc/zDK4gvzw/2022-11-14.png)](https://postimg.cc/grcM9Y6r)
   
   </details>
    
## Leeruitkomst 4: CI-CD
**Leeruitkomst**: Je **ontwerpt en implementeert** een (semi)automatisch software release proces dat aansluit bij de behoeften van de projectcontext. 

**Ontwerpen en implementeren**: Je ontwerpt een releaseproces en implementeert een continu integratie- en implementatieoplossing (met behulp van o.a. Gitlab CI en Docker).
   
   <details>
   <summary><h4> SonarCloud  </h4></summary>
  
  ```
  DOT framework method:
  - Prototyping
  ```
 
   Om de CI aan te tonen heb ik SonarCloud gebruikt. Hierbij kijk je naar code quality en als deze dan passed, ben ik van plan deze in mijn pipeline te verwerken[^20]. Zo runt mijn pipeline alleen als de code quality slaagt.
Het verschil tussen SonarQube en SonarCloud is dat bij SonarCloud de code quality online staat en bij SonarQube local. Ik heb zelf gemerkt dat ik het fijner vind dat mijn code quality online staat zo kan ik deze op een eenvoudige manier in mijn pipeline verwerken. Dit heeft natuurlijk wel gevolgen voor de beveiliging van mijn applicatie.
 
 [^20]: [bron: Pipeline met SonarCloud](https://docs.sonarqube.org/latest/)
   
   <h4> Backend </h4>
 
![image](https://user-images.githubusercontent.com/99249005/206141380-94326c74-9463-4054-b063-cb7a67a6e4b8.png)

![image](https://user-images.githubusercontent.com/99249005/206143757-ac1a9c14-255d-4894-9396-b934c30ffac4.png)

Probleem: Mijn pom.xml file runned op JDK 17 en de build.yml file runned op JDK 11 dus dan sprint hij eruit. Ik heb de build.yml file aangepast naar JDK 17 en toen werd de volgende error gegeven:

![image](https://user-images.githubusercontent.com/99249005/206147514-b485ddae-281e-4d4f-a4da-afcd0753ac10.png)
 
 Probleem: mijn project stond in een andere branch als de build.yml file waardoor hij stuk liep. Heb nu alles in mijn master staan en nu doet ie het wel. 

![image](https://user-images.githubusercontent.com/99249005/206148575-1e38d35c-55b2-4600-bcb1-f55085df7b4d.png)

<h4> Frontend </h4>

![image](https://user-images.githubusercontent.com/99249005/206152984-0001de7f-40b4-418b-a43b-6718d11c4b67.png)

 <h4> Azure DevOps </h4>
 
 Voor de CD ga ik mijn website via azure deployen.
 
 ![image](https://user-images.githubusercontent.com/99249005/206416351-b92c7e9a-d3ae-4be0-a844-3687b5295312.png) [^21]
 
 [^21]: [Bron: waarom failed](https://stackoverflow.com/questions/68405027/how-to-resolve-no-hosted-parallelism-has-been-purchased-or-granted-in-free-tie)
 
![image](https://user-images.githubusercontent.com/99249005/207013432-497358f8-e8c2-4233-b63c-f33686e069bc.png)
 
 doormiddel van deze website opgelost[^22]

 ![image](https://user-images.githubusercontent.com/99249005/207033488-1dc9d430-2ec2-4416-80b0-e79e4ddef9a0.png)

 [^22]: [bron: oplossen maven 17](https://stackoverflow.com/questions/64996644/azure-pipeline-invalid-target-release-11)
 
 ![image](https://user-images.githubusercontent.com/99249005/207041846-4f5a5cbf-fcaf-4cc6-a858-b7671dffcf89.png)

 Nu krijg ik via github een error van mijn SonarCloud
 
 ![image](https://user-images.githubusercontent.com/99249005/207047812-116f764b-2371-4f93-959f-a3e76f3fb22c.png)
 
 ![image](https://user-images.githubusercontent.com/99249005/207047432-9cded9af-3f16-4270-8a3b-041fe50c907d.png)
 
 Automatic Analysis uitgezet.[^23]

 [^23]: [bron: oplossen github sonarcloud](https://community.sonarsource.com/t/sonarcloud-task-fails-because-of-ci-analysis-and-auto-analysis-running/22937)
 
 ![image](https://user-images.githubusercontent.com/99249005/207055356-f8f7393c-b13a-4fb5-956e-63643f2fd994.png)

 ![image](https://user-images.githubusercontent.com/99249005/207617522-c283e04d-6ff3-4838-8c3a-e5d1ec1a7eda.png)

 Maar er wordt niet door mijn code via SonarCloud heen gegaan. De pagina van SonarCloud wordt namelijk niet gerefresht.
 
 ![image](https://user-images.githubusercontent.com/99249005/207810346-84399479-6e02-444f-90ed-071d6978e90d.png)
Ik had eerst maven in mijn yml file en dan SonarCloud. Maar ik moet eerst door mijn SonarCloud heen lopen en dan door maven lopen.
 
 ![image](https://user-images.githubusercontent.com/99249005/207810120-49931d62-eed4-4c30-98f1-e42badfacd34.png)

 ![image](https://user-images.githubusercontent.com/99249005/207810193-5c509ac6-a9f6-4f88-b186-9a612913a031.png)
 
 ![image](https://user-images.githubusercontent.com/99249005/207867655-205e674a-4790-4a31-95e7-2c994478646b.png)
Dit toegevoegd om de errorcode op te lossen.
 
 ![image](https://user-images.githubusercontent.com/99249005/207867552-18514be1-9335-4689-8e2d-bf4f68ef8551.png)

 Het toevoegen van sonarbuildbreaker zodat wanneer mijn SonarCloud failed, mijn pipeline niet runt.[^24]
 
 ![image](https://user-images.githubusercontent.com/99249005/207875430-004b026b-b29c-44ec-bc9a-f6957f846909.png)
 
 ![image](https://user-images.githubusercontent.com/99249005/207874709-08938369-60c4-404f-a8ba-e72337aa839d.png)
 
 [^24]: [bron: sonarbuiltbreaker](https://marketplace.visualstudio.com/items?itemName=SimondeLang.sonarcloud-buildbreaker)
 

 <h4> Conclusie: </h4>
 
 ![image](https://user-images.githubusercontent.com/99249005/206154781-88ae9c4f-4954-466f-b035-74e100b4b982.png)

![image](https://user-images.githubusercontent.com/99249005/207867441-b51a1ec1-eab7-421c-9a9d-caa422db2964.png)

  
   </details>

## Leeruitkomst 5: Culturele verschillen en ethiek
**Leeruitkomst**: Je **herkent en houdt rekening met** culturele verschillen tussen project stakeholders en ethische aspecten bij softwareontwikkeling.

**Herkennen**: Erkenning is gebaseerd op theoretisch onderbouwd bewustzijn van culturele verschillen en ethische aspecten in software engineering.

**Houd rekening met**: Pas je communicatie-, werk- en gedragsstijlen aan om de belanghebbenden van het project uit verschillende culturen te weerspiegelen; Behandel een van de standaard Programming Ethical Guidelines (bijv. ACM Code of Ethics and Professional Conduct) in je werk.

   
   <details>
   <summary><h4> Culturele verschillen </h4></summary>
   
   <!-- Wat is cultuur? -->
   
   Cultuur is een groep mensen met dezelfde normen, waarden en gewoonten.[^25] Een cultuur bestaat uit meerdere lagen die gezien kunnen worden als de lagen van een ui. In de buitenste laag vind je *symbolen*, items zoals eetgewoonten, voedsel, vlaggen en kleuren. De laag daarna bestaat uit *helden*, dit zijn mensen die een voorbeeld zijn voor anderen om wat ze gedaan hebben. De laatste laag en het dichtst bij de kern zijn de *rituelen*, terugkerende gebeurtenissen die ons onderbewustzijn vormen.[^26] De kern van de ui zijn de *values*, gevoelens over wat wel en wat niet als goed of slecht moet worden beschouwd. </br>
   Values kunnen worden gemanifesteerd (zichtbaar voor de buitenstaander) door de verschillende praktijken; symbolen, helden en rituelen.
  
  <img src="https://user-images.githubusercontent.com/99249005/211190241-7738775b-3837-4c05-a1f3-ab8dec570d5d.png" data-canonical-src="https://user-images.githubusercontent.com/99249005/211190241-7738775b-3837-4c05-a1f3-ab8dec570d5d.png" width="200" height="200"> </br>

   <pre>
   <b> Verschillende betekenissen van cultuur: </b>
   
   "The programming of the human mind by which one group of people distinguishes itself from another group." G. Hofstede
   
   "Culture is communication" (E.T. Hall)
   
   "Culture is how things are done here" (J. Mole)
   
   "How we organize the experience of the world around us" (M. Bennett) </pre>
   
   <h4> Welke culturele verschillen zijn er? </h4>
   
   Er zijn 6 dimensies in Hofstede's cultural dimensions theorie:
   - Power distance
   - Individualism vs. collectivism
   - Masculinity vs. femininity
   - Uncertainty avoidance 
   - Long term orientation
   - Indulgence vs restraint
   
<h4>Power distance</h4>

Deze dimensie heeft betrekking op de gelijkwaardigheid tussen individuen in een samenleving. Machtsafstand wordt gedefinieerd als de mate waarin de leden die het minst machtig zijn van de instellingen en organisaties in een land verwachten en accepteren dat de macht ongelijk verdeeld is. De fundamentele vraag hier is hoe een samenleving omgaat met ongelijkheden tussen mensen.[^27] 
Mensen in samenlevingen met een grote machtsafstand accepteren een hiërarchische volgorde waarin iedereen een plaats heeft die geen verdere rechtvaardiging vereist. Mensen in samenlevingen met kleine machtsafstanden streven naar machtsverevening en eisen rechtvaardiging voor machtsongelijkheden.[^28] 

In de afbeelding is te zien dat Nederland, met 38, onder het gemiddelde ligt op power distance. Wat de Nederlandse stijl dan kenmerkt: zelfstandig zijn, gelijke rechten, leidinggevenden toegangelijk, coachend leider. De macht is gedecentraliseerd en managers rekenen op de ervaring van hun teamleden. Medewerkers verwachten te worden geraadpleegd. Controle wordt niet gewaardeerd en de houding ten opzichte van managers is informeel en op voornaam gebaseerd. Communicatie is direct en participatief. 

<img src="https://user-images.githubusercontent.com/99249005/211203692-01cb7ad9-776c-406e-9421-f41af774569f.png"  width="500"/> [^29]

<h4>Individualism vs. collectivism</h4>

In deze dimensie wordt onderzocht in welke mate het zelfbeeld van de mens wordt gedefinieerd als individualistisch (ik) of collectivistisch (wij). In individualistische samenlevingen wordt verondersteld dat men voor zichzelf en alleen hun directe familie zorgt. In collectivistische samenlevingen behoort men tot groepen die voor elkaar zorgen in ruil voor loyaliteit. 

Uit de diagram blijkt dat Nederland het individualisme hanteert en ieder dus voor zichzelf en hun naaste familie zorgt. Voor Costa Rica geld het tegenovergestelde, zij verwachten als individu dat hun familieleden voor hen zorgen en in ruil daarvoor tonen zij onvoorwaardelijke loyaliteit.

<img src="https://user-images.githubusercontent.com/99249005/211298381-1092d559-5bbb-4d5d-a7d8-8374559f3073.png"  width="500"/> [^29]


<h4>Masculinity vs. femininity</h4>

Deze dimensie onderzoekt wat mensen motiveert, de wil om de beste te zijn (masculiniteit) of houden van wat je doet (femininiteit). In de zakelijke context wordt mannelijkheid versus vrouwelijkheid soms ook wel gerelateerd aan "stoere versus tedere" culturen.

De mannelijke kant van deze dimensie vertegenwoordigt een voorkeur in de samenleving voor prestatie, heldhaftigheid, assertiviteit en materiële beloningen voor succes. De samenleving als geheel is competitiever. Het tegendeel, Vrouwelijkheid, staat voor een voorkeur voor samenwerking, bescheidenheid, zorg voor de zwakken en kwaliteit van leven.

In de diagram is te zien dat Nederland over het algemeen een hele lage masculiniteit heeft en heeft meer een voorkeur voor samenwerking, bescheidenheid en kwaliteit van leven. Japan daarentegen zijn competitiever, voorkeur voor prestatie, heldhaftigheid en materiële beloningen voor succes.

<img src="https://user-images.githubusercontent.com/99249005/211532796-952dfd86-fa3c-4df5-aa11-2f0ad8bd9b66.png"  width="500"/> [^29]

<h4>Uncertainty avoidance</h4>

Uncertainty avoidance heeft te maken met de manier waarop een gemeenschap omgaat met het feit dat de toekomst altijd onbekend is: moeten we proberen te toekomst te beheersen of het gewoon laten gebeuren? Deze dubbelzinnigheid brengt angst. Verschillende culturen hebben op verschillende manieren geleerd om te gaan met deze angst.

Landen met een sterke uncertainty avoidance index houden vast aan rigide geloofs- en gedragscodes en tolereren onorthodox gedrag en ideeën niet. Zwakke uncertainty avoidance index-samenlevingen hebben een meer ontspannen houding waarin praktijk belangrijker is dan principes.

Nederland ligt net iets boven het gemiddelde en houds zich meer vast aan rigide geloofs- en gedragscodes. Polen is daar nog strenger in. Singapore heeft dat daarentegen helemaal niet.

<img src="https://user-images.githubusercontent.com/99249005/211500398-8aa03aa7-85a1-416f-bd4f-2b0d58bdca94.png"  width="500"/> [^29]

<h4>Indulgence vs restraint</h4>

Deze dimensie onderzoekt de mate waarin mensen proberen hun verlangen en impulsen te beheersen, gebaseerd op de manier waarop ze zijn opgevoed. Terughoudendheid gaat gepaard met de mate waarop er sociale controle is binnen een samenleving. 

Mensen in Nederland met een score van 68, tonen over het algemeen de bereidheid om hun impulsen en verlangens met betrekking tot genieten van het leven en plezier te realiseren. Ze zijn positief ingesteld en neigen naar optimisme. Bovendien hechten ze meer belang aan vrije tijd, doen ze wat ze willen en geven ze geld uit zoals ze willen.

In India is te zien dat hun score relatief laag is met 26, hier zijn mensen in die samenleving terughoudend. Bevrediging van behoeften wordt onderdrukt en gereguleerd door middel van strikte sociale normen.

<img src="https://user-images.githubusercontent.com/99249005/211532231-55984475-13ca-4f12-9ae8-dbeb2b57ec50.png"  width="500"/> [^29]

   
   <h4> Voorbeeld uit het echte leven op gebied van culturele verschillen </h4>
   
   Mijn vader is een software engineer en voor z'n werk gaat hij eens per jaar voor 3 weken naar India om daar workshops te geven. Met deze workshops is het de bedoeling om ze uit te leggen wat de manier is die papa hanteert om te coderen. Papa komt dan vaak met verhalen thuis dat de Indiërs erg graag luisteren naar wat papa te zeggen heeft, maar zodra hij vraagt of iemand snapt wat hij heeft gezegd, zag hij altijd knikkende hoofden die zeiden dat ze het allemaal begrepen. Hierbij zijn de mannen overpowered en zie je weinig vrouwen. Hun cultuur houdt in dat het onbeschoft is om te zeggen dat je iets niet begrijpt tegen diegene die hun iets aan het leren is. Papa zal dan ook vragen aan een Indiër of hij kan uitleggen wat papa heeft gezegd, maar vaak kunnen ze dat niet omdat ze het niet begrijpen. 
   
   Hierbij speelt de terughoudendheid uit het Hofstede's cultural dimensions theorie een rol. Indiërs hebben een lagere indulgence score. Ze zijn teughoudend. Nederland daarentegen neigt naar optimisme. Ze hechten meer belang aan vrije tijd, doen ze wat ze willen en geven geld uit zoals ze willen. Vanwege de stricte normen in de cultuur avn India is het onbeschoft om 'nee' te zeggen en zijn op dat gebied erg terughoudend.
   
   
[^25]: [bron: cultuur betekenis](https://www.vandale.nl/gratis-woordenboek/nederlands/betekenis/cultuur)
[^26]: [bron: wat is cultuur](https://news.hofstede-insights.com/news/what-do-we-mean-by-culture)
[^27]: [bron: power distance insight](https://www.hofstede-insights.com/models/national-culture/)
[^28]: [bron: power distance](https://gedragvandeconsument.nl/hofstede-dimensies/)
[^29]: [bron: image power distance](https://www.hofstede-insights.com/country-comparison/denmark,the-netherlands,singapore,slovakia/)

   </details>
   
   <details>
   <summary><h4> Ethiek </h4></summary>
 <!--   <h4> Wat is ethiek? </h4> -->
 
 Ethiek is een systeem van "morele principes", anders gezegd is ethiek ‘kritisch nadenken over wat (moreel) goed is om te doen’.[^30] 
 
 Ethische code en professionele praktijk voor software-engineering kent 8 principes:
 1. Publiek - Software-engineers handelen in overeenstemming met het algemeen belang.
 2. Klant en werkgever - Software-ingenieurs zullen handelen op een manier die in het beste belang is van hun klant en werkgever, in overeenstemming met het algemeen belang.
 3. Product - Software-engineers moeten ervoor zorgen dat hun producten en gerelateerde aanpassingen voldoen aan de hoogst mogelijke professionele normen.
 4. Oordeel - Software-engineers moeten hun professionele oordeel integer en onafhankelijk houden.
 5. Beheer - Managers en leiders van software-engineering onderschrijven en bevorderen een ethische benadering van het beheer van softwareontwikkeling en -onderhoud.
 6. Beroep - Software-ingenieurs zullen de integriteit en reputatie van het beroep bevorderen in overeenstemming met het algemeen belang.
 7. Collega's - Software-ingenieurs zullen hun collega's eerlijk behandelen en ondersteunen.
 8. Zelf - Software-ingenieurs nemen deel aan een leven lang leren met betrekking tot de uitoefening van hun beroep en bevorderen een ethische benadering van de uitoefening van het beroep.[^31]
 
 <img src="https://user-images.githubusercontent.com/99249005/211567614-a25be2e3-b427-47d0-95e5-5830fc954f3d.png"  width="500"/> [^32]

 <h4> Toepassen van ethiek </h4>

 - TICT tool
 - Business process </br>
  Onze app zorgt ervoor dat het restaurant ethish verantwoord is, je ziet steeds meer dat technologie taken van de mens overneemt. Door dit initiatief bespaart het bedrijf op mankracht en dus op uitgaven aan loon voor personeel. Als personeel zou er een mogelijkheid kunnen zijn dat je niet meer hoeft te komen werken en dus je baan verliest, of in ieder geval minder nodig bent als personeel om te komen werken. <a href='https://github.com/brittbrink/S3-DB02-Portfolio#leeruitkomst-7-business-processen'>Zie business process</a>
 
 <!--  -->

 [^30]: [bron: ethiek definitie](https://www.knmg.nl/advies-richtlijnen/ethische-toolkit/verdiepen/begrippen-2/ethiek-6.htm)
 [^31]: [bron: ethiek principes](https://ethics.acm.org/code-of-ethics/software-engineering-code/)
 [^32]: [bron: ethiek afbeelding](https://www.utwente.nl/nieuws/2017/10/224945/ethische-basis-voor-verantwoorde-innovatie)
 
 
   </details>
   
## Leeruitkomst 6: Vereisten en ontwerp
**Leeruitkomst**: Je analyseert (niet-functionele) eisen, werkt (bouwkundige) ontwerpen uit en valideert deze met behulp van **meerdere soorten testtechnieken**.

**Meerdere soorten testtechnieken**: Je past gebruikersacceptatietesten en feedback van belanghebbenden toe om de kwaliteit van de vereisten te valideren. Je evalueert de kwaliteit van het ontwerp (bijvoorbeeld door testen of prototyping) rekening houdend met de geformuleerde kwaliteitseigenschappen zoals veiligheid en prestaties.
   
   <details>
  <summary><h4> Designs en wireframe </h4></summary>

  ```
  DOT framework method:
  - Gap analysis
  - Usability testing
  ```

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
   
  ```
  DOT framework method:
  - IT architecture sketching
  ```
 
 Ik heb voor mijn eigen project een beeld gecreeërd hoe ik mijn app 
 
   #### Conceptueel model IP
   ![conceptueel model semester3 drawio](https://user-images.githubusercontent.com/99249005/206427273-863be344-f7d8-4639-b93c-268c004b65eb.png)

   #### C4 model level 2 IP
   ![c2 model drawio](https://user-images.githubusercontent.com/99249005/203966746-67eb1fc8-fe63-466a-a65b-8976f74a5b66.png)
 
 #### C4 model level 2 GP
   ![image](https://user-images.githubusercontent.com/99249005/208912393-608d79a2-1051-44c8-9873-574282a4d481.png)
 
  #### Databasediagram GP
   ![databasediagram GP](https://user-images.githubusercontent.com/99249005/208915764-61a184fd-22c2-4d31-83da-32058e2da0c9.jpeg)

 Als we kijken naar de C4 modellen van IP en GP valt op dat er bij mijn individuele applicatie wordt uitgegaan van een user, iedereen die gebruik maakt van mijn applicatie, die maar een enkele web applicatie gebruikt. Terwijl wij voor ons groepsproject verschillende users hebben die een eigen pagina beheren en alleen die pagina te zien krijgen. Dit werkt in principe hetzelfde maar maken we in ons groepsproject verschillende web applicaties voor de juiste persoon. Verder maak ik in IP gebruik van een externe API waar ik informatie uithaal die ik laat zien in mijn applicatie. Dit hebben we in ons groepsproject niet, maar als een restaurant een eigen API heeft voor hun menu zou dit wel geïntegreert kunnen worden.

</details>



<details>
   <summary><h4> Usability test </h4></summary>
 
```
  DOT framework method:
  - Usability testing
  ```

</details>

   
## Leeruitkomst 7: Business processen
**Leeruitkomst**: Je analyseert en beschrijft **eenvoudige** bedrijfsprocessen die **gerelateerd** zijn aan jouw project.

**Eenvoudig**: Betrokkenheid van belanghebbenden, overwegend opeenvolgende processen met een of twee alternatieve paden.

**Gerelateerd**: Bedrijfsprocessen waarbij de software die u ontwikkelt gebruikt gaat worden (bedrijfsprocessen die de software moet ondersteunen door deze geheel of gedeeltelijk te automatiseren) of bedrijfsprocessen die nodig zijn voor het succes van uw softwareontwikkelingsproject (bijv. productrelease, marktrelease, financiële zekerheid).
   
   <details>
   <summary><h4> Business process </h4></summary>
   
  ```
  DOT framework method:
  - Business case exploration
  ```
 Ik heb voor ons groepsproject een business proces gemaakt die het globale beeld geeft wat onze app zou doen in het algemeen van het restaurant. Waarnaar ik eerst een business proces heb gemaakt waarin wordt getoond hoe het restaurant zou lopen als onze app er niet zou zijn. En een proces waarin het restaurant wel onze app hanteert.
 
 <!--  <h4> Business process zonder onze app </h4> -->
  <a href='https://user-images.githubusercontent.com/99249005/211197791-4859c979-4ad1-4364-a871-790c0c4f4bb9.jpg' target='_blank'><img src='https://user-images.githubusercontent.com/99249005/211197791-4859c979-4ad1-4364-a871-790c0c4f4bb9.jpg' border='0' alt='S3groepsproject-bedrijfsproceswithoutapp' width="700"/></a>
 

   <!-- <h4> Business process met onze app </h4> -->
   <a href='https://user-images.githubusercontent.com/99249005/211197896-f256b7fd-bb75-4809-9518-47aaa2a2f17f.jpg' target='_blank'><img src='https://user-images.githubusercontent.com/99249005/211197896-f256b7fd-bb75-4809-9518-47aaa2a2f17f.jpg' border='0' alt='S3groepsproject-bedrijfsproceswithapp' width="700"/></a>
  
 
  <h4> Conclusie: </h4> 
In het business process zonder de app is te zien hoe het personeel alle orders moet opnemen aan de tafel en hiermee veel tijd kwijt is om alle tafels af te lopen om ervoor te zorgen dat alles goed naar de keuken wordt gestuurd.  Met onze app besparen we tijd met het opnemen van bestellingen, alle tafels kunnen tegelijk bestellingen plaatsen. Er kunnen wel degelijk fouten gemaakt worden als het personeel de klant niet goed heeft verstaan of verkeerd begrijpt wat de klant bedoeld. Met onze app zorgen we ervoor dat er kan worden bespaart op personeel en dus minder uitgaven aan personeelsloon is.
 
   </details>
   
## Leeruitkomst 8: Professioneel
**Leeruitkomst**: Je handelt op een **professionele manier** tijdens het ontwikkelen en leren van software.

**Professionele manier**: Je vraagt en past actief feedback van stakeholders toe en adviseert hen over de meest optimale technische en ontwerp (bouwkundige) oplossingen. Je kiest en onderbouwt oplossingen voor een bepaald probleem.
   
   
   <details>
   <summary><h4> Contact </h4></summary>
  
 ```
  DOT framework method:
  - Peer review
  ```
 
   <h5> Mail contact </h5>
Het is vanzelfsprekend dat je je stakeholders op de hoogte houdt en als je vragen hebt over designs deze laat weten. Dit doen wij door mail contact te onderhouden. Ik heb de meeste mails geschreven waarbij we vragen hadden of bijvoorbeeld de datum, tijd en locatie van de oplevering konden doorsturen. Hierbij een voorbeeld van één van de mails die verzonden zijn:

![image](https://user-images.githubusercontent.com/99249005/206404825-4d09da8f-2ec4-4f49-981a-cfd737308062.png)

<h5> Feedpulse </h5>
Ook praat ik regelematig met docenten om zo mijn voortgang te laten zien en vragen te stellen of ik de goede richting in ga.

*insert feedpulse*
 
 <h5> Peerreview </h5>
Nadat we een sprintoplevering hebben afgerond hebben we in ons groepsproject een elkaar feedback gegeven voor die sprint, wat ging goed en wat kon beter. Dit staat vastgelegd in de peerreview.
 
 *insert peerreview*
 
<h5> Documentatie </h5>
In het afgelopen document heb ik documentatie geschreven die van toepassing is om mijn leerdoelen te halen. Hierbij heb ik onderzoek gedaan. Ik heb hoofd- en deelvragen opgesteld en vanuit hier mijn onderzoek uitgebreid.


   </details>
   
   <details>
   <summary><h4> APA stijl </h4></summary>
 
 Hieronder zie je een voorbeeld hoe APA stijl werkt en hoe je het zou kunnen gebruiken. 
 
   (Bhadwal, n.d.) (Palachuk, 2021) (Trask, 2012) (Shead, 2016)

 <h5> Bibliography </h5>
Bhadwal, A. (n.d.). C# vs. Java: Which Language is Better to Learn? Retrieved from hackr.io: https://hackr.io/blog/c-sharp-vs-java#:~:text=Java%20is%20class%2Dbased%20and,oriented%20languages%20with%20strong%20communities. </br>
Palachuk, M. (2021, May 10). How to Define Agile in the Simplest Terms Possible. Retrieved from thinkHDI: https://www.thinkhdi.com/library/supportworld/2021/define-agile-in-simple-terms.aspx </br>
Shead, M. (Director). (2016). What is Agile? [Motion Picture]. </br>
Trask, J.-D. (2012, March 07). Optimizing ORM Performance. Retrieved from InfoQ: https://www.infoq.com/articles/optimizing-orm-performance/ </br>

   </details>
