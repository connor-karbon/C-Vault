---
type: daily note
---
- [ ] <% tp.date.now() %>

# Agenda













# Meetings
```dataview
TABLE file.cday as Created, summary AS "Summary"
FROM "Extras/Meetings" where contains(file.name, this.file.name)
SORT file.cday DESC
```