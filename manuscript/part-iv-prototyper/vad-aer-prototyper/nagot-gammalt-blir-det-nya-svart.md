# Något gammalt blir det nya svart

**Nej, låt oss ta om det där!**

Det ovanstående var början till ett tidigt utkast av det här kapitlet. Vi skulle kunna kalla det en skiss eller kanske till och med en...prototyp! Och efter att flera kloka människor läst utkastet --- inklusive bokens eminenta redaktör --- så kom det många smarta synpunkter och förslag på förbättringar. Några tyckte det var lite stolpigt skrivet, att det inte riktigt passade in i den ton som den övriga texten hade. Några tyckte att det liksom började i fel ände, att det vore bättre att börja med en tillbakablick så att läsaren genast fick lite kontext. Typ så här:

Något gammalt och beprövat blir det nya svarta

Som vi redan varit inne på är prototyper långt ifrån något nytt under solen. Men det har blivit något som fler och fler pratar om i den digitala världen. Du har säkert hört talas om _Rapid Prototyping_ eller något annat sådant buzzword. Och innan vi ger oss in på hur vi ska använda prototyper på ett effektivt sätt, ska vi göra en snabb orientering.

Inom många sorters tillverkning, särskilt där det krävs en stor investering i framställandet av själva slutprodukten, har man länge använt sig av prototyper. Också när det finns en hög grad av komplexitet och det är listigt att prova några olika sätt att lösa saker på som ett led i själva konstruktionsprocessen. Vi är alla vana att se prototyper av till exempel bilar och flygplan som används till allt från vindtunneltest till att visa upp på mässor. Just vindtunneltest har blivit en sådan symbolisk övning att det i vissa kretsar blivit ett uttryck att “vindtunnla” även sådant som inte är fysiska objekt utan även abstrakta idéer. För att få motsvarande nytta som i en fysisk tunnel blir det då avgörande att definiera vad som är vinden och hur stark den är.

Många andra verksamheter har också använt sig av prototyper. Ta till exempel textilindustrin där man gör provplagg innan det är dags för serietillverkning. Samma med möbler och med arkitekter. Redan Christofer Polhem byggde modeller av de nyskapande maskiner han konstruerade för att kunna prova olika lösningar innan de tillverkades i full skala. Ett smart drag när full skala innebär att ge sig hundratals meter ned i gruvschakt. Flera av dessa prototyper finns bevarade och till beskådande i Gruvmuseet i Falun, Dalarna.

Så varför behöver vi prata om prototyper nu?

**Vad hände?**

De flesta verksamheter som använder prototyper som en naturlig del av sin utvecklingsprocess sysslar med serietillverkning av fysiska produkter. Antingen är slutprodukterna i sig själva dyra och komplicerade --- som byggnader och flygplan --- eller så behöver serien vara stor -- som med kläder. Det finns dessutom en hög grad av uppdelning. En biltillverkare gör en prototyp för att testa en ny form på hjulhusen. En klädtillverkare vill testa ett nytt material till foder eller en ny form på en huva. Men resten av bilen eller plagget behöver inte vara färdigt eller ens på plats för att testa delen i fråga.

Och för att öka farten på vår digitalisering behöver vi göra samma sak: Testa mindre delar som ett led i beslutsprocessen för vad vi ska utveckla och inte.

Varför har inte detta sätt att arbeta varit vanligt inom digital tjänsteutveckling, trots att digital utveckling är enklare/billigare än fysisk? Det finns så klart många förklaringar och några av dem pekar på saker som är viktiga att undvika framåt.

Ett \(Tjänsteutveckling har en sämre tradition\)

Sedan tjänstesektorn började öka i volym från 1980-talet och framåt \(vissa hävdar att den totalt sett inte ökade, utan att tjänster som företagen själva gjorde outsourcades till utomstående leverantörer\) och blev till en mycket stor andel av vår totala BNP, har utvecklingen av tjänster gått igenom några olika stadier. Och tyvärr har det inte bara blivit bättre och bättre --- det är en av anledningarna till att vi ser att digitaliseringen innebär en disruption för befintliga tjänster. Istället har mycket icke-digital tjänsteutveckling präglats av massiva processarbeten som varit skrivbordsprodukter. En stor investering i början av processen. Det vill säga de har inte testats live i den utsträckning som skulle behövas för att få värdeskapande feedback från kunder eller användare. En av de stora fördelarna med den digitala världen är att det är så mycket lättare att testa, eftersom tjänsten också är lika med sin digitala upplevelse, sitt digitala flöde. Men vi har länge levt kvar i den tradition som vi redan befann oss i. Och som många fortfarande befinner sig i.

Två \(Design och marknad har jobbat i stafetter\)

Precis som inom tjänsteutvecklingen har design och marknadsföring också traditionellt jobbat i stafetter, i linjära projekt där en stor del av investeringen i tid och resurser görs i början. Även när design och UX blev digitala discipliner var det vanligt att man designade och gjorde UX för en hel sajt eller en hel app på en gång. Man gjorde skisser för allting, gjorde all design klar, innan man började bygga sajten eller appen. Eller, varför använder vi egentligen förfluten tid här? Detta är fortfarande oerhört vanligt och är en av de största orsakerna till flaskhalsarna i utvecklingen av kundupplevelsen.

Det är en av de vanligaste anledningarna till att det går långsammare att bygga digitala tjänster och appar än det borde. Och det är en av de största anledningarna till att tjänsterna inte blir så bra som de skulle kunna bli.

Tre \(Agila processer går ofta direkt på högupplöst kod\)

Inom programmering har vi kommit från en värld där vi satt på kammaren och utvecklade stora mängder kod, testade den på kammaren och lanserade den. Till en värld där vi kodar små mängder, moduler, av kod och testar och lanserar. Där också lanseringen är del av att testa: Vi tittar i Google Analytics och liknande verktyg för att se hur den nya koden fungerar i verkligheten, hur den fungerar för användarna och ändrar ifall den inte fungerar tillräckligt bra. Men även om det är en oändlig skillnad mellan de gamla vattenfallprojekten och att arbeta agilt, så har de agila arbetssätten fokuserat på att lansera fungerande kod -- det vill säga något vi skulle kunna kalla _högupplöst kod_ eller för att använda en teknisk glosa: Vi släpper saker i _produktionsmiljön_, den som är “live” och som alla användare och kunder interagerar med. Vilket ställer höga krav på hur färdigt det måste vara. \(Saker får till exempel inte gå sönder.\)

Men en prototyp _behöver_ _inte_ testas i produktionsmiljön. Det finns många andra, snabbare sätt att testa och det är just det en prototyp är till för: Att med så låg insats som möjligt snabbt få svar på om vi är på rätt väg och därmed ska gå vidare på den eller inte.

Nu för tiden behöver prototyper inte ens kodas och använder du den typen av prototypverktyg som vi gick igenom i avsnittet om verktyg \[sidreferens\] finns det ännu mindre anledning att testa dem live på din sajt. Du har då möjligheten att testa saker lätt och snabbt med användare på plats eller “på avstånd” -- det vill säga via webben. \(Mer om olika sätt att testa i nästa kapitel.\)

Så även om först mjukvaruutveckling och sedan utvecklingen av digitala tjänster blivit agila, har det fram till nu funnits ett fokus på “högupplöst” kod som gjort att man generellt inte arbetat med prototyper innan utveckling, utan med _working software._ Det har varit en helt nödvändig utveckling, för den har givit oss den livsviktiga möjligheten att uppdatera digitala produkter när som, pö om pö. Men nu när vi också har verktygen för att enkelt göra prototyper som kan vara “lågupplöst kod” och ibland ingen kod alls, så gäller det att ta vara på den möjligheten. Så att vi kan få feedback och lära oss saker _innan_ vi investerar tid och resurser i att bygga högupplöst kod.

Fyra \(Nu kan vi testa kundupplevelsen\)

En stor och viktig skillnad mellan hur vi utvecklade digitala tjänster tidigare och vad vi kan göra nu är att kundupplevelsen då var svår att testa på en nivå som var tillräckligt illusorisk för att ge vettiga testresultat. Men nu när den tekniska utveckling givit oss verktyg som gör det möjligt att med förhållandevis liten insats bygga prototyper som av användarna upplevs som nära nog “the real thing” så är situationen den motsatta. Vilket betyder en hel del för hur vi kan utveckla kundupplevelser.

En bra jämförelse är arkitektur, där VR-tekniken nu gör det möjligt för kunderna att “gå in i” arkitektens ritningar. Vilket i sin tur leder till att företag som Skanska har VR-rum som står färdiga så att det inte ska finnas någon uppförsbacke för att bara gå in och testa. Då blir en virtuell verklighet lika enkel att bygga upp som att förr i tiden göra en utskrift av ritningarna och då börjar man också använda det dagligen och får en katalysatoreffekt av metoden.

Men trots att VR-teknik är mycket mer avancerad att installera jämfört med de verktyg som finns för digitala kundupplevelser, så används inte denna möjlighet till att testa prototyper lika mycket inom utveckling av digitala tjänster som inom byggbranschen. Varför?

En förklaring är att arkitekter och byggbranschen kommer från en tradition där man byggt modeller innan man byggt i full skala ända sedan Polhem, minst.

En annan förklaring är att design och UX som branscher kommit senare till matchen än vad utvecklarna har. Det har funnits ett större mått av “testmentalitet” inom programmering som hantverkstradition. Och det går inte att komma undan hur designbyråer \(likt reklam- och webbyråer\) odlat auteurmyten --- kreatörsmyten. Dels som ett sätt att höja det upplevda värdet av det man levererar \(du får tillgång till den här experten\), men dels också som en version av det vi brukar kalla _Hero-komplexet_. En variant på myten om det ensamma geniet som alltid kommer med de bästa lösningarna, de _rätta_ lösningarna. Något som förstärks av de många olika tävlingarna och priserna inom design. \(När hörde du om en utvecklare som vunnit en kodtävling sist?\)

Detta är Hero-komplex något vi vill undvika i hur vi jobbar.

I brist på “tidiga tester” --- det vill säga innan man börjar skriva kod --- ramlade också UX-yrket ner i ett kaninhål som var mer än kvasivetenskapligt. Man formulerade teorier om vilka interaktionsmönster som var bäst i vilka situationer, för vilka syften, och detta blev till en slags grammatik som utbildningar i User Experience lärde ut. Allt var självklart inte bortkastat, men hela approachen led av problematiken som uppstår när vi sitter på kammaren och försöker räkna ut hur kunderna ska bete sig, istället för att låta kunderna visa och berätta för oss.

Många av de hitte-på-på-kammaren-teorierna har tyvärr överlevt och blivit till starka “sanningar”, vilket gör det så mycket viktigare att testa många olika idéer till interaktion i prototyper. Annars är det lätt att fastna i sådant vi tror är rätt men som inte fungerar bra i praktiken.

Ett bra exempel är den oerhört långlivade regeln att användarna inte såg något som var “under kanten” -- eller _below the fold_ på anglikanska. Folk skulle inte orka scrolla och se vad som fanns på den delen av en sida som låg utanför och under vad skärmen visade. Istället skulle man se till att besökaren agerade på saker inom den “första skärmen” och med hjälp av knappar eller menyer laddade en ny sida. På vilken samma regel applicerades.

Sen fick vi smartphones och appar som Instagram.

Och då visade det sig att användarna hellre scrollade än bytte sidor hela tiden. En beteende som egentligen var så naturligt att när tjänster började använda sig av samma design och UX oavsett vilken device besökaren använde visade det sig att de tog med sig beteendet från mobilerna till desktop där “regeln” än gång föddes. En måttståck på hur fel teorin var är siffror från en av Europas största e-handlare. När de gjorde om sitt betalflöde --- kassan där du ska betala vad du har beställt --- från en flersidigt där varje steg i flödet var på sin egen sida och sen gick du vidare, till en ensideslösningar där du istället scrollade dig vidare \(_long scroll_\) så ökade antalet genomförda betalningar med 17%.

Nu när vi enkelt kan göra klickbara prototyper utan att koda måste vi med andra ord undvika att bestämma oss i förväg för vilken design och vilka sätt att interagera med produkten som är de rätta. Istället måste vi formulera hypoteser som vi med hjälp av prototyper kan validera eller förkasta.

En annan faktor inom testning av högupplöst kod --- _working software_ --- är att den är ytterligare exempel på de senaste årens fokus på _kvantitativ_ data. Som leder till ett cirkelresonemang. Självklart är det ultimata testet när riktiga kunder använder den “färdiga” digitala produkten live. Precis som inga modeller kan jämföra sig med hur det är att gå in i det färdigbyggda huset. Men för att komma dit behöver vi göra den största investeringen i processen: Vi behöver utveckla högupplöst kod, vi måste bygga huset på riktigt.

Om det då finns ett väldigt enkelt och kostnadseffektivt sätt att testa olika alternativ _innan_ vi gör den investeringen för att se till att vi lägger tid och pengar på att utveckla i rätt riktning, vad skulle då vara argumentet emot det?

När det dessutom visar sig att åtta-tio djupintervjuer, där testpersonerna får använda en prototyp på samma sätt som de skulle använda den färdiga produkten, ger så pass tydliga svar \(och ny kunskaper vi inte ens visste vi skulle fråga efter\) att de korrelerar med vad Google Analytics-siffror säger om ett A/B-test av samma sak i produktionsmiljö, då är det underligt att så få använder det verktyget.

_Kvalitativ_ data är, som vi ska se i kapitlet om tester, nyckeln till att skapa en bättre kundupplevelse.

Fem \(Nu kan vi integrera design i arbetsflödet\)

Om det första vi skulle undvika var att gå direkt till att producera högupplöst kod och det andra var att falla för Hero-komplexet inom design och UX så är den tredje saken att undvika en slags kombination och ettan och tvåan.

Vi har redan varit inne på hur de agila arbetsmetoderna är överlägsna inom digital utveckling, men det finns självklart förbättringsmöjligheter. Och en av dem är integrationen mellan design och kodning. De agila metoderna utvecklades av mjukvaruingenjörer för mjukvaruingenjörer och ska man vara fördomsfull så är ingenjörer normalt inte starka på design. \(Självklart en total och grov generalisering!\) Även om det heter att agila team ska vara tvärfunktionella så innehöll de inte i början några designers eller UX:are. Men i takt med att webben växte och en allt större volym av digitala tjänster skulle användas av vanliga människor blev design och UX allt viktigare. Fortfarande är det dock mycket vanligt att design och UX är en flaskhals i organisationen. Att det inte finns tillräckligt många för att varje agilt team ska ha fasta medlemmar av detta skrot och korn! Det är också mycket vanligt att höra utvecklingsteam som ska plocka upp något från backlogen för göra det under sprinten, bara för att utbrista “Den här User Storyn behöver ju UX!”.

Många olika lösningar på detta problem har sett dagens ljus -- allt från _Design Ahead_ till _Lean UX,_ men de allra flesta av dem har en sak gemensamt: De skapades innan vi hade dagens verktyg. Och innan vi hade dagens infrastruktur med mikrotjänster och API:er. När du nu mycket enkelt kan tillverka en klickbar prototyp i samma verktyg som du ändå använder för design och UX, så betyder det väldigt mycket för det arbetsflöde du kan skapa.

Jämfört med tidigare när UX:are satt i Axure och designers i Photoshop kan vi integrera arbetsflödet lättare och eftersom vi med mycket mindre ansträngning kan få reda på vilken design, vilken kundupplevelse, som kunderna verkligen skulle föredra, så ska vi också utnyttja den möjligheten. För våra konkurrenter gör det redan. Och framför allt kan vi integrera design och UX på ett annat sätt i tvärfunktionella team.

De klickbara prototyperna innebär inte bara möjligheten att testa fram vilket vägval som är det rätta innan vi lägger ned stora resurser på att utveckla. De innebär också att vi nu har en mycket bättre möjlighet att prova delar av interaktion och funktionalitet i teamet innan vi kodar dem. Även för vår egen del kan vi alltså visualisera mycket bättre, till exempel prova fram vilka animationer som fungerar bäst. Vilket betyder att vi har ett mycket bättre underlag --- mycket bättre “skisser” --- jämfört med tidigare.

Den tredje saken vi ska se upp för och undvika är alltså att separera på design, UX och utveckling. Istället ska vi se till att det i största möjliga mån ingår design och UX i utvecklingsteamen för annars är de egentligen inte tvärfunktionella. Och om det inte är möjligt just idag där du jobbar så finns det sätt att saxa resurser och se till att varje team vet vilka designresurser som är dedikerad till dem, även om de inte har sina egna. Mer om detta i avsnittet om Fascilitering\[länk\].

För att öka farten på digitaliseringen och innovationen är det ett måste att integrera design och utveckling. För det är kundupplevelsen som resan nu och i framtiden är den största konkurrensfaktorn.

