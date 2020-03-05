**Vilken ny teknologi måste vi lära oss?** 

Låt oss börja med att konstatera att rubriken till detta kapitel är en kuggfråga. Det har under de senaste åren funnits en uppsjö av teknologier som lanserats med buller och bång och fått status som ”måsten”, men som redan nu inte längre finns ibland oss. Den ökade förändringstakten gäller naturligtvis i högsta grad teknologi. Den är i sig själv en av de starkaste drivkrafterna till förändringarna. Vi har nyss gått igenom de tre M:n --- Mobilen, Molnet och Maskininlärning --- och de är exempel på de tre stora grupper, samlingar, av teknologier som samverkat för att se till att vi är i den situation som vi är i nu. Mendet finns väl också saker vi behöver i det dagliga för att åstadkomma det vi vill? För att bygga våra tjänster och upplevelser? Vad ska vi ha för CMS, för webbplattform? Det måste ju nu finnas de plattformar som är bättre än de som gällde för några år sedan, några vi borde byta till? 

Fram tills nyligen har det varit väldigt mycket av sådana resonemang inom det digitala. Mycket resurser har gått åt till valet av plattformar och när du väl valt har du suttit fast i den plattformen under några år. Tills det kommit en ny, bättre, och allt börjar om, Ny förstudie. Ny webb. Därför är det bra att ta till sig uttrycker “När tåget lämnar stationen är det plattformen som blir kvar.”

När vi säger “suttit fast” är det för att nästan alla plattformar har tidigare haft någon form av instängning. Antingen har det byggt på att leverantören förutom webbplattformar också gör andra, till exempel CRM --- system för Custom Relationship Management. Och för att skapa merförsäljning har de sett till att de olika plattformarna fungerar bäst tillsammans med varandra. Eller, i vissa fall, bara med varandra. I andra fall har det varit grundläggande teknologier: En särskild webbplattform kanske bygger på programmeringsspråket .Net eller Java och då behöver tillbehören också göra det. 

Men vän av ordning har nu redan dragit slutsatsen. Att vara instängd på olika sätt rimmar illa med en hög förändringstakt. Utvecklingen av en webb kräver stora resurser, stora investeringar i både kalendertid och arbetstimmar. Och om allt det arbetet är instängt i en viss teknologi så måste mycket göras om när du måste byta plattform för att skaffa er nya förmågor och möjligheter. Det handlar ju inte bara om allt det arbete som krävdes för att bygga det som då var den nya webben. Utan också om allt jobb som lagts ned efteråt på förbättringar, nya funktioner och nytt innehåll. 

Därför har det under de allra senast åren utvecklats en “teknikfilosofi” som går ut på att vara så plattformsoberoende som möjligt. Hur går det till? Det är ju livsavgörande för ett företag att ha en sajt och --- som vi ska se senare --- det är till och med avgörande att ha bra! På något sätt måste du väl kunna publicera innehåll, funktioner och upplevelser för/till dina kunder? 

Precis som tankarna bakom molnet och maskininlärning är grunden i den nya teknikfilosofin att bygga modulärt. Så att du med hjälp av nya moduler kan “koppla isär” allt det som nyss satt ihop i en och samma lösning, på en och samma plattform. En vanlig glosa för att beskriva det här är just *decoupled services/CMS*. Och om vi fortsätter att använda webben som ett exempel kan vi ta isär ett traditionellt CMS (Som EPI, Drupal, Hybris eller WordPress) i sina delar:

1\. Att visa upp saker för den klient som någon använder för att titta på webbsidan med, till exempel en browser som Chrome. Det vill säga att “publicera till webben”.

2\. Att skapa och uppdatera innehåll. Det kan vara i form av artiklar eller mindre innehållsenheter som finns på dina sidor, till exempel puffar på en startsida. Text, bilder, ljud och film. 

3\. Funktioner som besökaren kan använda. Allt från att logga in till att söka på sajten eller beställa och köpa saker. Och hur du navigerar. 

4- Design av de ovanstående delarna är egentligen en egen, särskild del. Hur ser texten du skrivit ut när någon ser den på sajten? Vad är det för typsnitt, färg och storlek? Hur ser animationerna ut när du interagerar med olika funktioner? Hur ser puffarna och navigationen ut? 

Tidigare har alla dessa delar levt på ett och samma ställe: i CMS:et. Artiklarna du skrivit i redaktörsgränssnitet/läget/funktionen har sparats som text och bild i själva webbplattformen. Liksom koden för hur artikeln ska se ut eller hur animationerna i navigationen ska te sig. Om du då behöver byta webbplattform för att ni till exempel bestämt er för att utveckla affären och börja sälja produkter eller tjänster på nätet, så innebär det att alla funktioner och all design måste kodas om. Och allt innehåll som ni skapat måste “migreras” --- alltså flyttas över --- till den nya plattformen. Alla som varit med om en sådan övning vet att det är en grannlaga uppgift. 

Men om vi kopplar loss delarna från varandra och låter webbplattformen “hämta in” dem när de behövs, när en besökare kommer till sajten och pockar på en upplevelse, då kan de också återanvändas av andra webbplattformar utan att de behöver kodas om. De kan också användas av andra tjänster. Du kan till exempel visa samma innehåll i en app som på webben mycket lättare. 

Då *återanvänder* du innehåll som ni redan skapat och graden/volymen återanvändning är en av de viktigaste måttstockarna på hur snabb din digitala förändringstakt är. En hög grad av återanvändning är alltså något att sträva efter. Alltså vill du ha en approach till den teknologi du väljer som minimerar instängning och maximerar återanvändning. 

När det gäller själva upplevelsen som besökaren får har vi konstaterat att den både blivit den i särskilt viktigaste katalysatorn för att effektivisera/utveckla vad din organisation gör, och att den blivit en flaskhals. Om den separeras från själva webbplattformen, blir det inte bara extra jobb? Faktiskt är det precis tvärtom och det är det som är så intressant med den här filosofin. Om upplevelsen --- *look and feel* --- flyttas ut från webben (och från alla andra plattformar där den behövs och där det därför finns kod som styr utseendet) och sitt eget *designbibliotek* så vidgas flaskhalsen betydligt. Genom att bygga designbiblioteket som en *tjänst* kan alla plattformar prenumerera på upplevelsekoden och den behöver inte skrivas, eller ens kopieras och klistras in, flera gånger.

Dels återanvänder du designjobb som redan är gjort, vilket betyder att du frigör resurser till annat. Som då ökar förbättringstakten. Och dels slår förbättringar av kundupplevelsen *automatiskt* igenom på alla ställen som prenumererar på designbiblioteket. Dubbla tids- och effektivitetsvinster, med andra ord. Om du upptäcker i ett användartest att typsnittsgraden är för liten för en bra läsbarhet, så ändrar du storleken på texten i designbiblioteket. Du ändrar på ett ställe och då uppdateras webben, intranätet, appar, sociala medier och alla andra digitala kanaler där du styr kundupplevelsen. 

*Code once, use everywhere.*

Som du förstår betyder en sån förändring av hur din tekniska infrastruktur ser ut enormt mycket för din snabbrörlighet. Och den betyder också stora konkurrensfördelar om du dessutom ändrat arbetssätten i organisationen. Man kan säga att det här är ett sätt att ta vara på de förändrade arbetssättens ökade utvecklingshastighet. Att det är en perfekt match. 

**Glöm teknologistressen och omfamna arkitektur istället**

Nu förstår vi på vilket sätt kapitlets rubrik var en kuggfråga och varför du ska akta dig för att fokusera för mycket på teknologier på plattformsnivå. Samtidigt är det inte konstigt att organisationer har en tendens att fasta i den sortens diskussioner. Ibland känns det som om det fanns miljoner olika vägar att gå och att nya alternativ dyker upp varje vecka. Det är en den ena appen och en den andra. Plötsligt säger alla experter att det är den här plattformen du ska ha, men ett kvartal senare är det en annan. Då är det viktigt att komma ihåg två saker.

Alla dessa experter lever på att hela tiden hävda att det är något nytt på gång. För att motivera sin egen roll som expert måste de uppfattas som att de ligger före. Och det leder inte sällan till en kombination av självuppfyllande profetior och kejsarens nya kläder. Detsamma gäller tillverkarna av olika plattformar. De vill så klart sälja sina produkter och visar därför upp dem i bästa tänkbara sken. Inte sällan finns det dessutom i dagens blog- och influencer-värld en ohelig allians mellan producenter och experter. Det är svårt att skilja mellan *native advertising* och redaktionellt material och sen finns också de helt hederliga och naturliga situationerna där vissa experter jobbar på mjukvaruföretag. Det är därför de är experter. 

Det är också viktigt att inte utgå ifrån vad som finns tillgängligt, utan ifrån vad du och din organisation behöver. Och, framför allt, vad era kunder och användare behöver för att de ska bli mer nöjda med upplevelsen. Som vi ska gå in på i detalj snart handlar det om att prioritera vad som är i störst behov av förbättring, hitta ett avgränsat område, börja där och sedan gå vidare pö om pö. 

Det är precis av de här anledningarna som den nya teknologifilosofin har utvecklats. Och den kommer inte från någon särskild expert eller företag utan har växt fram evolutionärt, steg för litet steg.

Mycket berodde det på att många organisationer också kommit till vägs ände. Inte bara med enstaka plattformar som blivit för gamla för att kunna leverera det som behövs och måste bytas ut. Utan också för att de fått ett härke av plattformar, ett lapptäcke som där set ena problemet ledde till det andra om man bytte ut någon av lapparna. Så vad skulle istället hände om vi lyfte oss en nivå ovanför plattformarna och skapade ett nytt lager som kunde knyta samman olika teknologier? 

Vilka plattformar du har och hur du integrerar dem kallas på fackspråk (märkligt nog) arkitektur. Kanske löst baserat på att man behöver veta hur huset ska se ut innan man börjar bygga det. Och det nya lager vi pratar om  var inte som en ny våning utan snarare ett nytt elsystem. 

Tanken var egentligen enkel. Internet hade redan gjort det möjligt att bygga enkla, specialiserade tjänster som kunde distribuera både innehåll och funktioner mellan olika sorters servar. Email är ett exempel, där vi alla kan maila med varandra utan att det spelar någon roll vilket mailprogram och mailserver jag har och vilka du har. Webben hade gjort konceptet ännu mer populärt, med till exempel RSS-flöden för att prenumerera på innehåll. 

Tänk om man skulle kunna komma ifrån mycket av plattformsoberoendet och instängdheten genom att bygga system där många, små och specialiserade tjänster knöt ihop arkitekturen?  




När valen känns övermäktiga, samtidigt som de skyndar, är det dags att ta ett djupt andetag och upprepa mantrat du nu fått. Minska instängdhet och öka återanvändning. Minska instängdhet och öka återanvändning. OK, men hur hjälper det rent praktiskt? 

Två viktiga aspekter som du behöver ta till dig för att utveckling av kundupplevelsen verkligen ska kunna ta fart: Både i våra egna liv och i våra organisationer pratar vi ofta lite för specifikt när vi pratar om teknologi. Det är inte så konstigt om många av oss tycker det är jobbigt med tekniksnack och slår dövörat till och det är inte heller meningen att vi alla måste vara/bli dataingenjörer för att det ska fart i verksamheten. (Snarare tvärtom.) 

Uppdaterar du nåt i designen så ändrar sig utseendet i det du gör. 



För den som backar ut och skaffar sig lite perspektiv blir det dock klart att vi också lider av en kombination av övertro, stress och förträngning -- strutsbeteende -- när det gäller ämnet nya teknologier.

Om vi börjar med att konstatera att vi *både* befinner oss i en era där det kommer nya teknologier med en högre frekvens än någonsin, *och* i en era då fler av dessa fallerar. Det är i sig själv något av en naturlag. Bara lätt att glömma bort när man befinner sig mitt i strömmen. (Ju fler nya appar som kommer, desto fler av dem som inte blir något.) 

Då är det bra att komma ihåg citat från några kapitel tidigare: “En majoritet av alla förstudier som genomförs landar nu på en rekommendation som redan är föråldrad när förstudien är klar.”

Därför är det viktigt att inte känna stress, inte känna sig tvungen att ständigt söka av utbudet och hitta kandidater att lära sig och byta till. Därför är det *lika* viktigt att inte sticka huvudet i sanden och tro att man undviker teknologistress genom att förtränga att förändringarna sker runt oss. Lustigt nog verkar det som att de som ständigt ska byta till det *senaste* och de som har ett mer strutsliknande beteende i slutänden hamnar i samma situation. Bägge är teknikstressade. Och bägge grupperna missar de viktiga skeendena. 

Å andra sida är den teknologistress många känner inte så konstig. Alla i branschen försöker marknadsföra just sina lösningar som det nya svarta. Samtidigt som det finns en branschpress och en uppsjö med förståsigpåare i sociala medier och självutnämnda experter som bygger hela sin utkomst på att framstå som om de visste vad som gäller. Vilket helt naturligt leder till att de inte kan prata om gårdagens, slash vardagens lösningar, utan tror sig hela tiden behöva prata om något så nytt att vi inte hört talas om det. 

En genuin ”rapportering” av nyheter blandas med andra ord upp med en slags pose. Alla branscher har sina charlataner, inget märkvärdigt med det. Men av någon anledning har de senaste tio årens digitala utveckling saknat mer av det som vanligtvis agerar som motvikt till charlatanerna: *Accountability*. (Tillförlitlighet?)

(De flesta fält inom vetenskap, medicin och kultur har mer av den varan än den digitala världen. Peer review och så vidare.) Detta förstärks av att de gängse/traditionella strukturerna är satta ur spel. Internet självt har ju sett till att informationshierarkierna demokratiserats. Bara för att någon är tidningskrönikör betyder inte det automatiskt att åsikterna som den publicerar är mer trovärdiga än vad du kan läsa i en hemmagjord blogg på andra sidan jordklotet. Och tvärtom. 

Många liknar tiden vi lever i vid två väldigt distinkta förändringsperioder ur vår (inte alltför avlägsna) historia. Den industriella revolutionen eller guldrushen i Kalifornien.  Rent strukturellt är den första liknelsen bättre. Inte sedan industrialiseringen har så mycket av vår infrastruktur, både i samhället, i företag och hos individerna stått under så stor omstrukturering. Men guldrushen innehåller ett antal intressanta paralleller. Hur det i början fanns lika mycket lurendrejare som seriösa affärsmän som handlade med guldet, sålde inmutningar och utrustning. Detta sorterade med tiden ut sig själv och vi kommer att se samma utveckling i den digitala världen. Charlataner och gurus som i längden levererar mer *buzz* än *words* kommer att försvinna. Google Analytics och artificiell intelligens kommer att hjälpa oss med den filtreringen, som vi ska se lite längre fram.

Det är också svaret på hur du kan undvika teknologistress utan att stoppa huvudet i sanden. Istället för att lyssna på buzzwords och gurus kan du applicera ditt eget filter på flödet av teknologinyheter. Vad är det som är viktigt för dig? Vad är viktigt för din organisation? 

Låt oss ta *samarbete* som exempel. Och låt oss säga att du tycker att ökat samarbete är nyckeln till framgång både för dig själv som individ och yrkesmänniska, samt för din organisation som helhet. Då använder du detta filter och inga nya teknologier kommer igenom om de inte handlar om samarbete. Ibland uppstår fall där ett digitalt verktyg i sig själv inte förbättrar samarbete, men gör det i kombination med andra tjänster. Då är ditt filter -- du! -- tillräckligt smart för att se det. Det behöver inte vara svart eller vitt. 

\[Illustration: Filter\] 

Självklart kan ditt filter också utvecklas över tid. Du fokuserar på samarbete just nu och sedan är det något annat som blir viktigt. Det enda viktiga är att det filter du använder reflekterar ett värde som du har identifierat. I exemplet skulle en ökad grad av nya sätt att samarbeta både öka er produktivitet och kvalitén på det ni levererar. Då startar filtrerandet en process fokuserad på värdefulla förbättringar.

Med detta sagt så finns det *tendenser* i teknologiutvecklingen som är mycket intressanta att ta till sig. Eller rent av livsviktiga om du och din organisation ska klara er i konkurrensen. Då pratar vi med andra ord inte om enskilda teknologier, plattformar eller tjänster. Utan om mer övergripande strukturer och *mönster* som man kan skönja. Mönster som säger något om hela kluster av teknologier och vart de är på väg. Låtom oss prata mer om det i nästa kapitel. 
