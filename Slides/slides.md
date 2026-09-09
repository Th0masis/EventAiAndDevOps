---
theme: default
title: The future of automation
titleTemplate: '%s | B&R Industrial Automation'
author: B&R Industrial Automation
colorSchema: light
aspectRatio: 16/9
canvasWidth: 1280
transition: slide-left
duration: 90min
timer: countdown
drawings:
  enabled: true
  persist: false
fonts:
  sans: IBM Plex Sans
  serif: Barlow Condensed
  mono: IBM Plex Mono
  provider: google
exportFilename: agentic-engineering
defaults:
  layout: default
---

<script setup>
const materialsLink = import.meta.env.BASE_URL === '/'
  ? '/21?clicks=8'
  : `${import.meta.env.BASE_URL}#/21?clicks=8`
</script>

<div class="materials-slide">
<div class="materials-intro">
  <div class="eyebrow">EVENT RESOURCES</div>
  <h1>Materials <span class="accent">&amp; Links</span></h1>
  <p>Everything from today's AI and DevOps event, in one place.</p>
</div>

<div class="materials-links">
  <a class="materials-link" href="https://github.com/BRDK-Public/EventAiAndDevOps" target="_blank" rel="noreferrer">
    <span class="materials-link-number">01</span>
    <span class="materials-link-main">
      <strong>BRDK-Public/EventAiAndDevOps</strong>
      <small>Event repository</small>
    </span>
    <span class="materials-link-action">OPEN</span>
  </a>
  <a class="materials-link" :href="materialsLink" target="_blank" rel="noreferrer">
    <span class="materials-link-number">02</span>
    <span class="materials-link-main">
      <strong>MCP SERVER OVERVIEW</strong>
      <small>SLIDE 21</small>
    </span>
    <span class="materials-link-action">OPEN</span>
  </a>
</div>
</div>

---
layout: default
class: reference-slide
---

# Welcome!

<div class="welcome-grid">
  <div class="reference-photo welcome-photo-foodtruck"><img src="/welcome-foodtruck.jpg" alt="Foodtruck at the event"></div>
  <div class="reference-copy welcome-copy-feedback">
    <h2>Feedback</h2>
    <p>We value your feedback. Please complete the survey at the end of the day.</p>
  </div>
  <div class="reference-photo welcome-photo-audience"><img src="/welcome-audience.jpeg" alt="Audience at the event"></div>
  <div class="reference-copy welcome-copy-stay">
    <h2>Stay afterward</h2>
    <p>The event officially ends at 13:00, but you are welcome to stay if you have additional questions.</p>
  </div>
  <div class="reference-copy welcome-copy-lunch">
    <h2>Lunch</h2>
    <p>Foodtruck from Original Pita will be ready with lunch at 12.15.</p>
  </div>
  <div class="reference-photo welcome-photo-collaboration"><img src="/welcome-collaboration.jpeg" alt="People collaborating"></div>
  <div class="reference-copy welcome-copy-slides">
    <h2>Slides</h2>
    <p>All slides will be available after the event. Complete the survey to receive a link.</p>
  </div>
  <div class="reference-photo welcome-photo-networking"><img src="/welcome-networking.jpg" alt="People networking at the event"></div>
</div>

<img class="reference-brand" src="/br-logo.svg" alt="B&R Industrial Automation">

---
layout: default
class: reference-slide events-reference
---

# Upcoming Events<br><span class="accent">2026</span>

<div class="event-grid">
  <article class="event-card">
    <img src="/upcoming-adaptive.jpeg" alt="Adaptive automation robot and conveyor">
    <h2>Passion4AdaptiveAutomationDays 2026</h2>
    <p>Date: 6.-7. October 2026<br>Location: Orange Point, Malmö Sweden</p>
  </article>
  <article class="event-card">
    <img src="/upcoming-rugged.png" alt="Rugged automation controller in a field">
    <h2>Passion4RuggedAutomationDays 2026</h2>
    <p>Date: 10.-11. November 2026<br>Location: Orange Point, Malmö Sweden</p>
  </article>
</div>

<img class="reference-brand" src="/br-logo.svg" alt="B&R Industrial Automation">

---
layout: cover
---

<img class="cover-image" src="/evolution.png" alt="Evolution from AI assistant to AI agent and agentic AI">
<img class="cover-logo" src="/br-logo.svg" alt="B&R Industrial Automation">

<div class="eyebrow" v-motion :initial="{ opacity: 0, x: -30 }" :enter="{ opacity: 1, x: 0, transition: { delay: 150 } }">
  AI · DEVOPS · AGENTIC ENGINEERING
</div>

<div class="cover-event" v-motion :initial="{ opacity: 0, x: -30 }" :enter="{ opacity: 1, x: 0, transition: { delay: 280 } }">
  <span>03 SEP 2026</span><span>ODENSE</span><span>08.30–13.00</span>
</div>

# The future of<br><span class="accent">automation</span>

<p class="cover-sub" v-motion :initial="{ opacity: 0, y: 18 }" :enter="{ opacity: 1, y: 0, transition: { delay: 450 } }">
  How do we create real value in industrial engineering?
</p>

<div class="bridge-visual" v-motion :initial="{ opacity: 0, y: 24 }" :enter="{ opacity: 1, y: 0, transition: { delay: 700 } }">
  <div class="bridge-node"><span>01</span> IDEA</div>
  <div class="bridge-track"><i></i><i></i><i></i><i></i><i></i></div>
  <div class="bridge-node is-proof"><span>02</span> DEPLOYMENT</div>
</div>
<div class="slide-id">01</div>

<!--
Představení nás samých.
Pracujeme s AI poslední 2 roky, kde se nyní nacházíme.

Rozhodli jsme se uspořádat event s AI i DevOps, protože <b>vidíme mnoho synergií.</b>
AI nabízí úplně novou úroveň produktivity, zatímco DevOps zajišťuje kvalitu. Tyto dvě věci spolu podle nás pracují ruku v ruce.

Cítíme také, že AI i DevOps jsou témata, která dělí vody. <b>AI je všude</b>. Je fascinující, k čemu se dá použít. Je tu spousta hype a je zcela přirozené mít <b>zdravou skepsi</b>. Protože to přece není magie!

DevOps zavádí <b>spoustu pravidel a struktury</b>. Někdo to vidí jako náboženství, zatímco jiní je vidí jako rigidní procesy, které <b>zabíjejí jakoukoli formu kreativity a produktivity.</b>

S konceptem Agentic Engineering je chceme sjednotit a doufejme <b>ukázat to nejlepší z obou světů!</b>
-->

---
layout: default
class: agenda-slide dark-slide
---

<div class="kicker">TODAY · PRACTICAL INFO</div>

<div class="agenda-layout">
  <div class="agenda-intro" v-motion :initial="{ opacity: 0, x: -24 }" :enter="{ opacity: 1, x: 0 }">
    <h1>AI & DevOps<br><span class="accent">A shared vision.</span></h1>
    <p class="agenda-lead">A practical path from why this matters to how we build trustworthy agentic workflows for industrial engineering.</p>
    <div class="agenda-event-mark">
      <span>03</span>
      <div><b>SEPTEMBER 2026</b><small>ODENSE · B&R INDUSTRIAL AUTOMATION</small></div>
    </div>
  </div>

  <div class="agenda-timeline" v-motion :initial="{ opacity: 0, x: 28 }" :enter="{ opacity: 1, x: 0, transition: { delay: 220 } }">
    <div class="agenda-row">
      <time datetime="08:30">08.30</time><i aria-hidden="true"></i><div><b>Arrival and breakfast</b><small>Settle in</small></div>
    </div>
    <div class="agenda-row">
      <time datetime="09:00">09.00</time><i aria-hidden="true"></i><div><b>Welcome and introduction</b><small>Why DevOps + Agentic Engineering</small></div>
    </div>
    <div class="agenda-row is-session">
      <time datetime="09:30">09.30</time><i aria-hidden="true"></i><div><b>Agentic Engineering</b><small>Definitions · bridge · constraints</small></div>
    </div>
    <div class="agenda-row">
      <time datetime="10:30">10.30</time><i aria-hidden="true"></i><div><b>Break and networking</b><small>30 minutes</small></div>
    </div>
    <div class="agenda-row is-session">
      <time datetime="11:00">11.00</time><i aria-hidden="true"></i><div><b>DevOps in industry</b><small>Version · build · test · release</small></div>
    </div>
    <div class="agenda-row">
      <time datetime="12:15">12.15</time><i aria-hidden="true"></i><div><b>Questions, lunch and networking</b><small>Until 13.00</small></div>
    </div>
  </div>
</div>

<div class="slide-id">02</div>

<!--
Prezentace Programu.

Nejdříve stručný přehled AI a DevOps.
Ne všichni zde znají tyto koncepty.

Poté hlubší session s Agentic Engineering:
Jak přesně můžeme pracovat s AI v průmyslnějším světě, kde byly systémy historicky uzavřenější a proprietární?
Myslíme si, že jsme na cestě k vyřešení tohoto na platformě B&R.

Pak bude Mads mít session o DevOps:
Vysvětlí, co je možné s platformou B&R.
Dá pár super demoů automatizovaného testování a nasazení.

-->

---
layout: default
class: light-grid
---

<div class="kicker">WHY THIS EVENT · 04 MIN</div>

# Just another<br><span class="accent">AI Event?</span>

<div class="split-verdicts">
  <div class="verdict no" v-click>
    <div class="verdict-head"><mdi-close-circle-outline /> WHAT WE WILL NOT TELL YOU</div>
    <div class="verdict-row"><b>Everyone else has</b><span>solved AI</span></div>
    <div class="verdict-row"><b>Copy our</b><span>productivity percentage</span></div>
    <div class="verdict-row"><b>Buy one tool and</b><span>transformation follows</span></div>
    <div class="verdict-row"><b>The newest LLM</b><span>benchmarks and hype</span></div>
  </div>
  <div class="verdict yes" v-click>
    <div class="verdict-head"><mdi-check-circle-outline /> WHAT WE WILL TELL YOU</div>
    <div class="verdict-row"><b>Industrial AI is</b><span>high priority, but still very early</span></div>
    <div class="verdict-row"><b>Our current strategy</b><span>and what we are working on</span></div>
    <div class="verdict-row"><b>Results depend on</b><span>context and process</span></div>
    <div class="verdict-row"><b>How to get started</b><span>in your own team</span></div>
  </div>
</div>

<div class="bottom-statement" v-click>
  We don't have all the answers. <strong>Please keep the discussion ongoing!</strong>
</div>

<div class="slide-id">03</div>

<!--

<b>Sám jsem byl na mnoha AI přednáškách a konferencích.</b>
Často se člověk vrátí domů s pocitem, že je úplně pozadu a že všichni ostatní rozluštili kód úspěchu s AI.<br><br>

[CLICK]
<b>Dnes by to tak samozřejmě být nemělo!</b>

NECHCEME ŘÍKAT:

<b>Že máme standardní řešení, které vyřeší všechny vaše problémy</b> AI a DevOps jsou složité a musí se přizpůsobit každému scénáři a platformě!

<b>Také vám nechceme prodávat produkt.</b> Vše, co vám dnes ukážeme, vám nic nestojí. Je to workshop, ne prodejní prezentace!

<b>Nebudeme mluvit o AGI, sci-fi a všem, co by se mohlo stát za chvíli</b>

[CLICK]
MÍSTO TOHO CHCEME MLUVIT O:

AI v automatizačním průmyslu je <b>relativně nová</b>, a chceme se ujistit, že máte nástroje, které potřebujete!

Chceme informovat naše zákazníky a partnery o <b>naší strategii a směru.</b><br>

Pokud neexistuje standardní řešení, jaké jsou možnosti na platformě B&R a <b>jak začít?</b>

[CLICK]

Rádi bychom si s vámi povídali / diskutovali. Prosím, pokládejte otázky nebo dejte nám zpětnou vazbu

Přechod: Podívejme se na to, jak se DevOps a Agentic Engineering navzájem doplňují.
-->

---
layout: default
class: dark-slide loop-slide
---

<div class="kicker">COMPLEMENTARY SYSTEMS · 03 MIN</div>

# DevOps + Agentic<br><span class="accent">Engineering</span>

<div class="loop-compare">
  <div class="loop-linear" v-click>
    <div class="loop-bars">
      <span>Plan</span><i></i>
      <span>Design</span><i></i>
      <span>Build</span><i></i>
      <span>Test</span><i></i>
      <span>Deploy</span><i></i>
      <span>Maintain</span>
    </div>
    <p><b>Traditional DevOps stages.</b> Every step is handled manually</p>
  </div>

  <div class="loop-cycle" v-click>
    <svg viewBox="0 0 300 300">
      <defs>
        <marker id="loopArrow" viewBox="0 0 10 10" refX="6" refY="5" markerWidth="4" markerHeight="4" orient="auto-start-reverse">
          <path d="M0 0 L10 5 L0 10 z" fill="var(--br-orange)" />
        </marker>
      </defs>
      <g class="loop-arrows" fill="none" stroke="var(--br-orange)" stroke-width="3" stroke-linecap="round" marker-end="url(#loopArrow)">
        <path d="M189.3 41.9 A115 115 0 0 1 223.9 61.9" />
        <path d="M263.2 130 A115 115 0 0 1 263.2 170" />
        <path d="M223.9 238.1 A115 115 0 0 1 189.3 258.1" />
        <path d="M110.7 258.1 A115 115 0 0 1 76.1 238.1" />
        <path d="M36.7 170 A115 115 0 0 1 36.7 130" />
        <path d="M76.1 61.9 A115 115 0 0 1 110.7 41.9" />
      </g>
      <circle class="loop-hub" cx="150" cy="150" r="56" />
      <text class="loop-hub-label" x="150" y="145">Agent</text>
      <text class="loop-hub-sub" x="150" y="166">Workflows</text>
      <g class="loop-node">
        <circle cx="150" cy="35" r="31" /><text x="150" y="39">Plan</text>
        <circle cx="249.6" cy="92.5" r="31" /><text x="249.6" y="96.5">Design</text>
        <circle cx="249.6" cy="207.5" r="31" /><text x="249.6" y="211.5">Build</text>
        <circle cx="150" cy="265" r="31" /><text x="150" y="269">Test</text>
        <circle cx="50.4" cy="207.5" r="31" /><text x="50.4" y="211.5">Deploy</text>
        <circle cx="50.4" cy="92.5" r="31" /><text x="50.4" y="96.5">Maintain</text>
      </g>
    </svg>
    <p><b>AI-native DevOps.</b> Humans above the loop instigating, directing and governing.</p>
  </div>
</div>

<div class="signal-callout" v-click>
  <div class="signal-pulse"></div>
  <p>DevOps gives agents rails.<br><strong>Agents make the rails more useful.</strong></p>
</div>
<div class="slide-id">04</div>

<!--
[CLICK]
<b>DevOps je postup sestávající z různých fází</b>, kterými musí software projít. Každá fáze nastavuje požadavky, které zajišťují, že další fáze bude úspěšná. Musí se <b>buď provádět ručně, nebo se ručně předávat dál</b>. Pokud nejsou požadavky splněny dostatečně důkladně, nemá workflow žádnou skutečnou hodnotu. Proto to pro některé může vypadat rigidně a těžkopádně - i když je to nutnost pro poskytování vysoké kvality.

[CLICK]

<b>Zavedením AI-Agentů do vašeho DevOps procesu existuje mnoho výhod. AgentOps</b>

0. DevOps se stává rámcem pro AI, který zajišťuje kvalitu a předvídatelnost. (AI, stejně jako lidé, není deterministická). To je důležité, protože nikdy jsme nebyli schopni udělat chybu rychleji než nyní.
1. Agenti na rozdíl od lidí VŽDY dodržují své pokyny. Nejsou ani fanatičtí, ani si nestěžují, že je to rigidní!
2. Velkou část procesů DevOps lze automatizovat a ušetřit tak čas.
3. Znalosti se ukládají do pracovních postupů, nikoli do jednotlivců
4. Stále můžeme mít plnou kontrolu nad procesem, pokud jej chytře integrujeme. To je v OT zásadní požadavek!

[CLICK]
<b>DevOps se tedy stane samotným rámcem pro AI <br>
a AI činí tento rámec super efektivním!</b>


-->

---
layout: default
class: dark-slide cycletime-slide
---

<div class="kicker">CYCLE TIME · 03 MIN</div>

# Where the time<br><span class="accent">actually goes</span>

<div class="cycle-block" v-click>
  <p class="cycle-head"><b>Without DevOps</b> — no safety net, a variable cost lands after release</p>
  <div class="cycle-track track-nodevops">
    <span>Idea</span>
    <span class="hot">Build</span>
    <span>Deploy</span>
    <span class="bad">Bugfix</span>
  </div>
</div>

<div class="cycle-block" v-click>
  <p class="cycle-head"><b>DevOps before AI</b> — every stage runs at human speed</p>
  <div class="cycle-track track-before">
    <span>Plan</span>
    <span>Design</span>
    <span class="hot">Build</span>
    <span>Test</span>
    <span>Deploy</span>
    <span>Maintain</span>
    <em>reclaimed</em>
  </div>
</div>

<CycleTradeoff v-click />

<div class="slide-id">05</div>

<!--
Pojďme se podívat, jak by mohla vypadat investice času jedné osoby během fáze vývoje:

[CLICK]
<b>Nahoře: Bez DevOps:</b> Člověk rychle přeskakuje plánování a design. Začínáme od prvního dne. Je to sakra vzrušující!

Vývoj trvá dlouho, protože se specifikace neustále mění a software se stal komplexním. Možná jsme to měli pojmout jinak? Ale teď už je pozdě!

Čas je pryč a lhůta je tady, nasazujeme, co máme.

Faktura přichází po vydání jako opravy chyb. Člověk nikdy neví, kdy dosáhne přijatelné fáze, a cena je tedy nepředvídatelná!

[CLICK]
<b>Uprostřed: S DevOps:</b> Z výše uvedeného vyplývá, že DevOps je nutností. Ale v OT je často příliš drahé implementovat pro malé/střední jednorázové projekty. A všechny projekty přece začínají jako jednorázové projekty, dokud nepostaví stroj číslo 2 :-).

Řádné plánování a design stojí čas, ale jsou celým základem pro vývoj a testování dobré kvality. Opravy chyb se minimalizují, čas je již ušetřen a konečné náklady jsou předvídatelnější. Je jen často těžké zdůvodnit dodatečné počáteční investice

[CLICK]
<b>Dole: AgentOps:</b> Investice času se posunuje ještě dále vpřed v procesu. Agenti nemají žádnou paměť ani vnitřní znalost o "best practice". Všechno musí být velmi explicitně definováno, aby se zabránilo nedorozuměním. Pracovní postupy a pokyny musí být bezchybné a dotažené do detailu.

Naopak vývoj se zkrátí na zlomek původního času. Možná dokonce na 0, protože proces neblokuje práci na čemkoli jiném mezitím.
Recenze a rozhodnutí o vydání zůstávají stále u nás.

<b>Uvolněný čas není nutně bezplatný zisk</b> - lze ho investovat do lepšího kontextu, lepších testů a lepší správy a rozhodování.

Poprvé v dlouhé době je možné výrazně zvýšit kvalitu bez potřeby investovat do výrazně více inženýrů.

Přechod: Jaký je rozdíl mezi ChatGPT a OT Super Agentem?
-->

---
layout: default
class: stack-slide dark-slide
---

<div class="kicker">DEFINITION · 04 MIN</div>

# What is an<br><span class="accent">agent?</span>

<div class="agent-nest">
  <div class="agent-box">
    <span class="nest-tag">AGENT</span>
    <div class="harness-grid">
      <span v-click>instructions</span>
      <span v-click>context</span>
      <span v-click>tools</span>
      <span v-click>memory</span>
      <div class="model-core">
        <b>LLM</b>
        <small>patterns · reasoning</small>
      </div>
      <span v-click>permissions</span>
      <span v-click>logs</span>
      <span v-click>feedback</span>
      <span v-click>approvals</span>
    </div>
    <p class="harness-note" v-click>
      <span>Everything around the model is the <b>harness</b></span>
      <span class="harness-logos" role="img" aria-label="GitHub Copilot, Claude Code, Codex and Cursor">
        <span class="harness-logo copilot" title="GitHub Copilot"><simple-icons-githubcopilot aria-hidden="true" /></span>
        <span class="harness-logo claude" title="Claude Code"><simple-icons-claudecode aria-hidden="true" /></span>
        <span class="harness-logo codex" title="Codex"><simple-icons-openai aria-hidden="true" /></span>
        <span class="harness-logo cursor" title="Cursor"><simple-icons-cursor aria-hidden="true" /></span>
      </span>
    </p>
  </div>
</div>

<div class="record-rail" v-click>
  <mdi-robot-outline />
  <span>AN AGENT IS A MODEL IN A HARNESS</span>
  <small>THINKING, PLANNING & ACTING</small>
</div>


<div class="slide-id">06</div>

<!--
Co je Agent?

Skládá se v zásadě ze dvou nezávislých komponent.
LLM (jazykový model) a Harness.

Mnozí vidí LLM jako magickou komponentu, která dělá rozdíl. Je to ta, která si vezme všechnu pozornost, ale prostředí, ve kterém pracuje, má minimálně stejný vliv na výsledek.

LLM se neustále mění. Příští týden to může být úplně jiný model, který je buď lepší, nebo levnější.

LLM a Harness jsou proto nezávislé komponenty, kde my (převážně) nemáme vliv na samotný model, ale máme velký vliv na harness, kde se používá.

Model sám nemá přístup k Automation Studio, projektu, PLC nebo simulátoru. Může pracovat pouze s kontextem, který mu je dán, a posoudit, jak bude používat nástroje, které jeho Harness zpřístupňuje.

Agent vzniká, když model může zvolit nástroj, zavolat jej, vidět výsledek a rozhodnout o dalším kroku. Harness je prostředí kolem agenta:

[CLICK]
Instructions: Agent.md. Skills. Co by měla umět. Co by měla dělat?<br>
[CLICK]
Context: V čem pracujeme?<br>
[CLICK]
Tools: K čemu by měl mít agent přístup ve vnějším světě? Nebo lokálně na vašem počítači?<br>
[CLICK]
Memory: Protože LLM je zcela bezstavový, musí existovat něco, co uchovává historii. Možná ji také sdílí mezi relacemi.<br>
[CLICK]
Permissions: Co smí agent dělat sám? Které nástroje smí používat?<br>
[CLICK]
Logs: Zaznamenává, co agent dělal. Které nástroje zavolal. Vytvořil subagenty? Jaké odpovědi od nich dostal?<br>
[CLICK]
Feedback: Agent se vás může zeptat na radu (agent vás vyzve). Co si o tom myslíte? Mám zvolit X nebo Y?<br>
[CLICK]
Approvals: Musíte agentovi dát oprávnění nebo přístup k vašemu počítači. Mohu smazat váš C-disk?<br>

[CLICK]
Agent je LLM v Harnessu!

[CLICK]
Přechod: Proč se to stalo rychleji v IT než v OT? Proč neexistují agenti, kteří by mohli dělat AS stejně dobře jako vyvíjí weby?
-->

---
layout: default
class: process-slide
---
<div class="kicker">FOUNDATION · 04 MIN</div>

# IT & OT are<br><span class="accent">converging</span>

<p class="it-ot-lead">The engineering tools are meeting. The feedback loop still has to reach the machine.</p>

<div class="it-stack-strip" role="img" aria-label="IT engineering tools and agent protocols">
  <span class="it-stack-label">SHARED<br>TOOLCHAIN</span>
  <span class="it-stack-logo vscode" title="Visual Studio Code"><simple-icons-visualstudiocode aria-hidden="true" /></span>
  <span class="it-stack-logo git" title="Git"><simple-icons-git aria-hidden="true" /></span>
  <span class="it-stack-logo github" title="GitHub"><simple-icons-github aria-hidden="true" /></span>
  <span class="it-stack-logo docker" title="Docker"><simple-icons-docker aria-hidden="true" /></span>
  <span class="it-stack-logo test" title="Unit tests"><mdi-test-tube aria-hidden="true" /></span>
  <span class="it-stack-logo cli" title="Command line interface"><mdi-console aria-hidden="true" /></span>
  <span class="it-stack-logo mcp" title="Model Context Protocol"><simple-icons-modelcontextprotocol aria-hidden="true" /></span>
  <span class="it-stack-logo copilot" title="GitHub Copilot"><simple-icons-githubcopilot aria-hidden="true" /></span>
  <span class="it-stack-logo claude" title="Claude Code"><simple-icons-claudecode aria-hidden="true" /></span>

</div>
<div class="it-ot-messages">
  <div><span>01</span><b>Agentic Engineering in IT is <strong>moving fast!</strong></b></div>
  <div><span>02</span><b>Competences are <strong>converging</strong> but solutions are <strong>diverging</strong></b></div>
  <div><span>03</span><b>Only an <strong>open Automation Platform</strong> supports a unified future</b></div>
</div>
<div class="it-ot-figure-card">
  <img class="it-ot-figure" src="/it-ot.png" alt="IT and OT convergence">
</div>
<div class="it-ot-platform" v-click>
  <div class="it-ot-platform-copy">
  </div>
  <div class="it-ot-platform-lockup">
    <img class="as-logo" src="/as-logo.png" alt="Automation Studio">
    <div class="as-labels"><span>No binaries</span><span>Only text</span></div>
  </div>
</div>

<div class="slide-id">07</div>

<!--
Již mnoho let se „někteří“ zmiňují o tom, že se IT a OT budou prolínat. Do jisté míry to také platí. Mnoho nástrojů používaných v IT je nyní k dispozici i pro OT. (Pracujeme na AS ve VS Code a Dockeru. Jsme si vědomi, že ještě nejsme úplně u cíle.)

<b>Od té doby, co se AI stala součástí technologického stacku, se IT opět začalo „vzdalovat“.</b>

Není to proto, že bychom neměli stejné dovednosti v OT, ale protože IT a celý přístup <b>open source</b> jde opravdu rychle.

<b>LLM jsou již trenovány na nekonečně mnoho IT projektů</b>, zatímco OT je téměř vždy uzavřený zdroj. Jak pokud jde o samotnou platformu automatizace, tak i o doménu, se kterou pracujete. Jak funguje slévací stroj nebo lisovací stroj?

IT už má nástroje a kontext jako přirozenou součást vývojového prostředí: správu verzí, API, CLI a diagnostiku. Modely a agenti se proto mohou rychle připojit k existující zpětnovazební smyčce.

<b>Přestože máme stejné dovednosti</b> nemůžeme držet krok s inovacemi, které se právě nyní dějí v IT

V OT musíme sami ve větší míře vyvíjet odpovídající nástroje a kontext, se kterým může AI pracovat. OT navíc má fyzické důsledky, dlouhé cykly životnosti, závislosti na hardwaru a verzích, pohyb, bezpečnost a méně standardizovanou zpětnou vazbu.

[CLICK]
<b>Úkolem proto není zavést AI do OT, ale zpřístupnit OT pro AI.</b>

Přechod: Největší propastí je rozdíl mezi generováním kódu a jeho kódu.
-->

---
layout: default
class: foundation-slide dark-slide
---

<div class="kicker">OT ENABLEMENT · 04 MIN</div>

# what is needed to<br><span class="accent">close the gap</span>

<div class="foundation-layout">
  <div class="foundation-stack">
    <div class="foundation-row" v-click>
      <span class="foundation-index">01</span>
      <span class="foundation-icon"><mdi-database-search-outline /></span>
      <div class="foundation-copy">
        <h2>Domain knowledge</h2>
        <p>Product, platform and OEM knowledge the LLM does not carry.</p>
      </div>
      <span class="foundation-tag">B&amp;R + OEM</span>
    </div>
    <div class="foundation-row" v-click>
      <span class="foundation-index">02</span>
      <span class="foundation-icon"><mdi-file-tree-outline /></span>
      <div class="foundation-copy">
        <h2>Project context</h2>
        <p>A readable map of programs, configuration, hardware, and dependencies.</p>
      </div>
      <span class="foundation-tag">B&amp;R</span>
    </div>
    <div class="foundation-row" v-click>
      <span class="foundation-index">03</span>
      <span class="foundation-icon"><mdi-source-commit /></span>
      <div class="foundation-copy">
        <h2>Git source control</h2>
        <p>Reproducible commits make every change traceable and reversible.</p>
      </div>
      <span class="foundation-tag">B&amp;R</span>
    </div>
    <div class="foundation-row" v-click>
      <span class="foundation-index">04</span>
      <span class="foundation-icon"><mdi-tools /></span>
      <div class="foundation-copy">
        <h2>B&amp;R platform tools</h2>
        <p>Supported actions for debugging, testing, and deployment on the platform.</p>
      </div>
      <span class="foundation-tag">B&amp;R</span>
    </div>
    <div class="foundation-row" v-click>
      <span class="foundation-index">05</span>
      <span class="foundation-icon"><mdi-shield-check-outline /></span>
      <div class="foundation-copy">
        <h2>Guardrails</h2>
        <p>B&amp;R specific rules or skills. OEM architecture, coding, naming, and testing strategies. </p>
      </div>
      <span class="foundation-tag">B&amp;R + OEM</span>
    </div>
  </div>
  <div class="foundation-contract" v-click>
    <div class="foundation-contract-head">
      <span>THE ENGINEERING CONTRACT</span>
      <mdi-lock-check-outline />
    </div>
    <div class="foundation-agent">
      <span class="foundation-agent-icon"><mdi-robot-outline /></span>
      <div>
        <b>LLM / AGENT</b>
        <small>reason over feedback</small>
      </div>
    </div>
    <div class="foundation-contract-arrow"><mdi-arrow-down /></div>
    <div class="foundation-contract-flow">
      <div><span>01</span><b>READ</b><small>context that is in scope</small></div>
      <div><span>02</span><b>CHANGE</b><small>controlled platform actions</small></div>
      <div><span>03</span><b>VERIFY</b><small>tests, diagnostics, and feedback</small></div>
    </div>
    <p class="foundation-contract-foot">Same engineering pattern as IT.<br><strong>Different domain boundary.</strong></p>
  </div>
</div>

<div class="foundation-outcome"><i></i><span>CONTEXT + CONTROL + FEEDBACK</span><i></i></div>

<div class="slide-id">08</div>

<!--
<b>Co konkrétně je zapotřebí?</b><br>
Nemůžeme konkurovat IT. Musíme se přizpůsobit. Nemůžeme trénovat naše vlastní modely ani vytvářet náš vlastní harness.

[CLICK]1. <b>Chybějící znalost domény, kterou LLM nejsou trenovány. B&R + OEM</b>

[CLICK]2. <b>Kontext projektu. Model by měl být schopen číst soubory v projektu a porozumět jejich vzájemným vztahům. B&R</b>

[CLICK]3. <b>Zdrojový kód, HMI, konfigurace, bezpečnost atd. by měly být kontrolovány verzí. B&R</b>

[CLICK]4. <b>Musíme dodat nástroje nezbytné pro zavření feedback loopu na výzkum, ladění, testování a nasazení. B&R</b>

[CLICK]5. <b>Musíme definovat některé pokyny (guardrails) pro to, jak může a smí agent pracovat v AS projektu. Např: vždy aktualizuj pkg-soubor, přidej soubory do textsystému atd.  B&R + OEM   </b>

Přechod: Jakmile bude základ na místě, můžeme uzavřít smyčku průmyslového inženýrství.
-->

---
layout: default
class: agent-loop-slide
---

<div class="kicker">JOURNEY · 04 MIN</div>

# The path<br><span class="accent">Going forward</span>

<div class="strategy-shift" aria-label="B&amp;R strategy shift from custom models to an open platform">
  <section class="strategy-shift-side custom-model" v-click>
    <div class="strategy-shift-label"><span>THEN</span><strong>BUILD THE MODEL AND THE HARNESS</strong></div>
    <h2>AS-Copilot + AS-Code <span>pretrain + fine-tune</span></h2>
    <div class="strategy-shift-costs">
      <div><span>01</span><p><b>Expensive to build</b><small>resources, compute, and time</small></p></div>
      <div><span>02</span><p><b>Outdated quickly</b><small>a new model arrives before release</small></p></div>
      <div><span>03</span><p><b>Overcomplete by design</b><small>extra data can increase hallucination</small></p></div>
      <div><span>04</span><p><b>Fine-tuning to maintain</b><small>new data, evaluations, and retraining</small></p></div>
      <div><span>05</span><p><b>Locked to one model</b><small>never the best fit for every use case</small></p></div>
      <div><span>06</span><p><b>Requires B&amp;R hosting</b><small>the customer cannot choose the IP trust boundary</small></p></div>
    </div>
  </section>

  <div class="strategy-shift-pivot" v-click>
    <span>STRATEGY SHIFT</span>
    <mdi-arrow-right />
    <strong>Own the<br>engineering layer.</strong>
  </div>

  <section class="strategy-shift-side open-platform" v-click>
    <div class="strategy-shift-label"><span>NOW</span><strong>INTEGRATION OF YOUR CHOICE</strong></div>
    <h2>Open platform <span>any LLM / harness / IDE</span></h2>
    <div class="strategy-shift-stack">
      <div><span>CONTEXT ENGINEERING</span><small>current B&amp;R and customer knowledge</small></div>
      <i>+</i>
      <div><span>HARNESS ENGINEERING</span><small>tools, workflows, tests, and approvals</small></div>
    </div>
    <div class="strategy-shift-benefits">
      <div><mdi-bridge /><p><b>Portable as models evolve</b><small>let specialist providers lead model and harness innovation</small></p></div>
      <div><mdi-account-check-outline /><p><b>Customer choice stays visible</b><small>model, provider, hosting, data policy, and IP trust boundary</small></p></div>
    </div>
  </section>
</div>

<div class="strategy-shift-footer" v-click>
  <span>OUR DIFFERENTIATOR</span>
  <strong>B&amp;R owns the bridge.</strong>
  <small>Customers choose the model, harness, and trust boundary.</small>
</div>

<div class="slide-id">09</div>

<!--
<b>Naše strategie se změnila</b> a možná nebylo tak jasné, kam vlastně teď míříme. Již nebudeme předtrénovat nebo dolaďovat svůj vlastní model jako uzavřený AS-Copilot ekosystém. <b>To byla jednou správná volba</b>, protože modely nebyly schopny programovat PLC. To se změnilo!

[CLICK]
Naštěstí:
<b>Protože je to drahé a pomalé stavět </b>

<b>Model riskuje, že bude zastaralý před vydáním, </b>

a <b>nadměrně kompletní tréninkový soubor</b> může dát modelu více znalostí, než jaké jednotlivý zákazník potřebuje, a skončit s halucinacemi. Co když používám pouze X20?

K tomu všemu přidejte <b>průběžné ladění, vyhodnocení a údržbu.</b>

<b>Uzamčeme se na jednu model,</b> ačkoli různé úkoly vyžadují různé modely, a

<b>B&R-hostovaný model</b> omezuje zákazníkovi výběr dodavatele AI a může dokonce vést ke konfliktům s jeho směrnicemi o duševním vlastnictví.

[CLICK]
Co tedy děláme?

[CLICK]
Naše platforma je již otevřená a textová. <b>Proto můžeme vytvořit trvalejší hodnotu pomocí kontextového inženýrství a harnessového inženýrství s modely a harnessy, které již existují a které přijdou v budoucnosti:</b>

[CLICK]
B&R by měla vlastnit most / integraci a hranici domény, ne všechny vrstvy AI stacku. Pak můžeme nejlepší nové technologie, aniž by musel zákazník koupit uzavřený a zastaralý B&R ekosystém.

Přechod: To je směr, na kterém nyní dále stavíme a který nám zde v Dánsku otevřel možnost přispět například k nezbytné integraci.
-->

---
layout: default
class: takeaway-slide
---

<div class="kicker">WHY IT MATTERS · 02 MIN</div>

# Why care about<br><span class="accent">Agentic Engineering?</span>

<div class="why-care-layout">
  <section class="abstraction-panel" aria-label="Agentic Engineering as a new software abstraction layer">
    <div class="why-care-label"><span>THE SHIFT</span><strong>ANOTHER ABSTRACTION LAYER</strong></div>
    <div class="abstraction-ladder">
      <div class="abstraction-step"><span>01</span><div><b>Machine code</b><small>hardware instructions</small></div></div>
      <div class="abstraction-step"><span>02</span><div><b>Compiler</b><small>translate intent into code</small></div></div>
      <div class="abstraction-step"><span>03</span><div><b>Frameworks</b><small>compose reusable systems</small></div></div>
      <div class="abstraction-step is-current"><span>04</span><div><b>Agentic workflow</b><small>intent + context + tools + feedback</small></div></div>
    </div>
    <div class="abstraction-caption"><span>THE COMPETITIVE EDGE</span><strong>Master it early.<br>Or be outpaced.</strong></div>
  </section>

  <section class="why-care-list" aria-label="Reasons to care about Agentic Engineering">
    <div class="why-care-list-head"><span>WHY CARE NOW</span><small>the advantage moves to the workflow</small></div>
    <div class="why-care-item" v-click><span>01</span><div><b>It is the next abstraction layer</b><small>Learn to master it, or be outpaced by those who do.</small></div></div>
    <div class="why-care-item" v-click><span>02</span><div><b>It is the future of software development</b><small>Whether we like it or not, agentic workflows are joining the stack.</small></div></div>
    <div class="why-care-item" v-click><span>03</span><div><b>Knowledge becomes part of the system</b><small>Store expertise in workflows, not only in people.</small></div></div>
    <div class="why-care-item" v-click><span>04</span><div><b>Productivity can finally buy quality</b><small>Reinvest implementation speed in tests, review, and evidence.</small></div></div>
    <div class="why-care-item" v-click><span>05</span><div><b>Agility and profitability</b><small>Ramp up or down as needed; profit depends less on one perfect team.</small></div></div>
  </section>
</div>

<div class="why-care-footer" v-click><span>THE PAYOFF</span><strong>More agility. More quality. More resilient profit.</strong></div>

<div class="slide-id">10</div>

<!--
Zakončíme úvod shrnutím:
Proč je to zajímavé? Proč byste měli investovat svůj čas do AE?

[CLICK]
1. Je třeba si uvědomit, že AI je dalším přirozeným abstraktním vrstvou. Ti, kteří umějí AI efektivně používat, budou kdykoli překonávat ty, kteří to nezvládnou! Nebudeme nezaměstnaní, jen posuneme zaměření výše po žebříku abstrakce. Ne abychom byli líní, ale abychom dosáhli více ve světě, který očekává více.

[CLICK]
2. Ať už milujete AI nebo máte plnou skepsi, musíte uznat, že se stalo součástí technologického stacku a je tu, aby zůstala. Osobně si myslím, že být inženýr se stalo 100krát zábavnější. Děláme neuvěřitelné věci a překvapuje nás to každý den.

[CLICK]
3. Znalosti se ukládají v systému místo v jednotlivcích. Systém nemusí na dovolenou, na mateřskou, nemůže být nemocný nebo (Bůh chraň) podat výpověď.

[CLICK]
4. Máme možnost znovu investovat svůj čas v dosažení lepší kvality a kontinuálním optimalizací, která vede k větší autonomii a větší důvěryhodnosti.

[CLICK]
5. Naše oddělení se stane mnohem agilnější a odolnější. To se škáluje podle potřeby. Ne jen podle lidí.

Řekl jsem na začátku, že AI přednášky téměř vždy slibují zázraky a toto mělo být jiné??. Omlouvám se, pokud se mi to dosud nepovedlo.

[CLICK]
Neslibujeme úspěch. Chceme odstranit bariéry, které vám mohou stát v cestě k úspěchu s AI a DevOps.

Přechod: Konec úvodu.
-->

---
layout: default
class: devops-cover ai-workshop-cover dark-slide
---

<div class="devops-chapter">01</div>

<div class="kicker">WORKSHOP 01 · 60 MIN</div>
<div class="part-label">LARS JENSEN · AUTOMATION ENGINEER</div>

# It's all about<br><span class="accent">the workflow</span>

<p class="devops-cover-copy">The model proposes. The harness provides context and feedback. The workflow governs.</p>

<div class="devops-spine" v-motion :initial="{ opacity: 0, y: 18 }" :enter="{ opacity: 1, y: 0, transition: { delay: 300 } }">
  <div><span>01</span><b>PLAN</b><small>What and how</small></div>
  <i></i>
  <div><span>02</span><b>IMPLEMENT</b><small>According to guardrails</small></div>
  <i></i>
  <div><span>03</span><b>TEST</b><small>Validate the result</small></div>
  <i></i>
  <div><span>04</span><b>APPROVE</b><small>What is being deployed</small></div>
</div>


<div class="slide-id">11</div>

<!--
Než přejdeme na další bod programu:

- Máte pro mě otázky?

1. Kolik z vás používá AI-agenty jako denní a nezbytný nástroj pro vývoj software?
2. Kolik z vás používá DevOps principy ve vašem vývoji software?
 

Nejdůležitější není AI model ani agent. Je to workflow.

Model se dá vyměnit. Harness se dá změnit. Ale workflow definuje, jak se nápad stane ticketem, jak se řešení implementují, revidují a testují a kdo nakonec může výsledek schválit.

Je to živý engineering-systém. Musí být spravován pomocí verzí, měřen, udržován a vylepšován, přesně jako ostatní části vaší platformy.
-->

---
layout: default
class: maturity-compare-slide dark-slide
---

<figure class="vibe-coder-visual">
  <img src="/vibe-coder.png" alt="Vibe coder working at an unpredictable bottle line">
</figure>

<!--
Jak starý je pojem vibe-coding ? (únor 2025)

Fenomén, který se objevil přibližně před 1,5 rokem. Popište, co chcete, a opakujte to, dokud nebudete spokojeni.

Vibe coding může být efektivní pro učení a prototypy. Sami jsme hodně vibecodovali. Ne na vašich strojích samozřejmě ;) Ale pro rychlé interní nástroje, pro POC a pro ladění není nic špatného na tom, jen se pustit bez plánu.

Ale pro skutečné stroje, které musí splňovat spoustu požadavků, to zřídka bývá dobrý proces.

Když to postavíme proti "Agentic Engineering", je to proto, aby se ukázalo, že AI není kouzlo. Musíme jej držet v rukou stále a vlastnit proces. AI agenti nejsou determinističní (stejně jako lidé). Potřebují vedení (ve formě guardrails) kontrolních bodů kvality, které umožní, aby proces mohl pokračovat.

Pokud neřídíte proces, ztratíte přehled.

Na stroji není "vypadá to správně" kritérium úspěchu.
V IT možná není tolik problém, když je web nedostupný 5 minut, ale v OT není jedno, když se do pomerančového džusu dostanou kovové piliny.

-->

---
layout: default
class: use-case-slide dark-slide
---

<div class="status-badge direction">USE CASE · BOUNDED FEATURE</div>
<div class="kicker">FEATURE REQUEST · 03 MIN</div>

# Recover the axis fault.<br><span class="accent">Resume the batch.</span>

<div class="use-case-layout">
  <div class="use-case-brief">
    <div class="use-case-intent">
      <span>FEATURE REQUEST</span>
      <p>When the conveyor axis faults, stop cleanly, clear every uncapped bottle off the conveyor as reject, keep the produced count, and resume the same 100-bottle batch.</p>
    </div>
    <div class="use-case-contract">
      <div><span>01</span><b>OBSERVE</b><small>Abort is visible and the counter holds its value.</small></div>
      <div><span>02</span><b>CLEAR</b><small>Reject every uncapped bottle, empty or filled.</small></div>
      <div><span>03</span><b>RESUME</b><small>Start again and resume counting from the held value.</small></div>
      <div><span>04</span><b>PROVE</b><small>Complete the 100 batch with state and logbook evidence.</small></div>
    </div>
  </div>

  <div class="use-case-machine">
    <BottleConveyor interactive />
    <div class="use-case-machine-caption"><span>INTERACTIVE CONTROLLER</span><b>E-STOP → CLEAR → START</b></div>
  </div>
</div>

<div class="use-case-bridge" v-click>
  <div><span>THE WORKSHOP QUESTION</span><b>How can an agent implement this without becoming the spec, tester, and approver?</b></div>
  <mdi-arrow-right />
  <strong>Build the workflow</strong>
</div>

<div class="slide-id">12</div>

<!--
Zkusme se podívat na konkrétní příklad, který budeme v průběhu workshopu řešit.

<b>Feature request:</b> V případě poruchy osy dopravníku se stroj musí řízeně zastavit. Funkce „Clear“ musí odstranit všechny láhve, které ještě nebyly uzavřeny – bez ohledu na to, zda jsou prázdné nebo plné – a tyto láhve se započítávají jako zmetky. Počítadlo si zachová svou hodnotu a dávka pokračuje od stejného čísla jako na začátku, dokud nebude dokončeno 100 lahví.

Ukažte chybu a požadovaný výsledek, ale zatím nevysvětlujte řešení. Místo toho položte pro workshopu: <b>Jak můžeme delegovat implementaci agentovi, aniž by se agent stal tvůrcem specifikace, testerem a schvalovatelem? </b>

Zbytek workshopu staví na této odpovědi: MCP poskytuje znalosti, AS CLI provádí a sleduje, dovednosti a ochranná opatření řídí práci, testy poskytují důkazy a lidé spolu s kontrolními body rozhodují, zda může změna pokračovat.

[CLICK]
Přechod: Aby to bylo možné, musí mít agent připojení k Automation Studio, Automation Runtime a doménové znalosti, které umožní uzavřít feedback loop.
-->

---
layout: default
class: bridge-slide dark-slide
---

<div class="kicker">THE BRIDGE · 03 MIN</div>

# The Automation Studio<br><span class="accent">Agentic Bridge</span>

<figure class="agentic-bridge-visual" v-motion :initial="{ x: -170, y: 100, scale: 1.45 }" :click-1="{ x: 0, y: 0, scale: 0.76, transition: { duration: 650, ease: 'easeInOut' } }">
  <img src="/agentic-bridge.png" alt="Automation Studio Agentic Bridge">
</figure>

<div class="architecture" v-click v-motion :initial="{ opacity: 0 }" :click-1="{ opacity: 1, transition: { duration: 500 } }">
  <div class="architecture-top">
    <div class="architecture-top-copy">
      <mdi-application-braces-outline />
      <div><b>POPULAR HARNESSES + MODELS</b><small>bring your preferred runtime. API or selfhosted (On-prem or cloud)</small></div>
    </div>
    <div class="architecture-top-logos" role="img" aria-label="GitHub Copilot, Claude Code, Codex and Cursor">
      <span class="harness-logo copilot" title="GitHub Copilot"><simple-icons-githubcopilot aria-hidden="true" /></span>
      <span class="harness-logo claude" title="Claude Code"><simple-icons-claudecode aria-hidden="true" /></span>
      <span class="harness-logo codex" title="Codex"><simple-icons-openai aria-hidden="true" /></span>
      <span class="harness-logo cursor" title="Cursor"><simple-icons-cursor aria-hidden="true" /></span>
    </div>
  </div>
  <div class="architecture-connectors" v-click="2"><i></i><i></i><i></i></div>
  <div class="architecture-pillars" v-click="2">
    <div class="pillar">
      <span>01 · WORKFLOW</span>
      <img class="pillar-bridge-logo" src="/agentic-bridge-logo.png" alt="Agentic Bridge logo">
      <b>Instructions<br>hooks & skills</b>
    </div>
    <div class="pillar">
      <span>02 · KNOWLEDGE</span>
      <img class="pillar-bridge-logo" src="/agentic-bridge-logo.png" alt="Agentic Bridge logo">
      <b>B&amp;R context<br>through MCP</b>
    </div>
    <div class="pillar">
      <span>03 · EXECUTION</span>
      <img class="pillar-bridge-logo" src="/agentic-bridge-logo.png" alt="Agentic Bridge logo">
      <b>AS CLI<br>do + observe</b>
    </div>
  </div>
  <div class="architecture-connectors architecture-lower-connectors" v-click="3"><i></i><i></i><i></i></div>
  <div class="architecture-bases" v-click="3">
    <div class="architecture-base">
      <img class="architecture-base-logo automation-studio-logo" src="/automation-studio-logo.png" alt="Automation Studio logo"><span>Automation Studio</span>
    </div>
    <div class="architecture-base">
      <img class="architecture-base-logo domain-knowledge-logo" src="/domain-knowledge-logo.png" alt="Domain knowledge logo"><span>Domain Knowledge</span>
    </div>
    <div class="architecture-base">
      <img class="architecture-base-logo ar-sim-logo" src="/ar-sim-logo.png" alt="AR / ArSim controller"><span>AR / ArSim</span>
    </div>
  </div>
</div>

<div class="slide-id">13</div>

<!--
Co tedy můžeme nabídnout, abychom odpověděli na otázku?

Pokud se podíváte na LinkedIn nebo otevřete naši webovou stránku, uvidíte  marketingovou kampaň pro: Automation Studio Agentic Bridge. Několik lidí mě kontaktovalo a ptalo se, co to je. Doufám, že už teď máte představu, ale i přesto, že to není zcela definitivně definováno nebo vydáno (AS6.9), pojďme si to projít.

[CLICK]
Agentic Bridge představuje integraci doménových znalostí a nástrojů z jakéhokoli agenta (tj. z jakéhokoli harnessu s jakýmkoli modelem)

[CLICK]
<b>Skládá se</b> z pokynů, skills a hooks pro vedení agenta při práci na AS projektu


<b>Skládá se</b> z MCP serveru, který může poskytovat doménovou znalost agentovi o: B&R produktech, Automation Studio, Structured Textu, AS-Help, anonymizovaných support ticketech, prodejních upozorněních, manuálech, release notes atd. Tento MCP server je již nyní dostupný a je to oficiální B&R MCP server.

<b>Skládá se z rozhraní příkazového řádku pro Automation Studio</b>: CLI jsme postavili zde v Dánsku. Zpočátku jako neoficiální produkt, ale nyní jako integrovanou součást Automation Studio. CLI zpřístupňuje řadu funkcí agentovi, takže může budovat projekt, simulovat, číst/psát proměnné, číst logbook atd.

[CLICK]
Samozřejmě nejste omezeni na dovednosti, MCP a nástroje, které jsou součástí Agentic Bridge. Stále můžete samozřejmě využívat tisíce existujících dovedností, MCP serverů a CLI a samozřejmě si vytvářet vlastní, které propojují znalosti dané domény nebo systémy, ke kterým chcete přistupovat.

přechod: Kolik z vás ví, co je MCP server?

-->

---
layout: default
class: mcp-basics-slide dark-slide
---

<div class="kicker">MODEL CONTEXT PROTOCOL · 04 MIN</div>

# MCP - the semantic<br><span class="accent">tool API for Agents</span>

<div class="mcp-architecture" role="img" aria-label="An MCP server exposes tools and resources. The available servers are described in a manifest inside the LLM context window, where the agent can decide whether a tool is useful for the current task.">
  <section class="mcp-server-column" v-click="1">
    <div class="mcp-step-label">01 · EXPOSE</div>
    <div class="mcp-server-stack">
      <div class="mcp-server-card mcp-github-card">
        <div class="mcp-server-heading"><simple-icons-github class="mcp-github-mark" aria-hidden="true" /><b>GITHUB MCP</b><span class="mcp-transport-badge remote">REMOTE · HTTPS</span></div>
        <p class="mcp-endpoint">https://api.githubcopilot.com/mcp/</p>
        <div class="mcp-capability-group">
          <span class="mcp-capability-label"><mdi-wrench-outline /> TOOLS</span>
          <div class="mcp-chip-row"><span>search_repositories</span><span>create_issue</span></div>
        </div>
        <div class="mcp-capability-group">
          <span class="mcp-capability-label"><mdi-file-document-outline /> RESOURCES</span>
          <div class="mcp-chip-row"><span>repository_content</span></div>
        </div>
      </div>
      <div class="mcp-server-card mcp-as-help-card">
        <div class="mcp-server-heading"><mdi-book-open-page-variant-outline class="mcp-as-help-mark" aria-hidden="true" /><b>AS-HELP MCP</b><span class="mcp-transport-badge local">LOCAL · STDIO</span></div>
        <p class="mcp-endpoint">as-help-server.exe · AS6 Help</p>
        <div class="mcp-capability-group">
          <span class="mcp-capability-label"><mdi-wrench-outline /> TOOLS</span>
          <div class="mcp-chip-row"><span>search_help</span><span>get_page_by_id</span></div>
        </div>
        <div class="mcp-capability-group">
          <span class="mcp-capability-label"><mdi-message-text-outline /> PROMPTS</span>
          <div class="mcp-chip-row"><span>help_search</span><span>help_details</span></div>
        </div>
      </div>
    </div>
  </section>

  <div class="mcp-flow-arrow" aria-hidden="true" v-click="2"><span>discover</span><i></i></div>

  <section class="mcp-context-column" v-click="2">
    <div class="mcp-step-label">02 · DESCRIBE</div>
    <div class="mcp-context-card">
      <div class="mcp-context-heading"><span>MCP Manifest</span><small>connected MCPs + tools</small></div>
      <div class="mcp-manifest">
        <div class="mcp-manifest-heading"><b>TOOL CONTRACTS</b><span>INPUT → RETURNS</span></div>
        <div class="mcp-tool-server github"><simple-icons-github aria-hidden="true" /><b>GITHUB · REMOTE</b></div>
        <div class="mcp-tool-contract">
          <div class="mcp-tool-title"><strong>search_repositories</strong><span>READ</span></div>
          <div><b>in</b> query · optional org/owner qualifiers</div>
          <div><b>out</b> matching repos: name, owner, description, URL</div>
        </div>
        <div class="mcp-tool-contract">
          <div class="mcp-tool-title"><strong>create_issue</strong><span class="is-write">WRITE</span></div>
          <div><b>in</b> owner, repo, title · optional body/labels/assignees</div>
          <div><b>out</b> issue number, state, URL</div>
        </div>
        <div class="mcp-tool-server as-help"><mdi-book-open-page-variant-outline aria-hidden="true" /><b>AS-HELP · LOCAL</b></div>
        <div class="mcp-tool-contract">
          <div class="mcp-tool-title"><strong>search_help</strong><span>READ</span></div>
          <div><b>in</b> query · optional limit/category</div>
          <div><b>out</b> page IDs, titles, breadcrumbs, previews</div>
        </div>
        <div class="mcp-tool-contract">
          <div class="mcp-tool-title"><strong>get_page_by_id</strong><span>READ</span></div>
          <div><b>in</b> page_id · optional text/html/breadcrumb</div>
          <div><b>out</b> full page text, metadata, online URL</div>
        </div>
      </div>
      <div class="mcp-context-note"><mdi-information-outline /> Tool definitions are discoverable &mdash; the agent retrieves each tool's input schema before it calls it.</div>
    </div>
  </section>

  <div class="mcp-flow-arrow" aria-hidden="true" v-click="3"><span>reason</span><i></i></div>

  <section class="mcp-decision-column" v-click="3">
    <div class="mcp-step-label">03 · CHOOSE</div>
    <div class="mcp-decision-card">
      <div class="mcp-agent-mark"><mdi-brain /> <span>AGENT DECISION</span></div>
      <p>Task: decode ACOPOS error <strong>7070</strong> from the logbook</p>
      <strong>CALL search_help</strong>
      <div class="mcp-decision-options"><span class="is-call">CALL TOOL</span><i>or</i><span>ANSWER</span></div>
      <small>The model chooses a useful capability, or answers directly if the context is enough.</small>
    </div>
  </section>
</div>

<div class="mcp-takeaway" v-click="4"><span>MCP is not the model.</span><strong>It makes capabilities discoverable and callable through a shared semantic contract.</strong></div>

<div class="slide-id">14</div>

<!--
MCP je zkratka pro Model Context Protocol (Model Context Protocol). Představte si ho jako sémantické nástrojové API: server popisuje své nástroje a zdroje, aby je model mohl standardizovaným způsobem objevit a používat.

[CLICK]
<b>Příkladem by byl oficiální GitHub MCP server.</b>
Má kolem 47 nástrojů na vše od vytváření issues a PR, čtení repozitářů, slučování větví atd.


<b>Jako druhý příklad máme vlastní AS-Help MCP</b>. Je to lokální server, který prostřednictvím stdio poskytuje funkce pro vyhledávání v B&R Automation Studio help: search_help, get_categories, browse_section a get_page_by_id.

[CLICK]
Manifest není samotná data ani provádění. Poskytuje modelu katalog dostupných MCP serverů, jejich nástrojů s popisy a vstupními formáty v kontextu, ve kterém pracuje. Na základě úkolu si model může vybrat, aby zavolal search_help a vyhledal chybu ACOPOS 7070 v AS dokumentaci, create_issue k nahlášení chyby, nebo odpověděl bez nástroje.

[CLICK]
MCP server tedy zpřístupňuje své funkce přes standardní rozhraní, kterému agent rozumí
-->

---
layout: default
class: as-help-boot-slide dark-slide
---

<div class="kicker">AS-HELP MCP · FIRST BOOT · 03 MIN</div>

# AS-Help MCP:<br><span class="accent">index once, serve locally</span>

<div class="as-help-boot-grid">
  <figure class="as-help-boot-visual" v-click>
    <div class="as-help-image-frame"><img src="/as-help-mcp.png" alt="AS-Help MCP GitHub quick-start configuration for a local server"></div>
    <figcaption><span>LOCAL KNOWLEDGE CONNECTOR</span><b>br-automation-community/as-help-mcp</b><small>Rust server · installed Automation Studio help · LanceDB</small></figcaption>
  </figure>
  <section class="as-help-boot-process">
    <div class="as-help-process-heading"><span>FIRST BOOT</span><small>BUILD THE INDEX · THEN SERVE QUERIES</small></div>
    <div class="as-help-stage-list">
      <div class="as-help-stage" v-click>
        <span class="as-help-stage-number">01</span><mdi-file-tree-outline />
        <div><b>READ LOCAL HELP</b><small>Walk the installed AS Help HTML tree.</small></div>
        <strong>INGEST</strong>
      </div>
      <div class="as-help-stage" v-click>
        <span class="as-help-stage-number">02</span><mdi-database-search-outline />
        <div><b>BUILD FTS INDEX</b><small>Tokenize titles and content for keyword ranking.</small></div>
        <strong>RANK</strong>
      </div>
      <div class="as-help-stage" v-click>
        <span class="as-help-stage-number">03</span><mdi-map-marker-path />
        <div><b>PERSIST METADATA</b><small>Keep page_id, title, file_path, and breadcrumb_path.</small></div>
        <strong>ANCHOR</strong>
      </div>
      <div class="as-help-stage ready" v-click>
        <span class="as-help-stage-number">04</span><mdi-check-circle-outline />
        <div><b>FTS READY</b><small>Keyword search works while optional semantic loading continues.</small></div>
        <strong>SERVE</strong>
      </div>
    </div>
    <div class="as-help-index-record" v-click>
      <div class="as-help-record-heading"><span>SEARCH RECORD</span><small>metadata stays attached to the hit</small></div>
      <div class="as-help-record-grid"><code>page_id</code><b>&lt;returned page id&gt;</b><code>breadcrumb</code><span>Motion &gt; ... &gt; MC_BR_MoveAbsolute</span><code>preview</code><span>short desciption of the context</span></div>
    </div>
    <div class="as-help-query-flow">
      <div class="as-help-query-heading"><span>AGENT QUERY</span><strong>FTS · KEYWORD RANKING</strong></div>
      <div class="as-help-query-line"><code>search_help</code><span>query: "MC_BR_MoveAbsolute"</span></div>
      <div class="as-help-top-result"><b>#1</b><span>highest-ranked match</span><strong>page_id + breadcrumb + preview</strong></div>
      <div class="as-help-retrieve"><code>get_page_by_id</code><span>page_id</span><b>-&gt; full text + metadata + online URL</b></div>
    </div>
  </section>
</div>

<div class="as-help-boot-takeaway" v-click><span>THE PRO AND THE CON</span><strong>Only reflect what you have installed locally</strong> </div>

<div class="slide-id">15</div>

<!--
Rádi bychom propagovali náš vlastní AS-Help MCP, který je k dispozici na GitHubu. Myslíme si, že je MEGA dobrý!
Při prvním spuštění AS-Help MCP přečte lokální složku nápovědy Automation Studia a vytvoří index vyhledávání. Ukládá nejen hledaný text, ale také page_id, název, cestu k souboru a navigační cestu, aby bylo možné najít správnou stránku.

[CLICK]
[CLICK]
[CLICK]
[CLICK]
[CLICK]

FTS, fulltextové vyhledávání, je připraveno. <b>Sémantické vyhledávání může být později volitelná vrstva.</b>

Myslíme si, že FTS funguje tak dobře, že jsme vlastně nepoužívali embedding modely a vektorové databáze, ale můžete snadno přidat svůj vlastní embedding model a pak získat sémantické vyhledávání spolu s FTS. To může ušetřit tokeny a poskytnout přesnější vyhledávání, protože do vyhledávání vstupuje celý kontext, ne jen klíčová slova.

Důležité v toku agenta je, že search_help nepředstírá, že je celou odpovědí: vrací hodnocenou trefu s page_id, breadcrumb a krátkým náhledem.

[CLICK]


Agent pak používá page_id v get_page_by_id k načtení úplného textu, metadat a případně online-help URL. Je to jednoduchá, sledovatelná dvoustupňová smlouva: najděte nejlepší adresu, pak načtěte důkazy.

[CLICK]

Protože je projekt open source, lze jej snadno zkopírovat do jiných help systémů např. třetí strany. Neváhejte a udělejte to!

Myslíme si, že v mnoha věcech je výhodou, že MCP server má přístup POUZE k vaší lokální nápovědě, a tedy ne k technologiím, které nemáte nainstalované, nebo novějším verzím, které nepoužíváte. Samozřejmě nemůže používat celý katalog B&R jako data, ale pokud se má zabývat pouze vaším strojem, je to často i to nejlepší.

přechod: Pokud potřebujete nadměrně kompletní znalost, můžete použít oficiální B&R MCP server
-->

---
layout: default
class: mcp-image-pair-slide dark-slide
---

<div class="kicker">OFFICIAL B&amp;R MCP SERVER</div>

# Official B&R MCP<br><span class="accent">On B&R Community</span>

<div class="mcp-image-pair">
  <img src="/br-mcp.png" alt="B&R MCP server setup guidance on the B&R Community">
</div>

<div class="mcp-image-link">
  <mdi-link-variant /><a href="https://community.br-automation.com/t/release-2026-use-b-r-mcp-server-with-any-ai-assistant-using-jwt-from-as-code-6-7-github-copilot-continue-dev-more/11705" target="_blank">community.br-automation.com — Use B&amp;R MCP Server with any AI assistant (JWT from AS Code 6.7)</a>
</div>

<!--
Oficiální B&R MCP

Ten, který je součástí Agentic Bridge. Obsahuje více znalostí o B&R než jen nápovědu, ale má také určitá omezení.

1. Neodráží pouze produkty a knihovny, které používáte/máte nainstalovány, ale všechno, co je dostupné.

2. Je hostován na cloudové službě B&R. Vaše promptové zadání se odesílá z vašeho počítače, ale nezaznamenávají se ani neanalyzují.

3. Neposkytuje reference na všechny odpovědi, protože některá data nejsou dostupná jako PDF nebo help URL.

4. Je v Beta. Doporučujeme AS-Help, BR-Community MCP, dokud se nezlepší.


přechod: Jaké jsou další užitečné MCP servery?
-->

---
layout: default
class: br-role-slide
---

<div class="kicker">COMMUNITY CONNECTORS · 03 MIN</div>

# Practical knowledge<br><span class="accent">connectors</span>

<div class="br-role-stack">
  <a class="role-layer" href="https://github.com/br-automation-community/as-help-mcp" target="_blank" rel="noopener noreferrer" aria-label="Open AS-Help MCP on GitHub" v-click>
    <div class="role-number">01</div>
    <mdi-book-open-page-variant-outline />
    <div><span>B&amp;R COMMUNITY · GITHUB</span><b>AS-HELP MCP</b><small>search installed Automation Studio help</small></div>
    <div class="micro-status community role-link">GH REPO <mdi-open-in-new aria-hidden="true" /></div>
  </a>
  <a class="role-layer" href="https://github.com/br-automation-community/br-community-mcp" target="_blank" rel="noopener noreferrer" aria-label="Open B&amp;R Community MCP on GitHub" v-click>
    <div class="role-number">02</div>
    <mdi-forum-outline />
    <div><span>B&amp;R COMMUNITY · GITHUB</span><b>BR-COMMUNITY MCP</b><small>research B&amp;R community discussions</small></div>
    <div class="micro-status community role-link">GH REPO <mdi-open-in-new aria-hidden="true" /></div>
  </a>
  <a class="role-layer" href="https://learn.microsoft.com/microsoft-365/copilot/extensibility/work-iq/mcp/overview" target="_blank" rel="noopener noreferrer" aria-label="Open Work IQ MCP documentation on Microsoft Learn" v-click>
    <div class="role-number">03</div>
    <mdi-account-network-outline />
    <div><span>MICROSOFT · LEARN</span><b>WORK IQ</b><small>ground Microsoft 365 work context</small></div>
    <div class="micro-status direction role-link">MS LEARN <mdi-open-in-new aria-hidden="true" /></div>
  </a>
  <a class="role-layer" href="https://github.com/atlassian/atlassian-mcp-server" target="_blank" rel="noopener noreferrer" aria-label="Open the Atlassian MCP server on GitHub" v-click>
    <div class="role-number">04</div>
    <mdi-view-grid-outline />
    <div><span>ATLASSIAN · GITHUB</span><b>ATLASSIAN MCP</b><small>connect Jira and Confluence context</small></div>
    <div class="micro-status community role-link">GH REPO <mdi-open-in-new aria-hidden="true" /></div>
  </a>
  <a class="role-layer" href="https://github.com/github/github-mcp-server" target="_blank" rel="noopener noreferrer" aria-label="Open the official GitHub MCP server on GitHub" v-click>
    <div class="role-number">05</div>
    <simple-icons-github />
    <div><span>OFFICIAL · GITHUB</span><b>GITHUB MCP</b><small>read repos, issues, and pull requests</small></div>
    <div class="micro-status community role-link">GH REPO <mdi-open-in-new aria-hidden="true" /></div>
  </a>
  <a class="role-layer" href="https://github.com/figma/mcp-server-guide" target="_blank" rel="noopener noreferrer" aria-label="Open the Figma MCP server guide on GitHub" v-click>
    <div class="role-number">06</div>
    <mdi-vector-square />
    <div><span>FIGMA · GITHUB</span><b>FIGMA MCP</b><small>bring design context into engineering</small></div>
    <div class="micro-status community role-link">GH REPO <mdi-open-in-new aria-hidden="true" /></div>
  </a>
  <a class="role-layer" href="https://github.com/microsoft/playwright-mcp" target="_blank" rel="noopener noreferrer" aria-label="Open the Playwright MCP server on GitHub" v-click>
    <div class="role-number">07</div>
    <mdi-web-check />
    <div><span>MICROSOFT · GITHUB</span><b>PLAYWRIGHT MCP</b><small>drive and verify HMI in a real browser</small></div>
    <div class="micro-status community role-link">GH REPO <mdi-open-in-new aria-hidden="true" /></div>
  </a>
  <a class="role-layer" href="https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem" target="_blank" rel="noopener noreferrer" aria-label="Open the Filesystem MCP server on GitHub" v-click>
    <div class="role-number">08</div>
    <mdi-folder-open-outline />
    <div><span>MCP REFERENCE · GITHUB</span><b>FILESYSTEM MCP</b><small>read and write project files under policy</small></div>
    <div class="micro-status community role-link">GH REPO <mdi-open-in-new aria-hidden="true" /></div>
  </a>
</div>



<!--
Příklady relevantních MCP serverů:

přechod: Samozřejmě lze všechny tyto MCP servery používat ve vašich Agentic Engineering workflows, ale lze je také používat k jiným účelům!
-->

---
layout: default
class: support-agent-sequence-slide
---

<div class="support-agent-sequence">
  <img class="support-agent-frame" src="/support-agent-welcome.png" alt="B&R Support Agent welcome screen">
  <img class="support-agent-frame" src="/support-agent-chat.png" alt="B&R Support Agent chat response" v-click="1">
  <img class="support-agent-frame" src="/online-help.png" alt="B&R Automation Help documentation page" v-click="2">
</div>
<!--
<b>Příklad aplikace, kterou jsme vytvořili - B&R Support Agent</b>

Zde můžete připojit workspace, aby se agent mohl podívat do projektu.

Můžete nahrát soubory. Může to být například systémový dump nebo wireshark trace.

<b>Můžete mu dát pokyny:</b> Např. Když otázka obsahuje jméno zákazníka, vždy zkontroluj předchozí případy na Jira, nebo se vždy podívej na tuto sharepoint stránku, když jde o roboty Codian.

Nyní může použít své připojené MCP servery k vyhledání potřebné doménové znalosti.

- AS4 / AS6 help
- Atlassian (Jira tickety a confluence dokumentace)
- br-community mcp
- workIQ (sharepoint, teams kanály, support poštovní schránka)
- Revision history (vydaný firmware s release notes)

[CLICK]

Můžeme mu položit otázku a vidět, jak používá své nástroje.

A jak v tomto případě poskytuje odkaz přímo na online nápovědu.

[CLICK]

<b>USECASES:</b>

Existuje mnoho use case, kde jsme ušetřili obrovské množství času s takovým nástrojem.

1. Obecné vyhledávání v našich interních systémech
2. Ověření, že problém nebyl dříve vyřešen, než se pošle dál do centrály.
3. Nalezení složitých souvislostí mezi logy, kódem a předchozí historií.
<b>Našli jsme chyby, které bychom bez toho NIKDY nenašli!</b>

<b>Už není nutné, aby s podporou pomáhal nejlepší člověk ve firmě!</b>


přechod: To je to, co lze udělat se správnou doménovou znalostí. Ale co když musíme skutečně něco vyřešit na stroji?

<b>Pokud pauza, tak TEĎ!</b>
-->

---
layout: default
class: demo-slide dark-slide as-cli-slide
---

<div class="status-badge demonstrator">DEMONSTRATOR</div>
<div class="kicker">EXECUTION · 04 MIN</div>

# as cli:<br><span class="accent">action + observation</span>

<div class="demo-steps">
  <div v-click><span>01</span><b>BROWSE</b><small>as --help → command surface</small></div>
  <div v-click><span>02</span><b>PROJECT STATUS</b><small>name · config · cpu</small></div>
  <div v-click><span>03</span><b>SIM ENABLE</b><small>simulation on CPU</small></div>
  <div v-click><span>04</span><b>BUILD SIM</b><small>build + install to ARsim</small></div>
  <div v-click><span>05</span><b>PLC CONNECT</b><small>--ip 127.0.0.1</small></div>
  <div v-click><span>06</span><b>VAR READ</b><small>gProductionCount → value + type</small></div>
  <div v-click><span>07</span><b>VAR WRITE</b><small>gCmdClear → written</small></div>
  <div v-click><span>08</span><b>LOGBOOK READ</b><small>$arlogsys → error entries</small></div>
  <div v-click><span>09</span><b>BUILD PIP</b><small>offline install package</small></div>
</div>

<TerminalCli />


<div class="slide-id">16</div>

<!--
<b>Pokud pauza, tak TEĎ!</b>

`AS CLI` je rozhraní příkazového řádku, které může používat člověk, skript, automatizovaný test, CI pipeline i agent.

AS CLI je samotnou páteří Agentic Bridge a je to něco, <b>co jsme vyvinuli zde v Dánsku</b>. Je to víceméně kompletní rozhraní k Automation Studio 6 a umí spoustu stejných věcí, které se jinak musí provádět ručně v Automation Studio. <b>Kromě samotných runtime funkcí, na které se podíváme za chvíli, umí také přidávat knihovny, hardware, úkoly, HMI, konfigurace atd.</b> I když se samozřejmě jedná pouze o text, je spolehlivější použít stávající skriptovací engine za AS, aby bylo vše správně vloženo a nakonfigurováno s platnými parametry.

Otevírá Automation Studio v headless režimu (bez GUI) a připojuje se přímo k backendu v AS. Všechny funkce a stavy jsou dostupné přes json-rpc rozhraní, které usnadňuje stavbu dalších systémů na tomto základě. Pravděpodobně to bude také to, co využije naše oficiální rozšíření pro VS Code.

[CLICK]

Když jsme navrhovali CLI, bylo pro nás důležité, aby AI byla zohledněna už v návrhu. To znamená, že agent by měl být schopen sám zjistit, jak ho používat, aniž by ho bylo nutné instruovat jak.

Agent může kdekoli spustit --help, aby vyhledal informace o tom, jaké příkazy a jaké parametry může použít a co budou vracet.
[CLICK]

Může poskytnout status projektu, ke kterému je připojen

[CLICK]

Umí simulovat, ale také obsluhovat simulátor. Může například zrychlit nebo zpomalit čas. Tímto způsobem může zkoušet věci ve zpomaleném pohybu, nebo zrychlit čas, pokud má spustit test na velké dávce.

[CLICK]

Umí sestavit projekt buď pro fyzický hardware, nebo pro simulátor

[CLICK]

Připojit se k PLC nebo simulátoru

[CLICK]

Číst proměnné

[CLICK]

Psát proměnné

[CLICK]

Číst logbooky

[CLICK]

Vytvořit PIP balíček. ProjectInstallationPackage PIP (deployment artefakt)

přechod: Teď máme veškeré nástroje na místě, takže nám chybí jen instrukce a skills
-->

---
layout: default
class: skills-slide dark-slide
---

<div class="status-badge general">OPEN ECOSYSTEM</div>
<div class="kicker">AGENT WORKFLOWS · 02 MIN</div>

# <span class="accent">Skills</span>.sh

<SkillsEmbed />

<div class="slide-id">17</div>

<!--
Pokud znáte skills.sh vytvořené firmou Vercel, víte, že existuje opravdu hodně skills a že jsou dostupné pro naprostou většinu agentů.

Mnoho z nich je <b>stejně relevantních</b> pro automatizační projekt jako pro cokoliv jiného. A pokud používáte <b>principy DevOps</b>, nemusíte znovu vymýšlet kolo. Existují opravdu dobré skills pro všechny různé fáze.

Je super jednoduché je nainstalovat příkazem npx přímo z vašeho harness.

Nejpopulárnější skills jsou:
ukázat <b>grill-with-docs</b>

přechod: Ale nevyhnete se vytváření vlastních skills. Máte své vlastní požadavky, své vlastní principy a své vlastní standardy.
-->

---
layout: default
class: skill-matrix-slide dark-slide
---

<div class="kicker">SKILL DESIGN · 02 MIN</div>

# The four categories of<br><span class="accent">skills</span>

<div class="skill-axes">
  <div class="skill-axis"><mdi-lightbulb-auto-outline /><b>MODEL-INVOKED</b><small>discoverable — the agent loads it when the task needs it</small></div>
  <div class="skill-axis"><mdi-play-box-outline /><b>USER-INVOKED</b><small>invoked — you call it deliberately, like a saved prompt</small></div>
  <div class="skill-axis"><mdi-database-off-outline /><b>STATELESS</b><small>one shot, no memory between runs</small></div>
  <div class="skill-axis"><mdi-database-sync-outline /><b>STATEFUL</b><small>carries progress across turns and files</small></div>
</div>

<div class="skill-matrix">
  <article class="skill-quadrant" v-click>
    <span class="skill-tags">MODEL-INVOKED <i>·</i> STATELESS</span>
    <b>event-script skill for mappView</b>
    <small>Picked up automatically when writing HMI scripts for mappView.</small>
  </article>
  <article class="skill-quadrant" v-click>
    <span class="skill-tags">MODEL-INVOKED <i>·</i> STATEFUL</span>
    <b>domain-modeling skill</b>
    <small>Picked up automatically when discussing codebase terminology, consuming and editing a CONTEXT.md</small>
  </article>
  <article class="skill-quadrant" v-click>
    <span class="skill-tags">USER-INVOKED <i>·</i> STATELESS</span>
    <b>triage skill for GitHub issues</b>
    <small>You invoke it on a ticket. Same procedure every time, nothing carried over.</small>
  </article>
  <article class="skill-quadrant" v-click>
    <span class="skill-tags">USER-INVOKED <i>·</i> STATEFUL</span>
    <b>grill-with-docs skill</b>
    <small>You start it when describing a new feature. A CONTEXT.md and ADR.md is stored to document decisions for future runs.</small>
  </article>
</div>

<div class="skill-matrix-takeaway" v-click>
  <mdi-set-split /> <b>Model-invoked vs user-invoked</b> is about <i>how it is triggered</i><span>·</span><b>stateless vs stateful</b> is about <i>what it remembers</i>
</div>

<figure class="skill-invocation-shot" v-click>
  <img src="/skill-invocation.png" alt="SKILL.md frontmatter with disable-model-invocation set to true">
  <figcaption>One line in the frontmatter turns a <b>model-invoked</b> skill into a <b>user-invoked</b> skill</figcaption>
</figure>

<div class="slide-id">18</div>

<!--
Skills spadají do dvou nezávislých dimenzí.

<b>První dimenze</b> je, jak se aktivují.

<b>Model-invoked skill</b> je přítomna a načtena samotným agentem, když se agent domnívá, že obsah je relevantní pro daný úkol.

<b>User-invoked skill</b> voláte vědomě, jako uložený prompt pro provedení určité akce nebo rutiny.


<b>Druhá dimenze</b> je, zda si pamatují něco z jednoho běhu na druhý. Stateless skill (Bezstavová dovednost ) se spustí jednou a zapomene. Stateful skill (Stavová dovednost ) si buduje a znovu využívá předchozí výstupy v budoucích sezeních.


Tyto dvě dimenze se volně kombinují, takže vzniknou čtyři typy skills. Volte vědomě, když navrhujete nový skill. Zde je několik příkladů:

[CLICK]
Event script skill pro MappView. Je <b>model-invoked</b>, protože agent by měl být schopen sám vyvolat informace o event scriptech, pokud má opravit nebo vytvořit nové skripty. Je <b>stateless</b>, protože nevytváří žádné informace pro budoucí volání.

[CLICK]
Domain-modelling skill je také <b>model-invoked</b>. Agent ho volá, když se diskutuje o doménově specifických termínech. Agent by měl rozumět žargonu a dokumentovat ho <b>(stateful)</b>, aby se v budoucnu nepletl. Pokud například issue obsahuje slovo "filler" z příkladu, skill prověří, zda je součástí souboru context.md a co to případně je. Pokud tam není, prověří to / zeptá se, a poté to vloží do souboru context.md.

[CLICK]
Triage skill. Ten je <b>user-invoked</b>, protože pouze my rozhodujeme, zda má GitHub issue projít přepracováním. Může se stát, že jsme dostali nahlášenou chybu. Uživatel vytvořil GH issue, ale zapomněl důležité detaily, které agent potřebuje, aby mohl v práci pokračovat. Mohlo by jít o to, že uživatel napsal: "Nedostávám žádné alarmy, když selže servoosa." Ale jaký alarm chceme mít? Co by měl říkat? Proto na to uděláme triage, abychom to dostali na úroveň, kdy to můžeme delegovat agentovi.

[CLICK]
grill-with-docs. Jeden z nejpopulárnějších skills. Pokračuje v diskusi s uživatelem, dokud nedojde ke společnému porozumění. Pokud obsahuje terminologii nebo zvláštní designové požadavky, jsou zaznamenány pro budoucí sezení.

[CLICK]
Jak se skill načte a jak si do budoucna ukládá informace o sobě.

[CLICK]

přechod: Proč si musíme sami vytvářet skills?
-->

---
layout: default
class: guardrails-slide dark-slide
---

<div class="kicker">ENGINEERING CONTRACT · 05 PRINCIPLES</div>

# Guardrails for<br><span class="accent">useful speed</span>

<p class="guardrails-lead">Principles keep agent output compatible with the machine, the operator, and the release process.</p>

<div class="guardrails-grid">
  <article class="guardrail-principle" v-click>
    <div class="guardrail-head"><span>01</span><mdi-file-tree-outline /></div>
    <h2>Architecture</h2>
    <p>Bound the agent by modules, interfaces, and ownership.</p>
    <small>CLEAR DEPENDENCIES</small>
  </article>
  <article class="guardrail-principle" v-click>
    <div class="guardrail-head"><span>02</span><mdi-text-box-outline /></div>
    <h2>Naming conventions</h2>
    <p>How to name: vars, globals, types, io, safety, alarms, recipe</p>
    <small>CONSISTENT + SEARCHABLE</small>
  </article>
  <article class="guardrail-principle" v-click>
    <div class="guardrail-head"><span>03</span><mdi-test-tube /></div>
    <h2>TDD</h2>
    <p>Specify behavior first; make red, green, refactor routine.</p>
    <small>PROVE THE CHANGE</small>
  </article>
  <article class="guardrail-principle" v-click>
    <div class="guardrail-head"><span>04</span><mdi-monitor-dashboard /></div>
    <h2>HMI Design</h2>
    <p>Expose state, intent, alarms, and recovery to the operator.</p>
    <small>OPERATOR CAN ACT</small>
  </article>
  <article class="guardrail-principle" v-click>
    <div class="guardrail-head"><span>05</span><mdi-shield-check-outline /></div>
    <h2>Safety rules</h2>
    <p>Separate safety from optimization. Stop on uncertainty.</p>
    <small>HUMAN APPROVAL</small>
  </article>
</div>

<div class="guardrails-footer" v-click>
  <span>GUARDRAILS TURN GOOD INTENT INTO CHECKABLE ENGINEERING</span>
  <strong>READ · CHANGE · VERIFY</strong>
</div>

<div class="slide-id">19</div>

<!--
Až se stanete zdatnými v psaní skills a instrukcí (samozřejmě existují skills, které jsou dobré na psaní skills nebo souborů agent.md), můžete začít navrhovat své guardrails.

Guardrails jsou rozhodnutí, která chceme vidět odražená v kódu, testech a review.

[CLICK]
Může jít o požadavky na architekturu

[CLICK]
Konvence pojmenování

[CLICK]
Testovací strategie

[CLICK]
HMI a GUI design

[CLICK]
Principy bezpečnosti

[CLICK]
přechod: Guardrails pomáhají vést agenta při specifikaci, implementaci a review. Ale co testy?
-->

---
layout: default
class: testing-slide dark-slide
---

<div class="kicker">TDD + EVALUATION · 03 MIN</div>

# Tests are the<br><span class="accent">sensor system</span>

<div class="baseline-banner" >
  <mdi-radar /> <span>TEST-DRIVEN RULE</span>
  <b>Clear acceptance criteria give agents a fast signal. Establish the regression baseline <strong>before</strong> delegating feature work.</b>
</div>

<div class="test-pyramid">
  <div class="test-level hil" ><span>04</span><b>HIL / PHYSICAL</b><small>where risk + fidelity require it</small></div>
  <div class="test-level arsim" ><span>03</span><b>ARSIM / SMOKE</b><small>controlled application behavior</small></div>
  <div class="test-level integration" ><span>02</span><b>INTEGRATION</b><small>interfaces + module behavior</small></div>
  <div class="test-level unit" ><span>01</span><b>UNIT</b><small>local logic</small></div>
</div>

<div class="two-oracles">
  <div v-click>
    <mdi-check-circle-outline />
    <span>PRODUCT TESTS</span>
    <b>Does machine behavior satisfy the requirement?</b>
  </div>
  <div v-click>
    <mdi-robot-confused-outline />
    <span>AGENT EVALUATIONS</span>
    <b>Did it use tools, obey policy, escalate, and stop?</b>
  </div>
</div>



<div class="slide-id">20</div>

<!--
Nebudu o testech mluvit příliš mnoho. Mads se do toho pustí mnohem víc za chvíli.

Je však důležité říci, že testy jsou při kódování s agenty nepostradatelné. AI není deterministická, takže potřebujeme spolehlivé brány, které dokáží validovat náš software. Testy fungují jak jako zpětná vazba pro agenta, tak i jako dokumentace pro nás, kteří musíme schválit změnu.

Psát testy je dnes nekonečně jednodušší, než to bylo před AI. Ale AI agent se nemůže jen tak testovat sám.

[CLICK]

Product testy:
Test softwaru / stroje:
Fungují věci skutečně tak, jak chceme?

[CLICK]

Agent Evaluation:
Test workflow / systému:
Dělal agent to, co bylo domluveno?

Potřebujeme obojí. Agent může proces správně dodržet, a přesto udělat chybu. Naopak změny mohou náhodou fungovat, i když agent po cestě porušil pravidla.

přechod:

-->

---
layout: default
class: enforcement-slide
---

<div class="kicker">TRUST · 02 MIN</div>

# Steering guides.<br><span class="accent">Gates decide.</span>

<div class="control-compare">
  <div class="steering-side" v-click>
    <div class="control-head"><mdi-sign-direction /><span>STEERING / GUARDRAILS</span></div>
    <div class="control-signal probability"><i></i><i></i><i></i><i></i><i></i></div>
    <ul>
      <li>Instructions + examples</li>
      <li>Plans + retrieved context</li>
      <li>Influences the next action</li>
      <li>Can drift in noisy context</li>
    </ul>
    <small>PROBABILISTIC GUIDANCE</small>
  </div>
  <div class="enforcement-side" v-click>
    <div class="control-head"><mdi-shield-lock-outline /><span>DETERMINISTIC ENFORCEMENT</span></div>
    <div class="control-signal gate"><span>INPUT</span><i></i><b>PASS / BLOCK</b></div>
    <ul>
      <li>Compiler + schemas / types</li>
      <li>Tests + policy checks</li>
      <li>Permissions + CI gates</li>
      <li>Returns an enforceable verdict</li>
    </ul>
    <small>REPRODUCIBLE ENCODED CRITERION</small>
  </div>
</div>

<div class="control-bottom" v-click>
  <div><span>USE STEERING</span><b>to guide the trajectory</b></div>
  <mdi-arrow-right />
  <div><span>USE GATES</span><b>to decide whether output may proceed</b></div>
</div>

<div class="final-formula" v-click>
  <span>CONTEXT</span><i>+</i><span>ACTION</span><i>+</i><span>EVIDENCE</span><i>+</i><span>ACCOUNTABILITY</span><b>= AGENTIC ENGINEERING</b>
</div>

<div class="slide-id">21</div>

<!--
Myslím, že všichni pochopili, že guardrails řídí a vedou workflow, zatímco testy jsou deterministické pevné body (brány), které drží agenta v chodu, dokud nejsou splněny.

Instrukce a guardrails řídí pravděpodobnostní model. Jsou důležité, ale slouží jako behaviorální vodítko – nikoli jako vynucování.

Deterministické nástroje běží nezávisle na pozornosti agenta: kompilátor, schémata, oprávnění, kontroly architektury a blokující testy. To neznamená, že kontrola je úplná, nebo že test je nutně správný. Lidé si stále musí prohlédnout testovací orákulum.

Pull request shromažďuje požadavek, diff, výsledky testů, předpoklady, nevyřešená rizika a reprodukční příkazy. Build, statické kontroly a testy chování blokují. Kompetentní osoba přijímá strategická rozhodnutí a vydání.
-->

---
layout: default
class: feedback-slide dark-slide
---

<div class="kicker">EXECUTABLE FEEDBACK · 03 MIN</div>

# Close the industrial<br><span class="accent">engineering loop</span>

<AutomationStudioAgent />

<div class="slide-id">22</div>

<!--
Návrh agenta je cenný teprve tehdy, když můžeme smyčku uzavřít úplně. Než smyčka může jednat, musí mít doménový kontext: strukturu projektu, znalost produktu a verzí, pravidla a záměr. Projekt pak musí být možné sestavit reprodukovatelně. Musíme být schopni spustit řízenou simulaci, vyvolat stav, pozorovat proměnné a logbook a porovnat výsledek s požadavkem.

Na snímku vidíme guardrails prostřednictvím instrukcí a skills, poté research přes AS-HELP, BR-COMMUNITY, GitHub a cloudový AS-COPILOT MCP. Automation Studio čte a zapisuje kód prostřednictvím editoru Main.st, zatímco as sestavuje, simuluje, čte proměnné a čte logbook.

DevOps provádí známou sekvenci deterministicky. Agent volí další ohraničenou akci na základě zpětné vazby. Je proto důležité, aby stejný příkazový kontrakt mohl používat inženýr, testovací tým, pipeline a agent.

Přechod: To je přesně ta cesta, kterou samotné B&R prošlo.
-->

---
layout: default
class: vertical-modules-slide dark-slide
---

<div class="kicker">AGENTIC METHOD · VERTICAL SLICES</div>

# Build features<br><span class="accent">through the stack</span>

<p class="vertical-modules-lead">Humans optimize for focus. Agents can optimize for feedback.</p>

<div class="kanban-compare">
  <section class="kanban-panel horizontal-panel" v-click>
    <div class="kanban-panel-head">
      <div><span>HUMAN DEFAULT</span><b>Discipline lanes</b></div>
      <mdi-view-column-outline />
    </div>
    <p class="kanban-panel-note">Specialists stay focused. The feature waits at the integration boundary.</p>
    <div class="kanban-board category-board">
      <div class="kanban-columns"><span></span><b>BACKLOG</b><b>IN PROGRESS</b><b>PROVEN</b></div>
      <div class="kanban-lanes">
        <div class="kanban-lane category-lane"><span class="kanban-lane-label">HMI</span><div class="kanban-cell"><span class="kanban-card">fault + reset screen</span></div><div class="kanban-cell"><span class="kanban-card muted-card">needs state names</span></div><div class="kanban-cell"></div></div>
        <div class="kanban-lane category-lane"><span class="kanban-lane-label">SAFETY</span><div class="kanban-cell"><span class="kanban-card amber-card">safe stop on fault</span></div><div class="kanban-cell"><span class="kanban-card muted-card">needs reset rule</span></div><div class="kanban-cell"></div></div>
        <div class="kanban-lane category-lane"><span class="kanban-lane-label">CONTROL</span><div class="kanban-cell"><span class="kanban-card">abort + clear states</span></div><div class="kanban-cell"><span class="kanban-card muted-card">needs reject logic</span></div><div class="kanban-cell"></div></div>
        <div class="kanban-lane category-lane"><span class="kanban-lane-label">I/O + HW</span><div class="kanban-cell"><span class="kanban-card">axis error handling</span></div><div class="kanban-cell"><span class="kanban-card muted-card">needs sim rig</span></div><div class="kanban-cell"></div></div>
      </div>
    </div>
    <div class="kanban-result blocked">
      <mdi-clock-alert-outline />
      <div><span>INTEGRATION DAY</span><b>No complete feature to test</b></div>
    </div>
  </section>

  <div class="kanban-contrast" v-click>
    <span>SAME BOARD<br><strong>NEW UNIT</strong></span>
    <mdi-arrow-right />
  </div>

  <section class="kanban-panel vertical-panel" v-click>
    <div class="kanban-panel-head">
      <div><span>AGENT + TDD</span><b>Feature lanes</b></div>
      <mdi-view-column-outline />
    </div>
    <p class="kanban-panel-note">Keep one behavior in context. Cross every boundary, then prove it.</p>
    <div class="kanban-board feature-board">
      <div class="kanban-columns"><span></span><b>BACKLOG</b><b>IN PROGRESS</b><b>PROVEN</b></div>
      <div class="kanban-lanes">
        <div class="kanban-lane feature-lane"><span class="kanban-lane-label">OBSERVE<br>FAULT</span><div class="kanban-cell"><span class="kanban-card red-card">abort is visible</span></div><div class="kanban-cell"><span class="kanban-card">HMI + state + axis</span></div><div class="kanban-cell"><span class="kanban-card done-card">count holds</span></div></div>
        <div class="kanban-lane feature-lane"><span class="kanban-lane-label">CLEAR<br>CONVEYOR</span><div class="kanban-cell"><span class="kanban-card red-card">uncapped stay on</span></div><div class="kanban-cell"><span class="kanban-card">reject logic + safety</span></div><div class="kanban-cell"><span class="kanban-card done-card">conveyor empty</span></div></div>
        <div class="kanban-lane feature-lane"><span class="kanban-lane-label">RESUME<br>BATCH</span><div class="kanban-cell"><span class="kanban-card red-card">restart resets count</span></div><div class="kanban-cell"><span class="kanban-card">reset + sequence</span></div><div class="kanban-cell"><span class="kanban-card done-card">continues from held</span></div></div>
        <div class="kanban-lane feature-lane"><span class="kanban-lane-label">PROVE<br>100 BATCH</span><div class="kanban-cell"><span class="kanban-card red-card">no evidence</span></div><div class="kanban-cell"><span class="kanban-card">sim run + logbook</span></div><div class="kanban-cell"><span class="kanban-card done-card">100 bottles done</span></div></div>
      </div>
    </div>
    <div class="kanban-result ready">
      <mdi-test-tube />
      <div><span>EVERY MOVE HAS A SIGNAL</span><b>A working feature at every step</b></div>
    </div>
  </section>
</div>

<div class="tdd-loop" v-click>
  <div class="tdd-loop-label"><span>THE AGENT'S RHYTHM</span><b>One slice at a time</b></div>
  <div class="tdd-step red"><span>01</span><strong>RED</strong><small>write failing test</small></div>
  <mdi-arrow-right />
  <div class="tdd-step green"><span>02</span><strong>GREEN</strong><small>make the smallest change</small></div>
  <mdi-arrow-right />
  <div class="tdd-step refactor"><span>03</span><strong>REFACTOR</strong><small>review, then repeat</small></div>
</div>

<div class="vertical-modules-takeaway" v-click>
  <span>THINK IN BEHAVIORS, NOT LAYERS</span>
  <strong>One narrow outcome. One fast feedback loop.</strong>
</div>

<div class="slide-id">23</div>

<!--
[CLICK]
Lidé se často organizují do kanban tabulkách podle odborné disciplíny: HMI, safety, control a hardware. <b>horizontal slices</b> To je racionální způsob práce, když je zaměření omezené a když různí lidé mají různé odborné znalosti. Je to omezení, které máme jako lidé. Máme malou krátkodobou paměť a jsme špatní v multitaskingu / přepínání kontextu.
Jako lidé proto typicky děláme jednu disciplínu po druhé. Tam jsme nejproduktivnější, ale to vytváří problémy při testování. Jak otestujete HMI bez logiky? Není tam žádná zpětná vazba!

[CLICK]


[CLICK]
Agent tato omezení nemá a může jednoduše spustit subagenty, kteří se postarají o jiné odbornosti, nebo aby izoloval a delegoval kontext. Proto může pracovat vertikálně (<b>vertical slices</b>): feature swimlanes s HMI stavem, safety kontraktem, control logikou, I/O nebo simulací a akceptačním testem ve stejné krátké smyčce. To je obrovská výhoda z hlediska testování. Každou funkci lze testovat nezávisle, protože obsahuje všechny prvky.

[CLICK]
Matt Pocockův TDD skill popisuje horizontal slicing jako anti-pattern: nepiš nejdřív všechny testy a veškerou implementaci až potom. Pracuj ve vertical slices: jeden test, jedna minimální implementace, opakuj. Každý test je tracer bullet, který využívá zpětnou vazbu z předchozího cyklu.  Červená před zelenou; refaktorování patří do fáze kontroly.

Zdroj: https://github.com/mattpocock/skills/blob/main/skills/engineering/tdd/SKILL.md
-->

---
layout: default
class: feature-recap-slide dark-slide
---

<div class="kicker">BACK TO THE MACHINE · 01 MIN</div>

# One feature to build.<br><span class="accent">Now we have all the pieces.</span>

<div class="feature-recap-layout">
  <div class="feature-recap-machine">
    <BottleConveyor state="fault" :count="42" compact />
  </div>

  <div class="feature-recap-story">
    <div class="feature-recap-sequence" aria-label="Feature outcome sequence">
      <div><span>01</span><b>FAULT</b></div><i></i>
      <div><span>02</span><b>STOP</b></div><i></i>
      <div><span>03</span><b>REJECT</b></div><i></i>
      <div><span>04</span><b>RETAIN</b></div><i></i>
      <div><span>05</span><b>RESUME</b></div><i></i>
      <div><span>06</span><b>PROVE</b></div>
    </div>
    <div class="feature-recap-capabilities" v-click>
      <span>KNOWLEDGE</span><i>+</i><span>TOOLS</span><i>+</i><span>GUARDRAILS</span><i>+</i><span>TESTS</span><i>+</i><span>GATES</span>
    </div>
    <div class="feature-recap-question" v-click>
      <span>NOW ASSEMBLE THE SYSTEM</span>
      <strong>Which workflows turn these pieces into an accountable engineering change?</strong>
    </div>
  </div>
</div>

<!--
Je to stejný úkol se strojem, se kterým jsme workshop začali: chyba, řízené zastavení, odmítnutí neuzavřených lahví, zachovaný čítač, restart dávky a důkaz o dokončeném výsledku.

Nyní máme stavební kameny: doménovou znalost, nástroje k jednání a pozorování, guardrails, testy a deterministické brány.


Přechod: Pojďme dát stavební kameny dohromady do tří workflows, které dělají změnu ohraničenou a ověřitelnou.
-->

---
layout: default
class: planning-slide dark-slide
---

<div class="kicker">WORKFLOWS · 04 MIN</div>

# Three workflows<br><span class="accent">everyone needs</span>

<AgentWorkflow />

<div class="slide-id">24</div>

<!--
"Zotavení po chybě osy" zní jako úkol, ale není to specifikace. Agent může prozkoumat existující kód a vyhledat znalosti. Ale záměr a kompromisy se musí vrátit k nám, abychom mohli zaujmout stanovisko.

Zde je příklad, jak by mohl vypadat úplný workflow, který vede přímo k tomu, o čem bude Mads vyprávět po přestávce:

První workflow se zabývá tím, aby byl správně popsán zadaný úkol.

Druhý může být plně automatický, jakmile je ohraničený, izolovaný a získal si naši důvěru.

Poslední se zabývá validací a optimalizací systému.

přechod: OTÁZKY
-->

---
layout: default
class: devops-cover ai-workshop-cover dark-slide
---

<div class="devops-chapter">02</div>

<div class="kicker">WORKSHOP 02</div>
<div class="part-label">MADS ANDERSEN · AUTOMATION ENGINEER</div>

# DevOps in<br><span class="accent">industry</span>

<p class="devops-cover-copy">Building confidence in a world of AI-generated change</p>

<div class="devops-spine" v-motion :initial="{ opacity: 0, y: 18 }" :enter="{ opacity: 1, y: 0, transition: { delay: 300 } }">
  <div><span>01</span><b>VERSION</b><small>known inputs</small></div>
  <i></i>
  <div><span>02</span><b>BUILD</b><small>repeatable output</small></div>
  <i></i>
  <div><span>03</span><b>TEST</b><small>behavioral evidence</small></div>
  <i></i>
  <div><span>04</span><b>RELEASE</b><small>reviewable change</small></div>
</div>

<div class="slide-id">25</div>

<!--
"Jmenuji se Mads Andersen a pracuji v B&R téměř 8 let.

Pracoval jsem hlavně ve světě OT, ale vždy jsem měl velký zájem o softwarové inženýrství a nástroje a workflows, které se používají v IT.

Už mnoho let mluvíme o tom, že se OT a IT pomalu přibližují k sobě.

Ale posledních pár let se to prudce zrychlilo.

Právě jsme slyšeli o Agentic Engineering a o tom, jak nám AI může pomoct vytvářet software rychleji než dřív.

Ale to vyvolává novou otázku:

Jak zajistíme kvalitu, když množství softwaru a změn roste?

To je vlastně to, o čem DevOps je.

Jak můžeme software stavět, testovat a dodávat reprodukovatelným způsobem.

A na to se teď podíváme blíž."

-->

---
layout: default
class: agenda-slide dark-slide devops-agenda-slide
---

<div class="kicker">WORKSHOP 02 · AGENDA</div>

<div class="agenda-layout">
  <div class="agenda-intro" v-motion :initial="{ opacity: 0, x: -24 }" :enter="{ opacity: 1, x: 0 }">
    <h1>DevOps in<br><span class="accent">industry.</span></h1>
    <p class="agenda-lead">The engineering path from a project in Git to a tested, reviewable release.</p>
    <div class="agenda-event-mark">
      <span>02</span>
      <div><b>DEVOPS IN INDUSTRY</b><small>VERSION · BUILD · TEST · RELEASE</small></div>
    </div>
  </div>

  <div class="agenda-timeline" v-motion :initial="{ opacity: 0, x: 28 }" :enter="{ opacity: 1, x: 0, transition: { delay: 220 } }" aria-label="DevOps in industry agenda shown as a Git commit history">
    <div class="agenda-row is-session">
      <time datetime="commit-01">01</time><i aria-hidden="true"></i><div><b>What is DevOps?</b><small>Development · operations · feedback</small></div>
    </div>
    <div class="agenda-row">
      <time datetime="commit-02">02</time><i aria-hidden="true"></i><div><b>Why DevOps?</b><small>Make change visible and repeatable</small></div>
    </div>
    <div class="agenda-row">
      <time datetime="commit-03">03</time><i aria-hidden="true"></i><div><b>CI / CD</b><small>Build, test, verify, deploy</small></div>
    </div>
    <div class="agenda-row">
      <time datetime="commit-04">04</time><i aria-hidden="true"></i><div><b>Tooling + as CLI</b><small>Make engineering actions programmable</small></div>
    </div>
    <div class="agenda-row is-session">
      <time datetime="commit-05">05</time><i aria-hidden="true"></i><div><b>Demos: as cli, Orange Juice Machine and HMI testing</b><small>Prove expected machine behavior</small></div>
    </div>
    <div class="agenda-row">
      <time datetime="commit-06">06</time><i aria-hidden="true"></i><div><b>Start Monday</b><small>One bounded, repeatable workflow</small></div>
    </div>
  </div>
</div>

<div class="slide-id">26</div>

<!--
Pojďme se rychle podívat na dnešní cestu.

Nejdřív se musíme shodnout na tom, co vlastně myslíme pod DevOps.

Pak si povíme, proč je to relevantnější než kdy dřív ve světě AI a Agentic Engineering.

Poté se podíváme na CI/CD a základní principy automatizovaného dodávání softwaru.

Dále se podíváme, proč je tooling tak důležitý, a jak do toho zapadá as-cli.

Ale většinu času budou tvořit demoa, kde vše uvidíme v praxi.

Nakonec to všechno shrneme do otázky:

S čím lze reálně začít už v pondělí?
 -->

---
layout: default
class: devops-intro-slide dark-slide
---

<div class="status-badge general">GENERAL PRINCIPLE</div>
<div class="kicker">WORKSHOP 02 · ORIENTATION</div>

# What is<br><span class="accent">DevOps?</span>

<div class="devops-intro-lead">
  <span>DEVELOPMENT + OPERATIONS</span>
</div>

<div class="devops-loop" aria-label="The DevOps loop">
  <div class="devops-loop-stage development">
    <span class="devops-stage-number">01</span>
    <b>DEVELOPMENT</b>
    <ul>
      <li>Plan and code a change</li>
      <li>Build the application</li>
      <li>Test the expected behavior</li>
    </ul>
  </div>
  <div class="devops-loop-connector">
    <img class="devops-inf-logo" src="/DevOpsInfLogo.png" alt="DevOps infinity loop">
    <b>CONTINUOUS<br>FEEDBACK</b>
  </div>
  <div class="devops-loop-stage operations">
    <span class="devops-stage-number">02</span>
    <b>OPERATIONS</b>
    <ul>
      <li>Release and deploy</li>
      <li>Operate the machine</li>
      <li>Monitor real behavior</li>
    </ul>
  </div>
</div>

<br />
<br />
<br />

<div class="devops-beyond">
  <div class="devops-beyond-label"><span>ALSO DEVOPS</span><b>NOT COVERED TODAY</b></div>
  <ul aria-label="DevOps disciplines not covered today">
    <li>Automated Setup (IaC)</li>
    <li>Security / DevSecOps</li>
    <li>Issue reporting</li>
    <li>Team culture &amp; collaboration</li>
    <li>Coding Standards</li>
    <li>Documentation</li>
  </ul>
</div>

<div class="devops-intro-note">DevOps covers many practices and disciplines.
Today we focus on the software delivery flow: <strong>Code → Build → Test → Deploy.</strong></div>

<div class="slide-id">27</div>
<!--
Titulek: Co je DevOps
Než půjdeme dál, ujasněme si, co dnes myslíme pod DevOps.

Development se týká plánování, implementace a ověřování změn v softwaru.

Operations se týká bezpečného nasazení tohoto softwaru na správný stroj, sledování jeho chování v provozu a sběru zpětné vazby pro další změnu.

To je také důvod, proč se DevOps často znázorňuje symbolem nekonečna. Když se software dostane do provozu, získáme nové poznatky. Možná najdeme chyby. Možná objevíme něco, co lze zlepšit. A pak začíná další změna.

Ale to je velmi zjednodušená definice. DevOps je ve skutečnosti obrovská oblast.

Existuje mnoho dalších disciplín, které se často řadí pod DevOps. Infrastruktura, bezpečnost, spolupráce, dokumentace a tak dále.

Všechny jsou důležité.

Ale pokud bychom je dnes zkusili pokrýt všechny, budeme tu ještě zítra.

Takže když v této prezentaci dál říkám DevOps, myslím tím hlavně tuto část DevOps:

Jak se dostaneme od kódu k ověřenému vydání přes Build, Test a Deploy.

A to je zvlášť zajímavé ve světě, kde nám AI pomáhá vytvářet víc změn než kdy dřív.

-->

---
layout: default
class: why-devops-slide dark-slide
---

<div class="kicker">WORKSHOP 02 · WHY DEVOPS?</div>

# Why <span class="accent">DevOps?</span>

<div class="why-devops-flow" aria-label="Agentic Engineering connected to DevOps">
  <section class="why-devops-panel agentic">
    <div class="why-devops-panel-label">01 · ACCELERATE CREATION</div>
    <div class="why-devops-panel-title"><mdi-robot-outline /><b>AGENTS</b></div>
    <ul>
      <li>Generates code faster</li>
      <li>Makes automated tests easier to create</li>
      <li>Turns ideas into prototypes quickly</li>
    </ul>
  </section>

  <div class="why-devops-bridge" aria-label="Needs guardrails">
    <span class="why-devops-bridge-line"></span>
    <div class="why-devops-bridge-core"><mdi-shield-check-outline /><b>NEEDS<br>GUARDRAILS</b></div>
    <span class="why-devops-bridge-line"></span>
  </div>

  <section class="why-devops-panel devops">
    <div class="why-devops-panel-label">02 · DELIVER RELIABLY</div>
    <div class="why-devops-panel-title"><mdi-source-branch /><b>DEVOPS</b></div>
    <div class="why-devops-practices">
      <div><mdi-hammer-wrench /><span>AUTOMATED BUILD + TEST</span></div>
      <div><mdi-shield-check-outline /><span>QUALITY CHECKS</span></div>
      <div><mdi-source-branch /><span>CONTROLLED DEPLOYMENT</span></div>
      <div><mdi-chart-timeline-variant-shimmer /><span>CONTINUOUS FEEDBACK</span></div>
    </div>
  </section>
</div>

<br />
<br />
<br />
<br />

<div class="why-devops-takeaway">
  <strong>AI helps us create software faster. DevOps helps us deliver it safely.</strong>
</div>

<div class="slide-id">28</div>

<!--
Lars se toho na začátku dotkl, ale abychom to stručně zopakovali:

Agentic Engineering nám umožňuje rychle generovat kód, rychle psát automatické testy, proměnit nápad v prototyp v rekordním čase.
... Ale agent potřebuje "guardrails" a přesně tady vstupuje do hry DevOps se svým buildem, testem, řízeným nasazením a kontrolou kvality.

AI nám pomáhá tvořit software rychleji. DevOps nám pomáhá ho dodávat kontrolovaným způsobem.

-->

---
layout: default
class: old-way-slide dark-slide
---

<div class="kicker">WORKSHOP 02 · THE OLD WAY</div>

# Why <span class="accent">change?</span>

<div class="old-way-subtitle">Traditional software development in OT</div>

<div class="old-way-flow" aria-label="The old manual delivery flow">
  <div class="old-way-step">
    <span class="old-way-number">01</span>
    <mdi-account-hard-hat-outline />
    <b>ENGINEER</b>
  </div>
  <div class="old-way-arrow" aria-hidden="true"><mdi-arrow-right /></div>
  <div class="old-way-step">
    <span class="old-way-number">02</span>
    <mdi-file-edit-outline />
    <b>CODE CHANGE</b>
  </div>
  <div class="old-way-arrow" aria-hidden="true"><mdi-arrow-right /></div>
  <div class="old-way-step">
    <span class="old-way-number">03</span>
    <mdi-hammer-wrench />
    <b>BUILD<br>MANUALLY</b>
  </div>
  <div class="old-way-arrow" aria-hidden="true"><mdi-arrow-right /></div>
  <div class="old-way-step">
    <span class="old-way-number">04</span>
    <mdi-folder-multiple-outline />
    <b>COPY FILES<br>AROUND</b>
  </div>
  <div class="old-way-arrow" aria-hidden="true"><mdi-arrow-right /></div>
  <div class="old-way-step">
    <span class="old-way-number">05</span>
    <mdi-test-tube />
    <b>RUN TESTS<br>(IF ANY)</b>
  </div>
  <div class="old-way-arrow" aria-hidden="true"><mdi-arrow-right /></div>
  <div class="old-way-step">
    <span class="old-way-number">06</span>
    <mdi-package-variant-closed-check />
    <b>DEPLOY<br>MANUALLY</b>
  </div>
  <div class="old-way-arrow" aria-hidden="true"><mdi-arrow-right /></div>
  <div class="old-way-step warning">
    <span class="old-way-number">07</span>
    <mdi-help-circle-outline />
    <b>HOPE NOTHING<br>BROKE</b>
  </div>
</div>

<div class="old-way-pain">
  <div class="old-way-pain-label"><span>PAIN POINTS</span><b>COMMON CHALLENGES</b></div>
  <ul>
    <li><mdi-hammer-wrench /><span>Manual build steps</span></li>
    <li><mdi-monitor-multiple /><span>Different PC configurations</span></li>
    <li><mdi-test-tube-empty /><span>Missing tests</span></li>
    <li><mdi-undo-variant /><span>Difficult rollbacks</span></li>
    <li><mdi-help-circle-outline /><span>Hard to know what was deployed</span></li>
    <li><mdi-chart-line-variant /><span>Hard to scale</span></li>
  </ul>
</div>


<br />
<br />
<br />
<br />
<br />
<br />

<div class="why-devops-matters-takeaway" v-click>
  <blockquote><strong>If AI helps us create 10&times; more changes, we need a way to verify 10&times; more changes.</strong></blockquote>
</div>

<div class="slide-id">29</div>

<!--
Zkusme se podívat, jak dodávání softwaru historicky často fungovalo.

Inženýr provede změnu.
Projekt se sestaví lokálně.
Možná se někde okopírují nějaké soubory.
Možná se spustí nějaké testy - možná ne.
A nakonec se změna nasadí ručně.

V tomto procesu není nutně nic špatně.
Takto se vyvíjela spousta projektů celé roky.
Ale přináší to určité problémy:

Na jakém počítači byl projekt sestaven?
Jaká měl nastavení?
Jaké testy se spustily?
Dokážeme přesně obnovit stejný výsledek znovu?
A pokud se něco pokazí, jak snadné je to vrátit zpět?

Dokud je počet změn nízký, dokážeme to často zvládnout.
Ale když se tempo zvyšuje, je to čím dál těžší.
A to platí obzvlášť teď.
Protože celý smysl Agentic Engineering je přece v tom, že dokážeme produkovat změny rychleji.

[CLICK]

Pokud nám AI pomáhá dělat 10krát víc změn,
potřebujeme způsob, jak ověřit 10krát víc změn.

Nedostaneme 10krát víc hodin na testování.
Nedostaneme 10krát víc commissioning inženýrů.
Proto se musíme naučit automatizovat části procesu buildu, testování a vydávání.
Ne proto, že by lidé dělali něco špatně.
<b>Ale protože se lidé neškálují tak dobře jako software</b>.

A přesně to je problém, který se snaží vyřešit kontinuální integrace (Continuous Integration).

-->

---
layout: default
class: why-devops-matters-slide dark-slide
---

<div class="status-badge general">GENERAL PRINCIPLE</div>
<div class="kicker">WORKSHOP 02 · THE CASE FOR DEVOPS</div>

# Why Testing<br><span class="accent">Becomes Affordable</span>

<div class="why-devops-matters-grid" aria-label="Why DevOps matters more as software creation accelerates">
  <section class="why-devops-matters-panel historical" aria-label="Historically">
    <div class="why-devops-matters-head">
      <div><span>01</span><b>HISTORICALLY</b></div>
      <mdi-account-hard-hat-outline />
    </div>
    <div class="why-devops-matters-items">
      <div class="why-devops-matters-item"><mdi-file-edit-outline /><b>Engineer writes code</b></div>
      <div class="why-devops-matters-item"><mdi-test-tube /><b>Engineer writes tests</b></div>
      <div class="why-devops-matters-item"><mdi-clock-alert-outline /><b>Testing feels expensive</b></div>
    </div>
  </section>

  <section class="why-devops-matters-panel agentic" aria-label="Agentic Engineering">
    <div class="why-devops-matters-head">
      <div><span>02</span><b>AGENTIC ENGINEERING</b></div>
      <mdi-robot-outline />
    </div>
    <div class="why-devops-matters-items">
      <div class="why-devops-matters-item"><mdi-robot-outline /><b>Agent helps create code</b></div>
      <div class="why-devops-matters-item"><mdi-robot-outline /><b>Agent helps create tests</b></div>
      <div class="why-devops-matters-item"><mdi-shield-check-outline /><b>Testing becomes easier to justify</b></div>
    </div>
  </section>
</div>

<div class="slide-id">30</div>

<!--
Ekonomika psaní testů se s Agentic Engineering také změnila.

Historicky bylo automatizované testování v mnoha automatizačních projektech těžké obhájit.

Není to proto, že by testy nikdo neměl rád. Problém je, že testy se také musí vyvíjet, udržovat a aktualizovat. U menších projektů se úsilí často zdálo větší než přínos.

Ale Agentic Engineering tuto rovnici trochu mění.

Pokud čas potřebný na výrobu softwaru výrazně klesne, klesnou i náklady na výrobu testů. AI nám může pomoct jak s implementací funkčnosti, tak s vytvořením testovacích případů, které mají tuto funkčnost ověřit.

Zároveň často vidíme, že moderní agentní workflows samy generují a spouštějí testy jako součást svého pracovního procesu. Ověřování se tak stává mnohem přirozenější součástí vývojového toku.

Z toho důvodu se psaní testů stalo výnosnějším a snadněji obhajitelným i v OT projektu.
-->

---
layout: default
class: devops-tooling dark-slide
---

<div class="kicker">WORKSHOP 02 · DEVOPS</div>

<div class="delivery-heading">
  <div>
    <h1>Continuous<br><span class="accent">Integration</span></h1>
    <p>Every change is built and checked while it is still small.</p>
  </div>
  <div class="delivery-definition-mark"><span>CI</span><small>FAST FEEDBACK<br>BEFORE RELEASE</small></div>
</div>

<div class="delivery-flow ci-flow" aria-label="Continuous Integration stages">
  <section class="delivery-flow-stage is-code" aria-label="Code">
    <span class="delivery-flow-number">01</span>
    <mdi-source-commit />
    <b>CODE</b>
    <small>change is versioned</small>
  </section>
  <div class="delivery-flow-arrow" aria-hidden="true"><mdi-arrow-right /></div>
  <section class="delivery-flow-stage is-ci" aria-label="Build">
    <span class="delivery-flow-number">02</span>
    <mdi-hammer-wrench />
    <b>BUILD</b>
    <small>repeatable output</small>
  </section>
  <div class="delivery-flow-arrow" aria-hidden="true"><mdi-arrow-right /></div>
  <section class="delivery-flow-stage is-ci" aria-label="Test">
    <span class="delivery-flow-number">03</span>
    <mdi-test-tube />
    <b>TEST</b>
    <small>expected behavior</small>
  </section>
  <div class="delivery-flow-arrow" aria-hidden="true"><mdi-arrow-right /></div>
  <section class="delivery-flow-stage is-verify" aria-label="Verify">
    <span class="delivery-flow-number">04</span>
    <mdi-shield-check-outline />
    <b>VERIFY</b>
    <small>evidence recorded</small>
  </section>
</div>

<div class="delivery-footer">
  <div class="delivery-footer-label"><mdi-check-circle-outline /><span>CI QUESTION</span></div>
  <strong>Does this change still behave as expected?</strong>
  <small>Fast feedback keeps the change easy to understand and easy to fix.</small>
</div>

<div class="slide-id">31</div>



<!-- Comment out CD - slide . It felt a bit too repetitive
---
layout: default
class: where-agentic-fits dark-slide
---

<div class="kicker">WORKSHOP 02 · DEVOPS</div>

<div class="delivery-heading">
  <div>
    <h1>Continuous<br><span class="accent">Delivery</span></h1>
    <p>Verified software becomes a traceable candidate for controlled release.</p>
  </div>
  <div class="delivery-definition-mark"><span>CD</span><small>READY TO RELEASE<br>WHEN APPROVED</small></div>
</div>

<div class="delivery-handoff">
  <mdi-check-circle-outline />
  <span>FROM CI</span>
  <strong>VERIFIED ARTIFACT</strong>
  <small>same bits, named and traceable</small>
</div>

<div class="delivery-flow cd-flow" aria-label="Continuous Delivery stages">
  <section class="delivery-flow-stage is-package">
    <span class="delivery-flow-number">05</span>
    <mdi-package-variant-closed />
    <b>PACKAGE</b>
    <small>traceable artifact</small>
  </section>
  <div class="delivery-flow-arrow" aria-hidden="true"><mdi-arrow-right /></div>
  <section class="delivery-flow-stage is-cd">
    <span class="delivery-flow-number">06</span>
    <mdi-clipboard-check-outline />
    <b>RELEASE CANDIDATE</b>
    <small>ready for decision</small>
  </section>
  <div class="delivery-gate-slot">
    <div class="delivery-gate-arrow" aria-hidden="true"><mdi-arrow-right /></div>
    <div class="delivery-gate">
      <mdi-account-check-outline />
      <span>HUMAN GATE</span>
      <b>release decision</b>
    </div>
  </div>
  <section class="delivery-flow-stage is-deploy">
    <span class="delivery-flow-number">07</span>
    <mdi-upload-network-outline />
    <b>DEPLOY</b>
    <small>controlled target</small>
  </section>
  <div class="delivery-flow-arrow" aria-hidden="true"><mdi-arrow-right /></div>
  <section class="delivery-flow-stage is-monitor">
    <span class="delivery-flow-number">08</span>
    <mdi-chart-timeline-variant-shimmer />
    <b>MONITOR</b>
    <small>feeds the next change</small>
  </section>
</div>

<div class="delivery-footer">
  <div class="delivery-footer-label"><mdi-shield-check-outline /><span>CD QUESTION</span></div>
  <strong>Can we move this verified artifact safely to its target?</strong>
  <small>Automation prepares the release; people own the decision.</small>
</div>

<div class="slide-id">32</div>
-->
<!--
Na předchozím slidu jsme mluvili o tom, že se ekonomika testování a ověřování změnila.

Pokud dokážeme produkovat víc softwarových změn, musíme být také schopni ověřit víc softwarových změn.
Přesně to je problém, který se snaží vyřešit Continuous Integration.

Když se udělá změna, práce nekončí tím, že je kód napsaný.
Změnu musí být možné sestavit.
Musí být možné ji otestovat.
A musí být možné ji ověřit.

Důležité není, aby všechny změny byly dokonalé.
Důležité je, abychom dostali zpětnou vazbu, dokud je změna ještě malá.
Pokud se něco pokazí po 5 minutách práce, je snadné to pochopit a opravit.
Pokud se něco pokazí po 3 týdnech vývoje, bývá mnohem dražší najít příčinu.

Continuous Integration se proto zabývá tím, jak přiblížit zpětnou vazbu co nejblíž ke změně.

Pokud agent vyprodukuje 20 změn za den, budete je všechny ručně procházet?
Pravděpodobně ne.
Proto se automatizované ověřování stává tak důležité.

CI škáluje zpětnou vazbu stejným způsobem, jako Agentic Engineering škáluje vývoj softwaru.
-->

---
layout: default
class: devops-pipeline dark-slide
---

<div class="kicker">WORKSHOP 02 · DEVOPS</div>

<div class="delivery-heading combined-heading">
  <div>
    <h1>CI/CD<br><span class="accent">putting it together</span></h1>
    <p>From code change to controlled release.</p>
  </div>
  <div class="delivery-principle"><span>ONE SYSTEM</span><strong>ENGINEER CREATES THE CHANGE.<br>PIPELINE EXECUTES THE PROCESS.</strong></div>
</div>

<div class="delivery-combined-flow" aria-label="The combined DevOps delivery flow">
  <section class="delivery-region ci-region" aria-label="Continuous Integration">
    <div class="delivery-region-heading"><span>CONTINUOUS INTEGRATION</span><small>make the change trustworthy</small></div>
    <div class="delivery-region-flow ci-region-flow">
      <section class="delivery-flow-stage is-code">
        <span class="delivery-flow-number">01</span>
        <mdi-source-commit />
        <b>CODE</b>
        <small>engineer creates</small>
      </section>
      <div class="delivery-flow-arrow" aria-hidden="true"><mdi-arrow-right /></div>
      <section class="delivery-flow-stage is-ci">
        <span class="delivery-flow-number">02</span>
        <mdi-hammer-wrench />
        <b>BUILD</b>
        <small>repeatable output</small>
      </section>
      <div class="delivery-flow-arrow" aria-hidden="true"><mdi-arrow-right /></div>
      <section class="delivery-flow-stage is-ci">
        <span class="delivery-flow-number">03</span>
        <mdi-test-tube />
        <b>TEST</b>
        <small>expected behavior</small>
      </section>
      <div class="delivery-flow-arrow" aria-hidden="true"><mdi-arrow-right /></div>
      <section class="delivery-flow-stage is-verify">
        <span class="delivery-flow-number">04</span>
        <mdi-shield-check-outline />
        <b>VERIFY</b>
        <small>evidence recorded</small>
      </section>
    </div>
  </section>

  <div class="delivery-combined-handoff" aria-hidden="true">
    <span>VERIFIED SOFTWARE<br>BECOMES A<br>RELEASE CANDIDATE</span>
    <mdi-arrow-right />
  </div>

  <section class="delivery-region cd-region" aria-label="Continuous Delivery">
    <div class="delivery-region-heading"><span>CONTINUOUS DELIVERY</span><small>move it with control</small></div>
    <div class="delivery-region-flow cd-region-flow">
      <section class="delivery-flow-stage is-package">
        <span class="delivery-flow-number">05</span>
        <mdi-package-variant-closed />
        <b>PACKAGE</b>
        <small>traceable artifact</small>
      </section>
      <div class="delivery-flow-arrow" aria-hidden="true"><mdi-arrow-right /></div>
      <section class="delivery-flow-stage is-cd">
        <span class="delivery-flow-number">06</span>
        <mdi-clipboard-check-outline />
        <b>RELEASE</b>
        <small>ready for decision</small>
      </section>
      <div class="delivery-approval-slot">
        <mdi-arrow-right class="delivery-approval-arrow" aria-hidden="true" />
        <div class="delivery-inline-gate">
          <mdi-account-check-outline />
          <span>RELEASE DECISION</span>
        </div>
      </div>
      <section class="delivery-flow-stage is-deploy">
        <span class="delivery-flow-number">07</span>
        <mdi-upload-network-outline />
        <b>DEPLOY</b>
        <small>controlled target</small>
      </section>
      <div class="delivery-flow-arrow" aria-hidden="true"><mdi-arrow-right /></div>
      <section class="delivery-flow-stage is-monitor">
        <span class="delivery-flow-number">08</span>
        <mdi-chart-timeline-variant-shimmer />
        <b>MONITOR</b>
        <small>feeds the next change</small>
      </section>
    </div>
  </section>
</div>

<div class="delivery-feedback">
  <div class="delivery-footer-label"><mdi-chart-timeline-variant-shimmer /><span>FEEDBACK LOOP</span></div>
  <strong>Monitor what happened. Feed the next change.</strong>
</div>

<div class="slide-id">33</div>

<!--
Když to pak dáme dohromady s CD, nazýváme to CI/CD.

CI ověřuje naše změny.

Continuous Delivery (CD) balí a vydává (např. na GitHub),
nasazuje do PLC, ale téměř vždy s člověkem, který schvaluje kdy. V IT světě je zcela běžné, že aktualizace přichází automaticky bez schválení člověkem (např. tato prezentace na GitHub Pages - aktualizuje se automaticky při pushi na GitHub). To se do OT nehodí, protože to musí zapadat do plánování výroby.
Nakonec máme monitorovací část, která posílá další změny zpět do našeho CI, a tak znovu dostáváme ten "efekt přesýpacích hodin", o kterém jsme mluvili na začátku.

Tomu všemu říkáme CI/CD a později k tomu máme i demo, ale předtím si musíme trochu popovídat o toolingu.

-->

---
layout: default
class: tooling-matters-slide dark-slide
---

<div class="status-badge general">GENERAL PRINCIPLE</div>
<div class="kicker">WORKSHOP 02 · TOOLING</div>

# Why <span class="accent">Tooling Matters</span>

<div class="tooling-subtitle">Automation requires programmable access to engineering tools.</div>

<div class="tooling-access-grid" aria-label="Human-driven and pipeline-driven engineering workflows">
  <section class="tooling-workflow-panel gui-workflow-panel" aria-label="Human-driven workflow">
    <div class="tooling-panel-label">01 · HUMAN-DRIVEN WORKFLOW</div>
    <div class="tooling-panel-title"><mdi-monitor-dashboard /><b>GUI WORKFLOW</b></div>
    <div class="tooling-gui-window" v-click="1">
      <div class="tooling-window-bar"><span>ENGINEERING APPLICATION</span><i></i><i></i><i></i></div>
      <div class="tooling-step-list">
        <div class="tooling-step"><span>01</span><mdi-folder-open-outline /><b>OPEN PROJECT</b><span class="tooling-click-icon"><mdi-cursor-default-click-outline /></span></div>
        <div class="tooling-step-arrow"><mdi-arrow-down /></div>
        <div class="tooling-step"><span>02</span><mdi-tune-variant /><b>SELECT CONFIGURATION</b><span class="tooling-click-icon"><mdi-cursor-default-click-outline /></span></div>
        <div class="tooling-step-arrow"><mdi-arrow-down /></div>
        <div class="tooling-step"><span>03</span><mdi-hammer-wrench /><b>CLICK BUILD</b><span class="tooling-click-icon"><mdi-cursor-default-click-outline /></span></div>
        <div class="tooling-step-arrow"><mdi-arrow-down /></div>
        <div class="tooling-step"><span>04</span><mdi-text-box-search-outline /><b>READ RESULT</b><span class="tooling-click-icon"><mdi-cursor-default-click-outline /></span></div>
        <div class="tooling-step-arrow"><mdi-arrow-down /></div>
        <div class="tooling-step"><span>05</span><mdi-upload-network-outline /><b>CLICK TRANSFER</b><span class="tooling-click-icon"><mdi-cursor-default-click-outline /></span></div>
      </div>
      <div class="tooling-manual-cue"><mdi-cursor-default-click-outline /><span>REPEAT EACH HANDOFF BY HAND</span></div>
    </div>
    <p class="tooling-panel-note" v-click="1">Effective for engineering work, difficult for unattended execution.</p>
  </section>

  <div class="tooling-interface-bridge" v-click="2" aria-label="Complementary interfaces">
    <div class="tooling-bridge-box"><strong>GUI</strong><small>FOR PEOPLE</small></div>
    <mdi-arrow-down />
    <div class="tooling-bridge-caption">SAME<br>ENGINEERING<br>CAPABILITY</div>
    <mdi-arrow-down />
    <div class="tooling-bridge-box is-automation"><strong>CLI / API</strong><small>FOR AUTOMATION</small></div>
  </div>
  <section class="tooling-workflow-panel pipeline-workflow-panel" aria-label="Pipeline-driven workflow">
    <div class="tooling-panel-label">02 · PIPELINE-DRIVEN WORKFLOW</div>
    <div class="tooling-panel-title" v-click="2"><mdi-console-line /><b>PROGRAMMABLE INTERFACE</b></div>
    <div class="tooling-runner-shell" v-click="2">
      <div class="tooling-runner-bar"><mdi-source-branch /><span>PIPELINE RUNNER</span></div>
      <div class="tooling-runner-question"><mdi-help-circle-outline /><b>NEED A<br>PROGRAMMABLE INTERFACE</b></div>
    </div>
    <div class="tooling-cli-boundary" v-click="2">
      <div class="tooling-cli-label"><mdi-console-line /><b>CLI / API</b><small>ONE AUTOMATED BOUNDARY</small></div>
      <div class="tooling-automated-steps">
        <div><mdi-hammer-wrench /><b>BUILD</b></div>
        <div><mdi-test-tube /><b>TEST</b></div>
        <div><mdi-package-variant-closed /><b>PACKAGE</b></div>
        <div><mdi-upload-network-outline /><b>TRANSFER</b></div>
        <div><mdi-file-check-outline /><b>RETURN RESULT</b></div>
      </div>
    </div>
    <p class="tooling-panel-note" v-click="2">The same operation can be executed consistently every time.</p>
  </section>
</div>

<div class="tooling-takeaway" v-click="3">
  <strong>If a human must click it, a pipeline cannot reliably automate it.</strong>
  <small>The capability must also be exposed programmatically.</small>
</div>

<div class="slide-id">34</div>

<!--
Teď jsme mluvili o CI a CD.
Ale pořád chybí jedna důležitá otázka.
Jak to všechno vlastně uděláme?
Protože pipeline nemůže kliknout myší.

Vezměme si klasickou engineeringovou aplikaci.
Mohla by to být Automation Studio.
Mohl by to být TIA Portal.
Mohl by to být Studio 5000.

Jako lidé můžeme dělat spoustu věcí.
Můžeme otevřít projekt.
Můžeme zvolit konfiguraci.
Můžeme spustit build.
Můžeme přečíst výsledek.
Můžeme přenést software na target.
A vlastně to funguje opravdu dobře.

GUI jsou dělaná pro lidi.
Jsou optimalizovaná na to, abychom mohli se systémem zkoumat, chápat a pracovat.
Problém nastane teprve, když chceme automatizaci.
Protože pipeline neví, na co má kliknout.
Nevidí tlačítka.
Neumí číst dialogová okna.
Neumí interpretovat build okno stejně jako člověk.

[CLICK]

Takže pokud chceme automatizovat build, test, balení a nasazení...
potřebujeme jiný typ rozhraní.
Ne rozhraní pro lidi.
Ale rozhraní pro software.
Proto tak často vidíme CLI a API.
Ty dávají přístup přesně ke stejným možnostem jako GUI.
Jen způsobem, kterému pipeline rozumí.


A to nás přivádí k nejdůležitější myšlence celého slidu.
"Pokud na to musí kliknout člověk, pipeline to nedokáže automatizovat."
To je samozřejmě mírné zjednodušení.

Ale základní myšlenka je důležitá:
Pokud chceme DevOps.
Pokud chceme automatické testy.
Pokud chceme Agentic Engineering.
Musí být engineeringové funkce, ke kterým už máme jako lidé přístup...
dostupné i programově.
A přesně tady přichází na scénu B&R.

Podívejme se tedy, jak se to snažíme udělat v Automation Studio.
-->

---
layout: default
class: as-cli-intro-slide dark-slide
---

<div class="status-badge general">B&amp;R TOOLING</div>
<div class="kicker">WORKSHOP 02 · AS · DEMO ROADMAP</div>

# New <span class="accent">as CLI</span>

<div class="as-cli-subtitle">One programmable interface for pipelines, agents, and engineers.</div>

<div class="as-cli-consumer-row" aria-label="Consumers of as">
  <article class="as-cli-consumer-card as-cli-consumer-devops" v-click="1">
    <div class="as-cli-consumer-icon"><mdi-source-branch /></div>
    <div class="as-cli-consumer-copy">
      <span>01 · CONSUMER</span>
      <b>DEVOPS PIPELINE</b>
    </div>
    <mdi-arrow-down class="as-cli-consumer-arrow" />
  </article>
  <article class="as-cli-consumer-card as-cli-consumer-engineer" v-click="1">
    <div class="as-cli-consumer-icon"><mdi-account-hard-hat-outline /></div>
    <div class="as-cli-consumer-copy">
      <span>02 · CONSUMER</span>
      <b>ENGINEER</b>
    </div>
    <mdi-arrow-down class="as-cli-consumer-arrow" />
  </article>
  <article class="as-cli-consumer-card as-cli-consumer-agent" v-click="1">
    <div class="as-cli-consumer-icon"><mdi-robot-outline /></div>
    <div class="as-cli-consumer-copy">
      <span>03 · CONSUMER</span>
      <b>AI AGENT</b>
    </div>
    <mdi-arrow-down class="as-cli-consumer-arrow" />
  </article>
</div>

<div class="as-cli-core-row" aria-label="as programmable tool layer">
  <section class="as-cli-core" aria-label="as command-line tool">
    <div class="as-cli-core-topline"><span>PROGRAMMABLE TOOL LAYER</span><small>B&amp;R ENGINEERING ACCESS</small></div>
    <div class="as-cli-terminal-line"><span>&gt;_</span> <strong>as</strong></div>
    <div class="as-cli-core-name">AUTOMATION STUDIO COMMAND LINE INTERFACE</div>
  </section>
</div>

<div class="as-cli-roadmap" aria-label="as demonstration roadmap">
  <div class="as-cli-capability-grid">
    <article class="as-cli-capability-card as-cli-capability-build" v-click="1">
      <div class="as-cli-capability-head"><span>01</span><mdi-hammer-wrench /></div>
      <b class="as-cli-capability-name">BUILD</b>
      <div class="as-cli-capability-purpose">Compile the project</div>
      <div class="as-cli-command-stack">
        <div class="as-cli-command"><span>&gt;</span><span><strong>as</strong> build</span></div>
        <div class="as-cli-command"><span>&gt;</span><span><strong>as</strong> build sim</span></div>
      </div>
    </article>
    <article class="as-cli-capability-card as-cli-capability-test" v-click="1">
      <div class="as-cli-capability-head"><span>02</span><mdi-test-tube /></div>
      <b class="as-cli-capability-name">TEST INTERACTION</b>
      <div class="as-cli-capability-purpose">Set inputs and inspect behavior</div>
      <div class="as-cli-command-stack">
        <div class="as-cli-command"><span>&gt;</span><span><strong>as</strong> var write ...</span></div>
        <div class="as-cli-command"><span>&gt;</span><span><strong>as</strong> var read ...</span></div>
      </div>
    </article>
    <article class="as-cli-capability-card as-cli-capability-package" v-click="1">
      <div class="as-cli-capability-head"><span>03</span><mdi-package-variant-closed /></div>
      <b class="as-cli-capability-name">PACKAGE</b>
      <div class="as-cli-capability-purpose">Create an installation package</div>
      <small class="as-cli-capability-sublabel">PROJECT INSTALLATION PACKAGE</small>
      <div class="as-cli-command-stack">
        <div class="as-cli-command"><span>&gt;</span><span><strong>as</strong> build pip --output ...</span></div>
      </div>
    </article>
    <article class="as-cli-capability-card as-cli-capability-transfer" v-click="1">
      <div class="as-cli-capability-head"><span>04</span><span class="as-cli-capability-icon"><mdi-upload-network-outline /></span></div>
      <b class="as-cli-capability-name">TRANSFER</b>
      <div class="as-cli-capability-purpose">Transfer to a target</div>
      <div class="as-cli-command-stack">
        <div class="as-cli-command"><span>&gt;</span><span><strong>as</strong> transfer online --ip ...</span></div>
      </div>
    </article>
    <article class="as-cli-capability-card as-cli-capability-diagnostics" v-click="1">
      <div class="as-cli-capability-head"><span>05</span><mdi-file-search-outline /></div>
      <b class="as-cli-capability-name">DIAGNOSTICS</b>
      <div class="as-cli-capability-purpose">Read controller logbook entries</div>
      <div class="as-cli-command-stack">
        <div class="as-cli-command"><span>&gt;</span><span><strong>as</strong> logbook read</span></div>
      </div>
    </article>
  </div>
</div>

<div class="slide-id">35</div>

<!--
Zatím jsme mluvili o principech a teorii.
CI.
CD.
Automatizované testování.
Pipelines.

Ale celá ta teorie nám vlastně moc nepomůže, pokud se nástroje nedají automatizovat.

Proto jsme tady v Dánsku pracovali na as-cli.
(ukazuje doprostřed)

Ve skutečnosti to není DevOps platforma.
Není to AI agent.
A není to ani náhrada za Automation Studio.
Je to programovatelné rozhraní k Automation Studio.

To znamená, že stejnou engineeringovou funkčnost teď může používat:
- inženýr
- DevOps pipeline
- nebo AI agent

Mluvili jsme o tom, že člověk používá GUI, zatímco automatizace potřebuje CLI nebo API.
Přesně tuto roli plní as-cli.

(ukazuje na capabilities)

Pro dnešní demo je zajímavých zejména 5 capabilities.
Build projektů.
Interakce s runtime proměnnými.
Balení softwaru.
Transfer na target.
A diagnostika.

Ve skutečnosti je to dost na to, abychom postavili překvapivě velkou část DevOps pipeline.
A přesně těchto 5 věcí použijeme i v následujících demech.

-->

---
layout: default
class: as-cli-demo-slide dark-slide
---

<div class="status-badge demonstradtor">DEMO 1 / 3</div>
<div class="kicker">AS-CLI DEVELOPMENT · DEVOPS IN PRACTICE</div>

# How <span class="accent">as CLI</span> tests itself

<div class="as-cli-devops-flow" aria-label="as development test gates">
  <article class="as-cli-devops-gate as-cli-devops-unit">
    <div class="as-cli-devops-gate-head"><span>01 · FAST GATE</span><mdi-test-tube /></div>
    <b class="as-cli-devops-gate-name">PURE UNIT TESTS</b>
    <p>Fast tests of isolated logic, with no live Automation Studio</p>
    <code>.\tests\run-tests.ps1</code>
    <br />
  </article>
  <div class="as-cli-devops-arrow" aria-hidden="true"><span>THEN</span><mdi-arrow-right /></div>
  <article class="as-cli-devops-gate as-cli-devops-integration">
    <div class="as-cli-devops-gate-head"><span>02 · REAL SYSTEM</span><mdi-monitor-eye /></div>
    <b class="as-cli-devops-gate-name">INTEGRATION TESTS</b>
    <p>Slower tests that verify the complete system up against an Automation Studio simulator </p>
    <code>.\tests\run-integration-tests.ps1</code>
    <br />
  </article>
</div>

<div class="as-cli-devops-result">
  <mdi-shield-check-outline />
  <span>PASS / FAIL</span>
  <strong>Protects quality. Builds confidence. Catches issues early.</strong>
</div>

<div class="slide-id">36</div>

<!--
První demo je z vývojového projektu as CLI.

Projekt má několik jednoduchých unit testů, které testují velmi izolovanou logiku, např. že vstup do funkce dá očekávaný výstup.
Tyto testy jsou velmi rychlé a lze je spouštět často, ale moc neříkají o tom, zda funguje celý systém.
Na to máme integrační testy, kde testujeme všechny as cli příkazy proti testovacímu projektu Automation Studio. Otevřeme si projekt a podíváme se na něj.

Začněte tím, že v terminálu spustíte as --help a ukážete všechny různé příkazy.

Potom skočte do projektu a spusťte unit testy (trvá to asi 2 s).

Poté spusťte integrační test (trvá 1,5 min).
Udělejte "úmyslně" chybu a pak ukažte, že ji integrační test odchytí.
Vysvětlete, že máme GitHub workflow, který tyto testy spouští automaticky před vydáním. S tímto ale počkám do dalšího dema, kde budeme demonstrovat celou CI/CD pipeline.
-->

---
layout: default
class: machine-demo-slide dark-slide
---

<div class="status-badge demonstrator">DEMO 2 / 3</div>
<div class="kicker">FULL CI/CD PIPELINE · TEST PROJECT</div>

# The <span class="accent">orange</span> juice machine

<div class="machine-demo-subtitle">A GitHub workflow builds, tests, packages, and deploys this demonstration project.</div>

<div class="machine-demo-meta">
  <span>PROJECT IN GITHUB</span>
  <span class="machine-demo-path">.\EventAiAndDevOps\DevOps\DevOpsDemo</span>
</div>

<div class="machine-demo-machine">
  <BottleConveyor state="running" :count="42" />
</div>

<div class="slide-id">37</div>

<!--
Zatím jsme se na as CLI dívali jako na softwarový projekt.
Ale přesuňme pozornost k něčemu, co víc připomíná to, s čím mnozí z nás pracují každý den.

Toto je náš stroj na pomerančový džus.
Je to samozřejmě demo projekt.
Ale myšlenka je přesně stejná jako u skutečného stroje.
Máme projekt Automation Studio.
Máme software.
Máme HMI.
A máme přání být schopni dodávat změny reprodukovatelným způsobem.
Místo abychom o tom mluvili, zkusme to udělat.

[přepnout na GitHub]

Teď vytvořím release.
Jediné, co udělám, je vytvoření tagu a jeho push na GitHub.
A všimněte si, co se stane potom.
Protože teď to přebírá pipeline.
Ne já.

[vytvořit tag a pushnout]

Teď se spouští GitHub workflow.
Pokud otevřeme záložku Actions, můžeme to sledovat naživo.
Toto je náš digitalizovaný proces.
Všechny manuální kroky, o kterých jsme dřív mluvili...
jsou teď popsané jako workflow.

[ukázat workflow]

V praxi se teď děje víc věcí najednou.
Projekt se sestavuje.
Spouštějí se automatické testy.
Vytváří se release.
Generují se artefakty.
A nakonec se výsledek publikuje.
Všechno bez toho, abych se musel přihlašovat na build stroj nebo si pamatovat, jaké kroky se mají spustit.

[ukázat .github/workflows]

Zajímavý ve skutečnosti není GitHub.
GitHub by stejně dobře mohl být Gitlab, Azure DevOps, Jenkins nebo něco úplně jiného.
Zajímavé je, že proces je teď popsaný jako kód.
Pokud si kolega naklonuje projekt.
Dostane přesně stejný proces.
Pokud ho spustíme zítra.
Dostaneme přesně stejný proces.
Pokud ho spustíme za šest měsíců.
Pořád dostaneme přesně stejný proces.
Právě to ho dělá reprodukovatelným.

[ukázat jednotlivé kroky během běhu workflow]

Všimněte si, že produkujeme víc než jen software.
Produkujeme také evidence (důkazy).
Vidíme, co se sestavilo.
Jaké testy se spustily.
A zda prošly.
Přesně to nám dává CI/CD.
Nejen automatizaci.
Ale i sledovatelnost.
Když je workflow hotový, výsledek je připravený na release serveru.
Odtud si target může stáhnout přesně tu verzi, kterou jsme právě sestavili.
Zvlášť zajímavé je to, když máte hodně identických instalací.
Nebo když potřebujete přesně vědět, jaká verze byla nainstalovaná kde.
Protože pak už není žádná pochybnost o tom, co běží.

Existuje jeden build.
Jeden artefakt.
Jedna verze.
A všichni vědí, odkud pochází.

Přechod:
Teď jsme automatizovali build, test a release.
Ale co samotný uživatelský zážitek?
Jak vlastně otestujeme, že HMI stále funguje tak, jak operátor očekává?

-->

---
layout: default
class: hmi-testing-slide dark-slide
---

<div class="status-badge demonstrator">DEMO 3 / 3</div>
<div class="kicker">HMI VERIFICATION</div>

# Test the HMI <span class="accent">like an operator</span>

<p class="hmi-testing-subtitle">Automated checks of real operator workflows.</p>

<div class="hmi-testing-flow" aria-label="Operator workflow from action to verified result">
  <article class="hmi-testing-card is-user">
    <div class="hmi-testing-card-head"><span>01</span><mdi-account-outline /></div>
    <div><small>USER ACTION</small><strong>Press Start</strong></div>
  </article>
  <div class="hmi-testing-arrow" aria-hidden="true"><mdi-arrow-right /></div>
  <article class="hmi-testing-card is-hmi">
    <div class="hmi-testing-card-head"><span>02</span><mdi-monitor-dashboard /></div>
    <div><small>HMI</small><strong>Button changes state</strong></div>
  </article>
  <div class="hmi-testing-arrow" aria-hidden="true"><mdi-arrow-right /></div>
  <article class="hmi-testing-card is-plc">
    <div class="hmi-testing-card-head"><span>03</span><mdi-cog-outline /></div>
    <div><small>PLC</small><strong>Machine reacts</strong></div>
  </article>
  <div class="hmi-testing-arrow" aria-hidden="true"><mdi-arrow-right /></div>
  <article class="hmi-testing-card is-result">
    <div class="hmi-testing-card-head"><span>04</span><mdi-check-circle-outline /></div>
    <div><small>RESULT</small><strong>Expected behavior verified</strong></div>
  </article>
</div>

<div class="hmi-testing-takeaway">
  <mdi-shield-check-outline />
  <strong>Every software change can automatically prove that the operator workflow still works.</strong>
</div>

<div class="hmi-testing-examples">
  <span>EXAMPLES</span>
  <p>Start machine &bull; Change recipe &bull; Acknowledge alarm &bull; Verify status indication</p>
</div>

<div class="slide-id">38</div>

<!--
Poslední demo se týká něčeho, co bylo tradičně těžké automatizovat.
Konkrétně HMI verifikace.

(ukazuje na flow)

Dřív jsme mluvili o unit testech, integračních testech a PLC testech.
Ale nakonec to není PLC, kdo stroj používá.
Je to operátor.
A proto je zajímavé umět testovat i workflows, které operátor skutečně používá.

Například:
- dá se stroj spustit?
- dá se potvrdit alarm?
- dá se změnit recept?
- zobrazuje se na obrazovce správný stav?

Normálně by musel člověk klikat těmito scénáři ručně.

Ale přesně tak, jak dokážeme automatizovat build a test softwaru, dokážeme automatizovat i interakci uživatele s HMI.

To znamená, že u každé softwarové změny lze automaticky zkontrolovat, že nejdůležitější operátorské workflows stále fungují.

Přesně to vám teď chci ukázat.

Používáme k tomu CLI od Microsoftu, který se jmenuje Playwright.
Kvůli demu otevírám prohlížeč a přidal jsem k tomu nějaké animace navíc. Ve skutečné pipeline by to normálně běželo headless v terminálu.

npm run test:demo
Pokud by to mělo běžet headless, stačí napsat:
npm run test:hmi
-->


---
layout: default
class: devops-mountain-slide dark-slide
---

<div class="kicker">THE FIRST LOOP · PRACTICAL START</div>

# How to <span class="accent">get started</span>

<p class="mountain-subtitle">One step at a time</p>

<section class="mountain-stage" aria-label="DevOps journey from today's workflow to full CI/CD">
  <div class="mountain-visual">
    <div class="mountain-distant" aria-hidden="true"></div>
    <div class="mountain-main" aria-hidden="true"></div>
    <div class="mountain-facet" aria-hidden="true"></div>
    <div class="mountain-grid" aria-hidden="true"></div>
    <div class="mountain-trail" aria-hidden="true"></div>
    <div class="mountain-origin">
      <mdi-account-hard-hat-outline />
      <strong>TODAY</strong>
      <small>Current workflow</small>
    </div>
    <article class="mountain-checkpoint checkpoint-git">
      <span class="mountain-checkpoint-marker">01</span>
      <div class="mountain-checkpoint-label"><strong>GIT</strong><small>versioned project</small></div>
    </article>
    <article class="mountain-checkpoint checkpoint-build">
      <span class="mountain-checkpoint-marker">02</span>
      <div class="mountain-checkpoint-label"><strong>AS CLI</strong><small>Automate engineering tasks</small></div>
    </article>
    <article class="mountain-checkpoint checkpoint-test">
      <span class="mountain-checkpoint-marker">03</span>
      <div class="mountain-checkpoint-label"><strong>TEST</strong><small>Start with 1 test</small></div>
    </article>
    <article class="mountain-checkpoint checkpoint-evidence">
      <span class="mountain-checkpoint-marker">04</span>
      <div class="mountain-checkpoint-label"><strong>RELEASE</strong><small>Deployment package (PIP)</small></div>
    </article>
    <article class="mountain-checkpoint checkpoint-release">
      <span class="mountain-checkpoint-marker">05</span>
      <div class="mountain-checkpoint-label"><strong>Automate</strong><small>Pipeline execution</small></div>
    </article>
    <div class="mountain-summit">
      <span class="mountain-flag-pole" aria-hidden="true"></span>
      <span class="mountain-flag-pennant" aria-hidden="true"></span>
      <div class="mountain-summit-copy">
        <strong>FULL CI/CD</strong>
        <em>Repeatable and automated delivery</em>
      </div>
    </div>
  </div>
  <aside class="mountain-statement">
    <span class="mountain-statement-label">THE POINT IS PROGRESS</span>
    <strong>Don't start at<br> the summit.</strong>
    <b>Take the next step.</b>
  </aside>
</section>

<div class="mountain-footer">
  <span>Every organization starts from a different place.</span>
  <b>Success comes from taking the next step, not from reaching the summit immediately.</b>
</div>

<div class="slide-id">39</div>

<!--
Cílem DevOps není vybudovat dokonalý systém CI/CD přes noc.

Cílem je zajistit, aby byl jeden technický pracovní postup opakovatelnější než včera.


Začněte s Gitem.
Poté automatizujte sestavení.
Poté přidejte jeden smysluplný test.
Poté zaznamenejte důkazy.
Poté automatizujte činnosti související s vydáním.

Každý krok vytváří hodnotu.
-->

---
layout: default
class: working-in-progress dark-slide
---

<div class="status-badge progress">IN PROGRESS</div>
<div class="kicker">WHAT WE ARE WORKING ON</div>

# Work <span class="accent">in progress.</span>

<p class="working-lead">The tooling is taking shape. The next proof comes from using it in real customer workflows.</p>

<div class="working-streams">
  <article class="working-stream" v-click>
    <div class="working-stream-head"><span>01</span><mdi-docker /><small>PLATFORM SUPPORT</small></div>
    <h2>Automation Studio<span> in Docker</span></h2>
    <p class="working-stream-copy">Containerize engineering tools to simplify setup, improve integration, and ensure consistent execution across pipelines and agent workflows.</p>
    <div class="working-stream-status"><i></i><span>IN DEVELOPMENT</span></div>
  </article>
  <article class="working-stream" v-click>
    <div class="working-stream-head"><span>02</span><mdi-package-variant-closed /><small>PROJECT DEPENDENCIES</small></div>
    <h2>Package Manager</h2>
    <p class="working-stream-copy">Make project dependencies easier to discover, manage, and install, including technology packages and hardware-specific files.</p>
    <div class="working-stream-status"><i></i><span>IN DEVELOPMENT</span></div>
  </article>
</div>

<br/>

<div class="working-principle" v-click>
  <div class="working-principle-title"><strong>Where should we focus next?</strong></div>
  <p>Do you have suggestions for our next priorities?</p>
</div>

<div class="slide-id">40</div>

<!--

Dovolte mi na závěr být trochu upřímný.
Nestojíme tady proto, že si myslíme, že jsme vyřešili DevOps v průmyslové automatizaci.
Stojíme tady proto, že si myslíme, že jsme došli dost daleko na to, abychom to začali používat v praxi.
Máme nástroje.
Máme workflows.
Máme dema.
Máme zákazníky, kteří o to mají zájem.
Ale také jsme se naučili, že některé věci to pořád zbytečně ztěžují.

[CLICK]

První věc, na které pracujeme, je Automation Studio v Dockeru.
Když se podíváme, jak dnes probíhá moderní vývoj softwaru v IT světě, člověk skoro očekává, že dokáže spustit nové prostředí jedním příkazem.

Stejná verze.
Stejné závislosti.
Stejné nastavení.
Pokaždé.

To je extrémně atraktivní, když pracujete s CI/CD, build servery a AI agenty.
Protože čím méně záleží na prostředí, tím snazší je automatizace.
Ale je to zároveň těžký problém.
Automation Studio nebylo od začátku navržené jako cloud-nativní aplikace.
Takže na tomhle aktivně pracujeme a zkoumáme to.

[CLICK]

Druhá věc je package management.
Když se podíváme na moderní softwarové projekty, závislosti jsou něco, co se skoro bere jako samozřejmost.
Napíšete, na čem projekt závisí.
A systém to najde, stáhne a nainstaluje.
V automatizaci bývá realita často složitější.
Technology packages.
Popisy hardwaru.
Verze firmwaru.
Speciální komponenty.
Mnozí z nás zažili, že dostali projekt a strávili půl dne hledáním všeho, co k sestavení chybí.
Přesně tuhle zkušenost chceme zlepšit.

[CLICK]

A to je asi vůbec nejdůležitější část tohoto slidu.
Myslíme si, že jsme na správné cestě.
Ale minimálně stejně nás zajímá, co si o tom myslíte vy.
Protože zákazník používá systém způsobem, který si sami nikdy nedokážeme nasimulovat.
Takže kdybyste si měli vybrat:
Co by pro vás vytvořilo největší hodnotu?
Co je největší překážka, aby se s tím dalo začít?
Co nám chybí?
Protože další fáze se netýká jen budování nástrojů.
Jde o to naučit se, jak se tyto nástroje používají v realitě.

Přechod:
A s tím bychom moc rádi slyšeli, co si o tom myslíte.

-->


---
layout: default
class: questions-slide dark-slide
---

<div class="kicker">CLOSING · OPEN DISCUSSION</div>

# Questions?
<br />
<div class="questions-hero">
  <div class="questions-mark" aria-hidden="true"><span>OPEN FLOOR</span><b>?</b></div>
  <div class="questions-hero-copy">
    <span>OVER TO YOU</span>
    <strong>What should we explore next?</strong>
    <p>What do you think?</p>
  </div>
</div>

<div class="questions-footer"><span>THANK YOU</span><i></i><b>B&amp;R INDUSTRIAL AUTOMATION &middot; AGENTIC ENGINEERING + DEVOPS</b></div>

<div class="slide-id">41</div>