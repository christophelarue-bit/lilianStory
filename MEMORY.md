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
README.md              ← project pitch
eras/
  _template.md         ← era file template
  01-origins-and-early-childhood.md
  02-childhood-and-teens-in-france.md
  03-back-to-the-united-states.md
  04-marriage-to-mohamed.md
  05-flight-attendant-hawaii-alaska.md
  06-back-to-france.md
  07-chris-and-nice-draft.md
people/
  _template.md         ← person file template
  lillian.md
  dad.md
  mom.md
  gwen.md
  xavier.md
  maternal-grandfather.md
  clara.md
  mohamed.md
  david-ny.md
  david-friend.md
  walter.md
  yacine.md
  adriana.md
  jose.md
  the-rennes-man.md
  christophe.md
periods/
  _template.md         ← period file template
  01-01-meeting-in-frankfurt.md
  01-02-birth-in-heidelberg.md
  01-03-early-childhood-with-family.md
  01-04-summer-1985-saint-brevin.md
  02-01-childhood-and-teens-in-france.md
  03-01-syracuse-finding-dad.md
  03-02-new-york-city.md
  04-01-married-life-with-mohamed.md
  05-01-flight-attendant.md
  05-02-nurse-in-hawaii.md
  05-03-nurse-in-alaska.md
  06-01-the-rennes-man-brittany-ferries.md
  06-02-apartment-in-rennes.md
  07-01-meeting-chris.md
```

Convention: file names in English, lowercase, no accents, hyphens instead of spaces.

- **Eras** are prefixed with a chronological order number: `01-origins-and-early-childhood.md`.
- **Periods** are prefixed with the number of their era, then their number within the era: `03-02-new-york-city.md` is the 2nd period of era 03. Inserting a period only affects its era.

## Index

### People

| File | Summary |
|---|---|
| [lillian](people/lillian.md) | The main character. Has lived in Nice for about 1 year. |
| [dad](people/dad.md) | Mark, American, soldier (GI, Iraq), lives in Syracuse (New York State). |
| [mom](people/mom.md) | Béatrice, former au pair, lives in Saint-Brieuc, France. |
| [gwen](people/gwen.md) | Younger sister, born in 1982, lives in Vendôme. |
| [xavier](people/xavier.md) | Younger brother, born after summer 1985, lives in Nantes. |
| [maternal-grandfather](people/maternal-grandfather.md) | Béatrice's father, suggested she stay in France in 1985. |
| [clara](people/clara.md) | Role to clarify, linked to a wound involving Mark. |
| [mohamed](people/mohamed.md) | Lillian's husband for 15 years (sensitive). |
| [david-ny](people/david-ny.md) | Brief Chinese flirt in New York. |
| [david-friend](people/david-friend.md) | Friend from era 05, with Adriana. |
| [walter](people/walter.md) | From Bangladesh, met in New York. |
| [yacine](people/yacine.md) | Met during the marriage, role to clarify. |
| [adriana](people/adriana.md) | Friend from era 05. |
| [jose](people/jose.md) | A love from era 05. |
| [the-rennes-man](people/the-rennes-man.md) | Romantic encounter in 2021 in Rennes (sensitive). |
| [christophe](people/christophe.md) | Chris, minimal draft file. |

### Eras

| File | Summary |
|---|---|
| [01 — Origins and early childhood](eras/01-origins-and-early-childhood.md) | From the parents' meeting (1976) to summer 1985. |
| [02 — Childhood and adolescence in France](eras/02-childhood-and-teens-in-france.md) | Starter: 1985 to around 1997. |
| [03 — Back to the United States](eras/03-back-to-the-united-states.md) | Finding her father, the Clara disappointment, New York, meeting Mohamed. |
| [04 — Marriage to Mohamed](eras/04-marriage-to-mohamed.md) | 15 years of marriage (sensitive). |
| [05 — Flight attendant, Hawaii, Alaska](eras/05-flight-attendant-hawaii-alaska.md) | Three periods of work and encounters. |
| [06 — Back to France](eras/06-back-to-france.md) | 2021: Rennes, Brittany Ferries, moving closer to family. |
| [07 — Chris and Nice (draft)](eras/07-chris-and-nice-draft.md) | After 01/01/2023, draft. |

### Periods

| File | Summary |
|---|---|
| [01-01 — Meeting in Frankfurt](periods/01-01-meeting-in-frankfurt.md) | 1976, Mark and Béatrice meet in a GI bar. |
| [01-02 — Birth in Heidelberg](periods/01-02-birth-in-heidelberg.md) | 1979, birth at the military hospital. |
| [01-03 — Early childhood with family](periods/01-03-early-childhood-with-family.md) | 1979-1985, life with Mark, Gwen's birth. |
| [01-04 — Summer 1985 in Saint-Brevin](periods/01-04-summer-1985-saint-brevin.md) | The holiday that becomes a permanent return to France. |
| [02-01 — Childhood and adolescence in France](periods/02-01-childhood-and-teens-in-france.md) | Starter: 1985 to around 1997. |
| [03-01 — Syracuse: finding Dad](periods/03-01-syracuse-finding-dad.md) | Starter: reunion with Mark, the Clara disappointment. |
| [03-02 — New York City](periods/03-02-new-york-city.md) | David, Walter, meeting Mohamed. |
| [04-01 — Married life with Mohamed](periods/04-01-married-life-with-mohamed.md) | 15 years of marriage (sensitive). |
| [05-01 — Flight attendant](periods/05-01-flight-attendant.md) | Starter. |
| [05-02 — Nurse in Hawaii](periods/05-02-nurse-in-hawaii.md) | Starter. |
| [05-03 — Nurse in Alaska](periods/05-03-nurse-in-alaska.md) | Starter. |
| [06-01 — The Rennes man, Brittany Ferries, 2nd abortion](periods/06-01-the-rennes-man-brittany-ferries.md) | 2021, Rennes (sensitive). |
| [06-02 — Apartment in Rennes](periods/06-02-apartment-in-rennes.md) | A calmer period, close to family. |
| [07-01 — Meeting Chris](periods/07-01-meeting-chris.md) | Draft. |

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

- Every file created is added to the index of this file.

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
