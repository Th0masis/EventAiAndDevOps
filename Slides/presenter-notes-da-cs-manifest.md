# Presenter Notes Manifest — Danish → Czech

Source: `Slides/slides.md`. Branch: `translation/presenter-notes-da-cs`.

Each entry lists: stable ID, nearest slide number (from `<div class="slide-id">`), source line range in `slides.md`, exact Danish source text (unchanged), and status.

Special cases:
- **NOTE-012, NOTE-017, NOTE-018, NOTE-019, NOTE-028** have no preceding `<div class="slide-id">` (the note sits on a slide that does not render a slide number, or before the very next numbered slide). Slide column shows the nearest following/preceding slide for orientation, marked "(no slide-id)".
- **NOTE-036** follows a large HTML-comment block (lines 2420–2487) that disables an entire "Continuous Delivery" slide (structural/disabled content, NOT a presenter note). That disabled block is left completely untouched and is excluded from this manifest.
- **NOTE-043** (after slide 39) is already written in **English**, not Danish. No translation will be performed for it; it is listed only for completeness and will be marked `skip (not Danish)`.

---

### NOTE-001 — Slide 01 (lines 140–152)
Status: translated (PASS)

```
Introduktion af os selv.
Vi har arbejdet med AI de seneste 2 år, hvor vi er nu.

Vi har valgt at lave et event med både AI og DevOps fordi vi <b>ser mange synergier.</b> 
AI tilbyder et helt nyt niveau af produktivitet mens DevOps sikrer kvaliteten. De to ting går hånd i hånd i vores øjne.

Vi fornemmer også at både AI og DevOps er emner der deler vandende. <b>AI er overalt</b>. Det er facinerende hvad det kan bruges til. Der er meget hype og det er helt naturligt at have <b>en sund skepsis</b>. For det er jo trods alt ikke magi!

DevOps introducerer <b>en masse regler og struktur</b>. Nogen ser det som religion, mens andre ser dem som rigide processer der <b>dræber enhver form  for kreativitet og produktivit.</b>

Med konceptet Agentic Engineering vil vi forene dem og forhåbentligt <b>vise det bedste af begge verdener!</b> 
```

---

### NOTE-002 — Slide 02 (lines 195–210)
Status: translated (PASS)

```
Pressentation af Agendaen. 

Først en overfladisk gennemgang af AI og DevOps. 
Det er ikke alle her der kender koncepterne.

Derefter en mere dybtegående session med Agentic Engineering:
Hvordan kan vi helt nøjagtigt arbejde med AI i den mere industrielle verden hvor systemerne historisk set har været mere lukkede og propreitære?
Det mener vi at vi er på vej til at løse på B&R's platform.


Så har Mads en session om DevOps:
Han vil forklare om hvad der er muligt med B&R platformen.
Give nogle fede demoer af automatisk test og deployment.
```

---

### NOTE-003 — Slide 03 (lines 244–274)
Status: translated (PASS)

```

<b>Jeg har selv været til mange AI-foredrag og konferencer.</b> 
Man kommer tit hjem med en følelse af at være totalt bagud og at alle andre har knækket koden til success med AI.<br><br> 

[CLICK]
<b>Sådan skal det selvfølgeligt ikke være i dag!</b>

VI VIL IKKE SIGE:

<b>At vi har en standardløsning der løser alle jeres problemer</b> AI og DevOps er komplekst og skal skrædersyes til enhver usecase og platform! 

<b>Vi vil heller ikke sælge jer et produkt.</b> Alt hvad vi kommer til at vise jer i dag, kommer uden nogen regning. Det er en workshop, ikke nogen salgspitch!

<b>Vi vil ikke snakke om AGI, scify og alt hvad man måske kan lige om lidt</b>  

[CLICK]
VI VIL ISTEDET SNAKKE OM:

AI i automationsbranchen er <b>relativt nyt</b>, og vi vil gerne sikre at i har de værktøjer I har brug for! 

Vi vil gerne informere vores kunder og samarbejdspartnere omkring <b>vores strategi og retning.</b><br>

Hvis der ikke der findes en standardløsning, hvad er der så af muligheder på B&R platformen og <b>hvordan kommer vi igang?</b>.

[CLICK]

Vi vil gerne have nogle gode dialoger / diskutioner med jer. Stil endelig spørgsmål eller giv feedback undervejs

Transition: Lad os se på, hvordan DevOps og Agentic Engineering supplerer hinanden.
```

---

### NOTE-004 — Slide 04 (lines 335–354)
Status: translated (PASS)

```
[CLICK]
<b>DevOps er en fremgangsmåde med forskellige stadier</b> ens software skal igennem. Hvert stadie sætter nogle krav der sikrer at næste stadie bliver en success. De skal enten <b> manuelt udføres eller manuelt bringes videre</b>. Hvis kravene ikke opfyldes grundigt nok, har workflowet ingen reel værdi. Derfor kan det for nogle godt virke rigidt og tungt - selvom det er en nødvendighed for at levere høj kvalitet.

[CLICK]

<b>Ved at bringe AI-Agenter ind i din DevOps process er der en masse fordele. AgentOps</b>

0. DevOps bliver et framework til AI der sikrer kvalitet og forudsiglighed. (AI er ligesom mennesker ikke deterministiske). Det er vigtigt, for vi har aldrig kunnet lave en fejl hurtigere end vi kan nu.
1. Agenterne overholder ALTID deres instruktioner i modsætning til mennesker. De er hverken religiøse eller brokker sig over at det er rigidt!
2. Store dele af DevOps processerne kan automaticeres og spare tid.
3. Viden bliver gemt i workflows og ikke i individer
4. Vi kan stadig have fuld kontrol over processen hvis vi integrerer det smart. Det er et ultimativt krav i OT!

[CLICK]
<b>DevOps bliver altså selve frameworket for AI <br> 
og AI gør frameworket super effektivt!</b>

```

---

### NOTE-005 — Slide 05 (lines 392–420)
Status: translated (PASS)

```
Lad os prøve at kigge på hvordan investeringen af en persons tid kunne se ud under en udviklingsfase:

[CLICK]
<b>Øverst: Uden DevOps:</b> Man springer hurtigt over plan og design. Vi går i gang fra dag ét. Det er pisse spændende det her! 

Vi bygger længe da specifikationerne ændrer sig konstant og softwaren er blevet kompleks. Måske skulle vi have grebet det anderledes an? Men nu er det for sent! 

Tiden er brugt og deadline er kommet, vi deployer hvad vi har. 

Regningen kommer efter release som bugfix. Man ved aldrig hvornår man rammer et acceptabelt stadie og prisen er derfor uforudsiglig!

[CLICK]
<b>I midten: Med DevOps:</b> Det er udfra ovenstående at DevOps er en nødvendighed. Men it OT er det ofte for dyrt at implementere til små / mellemstore oneoff projekter. Og alle projekter starter jo som oneoff projekter indtil man bygger maskine nummer 2 :-).   

Ordentlig planlægning og design koster tid, men er hele fundamentet for udvikling og test af god kvalitet. Bugfix minimeres, og der er allerede vundet tid, samt den endelige kost er mere forudsigelig. Det er tit bare svært at argumentere for den ekstra investering up-front

[CLICK]
<b>Nederst: AgentOps:</b> Investeringen af tid flytter endnu frem i processen. Agenterne har ingen hukommelse eller indforstået viden om "best practise". Alt skal defineres meget eksplicit for at undgå misforståelser. Workflows og instruktioner skal være tip top og finpudsede. 

Tilgengæld bliver udviklingen til en brøkdel. Måske endda 0 fordi processen ikke blokerer for at man kan lave noget andet imens. 
Review og release-beslutning ligger stadig hos os. 

<b>Den frigjorte tid er ikke nødvendigvis en gratis gevinst</b> - den kan investeres i bedre kontekst, bedre tests og bedre styring og beslutninger.

For første gang i lang tid, bliver det muligt at øge kvaliteten markant uden at investere i markant flere ingeniører.

Transition: Hvad er forskellen på ChatGPT og en OT- Super Agent?
```

---

### NOTE-006 — Slide 06 (lines 469–507)
Status: translated (PASS)

```
Hvad er en Agent?

Består overordnet af to uafhængige komponenter. 
En LLM (sprogmodel) og et Harness.

Mange ser LLM'en som den magiske komponent der gør hele forskellen. Det er den der løber med al opmærksomheden, men det miljø den arbejder i har en mindst ligeså stor betydning for resultatet.

LLM'erne ændrer sig konstant. I næste uge er det måske en helt anden model, der enten er bedst eller billigst.

LLM'en og Harnesset er derfor uafhangige komponenter hvor vi (for det meste) ingen indflydelse har på selve modellen, men derimod stor indflydelse på det harness hvor den bliver anvendt.

Modellen alene har ingen adgang til Automation Studio, et project, en PLC eller en simulator. Den kan kun arbejde med den context den får, og vurdere hvordan den vil anvende de tools, som dens harness stiller til rådighed. 

Agenten opstår, når modellen kan vælge et tool, kalde det, se resultatet og beslutte næste trin. Harnesset er miljøet rundt om agenten: 

[CLICK]
Instructions: Agent.md. Skills. Hvad skal den kunne. Hvad skal den gøre?<br>
[CLICK]
Context: Hvad er det vi arbejder i?<br>
[CLICK]
Tools: Hvad skal agenten have adgang til i verden udenfor? eller lokalt på din PC?<br>
[CLICK]
Memory: Da en LLM er fuldstændig stateless skal der være noget til at holde på historikken. Måske også dele det på tværs af sessioner.<br>
[CLICK]
Permissions: Hvad må agenten gøre på egen hånd? Hvilke tools må den bruge?<br>
[CLICK]
Logs: Logger hvad agenten har gjort. Hvilke tools den har kaldt. Har den spawnet subagenter? Hvad svar fik den fra dem?<br>
[CLICK]
Feedback: Agenten kan spørge dig til råds (Agenten prompter dig). Hvad mener du? Skal jeg vælge X eller Y?<br>
[CLICK]
Approvals: Du skal give agenten tilladelser eller adgang til at bruge din PC. Må jeg slette dit C-drev?<br>

[CLICK]
En agent er en LLM i et Harness!

[CLICK]
Transition: Hvorfor er dette sket hurtigere i IT end i OT? Hvorfor findes der ikke agenter der kan lave AS ligeså godt som de kan lave websites? 
```

---

### NOTE-007 — Slide 07 (lines 551–570)
Status: translated (PASS)

```
I mange år har "nogen" snakket om at IT og OT ville flyde sammen. Det har også tildels været rigtigt. Mange af de værktøjer der bruges i IT er nu også tilgængelige for OT. (Vi arbejder for AS i VS-Code og Docker. Vi ved godt vi ikke er der helt endnu) 

<b>Men siden AI er begyndt at blive en del af stacken, er IT virkeligt begyndt at "stikke af" igen.</b>

Det er ikke fordi vi ikke besider de samme kompetencer i OT, men fordi IT og hele <b>opensource</b> tankegangen bare går rigtig stærkt.

<b>LLM'erne er allerede trænet på uendeligt mange IT projekter</b>, mens OT næsten altid er closed source. Både hvad angåer selve automationsplatformen, men også det domæne I arbejder med. Hvordan virker en støbemaskine eller en trykmaskine?

IT har allerede værktøjer og kontekst som en naturlig del af udviklingsmiljøet: Versionsstyring, APIs, CLIs og diagnostics. Modeller og agenter kan derfor hurtigt kobles på et eksisterende feedback-loop.

<b>Selvom vi besider de samme kompetencer</b> kan vi ikke harmle op med de inovationer der sker i IT lige nu

I OT skal vi i højere grad selv udvikle de tilsvarende værktøjer og den kontekst, som AI kan arbejde med. OT har desuden fysiske konsekvenser, lange livscyklusser, hardware- og versionsafhængigheder, motion, safety og mindre standardiseret feedback. 

[CLICK]
<b>Derfor er opgaven ikke at få AI ind i OT, men at gøre OT tilgængelig for AI.</b>

Transition: Det største gap er forskellen mellem at generere kode og at verificere koden.
```

---

### NOTE-008 — Slide 08 (lines 655–674)
Status: translated (PASS)

```
<b>Hvad skal der konkret til?</b><br>
Vi kan ikke konkure med IT. Vi må indordne os. Vi kan ikke træne vores egne modeller eller lave vores eget harness. 


[CLICK]1. <b>Den manglende domæne viden som LLM'erne ikke er trænet på. B&R + OEM</b> 

[CLICK]2. <b>Projekt context. Modellen skal kunne læse filerne i projektet og forstå deres sammenhænge. B&R</b>

[CLICK]3. <b>Sourcekode, HMI, configurationer, Safety osv. skal kunne versionstyres. B&R</b>

[CLICK]4. <b>Vi skal levere de værktøjer der er nødvendige for at kunne lukke feedback-loopet på research, debugging, test og deployment. B&R</b>

[CLICK]5. <b>Vi skal definere nogle retningslinjer (guardrails) for hvordan agenten må og kan arbejde i et AS projekt. F.eks: altid opdater pkg-filen, tilføje filer til textsystemet etc.  B&R + OEM   </b>




Transition: Når fundamentet er på plads, kan vi lukke det industrielle engineering-loop.
```

---

### NOTE-009 — Slide 09 (lines 728–755)
Status: translated (PASS)

```
<b>Vores strategi har ændret sig</b> og det har måske ikke været så tydeligt hvor vi egentligt er på vej hen nu. Vi vil ikke længere pretraine eller fine-tune vores egen model som et lukket AS-Copilot-økosystem. <b>Det var det rigtige valg engang</b>, fordi modellerne ikke var istand til at kode PLC. Det har ændret sig!

[CLICK]
Heldigvis:
<b>For det er dyrt og langsomt at bygge </b>

<b>Modellen risikerer at være forældet før release, </b>

og et <b>overcomplete træningssæt</b> kan give modellen mere viden end den enkelte kunde har brug for og ende med hallucinationer. Hvad hvis jeg kun bruger X20? 

Oven i det kommer <b>løbende fine-tuning, evaluering og vedligeholdelse.</b> 

<b>Vi låser os til én model,</b> selv om forskellige opgaver kræver forskellige modeller, og en 

<b>B&R-hostet model</b> begrænser kundens valg af AI-leverendør og måske enda konflikter med kundens IP retningslinjer.

[CLICK]
Hvad gør vi så?

[CLICK]
Vores platform er allerede åben og tekstbaseret. <b>Derfor kan vi skabe mere varig værdi med context engineering og harness engineering med de modeller og harnesses der allerede findes og kommer i fremtiden:</b> 

[CLICK]
B&R skal eje broen / integrationen og domænegrænsen, ikke alle lag i AI-stacken. Så kan vi tage den bedste nye teknologi i brug, uden at kunden skal købe ind i et lukket og forældet B&R-økosystem.

Transition: Det er den retning, vi nu bygger videre på, og som har åbnet muligheden for, at vi her i danmark f.eks kan bidrage med de integrationer der skal til.
```

---

### NOTE-010 — Slide 10 (lines 792–817)
Status: translated (PASS)

```
Lad os slutte introen af med at opsummere:
Hvorfor er det interressant? Hvorfor skal I investere jeres tid i AE?

[CLICK]
1. Man skal forstå at AI er det næste naturlige abstraktionslag. Dem der formår at bruge AI effektivt vil til enhver tid udkonkurerer dem der ikke gør! Vi bliver ikke arbejdsløse, vi flytter bare fokus op ad abstraktionsstigen. Ikke for at blive dovne, men for at kunne nå mere i en verden der forventer mere.

[CLICK]
2. Uanset om man elsker AI eller er fuld af skepsis, så må man indse at det er blevet en del af stacken og det er kommet for at blive. Jeg synes personligt at det er blevet 100 gange sjovere at være ingeniør. Vi kan lave de vildeste ting og vi bliver forundrede hver dag. 

[CLICK]
3. Viden bliver gemt i systemet i stedet for i individer. Systemet skal ikke på ferie, på barsel, er syg eller (gud forbyde det) siger op.

[CLICK]
4. Vi får muligheden for at geninvestere vores tid til at opnå bedre kvalitet, og ved kontinuerlig optimering der leder til mere autonomi og mere troværdighed.

[CLICK]
5. Vores afdeling bliver langt mere agil og robust. Det skallerer efter behov. Ikke kun efter mennesker.

Jeg startede med at sige, at AI foredrag næsten altid lover guld og grønne skove og at det her skulle være anderledes??. Jeg beklager hvis det ikke er lykkedes indtil videre.

[CLICK]
Vi vil ikke garantere success. Vi vil fjerne de barrierer der kan stå i vejen for jeres success med AI og DevOps. 

Transition: Slut med intro.
```

---

### NOTE-011 — Slide 11 (lines 846–860)
Status: translated (PASS)

```
Inden vi springer til næste punkt på dagsordenen:

- Spørgsmål til mig?

1. Hvor mange af jer bruger AI-Agenter som et dagligt og uundværligt værktøj til sw-udvikling?
2. Hvor mange af jer bruger DevOps principper i jeres sw-udvikling?
 

Det vigtigste er ikke AI-modellen eller agenten. Det er workflowet.

Modellen kan udskiftes. Harnesset kan ændres. Men workflowet definerer, hvordan ide bliver til tickets, hvordan løsningerne bliver implementeret, reviewed og testet og hvem der i sidste ende må godkende resultatet.

Det er et levende engineering-system. Det skal versionsstyres, måles, vedligeholdes og forbedres, præcis som andre dele af jeres platform.
```

---

### NOTE-012 — (no slide-id, "vibe-coder" visual slide, between slide 11 and slide 12; lines 871–887)
Status: translated (PASS)

```
Hvor gammelt er Vibe-coding begrebet? (februar 25)

Et fenomen der opstod for ca. 1,5 år siden. Beskriv hvad du vil have og itterer indtil du er tilfreds.

Vibe coding kan være effektivt til læring og prototyper. Vi har selv vibecoded en hel del. Ikke på jeres maskiner selvfølgelig ;) Men til hurtige interne værktøjer, til POCs og til fejlfinding er der intet i vejen med bare at give den gas uden en plan.

Men til rigtige maskiner der skal leve op til en masse krav, er det sjældent en god process.

Når vi sætter det op imod "Agentic Engineering", så er det for at synliggøre, at AI er ikke magi. Vi bliver nødt til at holde det i hånden hele tiden og eje processen. AI Agenter er ikke deterministiske (ligesom mennesker heller ikke er). De har brug for vejledning (i form af guardrailes)  og quality gates der tillader at processen må fortsætte.  

Hvis man ikke styrer processen så mister man overblikket.

På en maskine er "det ser rigtigt ud" ikke et successkriterie.
I IT gør det måske ikke så meget om en hjemmeside er nede i 5 min., men i OT er det ikke ligemeget om der kommer metalspåner i appelsinjuicen.

```

---

### NOTE-013 — Slide 12 (lines 927–938)
Status: translated (PASS)

```
Lad os prøve at kigge på et konkret eksempel, som resten af workshoppen skal besvare.

<b>Feature request:</b> Når conveyor-aksen fejler, skal maskinen stoppe kontrolleret. Clear skal rydde alle flasker, der endnu ikke er cappet - uanset om de er tomme eller fyldte - og de tæller som reject. Counteren beholder sin værdi, og batchen fortsætter fra samme tal ved start, indtil de 100 flasker er færdige.

Vis fejlen og det ønskede resultat, men forklar ikke løsningen endnu. Stil i stedet workshop-spørgsmålet: <b>Hvordan kan vi uddelegere implementeringen til en agent, uden at agenten samtidig bliver specifikation, tester og godkender?</b>

Resten af workshoppen bygger svaret: MCP leverer viden, AS CLI udfører og observerer, skills og guardrails styrer arbejdet, tests leverer evidens, og mennesker samt gates afgør, om ændringen må fortsætte.

[CLICK]
Transition: For at det skal kunne lade sig gøre, skal agenten have en forbindelse til Automation Studio, Automation runtime, og domæneviden, der kan lukke feedback-loopet.
```

---

### NOTE-014 — Slide 13 (lines 1000–1021)
Status: translated (PASS)

```
Så hvad kan vi tilbyde for at svare på spørgsmålet?

Hvis man går ind på linkedin eller åbner vores hjemmeside, så vil man se denne marketingskampagne for: Automation Studio Agentic Bridge. Der er flere der har kontaktet mig og spurgt ind til hvad det er. Det har i forhåbentlig en ide om nu, men selvom det ikke er helt endeligt defineret eller released (AS6.9), så lad os lige gennemgå det.

[CLICK]
Agentic Bridge er integrationen af domæneviden og tools fra enhver Agent (altså et hvilket som helst harness med en hvilken som helst model)

[CLICK]
<b>Den består af</b> nogle instruktioner, skills og hooks for at guide agenten med at arbejde i et AS-Projekt


<b>Den består af</b> en MCP server der kan levere domæneviden til agenten omkring: B&R produkter, Automation Studio, Structured Text, AS-Help, Anonymiserede support tickets, Sales notices, manualer, Release notes osv. Denne MCP server er tilgængelig allerede nu og er den officielle B&R MCP server. 

<b>Den består af et Command Line Interface til Automation Studio</b>: CLI'et har vi bygget her I DK. Først som et uofficielt produkt, men nu som en integreret del af Automation Studio. CLI'et stiller en række funktionaliteter til rådighed for agenten, så den kan bygge projektet, simulerer, læse/skrive variabler, læse logbogen osv. 

[CLICK]
Man er selvfølgelig ikke begrænset til de skills, MCPs og tools der er en del af Agentic Bridge. Man kan selvfølgelig stadig bruge de 1000 vis af skills, MCP-servere og CLI'er der findes, og selvfølgelig lave sine egne, der interfacer den domæneviden, eller de systemer man vil tilgå.

transition: Hvor mange ved hvad en MCP server er?

```

---

### NOTE-015 — Slide 14 (lines 1116–1131)
Status: translated (PASS)

```
MCP står for Model Context Protocol. Tænk på det som et semantisk tool-API: en server beskriver sine tools og resources, så en model kan opdage dem og bruge på en standardiseret måde.

[CLICK]
<b>Et eksempel kunne være den officielle GitHub MCP server.</b>
Den har omkring 47 tools til alt lige fra at oprette issues og PR, læse repositories, merge branches osv. 


<b>Som andet eksempel har vi vores egen AS-Help MCP</b>. Det er en lokal server, der via stdio, stiller funktioner til rådighed for at søge i B&R Automation Studio help: search_help, get_categories, browse_section og get_page_by_id. 

[CLICK]
Manifestet er ikke selve dataene eller udførelsen. Det giver modellen et katalog over tilgængelige MCP-servere, deres tools med beskrivelser og input-formater i den kontekst, den arbejder med. På baggrund af opgaven kan modellen vælge at kalde search_help for at slå ACOPOS error 7070 op i AS-dokumentationen, create_issue for at rapportere en fejl, eller svare uden et tool.

[CLICK]
En MCP server gør altså sine funktioner tilgængelige over et standard interface som en agent kan forstå
```

---

### NOTE-016 — Slide 15 (lines 1188–1216)
Status: translated (PASS)

```
Vi vil gerne reklamere lidt for vores egen AS-Help MCP der ligger tilgængelig på GitHub. Vi synes selv den er MEGA god!
Første gang AS-Help MCP starter, læser den den lokale Automation Studio help folder og bygger et søgeindeks. Den gemmer ikke kun søgetekst, men også page_id, titel, filsti og breadcrumb, så et hit kan følges tilbage til den rigtige side.

[CLICK]
[CLICK]
[CLICK]
[CLICK]
[CLICK]

FTS, full-text search, er klar. <b>Semantisk søgning kan være et senere, valgfrit lag.</b> 

Vi synes at FTS virker så godt, at vi ikke rigtigt har brugt embedding modeller og vector-databasen, men man kan nemt smide sin egen embedding model på, og så få semantisk søgning sammen med FTS. Det kan spare på tokens og give mere akkurate søgninger, da hele konteksten indgår i søgningen, og ikke kun keywords.

Det vigtige i agent-flowet er, at search_help ikke foregiver at være hele svaret: den returnerer et rangeret hit med page_id, breadcrumb og en kort preview.

[CLICK]


Agenten bruger derefter page_id i get_page_by_id for at hente den fulde tekst, metadata og eventuelt online-help URL. Det er en enkel, sporbar to-trins kontrakt: find den bedste adresse, hent derefter evidensen.

[CLICK]

Da <b>projektet er opensource</b>, kan det nemt kopieres til andre hjælpesystemer fra f.eks en tredjepart. Det skal i være velkomne til!

Til mange ting synes vi at det er en fordel, at MCP-serveren KUN har adgang til din lokale hjælp, og derfor ikke til teknologier du ikke har installeret eller nyere versioner du ikke bruger. Den kan selvfølgelig ikke bruge hele B&Rs katalog som data, men hvis den kun skal forholde sig til din maskine, så er det jo også tit det bedste. 

transition: Hvis man har brug for overkomplete viden kan man bruge den officielle B&R MCP-server
```

---

### NOTE-017 — (no slide-id, "Official B&R MCP Server" slide, between slide 15 and slide 16; lines 1235–1250)
Status: translated (PASS)

```
Official B&R MCP

Den som er med i Agentic Bridge. Den indeholder mere B&R viden end bare hjælpen, men den har også nogle begrænsninger. 

1. Den afspejler ikke kun de produkter og libraries du bruger / har installeret, men alt der er tilgængeligt. 

2. Den er hosted på en B&R cloud service. Dine prompts bliver sendt ud af din computer, men bliver ikke logget eller analyseret.

3. Den giver ikke refferencer på alle svar, da nogle data ikke er tilgængelige som pdf'er eller hjælp URL'er. 

4. Den er i Beta. Vi anbefaler AS-Help, BR-Community MCP indtil den bliver bedre.


transition: Hvad er der ellers af brugbare MCP-Servere?
```

---

### NOTE-018 — (no slide-id, "Practical knowledge connectors" slide, between slide 15 and slide 16; lines 1314–1318)
Status: translated (PASS)

```
Eksempler på relevante MCP servere:

transition: Alle de her MCP servere kan man selvfølgelig bruge i sine Agentic Engineering workflows, men man kan også bruge dem til andre formål!
```

---

### NOTE-019 — (no slide-id, "B&R Support Agent" sequence slide, between slide 15 and slide 16; lines 1330–1370)
Status: translated (PASS)

```
<b>Et eksempel på en application som vi har lavet - B&R Support Agent</b>

Her kan man forbinde et workspace så agenten kan kigge i et project.

Man kan uploade filer. Det kunne f.eks være en system dump eller en wireshark trace.

<b>Man kan give den instruktioner:</b> F.eks Ved spørgsmål der indeholder kundenavn, tjek altid for tidligere sager på Jira, eller kig altid på denne sharepoint side når det handler om Codian robotter.

Den kan nu bruge dens forbundne MCP servere til at søge den fornødne domæneviden.

- AS4 / AS6 help
- Atlassian (Jira tickets og confluence dokumentation)
- br-community mcp
- workIQ (sharepoint, teams kanaler, support mail box)
- Revision history (released firmware med release notes)

[CLICK]

Vi kan stille den et spørgsmål og se hvordan den bruger sine tools.

Og hvordan den i det her tilfælde giver link direkte til online-hjælpen.

[CLICK]

<b>USECASES:</b>

Der er mange usecases hvor vi har sparet enormt meget tid med sådan et værktøj.

1. Gennerel søgning i vores interne systemer
2. Validere at et problem ikke tidligere har været løst inden det sendes videre til HQ.
3. Finde komplekse sammenhænge mellem logs, kode og tidligere historik.
<b>Vi har fundet bugs vi ALDRIG havde fundet uden!</b>

<b>Det er ikke længere nødvendigt at det er firmaets bedste mand der hjælper til med support!</b>


transition: Det er hvad man kan med den rette domæneviden. Men hvad hvis vi rent faktisk skal løse noget på en maskine?

<b>Hvis pause så NU!</b>
```

---

### NOTE-020 — Slide 16 (lines 1399–1446)
Status: translated (PASS)

```
<b>Hvis pause så NU!</b>

`AS CLI` er et command-line interface der kan bruges af et menneske, et script, en automatisk test, en CI-pipeline og en agent.

AS CLI er selve rygraden i Agentic Bridge og er noget <b>vi har udviklet her i DK</b>. Det er et mere eller mindre komplet interface til Automation Studio 6 og kan mange af de samme ting som man ellers manuelt skal udføre i automation studio. <b>Ud over selve runtime funktionerne som vi kigger på om lidt, så kan det også tilføje libraries, hardware, tasks, hmi, konfigurationer osv.</b> Selvom det selvfølgelig bare er text, så er det mere pålideligt at bruge den existerende scripting engine bag AS, så alt bliver indsat rigtigt og konfigureret med valide parametre.

Det åbner Automation Studio i headless mode (uden GUI) og forbinder direkte til backenden i AS. Alle functioner og status bliver tilgængeligt via et json-rpc interface, der gør det nemt at bygge andre systemer ovenpå. Det bliver formentlig også det som vores officielle VS-Code extension kommer til at bruge.

[CLICK]

Da vi designede CLI'et var det vigtigt for os, at AI blev tænkt ind i designet. Dvs. at en Agent skal selv kunne finde ud af at bruge det, uden at man skal instruere den i hvordan.

Agenten kan lave --help overalt for at søge information om hvilke kommandoer og hvilke parametre den kan bruge og hvad de vil returnere.
[CLICK]

Den kan give status på det projekt den er forbundet til

[CLICK]

Det kan simulere, men også betjene simulatoren. Den kan f.eks skrue op eller ned for tiden. På den måde kan den prøve ting af i slowmotion eller speede tiden op hvis den skal køre en test på et stort batch.

[CLICK]

Det kan builde projektet til enten fysisk hardware eller en simulator  

[CLICK]

Forbinde til PLC'en eller simulatoren

[CLICK]

Læse variable

[CLICK]

Skrive variable

[CLICK]

Læse logbøger 

[CLICK]

Lave en PIP pakke. ProjectInstallationPackage PIP (Deployment artifact)

transsition: Nu har vi alt toolingen på plads, så mangler vi bare instruktioner og skills
```

---

### NOTE-021 — Slide 17 (lines 1462–1473)
Status: translated (PASS)

```
Hvis man kender skills.sh lavet af vercel, så ved man at der findes rigtig mange skills og at de er tilgængelige for langt de fleste agenter. 

Mange af dem er <b>ligeså relevante</b> for et automationsprojekt som for altmuligt andet. Og bruger man <b>DevOps principper</b>, så behøver man ikke at opfinde den dybe tallerken igen. Der er rigtig gode skills til alle de forskellige faser.

Det er supernemt at installere med npx kommandoen direkte fra dit harness.

De mest populære skils er:
vis <b>grill-with-docs</b>

transition: Men man slipper ikke for at lave sine egne skills. Man har sine egne krav, sine egne principper og sine egne standarder.
```

---

### NOTE-022 — Slide 18 (lines 1525–1558)
Status: translated (PASS)

```
Skills falder i to uafhængige dimensioner.

<b>Første dimension</b> er, hvordan de aktiveres. 

<b>Et model-invoked skill</b> ligger fremme og bliver loadet af agenten selv, når agenten mener at indholdet er relevant for den arbejde. 

<b>Et user-invoked skill</b> kalder du bevidst, som en gemt prompt for at udføre en bestemt handling eller rutine.


<b>Anden dimension</b> er, om de husker noget fra gang til gang. Et stateless skill kører én gang og glemmer. Et stateful skill bygger op og genbruger tidligere outputs i fremtidige sessioner.


De to dimensioner kombineres frit, så du får fire typer af skills. Vælg bevidst, når du designer et nyt skill. Her er et par eksempler:

[CLICK]
Event script skill til MappView. Det er <b>model-invoked</b>, fordi agenten selv skal kunne fremkalde information om eventscripts hvis den skal rette eller lave nye scripts. Det er <b>stateless</b> fordi det ikke producerer noget information til fremtidige kald.

[CLICK]
Domain-modelling skillet er også <b>model-invoked</b>. Agenten kalder det når der diskuteres domæne-specifikke termer. Agenten skal forstå jargonen og dokumentere den <b>(statefull)</b>, så den i fremtiden ikke bliver forviret. Hvis et issue f.eks indeholder ordet "filler" fra eksemplet, så vil skillet undersøge om det er en del af context.md filen og hvad det i så fald er. Hvis det ikke er det, så vil den undersøge / spørge for derefter at putte det i ccontext.md filen. 

[CLICK]
Triage skill. Dette er <b>user-invoked</b> fordi det udelukkende er os der bestemmer om et GitHub issue skal igennem en omskrivning. Det kan være at vi har fået indrapporteret en bug. Brugeren har oprettet et GH-issue, men han har glemt vigtige detaljer som en agent skal bruge, for at kunne arbejde videre med det. Det kunne være at brugeren havde skrevet, "Jeg får ingen alarmer når servoaksen fejler". Men hvad for en alarm vil vi gerne have? hvad skal den sige?. Vi laver derfor triage på den for at få den op på et niveau hvor vi kan uddellegere den til en agent.

[CLICK]
grill-with-docs. Et af de mest populære skills. Bliver ved med at diskutere med brugeren indtil der er en fælles forståelse. Indeholder det termonologi eller særlige designkrav bliver det noteret ned for fremtidige sessioner.

[CLICK]
Hvordan bliver skillet loaded ind og gemmer det information til sig selv i fremtiden.

[CLICK]

transition: Hvorfor skal vi selv lave skills?
```

---

### NOTE-023 — Slide 19 (lines 1611–1633)
Status: translated (PASS)

```
Når man er blevet dygtig til at skrive skills og instruktioner (Der findes selvfølgelig skills der er gode til at skrive skills eller agent.md filer) så kan man begynde at designe sine guardrails.

Guardrails er de beslutninger, vi vil kunne se igen i kode, tests og review.

[CLICK]
Det kan være krav til arkitektur 

[CLICK]
Naming konventions

[CLICK]
Testing strategi

[CLICK]
HMI og GUI design

[CLICK]
Safety principper

[CLICK]
transition: Guradrailes er med til at guide agenten når den specificerer, implementere og reviewer. Men hvad med tests?
```

---

### NOTE-024 — Slide 20 (lines 1673–1696)
Status: translated (PASS)

```
Jeg vil ikke sige så meget om tests. Det kommer Mads meget mere ind på om lidt. 

Det er dog vigtigt at sige, at test er uundværlige når man koder med Agenter. AI er ikke deterministikse, så vi har brug for pålidelige gates der kan validere vores software. Tests virker både som feedback til agenten, men ligeså meget som dokumentation til os der skal godkende en ændring.

Det er blevet uendeligt meget nemmere at skrive test i dag, end det var før AI. Men AI agenten kan ikke bare teste sig selv.

[CLICK]

Product tests:
En test af softwaren / maskinen:
Virker tingene rent faktisk som vi gerne vil have det? 

[CLICK]

Agent Evaluering: 
En test af workflowet / systemet:
Gjorde agenten som aftalt?

Vi har brug for begge dele. En agent kan følge processen korrekt, men stadig lave fejl. Omvendt kan ændringerne tilfældigvis virke, selvom agenten brød reglerne undervejs.

transition:

```

---

### NOTE-025 — Slide 21 (lines 1744–1752)
Status: translated (PASS)

```
Jeg tror alle har forstået at guardrails styrer og guider workflowet, mens tests er deterministiske fixpunkter (gates) der holder agenten igang indtil de er opfyldt.

Instructions og guardrails styrer en probabilistisk model. De er vigtige, men de er adfærdsvejledning - ikke enforcement.

Deterministiske tools kører uafhængigt af agentens opmærksomhed: compiler, schemas, permissions, architecture checks og blocking tests. Det betyder ikke, at checket er komplet eller at testen nødvendigvis er rigtig. Mennesker skal stadig reviewe test-oraklet.

Pull requesten samler requirement, diff, testresultater, assumptions, unresolved risk og reproduktionskommandoer. Build, static checks og behavior tests blokerer. En kompetent person accepterer de strategiske valg og release.
```

---

### NOTE-026 — Slide 22 (lines 1767–1775)
Status: translated (PASS)

```
Et agentforslag er først værdifuldt, når vi kan lukke loopet helt. Før loopet kan handle, skal det have domænekontekst: projektstruktur, produkt- og versionsviden, regler og intent. Projektet skal derefter kunne bygges reproducerbart. Vi skal kunne starte en kontrolleret simulation, stimulere en tilstand, observere variable og logbook og sammenligne resultatet med et krav.

På sliden ses guardrails via instructions og skills, derefter research via AS-HELP, BR-COMMUNITY, GitHub og den cloud-baserede AS-COPILOT MCP. Automation Studio læser og skriver kode gennem Main.st-editoren, mens as bygger, simulerer, læser variable og læser logbook.

DevOps udfører en kendt sekvens deterministisk. Agenten vælger næste afgrænsede handling ud fra feedback. Det er derfor vigtigt, at det samme command contract kan anvendes af en engineer, en test, en pipeline og en agent.

Transition: Det er præcis den rejse, B&R selv har været igennem.
```

---

### NOTE-027 — Slide 23 (lines 1853–1868)
Status: translated (PASS)

```
[CLICK]
Mennesker organiserer sig ofte i kanban-swimlanes efter fagdisciplin: HMI, safety, control og hardware. <b>horizontal slices</b> Det er en rationel arbejdsform, når fokus er begrænset, og når forskellige personer ejer forskellige fagligheder. Det er en begrænsning vi har som mennesker. En lille kortidshukommelse og vi er dårlige til at multitaske / context switche.
Som mennesker laver vi derfor typisk en disciplin ad gangen. Det er der vi er mest produktive, men det skaber udfordringer ved test. Hvordan tester man HMI uden logik? Der er ingen feedback!

[CLICK]


[CLICK]
En agent har ikke de begrænsninger og den kan bare starte subagenter op til at tage sig af andre ekspertiser, eller for at isolerer og delegerer konteksten fra. Derfor kan den arbejde vertikalt (<b>vertical slices</b>): feature-swimlanes med HMI-state, safety contract, control logic, I/O eller simulation og acceptance test i samme korte loop. Det er en kæmpe fordel ift. test. Hver feature kan testes uafhængigt fordi de indeholder alle ellementerne.

[CLICK]
Matt Pococks TDD-skill beskriver horizontal slicing som anti-patternet: skriv ikke alle tests først og al implementation bagefter. Arbejd i vertical slices: én test, én minimal implementation, gentag. Hver test er en tracer bullet, der bruger feedback fra den forrige cyklus. Red før green; refactor hører til reviewfasen.

Kilde: https://github.com/mattpocock/skills/blob/main/skills/engineering/tdd/SKILL.md
```

---

### NOTE-028 — (no slide-id, "One feature to build" recap slide, between slide 23 and slide 24; lines 1903–1910)
Status: translated (PASS)

```
Det er den samme maskinopgave, vi startede workshoppen med: fejl, kontrolleret stop, reject af ikke-cappede flasker, fastholdt tæller, genstart af batchen og evidens for det færdige resultat.

Nu har vi byggestenene: domæneviden, tools til at handle og observere, guardrails, tests og deterministiske gates.


Transition: Lad os samle byggestenene i de tre workflows, der gør ændringen afgrænset og verificerbar.
```

---

### NOTE-029 — Slide 24 (lines 1925–1937)
Status: translated (PASS)

```
"Recover efter en aksefejl" lyder som en opgave, men det er ikke en specifikation. Agenten kan researche eksisterende kode og søge viden. Men intention og trade-offs skal tilbage til os så vi kan tage stilling.

Her er et eksempel på hvordan et fuldt workflow kunne se ud der leder direkte til det Mads vil fortælle om efter pausen:

Den første workflow handler om at få den rigtige opgave beskrevet. 

Den anden kan være fuldt ud aftomatisk, når den er afgrænset, isoleret og har vundet vores tillid. 

Den sidste handler om validering og optimering af systemet.

transition: SPØRGSMÅL
```

---

### NOTE-030 — Slide 25 (lines 1965–1986)
Status: translated (PASS)

```
"Jeg hedder Mads Andersen og har arbejdet næsten 8 år hos B&R.

Jeg har primært arbejdet i OT-verdenen, men har altid haft en stor interesse for software engineering og de værktøjer og workflows man bruger i IT.

Igennem mange år har vi talt om at OT og IT langsomt bevæger sig tættere på hinanden.

Men de sidste par år er det accelereret voldsomt.

Vi har lige hørt om Agentic Engineering og hvordan AI kan hjælpe os med at skabe software hurtigere end tidligere.

Men det rejser et nyt spørgsmål:

Hvordan sikrer vi kvaliteten når mængden af software og ændringer stiger?

Det er i virkeligheden det DevOps handler om.

Hvordan vi kan bygge, teste og levere software på en reproducerbar måde.

Og det er det vi skal kigge nærmere på nu."

```

---

### NOTE-031 — Slide 26 (lines 2029–2045)
Status: translated (PASS)

```
Lad os lige hurtigt kigge på dagens rejse.

Først skal vi blive enige om hvad vi egentlig mener med DevOps.

Derefter skal vi snakke om hvorfor det bliver mere relevant end nogensinde i en verden med AI og Agentic Engineering.

Så kigger vi på CI/CD og de grundlæggende principper bag automatiseret levering af software.

Derefter skal vi se hvorfor tooling er så vigtigt, og hvordan as-cli passer ind i det billede.

Men størstedelen af tiden kommer faktisk til at være demoer, hvor vi ser det hele i praksis.

Til sidst samler vi det hele i spørgsmålet:

Hvad kan man realistisk begynde på allerede på mandag?
 
```

---

### NOTE-032 — Slide 27 (lines 2106–2130)
Status: translated (PASS)

```
Title: What is DevOps
Før vi går videre, lad os lige blive enige om hvad vi mener med DevOps i dag.

Development handler om at planlægge, implementere og verificere ændringer i software.

Operations handler om at få den software sikkert ud på den rigtige maskine, overvåge hvordan den opfører sig i drift, og samle feedback til næste ændring.

Det er også derfor man ofte illustrerer DevOps med uendelighedstegnet. Når software kommer ud i drift får vi ny viden. Måske finder vi fejl. Måske opdager vi noget der kan forbedres. Og så starter næste ændring.

Men det er en meget simplificeret definition. DevOps er i virkeligheden et kæmpe område.

Der er mange andre discipliner som ofte hører under DevOps. Infrastruktur, sikkerhed, samarbejde, dokumentation og så videre.

De er alle sammen vigtige.

Men hvis vi prøver at dække dem alle sammen i dag, så er vi her stadig i morgen.

Så når jeg siger DevOps i resten af præsentationen, så mener jeg primært denne del af DevOps:

Hvordan vi går fra kode til en verificeret release gennem Build, Test og Deploy.

Og det er især interessant i en verden hvor AI hjælper os med at skabe flere ændringer end nogensinde før.

```

---

### NOTE-033 — Slide 28 (lines 2181–2189)
Status: translated (PASS)

```
Lars har været inde på dette i starten, men for at gentage kort:

Agentic Engineering gør at vi kan generere kode hurtigt, skrive automatiske tests hurtigt, lave en idé til en prototype på rekordtid.
... Men agenten har brug for "Guardrails" og det er her DevOps kommre ind i billedet med build,test, kontroleret deployment, kvalitetstjek.

AI hjælper os med at lave software hurtigere. DevOps hjælper os med at levere det på en kontrolleret måde.

```

---

### NOTE-034 — Slide 29 (lines 2272–2309)
Status: translated (PASS)

```
Lad os prøve at kigge på hvordan softwarelevering ofte har fungeret historisk.

En ingeniør laver en ændring.
Projektet bygges lokalt.
Der kopieres måske nogle filer rundt.
Der køres måske nogle tests - måske ikke.
Og til sidst deployeres ændringen manualt.

Der er ikke nødvendigvis noget forkert i den proces.
Sådan er mange projekter blevet udviklet i årevis.
Men den giver nogle udfordringer:

Hvilken PC blev projektet bygget på?
Hvilke indstillinger havde den?
Hvilke tests blev kørt?
Kan vi genskabe præcis det samme resultat igen?
Og hvis noget går galt, hvor nemt er det så at rulle tilbage?

Så længe antallet af ændringer er lavt, kan vi ofte håndtere det.
Men når tempoet stiger, bliver det sværere.
Og det gælder især nu.
For hele pointen med Agentic Engineering er jo, at vi kan producere ændringer hurtigere.

[CLICK]

Hvis AI hjælper os med at lave 10 gange flere ændringer,
så har vi brug for en måde at verificere 10 gange flere ændringer.

Vi får ikke 10 gange flere timer til test.
Vi får ikke 10 gange flere commissioning engineers.
Derfor bliver vi nødt til at automatisere dele af build-, test- og release-processen.
Ikke fordi mennesker gør noget forkert.
<b>Men fordi mennesker ikke skalerer lige så godt som software</b>.

Og det er præcis det problem Continuous Integration forsøger at løse.

```

---

### NOTE-035 — Slide 30 (lines 2349–2363)
Status: translated (PASS)

```
Økonomien ved at skrive tests har også ændret sig med Agentic Engineering. 

Historisk set har automatiseret test været svært at retfærdiggøre i mange automationsprojekter.

Det er ikke fordi ingen kan lide tests. Problemet er, at tests også skal udvikles, vedligeholdes og opdateres. For mindre projekter har indsatsen ofte virket større end gevinsten.

Men Agentic Engineering ændrer lidt på den ligning.

Hvis tiden til at producere software falder markant, så falder omkostningen til at producere tests også. AI kan hjælpe os med både at implementere funktionalitet og oprette de test cases, der skal verificere funktionaliteten.

Samtidig ser vi ofte, at moderne agent workflows selv genererer og kører tests som en del af deres arbejdsproces. Verifikation bliver derfor en langt mere naturlig del af udviklingsflowet.

Af den grund er det blevet mere rentabelt at skrive tests og nemmere at retfærdiggøre i et OT projekt.
```

---

### NOTE-036 — Slide 31 (lines 2488–2511; note: this comment follows a separate, fully commented-out/disabled "Continuous Delivery" slide block at lines 2420–2487, which is structural content, not a presenter note, and is left untouched)
Status: translated (PASS)

```
På den forrige slide talte vi om at økonomien ved test og verifikation har ændret sig.

Hvis vi kan producere flere softwareændringer, så bliver vi også nødt til at verificere flere softwareændringer.
Det er præcis det problem Continuous Integration forsøger at løse.

Når en ændring bliver lavet, stopper arbejdet ikke ved at koden er skrevet.
Ændringen skal kunne bygges.
Den skal kunne testes.
Og den skal kunne verificeres.

Det vigtige er ikke at alle ændringer er perfekte.
Det vigtige er at vi får feedback mens ændringen stadig er lille.
Hvis noget går galt efter 5 minutters arbejde, er det nemt at forstå og rette.
Hvis noget går galt efter 3 ugers udvikling, er det ofte langt dyrere at finde årsagen.

Continuous Integration handler derfor om at flytte feedback så tæt på ændringen som muligt.

Hvis en agent producerer 20 ændringer på en dag, vil I så manuelt gennemgå dem alle sammen?
Sandsynligvis ikke.
Derfor bliver automatiseret verifikation så vigtig.

CI skalerer feedback på samme måde som Agentic Engineering skalerer softwareudvikling.
```

---

### NOTE-037 — Slide 33 (lines 2614–2625)
Status: translated (PASS)

```
Når vi så sætter det sammen med CD kalder vi det CI/CD.

CI verificerer vores ændringer. 

Continours Delivery (CD) pakker og releaser (f.eks. github),
Deployer til PLC, men næsten altid med et mennesker som godkender hvornår. I IT verdenen er det meget normalt at opdateringen kommer automatisk uden et mennesker godkender (eks. dette slide show til github pages. Opdateres auto ved et push til github). Dette passer ikke got i OT hvor det skal passe ind i produktionsplanlægning.
Til sidst har vi monitor delen som feeder de næste ændringer tilbage til vores CI og så får vi igen den her "timeglas effekt" som vi snakkede om i starten. 

Alt dette kalder vi CI/CD og senere har vi også en demo af det, men inden da skal vi snakker lidt om tooling.

```

---

### NOTE-038 — Slide 34 (lines 2696–2747)
Status: translated (PASS)

```
Vi har nu snakket om CI og CD.
Men der mangler stadig et vigtigt spørgsmål.
Hvordan får vi egentlig alt det her til at ske?
For en pipeline kan ikke trykke på musen.

Hvis vi tager en klassisk engineering-applikation.
Det kunne være Automation Studio.
Det kunne være TIA Portal.
Det kunne være Studio 5000.

Som menneske kan vi gøre en masse ting.
Vi kan åbne et projekt.
Vi kan vælge en konfiguration.
Vi kan starte et build.
Vi kan læse resultatet.
Vi kan overføre software til et target.
Og det fungerer faktisk rigtig godt.

GUI'er er lavet til mennesker.
De er optimeret til at vi kan udforske, forstå og arbejde med systemet.
Problemet opstår først når vi ønsker automation.
For en pipeline ved ikke hvad den skal klikke på.
Den kan ikke se knapper.
Den kan ikke læse dialogbokse.
Den kan ikke fortolke et build-vindue på samme måde som et menneske.

[CLICK]

Så hvis vi vil automatisere build, test, packaging og deployment...
så har vi brug for en anden type interface.
Ikke et interface til mennesker.
Men et interface til software.
Derfor ser vi ofte CLI'er og API'er.
De giver adgang til præcis de samme muligheder som GUI.
Bare på en måde som en pipeline kan forstå.


Og det leder os til den vigtigste pointe på hele sliden.
"Hvis et menneske skal klikke på det, kan en pipeline ikke automatisere det."
Det er selvfølgelig en lille simplificering.

Men grundideen er vigtig:
Hvis vi vil have DevOps.
Hvis vi vil have automatiske tests.
Hvis vi vil have Agentic Engineering.
Så skal de engineering-funktioner vi allerede har adgang til som mennesker...
også være tilgængelige programmatisk.
Og det er præcis her B&R kommer ind i billedet.

For lad os kigge på hvordan vi forsøger at gøre det i Automation Studio.
```

---

### NOTE-039 — Slide 35 (lines 2846–2883)
Status: translated (PASS)

```
Indtil nu har vi talt om principper og teori.
CI.
CD.
Automatiseret test.
Pipelines.

Men al den teori hjælper os faktisk ikke ret meget hvis værktøjerne ikke kan automatiseres.

Derfor har vi i Danmark arbejdet på as-cli.
(peger på midten)

Det er egentlig ikke en DevOps-platform.
Det er ikke en AI-agent.
Og det er heller ikke en erstatning for Automation Studio.
Det er et programmerbart interface til Automation Studio.

Det betyder at den samme engineering-funktionalitet nu kan bruges af:
- en ingeniør
- en DevOps pipeline
- eller en AI agent

Vi talte om at et menneske bruger en GUI, mens automation kræver en CLI eller API.
Det er præcis den rolle as-cli udfylder.

(peger på capabilities)

For dagens demo er der især 5 capabilities som er interessante.
Build af projekter.
Interaktion med runtime variabler.
Paketering af software.
Transfer til et target.
Og diagnostics.

Det er faktisk nok til at bygge en overraskende stor del af en DevOps pipeline.
Og det er også disse 5 ting vi kommer til at bruge i de næste demoer.

```

---

### NOTE-040 — Slide 36 (lines 2921–2935)
Status: translated (PASS)

```
Første demo er fra udviklingsprojektet af as CLI.

Projektet har nogle simple unit tests so tester meget isoleret logik eks. at et input til en funktion giver et forventet output. 
Disse tests er meget hurtige og kan køres ofte, men siger ikke meget om hele systemet virker. 
Til det har vi integration tests hvor vi tester alle as cli commands op imod et Automation Studio test projekt. Lad os åbne projektet og kigge på det.

Start  med at gør as --help i en terminal og vis alle de forskellige commands.

Herfeter hop ind i projektet og kør unit tests (tager ca. 2s).

Herefter kør integration test (tager 1.5min).
Lav en fejl "med vilje" og vis herefter at integration test fanger fejlen.
Forklar at vi har et github workflow som kører disse tests automatisk inden release. Dette vil jeg dog vente med at vise til næste demo hvor vi skal demo en helt CI/CD pipeline. 
```

---

### NOTE-041 — Slide 37 (lines 2960–3038)
Status: translated (PASS)

```
Indtil nu har vi kigget på as CLI som et softwareprojekt.
Men lad os flytte fokus over på noget der minder mere om det mange af os arbejder med til daglig.

Det her er vores orange juice machine.
Det er selvfølgelig et demo-projekt.
Men idéen er præcis den samme som på en rigtig maskine.
Vi har et Automation Studio projekt.
Vi har software.
Vi har en HMI.
Og vi har et ønske om at kunne levere ændringer på en reproducerbar måde.
I stedet for at snakke om det, lad os prøve at gøre det.

[skift til GitHub]

Jeg vil nu lave et release.
Det eneste jeg gør er at oprette et tag og pushe det til GitHub.
Og læg mærke til hvad der sker bagefter.
For her overtager pipelinen arbejdet.
Ikke mig.

[opret tag og push]

Nu starter GitHub workflowet.
Hvis vi åbner Actions-fanen kan vi følge det live.
Det her er vores digitaliserede proces.
Alle de manuelle trin vi tidligere snakkede om...
de er nu beskrevet som et workflow.

[vis workflow]

I praksis sker der nu flere ting.
Projektet bliver bygget.
Der bliver kørt automatiske tests.
Der oprettes et release.
Der genereres artifacts.
Og til sidst publiceres resultatet.
Alt sammen uden at jeg skal logge ind på en build-maskine eller huske hvilke trin der skal køres.

[vis .github/workflows]

Det interessante er faktisk ikke GitHub.
GitHub kunne lige så godt være Gitlab, Azure DevOps, Jenkins eller noget helt tredje.
Det interessante er at processen nu er beskrevet som kode.
Hvis en kollega kloner projektet.
Så får de præcis den samme proces.
Hvis vi kører den i morgen.
Så får vi præcis den samme proces.
Hvis vi kører den om seks måneder.
Så får vi stadig præcis den samme proces.
Det er det der gør den reproducerbar.

[vis de enkelte steps mens workflowet kører]

Læg mærke til at vi producerer mere end bare software.
Vi producerer også evidence.
Vi kan se hvad der blev bygget.
Hvilke tests der blev kørt.
Og om de bestod.
Det er præcis det CI/CD giver os.
Ikke bare automation.
Men sporbarhed.
Når workflowet er færdigt, ligger resultatet klar på release-serveren.
Herfra kan et target hente præcis den version vi lige har bygget.
Det bliver især interessant når man har mange identiske installationer.
Eller når man skal vide præcis hvilken version der blev installeret hvor.
For så er der ikke længere tvivl om hvad der kører.

Der findes ét build.
Ét artifact.
Én version.
Og alle ved hvor det kommer fra.

Transition:
Nu har vi automatiseret build, test og release.
Men hvad med selve brugeroplevelsen?
Hvordan tester vi egentlig at HMI'en stadig virker som operatøren forventer?

```

---

### NOTE-042 — Slide 38 (lines 3086–3117)
Status: translated (PASS)

```
Den sidste demo handler om noget som traditionelt har været svært at automatisere.
Nemlig HMI-verifikation.

(peger på flowet)

Tidligere talte vi om unit tests, integration tests og PLC tests.
Men i sidste ende er det jo ikke en PLC der bruger maskinen.
Det er en operatør.
Og derfor er det også interessant at kunne teste de workflows som operatøren faktisk bruger.

For eksempel:
- kan maskinen startes?
- kan en alarm kvitteres?
- kan en recept ændres?
- vises den rigtige status på skærmen?

Normalt ville en person skulle klikke sig igennem disse scenarier manuelt.

Men præcis som vi kan automatisere build og test af software, kan vi også automatisere brugerinteraktionen med HMI'et.

Det betyder at hver softwareændring automatisk kan kontrollere at de vigtigste operator-workflows stadig fungerer.

Det er præcis det jeg vil vise nu.

Til dette bruger vi et cli fra microsoft som hedder playwright.
For demoens skyld åbner jeg browseren og har lagt nogle animationer ind over. I en rigtig pipeline bille den normalt køre headless i en terminal.

npm run test:demo
Hvis det skulle køre headless kan man bare skrive:
npm run test:hmi
```

---

### NOTE-043 — Slide 39 (lines 3186–3198) — ALREADY ENGLISH, NOT DANISH
Status: skip (not Danish — source already in English, no translation performed)

```
The goal of DevOps is not to build a perfect CI/CD system overnight.

The goal is to make one engineering workflow more repeatable than it was yesterday.

Start with Git.
Then automate a build.
Then add one meaningful test.
Then capture evidence.
Then automate release activities.

Every step creates value.
```

---

### NOTE-044 — Slide 40 (lines 3236–3293)
Status: translated (PASS)

```

Lad mig slutte af med at være lidt ærlig.
Vi står ikke her fordi vi synes vi har løst DevOps i industriel automation.
Vi står her fordi vi synes vi er kommet langt nok til at begynde at bruge det i praksis.
Vi har tooling.
Vi har workflows.
Vi har demoer.
Vi har kunder som er interesserede.
Men vi har også lært at nogle ting stadig gør det unødigt svært.

[CLICK]

Den første ting vi arbejder på er Automation Studio i Docker.
Hvis vi ser på hvordan moderne softwareudvikling foregår i IT-verdenen, så forventer man næsten at kunne starte et nyt miljø med én kommando.

Samme version.
Samme dependencies.
Samme setup.
Hver gang.

Det er ekstremt attraktivt når man arbejder med CI/CD, build-servere og AI-agenter.
For jo mindre miljøet betyder, desto lettere bliver automation.
Men det er også et svært problem.
Automation Studio er ikke designet til at være en cloud-native applikation fra starten.
Så det her er noget vi aktivt undersøger og arbejder med.

[CLICK]

Den anden ting er package management.
Hvis vi ser på moderne softwareprojekter, så er dependencies noget man næsten tager for givet.
Man skriver hvad projektet afhænger af.
Og systemet finder, henter og installerer det.
I automation er virkeligheden ofte mere kompliceret.
Technology packages.
Hardware beskrivelser.
Firmware versioner.
Specialkomponenter.
Mange af os har prøvet at få et projekt og bruge en halv dag på at finde alt det der mangler før det kan bygge.
Det er præcis den oplevelse vi gerne vil forbedre.

[CLICK]

Og det er nok faktisk den vigtigste del af sliden.
Vi tror vi er på den rigtige vej.
Men vi er mindst lige så interesserede i at høre hvad I synes.
For kunden bruger systemet på en måde som vi aldrig selv kan simulere.
Så hvis I skulle vælge:
Hvad ville skabe mest værdi for jer?
Hvad er den største barriere for at komme i gang?
Hvad mangler vi?
For den næste fase handler ikke kun om at bygge tooling.
Den handler om at lære hvordan værktøjerne bliver brugt i virkeligheden.

Transition:
Og med det vil vi meget gerne høre hvad I tænker.

```

---

## Summary

- Total presenter-note blocks found: **44** (NOTE-001 … NOTE-044)
- Danish blocks requiring translation: **43**
- Non-Danish blocks (skip): **1** (NOTE-043, already English)
- Excluded structural content: 1 disabled/commented-out slide block (lines 2420–2487, "Continuous Delivery" slide) — not a presenter note, left untouched.
