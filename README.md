<div align="center">

```
┌──────────────────────────────────────────────────────────────────────┐
│ ● ● ●                                              root@sur4j: ~     │
├──────────────────────────────────────────────────────────────────────┤
│                                                                        │
│    ███████╗██╗   ██╗██████╗ ██╗  ██╗     ██╗                        │
│    ██╔════╝██║   ██║██╔══██╗██║  ██║     ██║                        │
│    ███████╗██║   ██║██████╔╝███████║     ██║                        │
│    ╚════██║██║   ██║██╔══██╗╚════██║██   ██║                        │
│    ███████║╚██████╔╝██║  ██║     ██║╚█████╔╝                        │
│    ╚══════╝ ╚═════╝ ╚═╝  ╚═╝     ╚═╝ ╚════╝                         │
│                                                                        │
│    BACKEND ENGINEER // AI ENGINEER // SYSTEM BUILDER                  │
│    ACCESS LEVEL: ROOT            STATUS: BUILDING                     │
│                                                                        │
└──────────────────────────────────────────────────────────────────────┘
```

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=14&duration=2800&pause=1000&color=00FF41&background=00000000&center=true&vCenter=true&width=620&height=28&lines=connecting+to+sur4j%40github...;authentication+successful;loading+profile+data...;ready." />

</div>

```
root@sur4j:~$ env | grep SUR4J
SUR4J_STATUS=BUILDING
SUR4J_FOCUS=BACKEND+AI
SUR4J_MODE=ENGINEERING
SUR4J_SIGNAL=ACTIVE
```

---

### `root@sur4j:~$ whoami`

Third-year CSE student building backend systems, AI applications, APIs, automation and products.

I care less about making the happy path work and more about understanding what happens when everything goes wrong — that's usually where the real system reveals itself.

```
IDEA → ARCHITECTURE → IMPLEMENTATION → TEST → BREAK → DEBUG → REFACTOR → SHIP
```

**Core interests:** `BACKEND ENGINEERING` `AI / LLM SYSTEMS` `SYSTEM DESIGN` `API ARCHITECTURE` `AUTOMATION` `PRODUCT ENGINEERING` `TESTING`

---

### `root@sur4j:~$ ls -la ./stack`

```
drwxr-xr-x  languages/     javascript  typescript  python  java  c++  sql
drwxr-xr-x  backend_ai/    node.js  express  rest-apis  llms  prompt-engineering  structured-ai-output
drwxr-xr-x  engineering/   git  github  testing  debugging  system-design  automation
```

---

### `root@sur4j:~$ ls -la ./projects`

```
-rw-r--r--  01_siteforge.md      AI BUSINESS -> WEBSITE ENGINEERING              [ACTIVE]
-rw-r--r--  02_fables_lab.md     PRODUCTS -> EXPERIMENTS -> SYSTEMS              [ACTIVE]
-rw-r--r--  03_carefree.md       IDEA -> PRODUCT -> SYSTEM -> INTERFACE -> USER  [ACTIVE]
-rw-r--r--  04_monetra.md        DATA -> LOGIC -> APPLICATION -> EXPERIENCE      [ACTIVE]
-rw-r--r--  05_inphase.md        COMPONENTS -> INTERFACES -> STATE -> LOGIC      [ACTIVE]
```

<details open>
<summary><code>root@sur4j:~$ cat ./projects/01_siteforge.md</code></summary>

<br/>

**SITEFORGE** — `AI BUSINESS → WEBSITE ENGINEERING` — centerpiece project

SiteForge explores how AI can turn raw, messy business information into structured website specifications — and eventually deployable websites — without letting the model freelance on anything that actually matters.

```
BUSINESS INPUT
      ↓
DATA EXTRACTION
      ↓
BUSINESS INTELLIGENCE
      ↓
BRAND DNA
      ↓
WEBSITE STRATEGY
      ↓
LANDING PAGE SPEC
      ↓
WEBSITE GENERATION
      ↓
VALIDATION
      ↓
DEPLOYMENT
```

`tags:` `BUSINESS DATA EXTRACTION` `PLACE / BUSINESS RESOLUTION` `STATE ISOLATION` `BUSINESS INTELLIGENCE` `BRAND DNA` `STRUCTURED AI GENERATION` `JSON VALIDATION` `FAIL-FAST VALIDATION` `SERVICE BOUNDARIES` `PIPELINE TESTING` `END-TO-END TESTING`

```
# NOTE — the actual engineering problem:
# how do you make probabilistic AI behave
# inside a deterministic software pipeline?
```

</details>

<details>
<summary><code>root@sur4j:~$ cat ./projects/02_fables_lab.md</code></summary>

<br/>

**FABLES LAB** — `PRODUCTS → EXPERIMENTS → SYSTEMS`

An experimentation ground for products, systems and ideas that deserve to escape the notes app before someone else builds them first.

</details>

<details>
<summary><code>root@sur4j:~$ cat ./projects/03_carefree.md</code></summary>

<br/>

**CAREFREE** — `IDEA → PRODUCT → SYSTEM → INTERFACE → USER`

Product engineering focused on turning a concept into usable, shippable software — not a proof of concept that lives in a demo folder.

</details>

<details>
<summary><code>root@sur4j:~$ cat ./projects/04_monetra.md</code></summary>

<br/>

**MONETRA** — `DATA → LOGIC → APPLICATION → EXPERIENCE`

A product-oriented engineering project centered on data, application logic and usability.

</details>

<details>
<summary><code>root@sur4j:~$ cat ./projects/05_inphase.md</code></summary>

<br/>

**INPHASE** — `COMPONENTS → INTERFACES → STATE → LOGIC → SYSTEM`

Application and systems engineering — concerned with how individual components resolve into one coherent product.

</details>

---

### `root@sur4j:~$ cat ./system_design.log`

```
                    ┌────────────┐
                    │   CLIENT   │
                    └─────┬──────┘
                          ↓
                    ┌────────────┐
                    │    API     │
                    └─────┬──────┘
                          ↓
                    ┌────────────┐
                    │  VALIDATOR │
                    └─────┬──────┘
                          ↓
              ┌───────────┴───────────┐
              ↓                       ↓
      ┌────────────────┐    ┌────────────────┐
      │    SERVICES     │    │  AI PIPELINES  │
      └────────┬────────┘    └────────┬───────┘
               └───────────┬──────────┘
                           ↓
                    ┌────────────┐
                    │ DATA LAYER │
                    └────────────┘
```

`actively considered:` `SCALABILITY` `STATE` `CONSISTENCY` `LATENCY` `FAILURE MODES` `SERVICE BOUNDARIES` `VALIDATION` `OBSERVABILITY` `RECOVERY`

---

### `root@sur4j:~$ cat ./ai_architecture.log`

```
INPUT -> CONTEXT -> PROMPT -> MODEL -> STRUCTURED OUTPUT -> PARSER -> VALIDATOR -> NORMALIZER -> BUSINESS LOGIC -> OUTPUT
```

```
# design rule
LLM != DATABASE
LLM != VALIDATOR
LLM != BUSINESS LOGIC
LLM != SOURCE OF TRUTH

# AI is a component. Not the entire architecture.
```

---

### `root@sur4j:~$ cat ./testing.log`

```
# happy-path testing tells me the demo works.
# failure-path testing tells me whether I actually built a system.
```

```
FAILURE CLASS   EXAMPLES
─────────────   ────────────────────────────────────────────────
INPUT           missing input, invalid input, duplicate input
OUTPUT          malformed AI output, missing fields, bad structure
STATE           state leakage, cross-request contamination
EXTERNAL        third-party failure, timeouts
EDGE            boundary conditions, unexpected combinations
```

```
UNIT -> SERVICE -> INTEGRATION -> PIPELINE -> END-TO-END
```

---

### `root@sur4j:~$ ./debug_system`

```
[BOOT]  services ..................... OK
[BOOT]  ai pipeline ................... OK
[BOOT]  validation ..................... OK
[TEST]  running ........................
[WARN]  unexpected output detected

[DEBUG] inspecting input
[DEBUG] inspecting state
[DEBUG] inspecting service boundary
[DEBUG] inspecting assumptions

[RESULT] bug located -> human code, not the model
[FIX]    applied
[TEST]   PASS
[SHIP]   READY
```

---

### `root@sur4j:~$ cat MANIFESTO.txt`

```
01  DESIGN BEFORE CODING
02  VALIDATE ASSUMPTIONS
03  EXPECT FAILURE
04  KEEP SERVICES BOUNDED
05  DON'T TRUST RAW AI OUTPUT
06  TEST THE EDGES, NOT JUST THE MIDDLE
07  DEBUG THE ROOT CAUSE, NOT THE SYMPTOM
08  AUTOMATE REPETITIVE WORK
09  SHIP WHAT ACTUALLY WORKS
```

---

### `root@sur4j:~$ curl -s api.github.com/stats`

<table width="100%">
<tr>
<td width="50%" valign="top">

<img width="100%" src="https://github-readme-stats.vercel.app/api?username=notbeingsuraj&show_icons=true&theme=dark&bg_color=000000&title_color=00FF41&icon_color=00FF41&text_color=C9D1D9&border_color=00FF41&hide_border=false"/>

</td>
<td width="50%" valign="top">

<img width="100%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=notbeingsuraj&layout=compact&theme=dark&bg_color=000000&title_color=00FF41&text_color=C9D1D9&border_color=00FF41&hide_border=false"/>

</td>
</tr>
</table>

<img width="100%" src="https://streak-stats.demolab.com/?user=notbeingsuraj&theme=dark&background=000000&stroke=00FF41&ring=00FF41&fire=00FF41&currStreakLabel=00FF41&sideLabels=C9D1D9&dates=6e7681&border=00FF41"/>

---

<div align="center">

```
root@sur4j:~$ echo $STATUS
BUILDING

root@sur4j:~$ ▮
```

[github.com/notbeingsuraj](https://github.com/notbeingsuraj)

</div>
