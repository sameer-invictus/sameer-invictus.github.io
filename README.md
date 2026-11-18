# Verena GitHub QA test site (templated)

Jekyll version of the Harbor Lane Studios test site for Verena staging QA (ENG-1444 Done when 3, templated run). Not a real business.

Planted accessibility problems, each in one template file:

| Shown on | Source file | Problem | WCAG |
|---|---|---|---|
| / (home) | _includes/team-photo.html | Image has no alt text | 1.1.1 |
| /contact.html | contact.html | Name input has no label | 1.3.1 |
| /about.html | _includes/case-study-link.html | Link has only an icon, no text | 2.4.4 |

Expected: one pull request from a new verena/accessibility-... branch, three file changes in these three source files only, never on main.
