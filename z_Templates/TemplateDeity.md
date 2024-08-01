
---
Title: 
Province: 
Symbol: 
Gender:
Pronouns:
Alignment: 
Holy Day: 
Temple: 
Relic: 

---

<% tp.file.title %>
<% await tp.file.move("content/Cosmology/Deities/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewDeity");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Deity Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

Placeholder

## Notable NPCs
Placeholder

## Appearance and Symbols
Placeholder

## Personality
Placeholder

## Worship
Placeholder

## Known Worshipers
Placeholder

## History
Placeholder