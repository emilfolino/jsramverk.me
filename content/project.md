# Projekt

<p class="author">Emil Folino</p>

> **Kursmomentet uppdateras** Kursen håller på att göras om inför kurstillfället HT2021. Kursmaterial för 2020 finns på [https://2020.jsramverk.se/](https://2020.jsramverk.se/).

Du jobbar som teknisk arkitekt och teamledare i en framstormande startup där du har [Carte Blanche](https://en.wikipedia.org/wiki/Carte_blanche) att välja teknik inför ett nytt spännande projekt, som är tänkt skaka om trading-branchen. Du har stor påtryckning från eran investor [a12o](https://a12o.emilfolino.se) att detta projekt måste lyckas för att de ska kunna glida resten av livet.

Du har valt att bygga ihop en väl fungerande applikation som påvisar alla de tekniker du tror på. När du är klar så är tanken att du presenterar projektet och teknikerna för dina medlemmar i teamet och din applikation fungerar som utvärderings- och utbildningsmaterial för ditt team.

Tänk på att ditt team till största del består av PHP-utvecklare kritiska mot nya tekniker och du behöver göra ett gott jobb för att imponera på dem. Annars är risken att de sågar dina nya idéer.



#### Projektspecifikation

Du ska utveckla och driftsätta en trading plattform baserad på följande kravspecifikation. Du ska själv välja objekt att sälja exempel på objekt kan vara råvaror, värdepapper, antikviteter eller varför inte kakor & tårtor?

Saknas info i specen så kan du själv välja väg, dokumentera dina val i redovisningstexten.

De tre första kraven är obligatoriska och måste lösas för att få godkänt på uppgiften. De tre sista kraven är optionella krav. Lös optionella kraven för att samla poäng och nå högre betyg.

För allra högsta betyg krävs en allmänt god applikation. Den skall vara snygg, tilltalande, lättanvänd, väl dokumenterad och felfri.

Varje krav ger max 10 poäng, totalt är det 60 poäng.

#### Repon på GitHub

Skapa flera repon för projektet. När du är klar, committa, tagga, pusha till GitHub. Länka till dina repon i din inlämning på Canvas.



### Krav 1: Backend

Skapa ett API för trading av dina valda objekt. Användare av din tradingplattform ska kunna registrera och autentisera sig mot plattformen. Som autentiserad användare ska det gå att köpa och sälja valda objekt som hamnar i ett depå kopplat till användaren. Gör det även möjligt för användaren att sätta in medel på depån, som användaren sedan kan handla för.

Gör ett medvetet val av teknik och berätta utförligt i din README om vilka teknikval du har gjort och varför.



### Krav 2: Frontend

Skapa en klient som är publikt tillgänglig.  Klienten ska vara designat för att användas på enheter av olika storlekar. I klienten ska det vara möjligt att autentisera sig mot API:t. När klienten är autentiserad kan användaren se tillgängliga medel och objekt i depån samt handla med objekt. Gör det även möjligt för att användaren att sätta in medel på depån, som användaren sedan kan handla för.

Gör ett medvetet val av teknik och berätta utförligt i din README om vilka teknikval du har gjort och varför.



### Krav 3: Realtid

Skapa en realtids micro-service som hanterar priserna för dina säljobjekt. I din frontend ska denna micro-service användas för att grafisk representera priserna i realtid.

I dina README beskriver du i ett eget stycke om hur du implementerade realtidsaspekten i din applikation. Du skriver också om vilken teknik/verktyg du valt för din implementation samt en kort reflektion av hur du tycker tekniken fungerar.



### Krav 4: Tester backend

<div class="under-construction" id="under-construction">
    <p class="optional">Optionellt krav</p>
</div>

I din README skriver du ett stycke om vilka verktyg du använt för din testsuite och om det är delar av applikationen som inte täcks av tester. Du reflekterar kort över hur dina teknikval fungerat för dig. Du reflekterar också över hur lätt/svårt det är att få kodtäckning på din applikation.

Man kan köra hela din testsuite lokalt via `npm test`.

Du har god kodtäckning i enhetstester och integrationstester på backend. Sträva efter 70% där det är rimligt, men se det som en riktlinje och inte ett hårt krav.

Ditt repo har en CI-kedja och automatiserade tester med tillhörande badges för byggtjänst, kodtäckning och tjänst för kodkvalitet.

I din README skriver du ett stycke om CI-kedjan, vilka tjänster du valt och varför samt eventuella begränsningar i hur CI-kedjan kan hantera din applikation. Du gör en kort reflektion över din syn på den hjälpen liknande verktyg ger dig.

Berätta om du är nöjd eller inte med de betyg som tjänsten för kodkvalitet ger dig.



### Krav 5: Tester frontend

<div class="under-construction" id="under-construction">
    <p class="optional">Optionellt krav</p>
</div>

I din README beskriver du 5 stycken use-cases för din applikation, som du sedan använder Selenium för att testa.

Man kan köra hela din testsuite lokalt via `npm test`.



### Krav 6: Akademiskt skrivande

<div class="under-construction" id="under-construction">
    <p class="optional">Optionellt krav</p>
</div>

En viktig del av forskning är att veta vad som har gjorts inom området tidigare och vad din studie bidrar med. Därför behöver man söka upp vad som har gjorts innan inom området. Som en del av exjobbet görs en literatur genomgång där du som författare samlar de viktigaste källor inom området och sammanställer nuvarande forskningen inom området.

Från exjobbsmallen tar vi följande text:

> Review the possible references. Write with your own words and refer to the selected references. Describe when references are supporting each other, and describe when they are in conflict with each other. Tie the references together and make your (theoretical) conclusion based on your interpretation.

I spellistan [Referenshantering](https://www.youtube.com/playlist?list=PLKtP9l5q3ce-2gQ9hDzqlW_K62GbfpZa_) på youtube finns det bra tips och trix för att hantera referenser.

**Lämna in texten som PDF bilaga till din inlämning på Canvas.**



## Redovisning

Gör en inlämning på Canvas med följande innehåll:

Länka till dina GitHub repon och driftsatta sidor i en kommentar till din inlämning.

På sidan `/reports/week/10` i din me-applikation skriv följande (länka till me-applikationen i en kommentar till inlämningen):

1. Berätta om vilka optionella krav du har gjort och om du gjorde nya vägval rörande tekniker inför projektet.

2. Skriv ett allmänt stycke om hur projektet gick att genomföra. Problem/lösningar/strul/enkelt/svårt/snabbt/lång tid, etc. Var projektet lätt eller svårt? Tog det lång tid? Vad var svårt och vad gick lätt? Var det ett bra och rimligt projekt för denna kursen?

3. Avsluta med ett sista stycke med dina tankar om kursen och vad du anser om materialet och handledningen (ca 5-10 meningar). Ge feedback till lärarna och förslå eventuella förbättringsförslag till kommande kurstillfällen. Är du nöjd/missnöjd? Kommer du att rekommendera kursen till dina vänner/kollegor? På en skala 1-10, vilket betyg ger du kursen?



### Presentation

Spela in en redovisningsvideo som ni länkar till i inlämningen på Canvas. Prata främst om de val ni har gjort och varför.
