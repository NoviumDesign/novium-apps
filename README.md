# Novium Apps®
Hej!

Välkommen till Novium Apps®. Denna handbok hjälper oss att ta smarta beslut och utveckla produkter som är lönsamma både för oss och våra kunder. Handboken förändras allt eftersom vi lär oss nya saker, vilket vi aldrig slutar att göra.

## Arbete och tider
Även om många aktiviteter inom utveckling kan skötas på distans eller valfria tider på dygnet försöker vi i största möjliga mån vara på plats under normala arbetstider. Våra designers och projektledare behöver ha en tät dialog med utvecklignsteamet. Din arbetstid är 8h per dag och du kan flexa din start mellan 8-9 på morgonen.

Varje fredagseftermiddag (start 12.00) dedikeras till egna utvecklingsprojekt. Under dessa tider gör vi inte konslutuppdrag till kunder utan fokuserar på eget lärande, utforska nya tekniker etc. Kom ihåg att Noviums styrka ligger i att ha väl utarbetade arbetsmodeller och koll på vilken teknik som är aktuell. Utan eget lärande halkar vi efter marknades utveckling.

Om någon är sjuk eller om vi haft ledigt i veckan används fredagseftermiddagen istället till konsultuppdrag.

Vi försöker i största möjliga mån undvika att ringa kollegor på helger och kvällar. Skicka istället ett mail och ta upp frågan nästkommande arbetsdag om du kommer på något under ledighet som du inte vill glömma bort. Ett aktut läge är alltid ett rimligt skäl att frångå detta. I dessa lägen försöker vi alltid hjälpa teamet.

##Egen utvecklingstid
Under din egna tid på fredagar kan du till exempel göra följande
* Skriva ett blogginlägg
* Pröva en ny teknik eller bilbliotek
* Se tutorials på youtube eller liknande i något som rör ditt arbete
* Träffa nya kontakter från branchen
* Ta en after work med en kund
* Bidra till ett open source projekt
* Utveckla nya riktlinjer till denna handbok

## Mobilappar
På Novium är vi specialicerade på business-appar. Vi utvecklar applikationer som understödjer ett affärsvärde. Vi utvecklar inte applikationer med enbart nöje som syfte, såsom spel etc.

All vår utveckling görs med webbtekniker. Vi utvecklar inte Native applikationer. Det finns flera anledningar till detta:

* Hyrbridappar går snabbt att utveckla
* Rätt utvecklat märks knappt någon skillnad på en native eller webbapp. Hur du ska utveckla din app förklarar vi i vår tekniska specifikation.
* Vi täcker av både iOS och Android med samma kodbas. Tidigare erfarenheter har visat oss att båda platformarna krävs i en lansering för att produkten ska bli lyckosam.
* Om kunden i framtiden även vill ha en app för datorer kan vi ofta återanvända stora delar av koden och spara kunden pengar.

Vi använder oss av följande tekniker
* Angular och Ionic för klientsidan
* Ruby On Rails för serversidan
* Slate Docs för att dokumentera API
* Firebase i de fall vi inte behöver ett rails backend.

## Starta ett nytt mobilappsprojekt


### Prototyp
Vi börjar alltid med en designprototyp av applikationen. Detta ligger till grunt för den slutgiltiga offert kunden får på att utveckla appen. Prototypen designar i Illustrator och får liv genom invisionapp. Genom detta tillvägagångssätt minskar vi behovet av att skriva om vår kod och sparar kunden pengar. Dessutom kan vi i ett tidigt statie ta in en testgrupp, vilket gör att vi skapar ännu bättre produkter.

### Val av backend
Firebase är en hostad NoSQL databas med automatiska endpoints. Vår erfarenhet säger att vi kan vara otroligt produktiva med Firebase i det fall applikationen som mest har behov av att joina 2-3 tabeller i taget. Om relationerna är komplexa är ett backend i Rails att föreda. Kom dock ihåg att Rails backend + API-dokumentation adderar tid till projektet. Överväg därför ditt val av backend noga.
