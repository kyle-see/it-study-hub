# IT fundamentals — study hub

**To help a learner learn the concepts introduced in Coursera's Google IT Support Professional
Certificate and the CompTIA A+ Core 1 and Core 2 objectives** — understand them, say them back, then
prove it on the drills.

Interactive study pages for **Coursera's Google IT Support Professional Certificate** (all six
courses) with **CompTIA A+ Core 1 and Core 2** filed into the same modules.

**Start here → `learn/index.html` — the learning path.** All 35 modules at entry-certification
level: why each one exists, what you must be able to do afterwards, and the facts the exams
actually test. Taught modules link into the lesson and its drills; untaught ones are labelled as
facts only rather than promised.

Every module page opens with **the essentials**, then explains them, with a drill after each part,
then flashcards and a quiz that explains every answer and remembers what you missed. Hover
tooltips on every acronym. One self-contained `.html` file per page: no fonts fetched, no CDN, no
trackers, no analytics. It works offline, from a phone, from a double-click.

Personal study notes. Not affiliated with, sponsored by or endorsed by Google, CompTIA, Coursera
or NPower; course titles and trademarks belong to their owners. Every definition, explanation and
quiz question in this repo is written for this site: the courses supply the syllabus and the vocabulary,
not the prose.

## Use it, share the link

[CC BY-NC-ND 4.0](LICENSE.md): attribute it, don't sell it, don't remix it. Read it as much as you like
and send people to `https://kyle-see.github.io/it-study-hub/` rather than copying the files around — one
place stays corrected, and the mirror nobody maintains is the one that keeps getting shared.

Support is optional and changes nothing: <https://buymeacoffee.com/kyle.see>.

## How this was built

Every page here — the prose, the drills, the generators that build them and the gate that checks them —
was written by a model running on the author's own machine, under his direction and review: a
`pi-agent` session driving **DeepSeek-V4.1-Flash-1017** (Unsloth `UD-Q3_K_XL`) served locally through
**llama-swap**. No Claude, OpenAI or other hosted model wrote any of it. The loop was a person's: he set
the syllabus, the house style and the standard a page had to reach, read every page, and sent it back
until it did. The machines did the typing and the arithmetic, and a gate recomputes the numbers before
anything is published — which is why the site can promise that a wrong answer is never marked right.

## Spotted a mistake?

[Open an issue](https://github.com/kyle-see/it-study-hub/issues/new). A wrong sentence on a page that a
hundred people read is worth more to fix than to leave, and the fix ships the same day.
