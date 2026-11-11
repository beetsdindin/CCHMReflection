# Seven Habits Teacher Resource

A grab-and-go webapp for teachers at Chung Cheng High (Main), based on Sean Covey's *The 7 Habits of Highly Effective Teens*.

## Status
Form prototype. Event-focused, Key SDEs only.

- **Events tab:** pick a level (Sec 1-4), then Individual or Class, then a month and event. The card shows the reflection cycle (What? / So What? / Now What?) and event-specific questions.
- **Glossary tab:** common terms and the SDSC 2027 definitions.
- **Questions written so far:** START Right (all four levels, Individual and Class). Other events show "[To be developed]".
- Content marked "[Sample]" or "[To be developed]" is a placeholder.

## Files
- `index.html`: the whole app (HTML, CSS and JavaScript in one file). No build step.

## Run it
Open `index.html` in a browser. It loads two Google Fonts from the web; without a connection it falls back to system fonts.

## Publish with GitHub Pages
1. Upload `index.html` (and this README) to the repository root.
2. In the repository, go to Settings, then Pages.
3. Under Source, choose the main branch and the root folder, then Save.
4. The site appears at `https://<username>.github.io/<repository>/` after a minute or two.

## Editing content
Data sits at the top of the script in `index.html`:
- `SDES`: the events, with month and linked habits.
- `EVQ`: event questions by event and level. `{I}`, `{my}` and similar tokens adapt the wording for Individual or Class.
- `VOICE` and `RUN`: wording for each scope.
- `MATRIX`: the habit emphasis by level.
