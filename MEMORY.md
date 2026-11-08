# MEMORY — Lillian's Stories

## Project goal

Produce a **series of books** telling the story of **Lillian**, a woman from the late Generation X, whose very rich life can be organized into a **collection of books**.

## Still to decide (later)

- Number of pages per book
- Organization of the chapters
- Structure of the collection (by period, by theme, by character…)
- Tone and style of the books

## Current phase: gathering information

No book writing for now. Little by little, over the exchanges and commits, we build a base of material in the form of Markdown files.

### 1. People (`people/`)

One file per person who is part of Lillian's life. Each file covers:

- their relationships with one another
- their relationships with Lillian
- their impact on her life
- their importance in her life
- their importance in her story and the shaping of who she is
- a **table of the periods** in which they appear, placed at the top of the file, right after the title (period, era, place, what was shared)
- everything that helps understand their impact on Lillian: pains, joys, strong feelings they stirred

Template: [people/_template.md](people/_template.md)

### 2. Periods (`periods/`)

One file per period of Lillian's life. Each file covers:

- the country, the city
- the date or dates
- the people around her, with life anecdotes and emotionally strong or deep stories in the relationship
- the stories and small details of the period
- the landscapes and the atmosphere

Template: [periods/_template.md](periods/_template.md)

### 3. Eras (`eras/`)

An era is a large part of Lillian's life, which can become **a book in the collection**. Its periods are the chapters. Each era file covers:

- the dates and Lillian's age
- a summary of the era
- the list of the periods that make it up
- the common thread and the stakes
- the interviews to plan with Lillian (themes, status)

An era describes its content in a few paragraphs and lists the periods that make it up. **People are linked only to periods, not to eras** (we will see later whether a table of people is useful at era level).

Template: [eras/_template.md](eras/_template.md)

## Repository structure

```
MEMORY.md              ← this file: goal, method, index
README.md              ← project pitch and links to the three folders
questions.md           ← open questions per person, by theme (snapshot of the "To clarify" sections)
eras/
  README.md            ← list of the eras
  _template.md         ← era file template
  01-origins-and-early-childhood.md
  02-childhood-and-teens-in-france.md
  03-back-to-the-united-states.md
  04-marriage-to-mohamed.md
  05-flight-attendant-hawaii-alaska.md
  06-back-to-france.md
  07-chris-and-nice-draft.md
people/
  README.md            ← list of the people
  _template.md         ← person file template
  lillian.md
  dad.md
  mom.md
  gwen.md
  eliot.md
  alexandre.md
  julia.md
  clement.md
  aymeric.md
  thomas.md
  xavier.md
  maternal-grandfather.md
  maternal-grandmother.md
  marc-lambert.md
  lou.md
  didier.md
  julie.md
  jerome.md
  paternal-grandmother.md
  paternal-grandfather.md
  larry.md
  jackie.md
  john.md
  michael.md
  christine.md
  joanne.md
  clara.md
  mohamed.md
  david-job-courts.md
  david-ny.md
  danielle.md
  david-hawaii.md
  steve.md
  walter.md
  yacine.md
  julien.md
  karen.md
  kisha.md
  geaniie.md
  april.md
  brahim.md
  mohamed-mother.md
  youssef.md
  zachzria.md
  zouria.md
  adriana.md
  jose.md
  mike.md
  cecile.md
  ivan.md
  miss-v.md
  veronica.md
  charlotte.md
  nicole.md
  patrice.md
  sebastien.md
  emilie.md
  romane.md
  raphael.md
  hanae.md
  kakinou.md
  gaelle.md
  julie-flazon.md
  kerezore.md
  laura-moreau.md
  kay.md
  sandrine.md
  james.md
  kim.md
  daniel.md
  christophe.md
  louis.md
periods/
  README.md            ← list of the periods
  _template.md         ← period file template
  01-01-meeting-in-frankfurt.md
  01-02-birth-in-heidelberg.md
  01-03-early-childhood-with-family.md
  01-04-summer-1985-saint-brevin.md
  02-01-childhood-and-teens-in-france.md
  03-01-syracuse-finding-dad.md
  03-02-job-courts.md
  03-03-new-york-city.md
  04-01-married-life-with-mohamed.md
  04-02-nurse-in-hospices-baltimore.md
  05-01-flight-attendant.md
  05-02-nurse-in-hawaii.md
  05-03-nurse-in-alaska.md
  06-01-daniel-brittany-ferries.md
  06-02-apartment-in-rennes.md
  06-03-greece-with-eliot.md
  07-01-meeting-chris.md
  07-02-holidays-in-correze.md
```

Convention: file names in English, lowercase, no accents, hyphens instead of spaces.

- **Eras** are prefixed with a chronological order number: `01-origins-and-early-childhood.md`.
- **Periods** are prefixed with the number of their era, then their number within the era: `03-03-new-york-city.md` is the 2nd period of era 03. Inserting a period only affects its era.

## Index

### People

| File | Summary |
|---|---|
| [lillian](people/lillian.md) | The main character. Has lived in Nice for about 1 year. |
| [dad](people/dad.md) | Mark, American, soldier (GI, Iraq), lives in Syracuse (New York State). |
| [mom](people/mom.md) | Béatrice, dental assistant, former au pair, lives in Saint-Brieuc, France. |
| [gwen](people/gwen.md) | Younger sister, born in 1982, lives in Vendôme. Four children; a hard, chaotic life that has always affected the family, and above all Lillian (sensitive). |
| [eliot](people/eliot.md) | Gwen's first son, with Aymeric; raised by his father after a court ruling (sensitive). |
| [alexandre](people/alexandre.md) | Child of Gwen and Thomas. |
| [julia](people/julia.md) | Child of Gwen and Thomas. |
| [clement](people/clement.md) | Child of Gwen and Thomas. |
| [aymeric](people/aymeric.md) | Florist, Gwen's first husband and Eliot's father; forced marriage (sensitive). |
| [thomas](people/thomas.md) | Petty officer, Gwen's partner and father of Alexandre, Julia and Clément; never married. |
| [xavier](people/xavier.md) | Younger brother, born after summer 1985, lives in Nantes. |
| [maternal-grandfather](people/maternal-grandfather.md) | Papouche, Béatrice's father and a notable of Saint-Brevin. An anchor and a symbol of fatherhood for Lillian; took Béatrice and her children in in 1985. |
| [maternal-grandmother](people/maternal-grandmother.md) | Mamouche, Papouche's wife. A soothing relationship, in listening and kindness toward the family; took Béatrice and her children in in 1985. |
| [paternal-grandmother](people/paternal-grandmother.md) | Mark's mother and Lillian's namesake, deceased; widowed at 36, waitress in diners, sent Christmas parcels to France (sensitive). |
| [paternal-grandfather](people/paternal-grandfather.md) | Mark's father, an accountant, died when Mark was 8; Lillian never knew him. |
| [larry](people/larry.md) | Mark's older brother, killed at 14 by a rock; the result of a rape of his mother (sensitive). |
| [jackie](people/jackie.md) | Mark's sister; one of the 7 children of Grandma Lillian. |
| [john](people/john.md) | Mark's brother; one of the 7 children of Grandma Lillian. |
| [michael](people/michael.md) | Mark's brother; one of the 7 children of Grandma Lillian. |
| [christine](people/christine.md) | Mark's sister; one of the 7 children of Grandma Lillian. |
| [joanne](people/joanne.md) | Mark's sister; one of the 7 children of Grandma Lillian. |
| [marc-lambert](people/marc-lambert.md) | Béatrice's partner around 1991-1994, owned a bar on the beach; Lillian never liked him (sensitive). |
| [lou](people/lou.md) | Lillian's aunt (Béatrice's sister, to confirm); phoned her about Papouche's death. |
| [didier](people/didier.md) | Lillian's uncle (Béatrice's brother, to confirm), father of Julie and Jérôme. |
| [julie](people/julie.md) | Lillian's cousin, lives in Switzerland. |
| [jerome](people/jerome.md) | Julie's brother, lives in England with his wife and 2 children. |
| [clara](people/clara.md) | Puerto Rican teacher born in 1950, Mark's partner in Syracuse; her ultimatum led Lillian to leave. |
| [mohamed](people/mohamed.md) | Lillian's husband for 15 years, wedding in March 2003 (sensitive). |
| [david-job-courts](people/david-job-courts.md) | Ivan's brother at Job Courts. |
| [david-ny](people/david-ny.md) | Brief Chinese flirt in New York. |
| [danielle](people/danielle.md) | Californian housemate at David's house in Maui. |
| [david-hawaii](people/david-hawaii.md) | Lillian's host in Maui from 2016, met through Kim; took her in at the last minute. |
| [steve](people/steve.md) | Neighbour in Maui (sensitive). |
| [walter](people/walter.md) | From Bangladesh, met in New York. |
| [yacine](people/yacine.md) | Mohamed's childhood friend who became Lillian's friend; now in Japan. |
| [karen](people/karen.md) | Steve's partner, neighbour in Maui (sensitive). |
| [kisha](people/kisha.md) | Short-time landlady in Maui, a friend of David (Hawaii). |
| [julien](people/julien.md) | Married man Lillian dated after the second separation from Mohamed (sensitive). |
| [geaniie](people/geaniie.md) | Flatmate for 6 months during the first separation; a Black woman of about 60 who became a close friend. |
| [april](people/april.md) | Met at the hairdressing school in Albany. |
| [brahim](people/brahim.md) | Mohamed's friend, married to an American woman. |
| [mohamed-mother](people/mohamed-mother.md) | An adorable woman, Lillian's mother-in-law. |
| [youssef](people/youssef.md) | Mohamed's brother, never met. |
| [zachzria](people/zachzria.md) | Mohamed's brother, never met. |
| [zouria](people/zouria.md) | Mohamed's sister; visited pregnant two weeks after Lillian's abortion in 2006 (sensitive). |
| [adriana](people/adriana.md) | Friend from era 05. |
| [jose](people/jose.md) | A love from era 05. |
| [sandrine](people/sandrine.md) | One of Lillian's best friends since the boarding school. |
| [james](people/james.md) | Cousin, son of Jackie; « back to your roots ». |
| [kay](people/kay.md) | Lillian's female friend in Alaska. |
| [gaelle](people/gaelle.md) | Cousin, Kakinou's daughter (to confirm). |
| [kakinou](people/kakinou.md) | Aunt, alcoholic, died in 2017 (sensitive). |
| [julie-flazon](people/julie-flazon.md) | Middle-school friend; her sister's secret (sensitive). |
| [kerezore](people/kerezore.md) | Spanish teacher at middle school (sensitive). |
| [laura-moreau](people/laura-moreau.md) | School friend who repeated the secret. |
| [patrice](people/patrice.md) | Chris's father. |
| [sebastien](people/sebastien.md) | Chris's brother, urologist surgeon in Nantes. |
| [emilie](people/emilie.md) | Chris's sister-in-law, obstetrician. |
| [romane](people/romane.md) | Chris's niece (2010). |
| [raphael](people/raphael.md) | Chris's nephew (2013). |
| [hanae](people/hanae.md) | Chris's niece (2016). |
| [ivan](people/ivan.md) | Friend from Ecuador at Job Courts. |
| [miss-v](people/miss-v.md) | Supervisor at Job Courts. |
| [veronica](people/veronica.md) | Friend who went to Hawaii with Lillian and Kim. |
| [charlotte](people/charlotte.md) | Boarding-school friend, restores old furniture in Nantes. |
| [nicole](people/nicole.md) | Chris's mother; put Lillian at ease in Corrèze. |
| [cecile](people/cecile.md) | Aymeric's partner, present in Eliot's life. |
| [mike](people/mike.md) | Hawaii friend, car dealer; received and sent her French passport in 2020. |
| [kim](people/kim.md) | Flight attendant friend; introduced Lillian to Hawaii and to David, then broke up with him just before the move. |
| [daniel](people/daniel.md) | Romantic encounter in 2021 in Rennes (sensitive). |
| [louis](people/louis.md) | Chris's son, who lives with Lillian and Chris in Nice (draft). |
| [christophe](people/christophe.md) | Chris, Lillian's partner since April 2023 (draft). |

### Eras

| File | Summary |
|---|---|
| [01 — Origins and early childhood](eras/01-origins-and-early-childhood.md) | From the parents' meeting (1976) to summer 1985. |
| [02 — Childhood and adolescence in France](eras/02-childhood-and-teens-in-france.md) | Starter: 1985 to September 1998. |
| [03 — Back to the United States](eras/03-back-to-the-united-states.md) | Finding her father, the Clara disappointment, New York, meeting Mohamed. |
| [04 — Marriage to Mohamed](eras/04-marriage-to-mohamed.md) | 15 years of marriage (sensitive). |
| [05 — Flight attendant, Hawaii, Alaska](eras/05-flight-attendant-hawaii-alaska.md) | Three periods of work and encounters; from 2014 (Omni Air, Hawaii in 2016). |
| [06 — Back to France](eras/06-back-to-france.md) | 2021: Rennes, Brittany Ferries, moving closer to family. |
| [07 — Chris and Nice (draft)](eras/07-chris-and-nice-draft.md) | After 01/01/2023, draft. |

### Periods

| File | Summary |
|---|---|
| [01-01 — Meeting in Frankfurt](periods/01-01-meeting-in-frankfurt.md) | 1976, Mark and Béatrice meet in a GI bar. |
| [01-02 — Birth in Heidelberg](periods/01-02-birth-in-heidelberg.md) | 1979, birth at the military hospital. |
| [01-03 — Early childhood with family](periods/01-03-early-childhood-with-family.md) | 1979-1985, life with Mark, Gwen's birth. |
| [01-04 — Summer 1985 in Saint-Brevin](periods/01-04-summer-1985-saint-brevin.md) | The holiday that becomes a permanent return to France. |
| [02-01 — Childhood and adolescence in France](periods/02-01-childhood-and-teens-in-france.md) | Starter: 1985 to September 1998. |
| [03-01 — Syracuse: finding Dad](periods/03-01-syracuse-finding-dad.md) | Arrival on 11 September 1998, life with Mark, Clara's ultimatum, leaving Syracuse. |
| [03-02 — Job Courts](periods/03-02-job-courts.md) | Free programme for disadvantaged youth in New York State, social-class shock, Miss V. |
| [03-03 — New York City](periods/03-03-new-york-city.md) | David, Walter, meeting Mohamed. |
| [04-01 — Married life with Mohamed](periods/04-01-married-life-with-mohamed.md) | 15 years of marriage (sensitive). |
| [04-02 — Nurse in hospices, Baltimore](periods/04-02-nurse-in-hospices-baltimore.md) | 2008-2013, hospices, the office job, the decision to change. |
| [05-01 — Flight attendant](periods/05-01-flight-attendant.md) | 2014-2016, Omni Air; the call of Hawaii. |
| [05-02 — Nurse in Hawaii](periods/05-02-nurse-in-hawaii.md) | Maui, from 2016, welcomed by David. |
| [05-03 — Nurse in Alaska](periods/05-03-nurse-in-alaska.md) | Seward, by the sea: the COVID, nature, Kim and friends. |
| [06-01 — Daniel, Brittany Ferries, 2nd abortion](periods/06-01-daniel-brittany-ferries.md) | 2021, Rennes (sensitive). |
| [06-02 — Apartment in Rennes](periods/06-02-apartment-in-rennes.md) | A calmer period, close to family. |
| [06-03 — Greece with Eliot](periods/06-03-greece-with-eliot.md) | A trip with her nephew Eliot after the separation from José. |
| [07-01 — Meeting Chris](periods/07-01-meeting-chris.md) | April 2023, Tinder, Rennes then Carnac. Draft. |
| [07-02 — Holidays in Corrèze](periods/07-02-holidays-in-correze.md) | A holiday week with Chris's family and Julia. Draft. |

## Working rules (to apply at every exchange)

- Invent nothing: anything not confirmed by Lillian stays in the “To clarify” section.
- Files grow over the exchanges; every significant addition gets its own commit.

### Rule 1 — The “To clarify” section

- Every file (person or period) contains a **“To clarify”** section.
- Whenever we discover a person or a period, and as the exchanges on that subject go on, we write down the questions that would help complete our understanding:
  - of the character
  - of the context
  - of a situation
  - of a period
  - of a particular event
  - of a personal story to dig into with a character
- This section is **updated at every exchange**: new questions are added, and the ones that have been answered are removed (the answer is moved to the right section of the file).

### Rule 2 — A period that introduces a person

- If, while talking about a period, a new person comes up, we **create their file** in `people/` from the template.
- The person file is **linked to the various periods** in which they appear (table at the top of the file, right after the title), and the period file is linked to the person file (“People around her” section).
- **Every named person mentioned in a period must have a person file.**
- **Lillian is the main character**: she is listed first in the “People around her” section of every period, with her role in that period.
- People or groups **without a name** (in-laws, friends, children, colleagues) get no file: they are mentioned in the period, and “To clarify” asks for their name. As soon as they are named, the file is created.

### Rule 3 — A person who introduces a period

- Conversely, if, while talking about a person, a period comes up that does not exist yet, we **create the period file** in `periods/` from the template, with its `EE-PP` number.
- Links are set in both directions, as in rule 2.

### Rule 4 — Eras

- Every period belongs to an **era** (“Era” field at the top of the file, in the introduction) and is listed in the “Periods” table of the era file.
- Every new period is added to its matching era, in both directions.
- Eras are the candidates for splitting into books, though this is not decided.
- Every era file contains an **“Interviews to plan”** section: themes to cover with Lillian and status (to do, done). Planned: era 04, 1 to 2 interviews; era 05, at least 1 interview per period (flight attendant, Hawaii, Alaska).

### Rule 5 — Index

- Every file created is added to the index of this file, and to the `README.md` of its folder.

### Rule 6 — Draft after 01/01/2023 (temporary rule)

- Everything about Lillian's life **after 01/01/2023** (including era 07, Chris and Nice) is treated as a **draft**: we create only the minimum, and the “To clarify” section contains **at most 3 essential questions** (dates, place, role of the person), with no questions about details, emotions or anecdotes.
- **To be removed** once eras 01 to 06 have been covered: we will then ask as many questions as needed to clarify this era.

### Rule 7 — Sensitive subjects

- For sensitive subjects (abortions, alcohol, humiliation, abandonment, violence…), the facts are recorded **soberly**, with no invented detail.
- The file concerned carries the mention: “**Sensitive: to confirm with Lillian before any use in a book**”.
- The names of real people are to be confirmed again with Lillian at the time of writing.

### Rule 8 — Commits

- Organizational changes are committed **separately**, in this order: rules (`MEMORY.md`), then eras, then periods, then people.
- Commit messages are in English (see rule 10), short, and end with the co-author line required by the tool.

### Rule 9 — Questions for Lillian

- Questions are asked **grouped by theme**.
- Before building a reorganization plan, we first ask **all the questions** needed to fully understand the request.

### Rule 10 — Language

- The default language of all documents (rules, templates, files, link labels, commit messages) is **English**.
- French is kept only where it is the better fit: a term or expression with no exact English equivalent, a specifically French notion (institution, custom, dish…), Lillian's own words, or the name of a town or place in France.
- French words and expressions are written **in quotation marks**, followed by their English translation in brackets: « fief » [home base].
- Names of towns and places (Saint-Brevin, Rennes, Saint-Brieuc) are proper names: they are written as is, without quotation marks or translation.
- File and folder names are always in English (see the convention under “Repository structure”).
