# week-1-webapp-from-scratch

Opdracht 2.

Pros-Cons-JavaScript-libraries-frameworks

Description of the pro's and con's of javascript libraries and frameworks

Het toepassen van een JS librarie/framework hangt geheel af van de context. Het is dan ook handig om jezelf af te vragen wat voor functionaliteiten je nodig hebt. Wil ik een model opstellen die reageert op een controller om zo een view te renderen? Of kom ik uit de voeten met een jquery librarie?

Wanneer zou iemand dan kunnen kiezen voor een JS librarie?

Voor mijn voorbeeld neem ik de JS library jQuery. Developers kunnen middels een laagdrempelige librarie op een effectieve manier hun DOM elementen manipuleren. jQuery heeft een makkelijke syntax en er zijn talloze voorbeelden online van allerlei functionaliteit die letterlijk te copy pasten valt. Wat men zichzelf af kan vragen, wat gebruik ik nou daadwerkelijk uit een jQuery librarie? En is het, het waard om de hele librarie in te laden? Als het gebruik van jquery alleen voor een spannende animatie bestemd is valt sterk te overwegen om de librarie niet te gebruiken, dit in verband met de laadtijd van je applicatie. Een goede source http://youmightnotneedjquery.com/.

Daarnaast liep ik laatst ook tegen een vereveld punt aan, de $ selector van jquery geeft geen nodeList terug maar een jquery element. Dit element is haasts niet mee te praten via vanilla js, dus het aanpassen is ook vrij lastig.

Als voordeel, libraries zijn veel gebruikt online en er zijn dus werkende voorbeelden te kopieren.

Wanneer gebruik ik dan wel een JS framework? Kijk goed naar de schaalbaarheid van je applicatie, welke functionaliteit moet ik hebben en hoe groot wordt mijn applicatie? Moet ik perse een MVC model aanhouden of kom ik ook weg met een framework? Als je het antwoord op die vraag hebt, dan weetje of je voor een librarie of niet moet kiezen.

Bronvermelding

http://lea.verou.me/2015/04/jquery-considered-harmful/ http://programmers.stackexchange.com/questions/105352/why-should-i-use-an-mvc-pattern Allenc. (2015). http://allenc.com/2015/02/when-to-not-use-a-javascript-framework/

Opdracht 3

Pro's en Con's van een single page webapp onderzoeken

Een SPA is een tijdbesparende manier op een applicatie op te leveren die bruikbaar is op alle devices. Uiteraard komt dit met zijn voor en nadelen. De nadelen: Een veelvoorkomend nadeel van een SPA is goede SEO behouden. Daarnaast is het ook belangrijk dat je de browser standaarden niet wilt overschrijven.

De voordelen: Het levert features en functionaliteit die afstammen van traditionele desktop applicaties. Het is snel, responsive en de information flow is enhanced. Ook is er immediate feedback voor de user.

Bronvermelding https://www.linkedin.com/pulse/why-single-page-application-pros-cons-ravi-hamsa
