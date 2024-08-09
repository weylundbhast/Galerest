
---
Title: 
Province: 
Symbol: 
Gender:
Pronouns:
Alignment: 
HolyDay: 
Temple: 
Relic: 
Worshipers:

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

> [!infobox]
> # `=this.file.name`
> ![[z_Assets/Misc/MapPlaceholder.png|cover hsmall]]
> ###### Deity Information
> Type |  Stat |
> ---|---|
> Title | `=this.Title` |
> Province | `=this.Province` |
> Symbol | `=this.Symbol` |
> Gender  | `=this.Gender` |
> Pronouns | `=this.Pronouns` |
> Alignment | `=this.Alignment` |
> ###### Worship
> Type |  Stat |
> ---|---|
> Worshipers | `=this.worshipers` |
> Holy Day | `=this.HolyDay` |
> Temple | `=this.Temple` |
> Relic | `=this.Relic` |
   


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