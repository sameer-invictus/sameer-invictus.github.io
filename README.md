# Verena GitHub QA test site

Test site for Verena staging QA (ENG-1441, ENG-1676, ENG-1444). Not a real business.

Planted accessibility problems, one per file, each one Verena can fix in code:

| File | Problem | WCAG |
|---|---|---|
| index.html | Team photo `<img>` has no alt text | 1.1.1 Non-text Content |
| contact.html | Email `<input>` has no label | 1.3.1 / 4.1.2 (form label) |
| about.html | Case-study link has only an icon, no text | 2.4.4 Link Purpose |

Expected: one pull request from a new `verena/accessibility-...` branch with three file changes (these three files only), never on `main`.
