---
NoteIcon: Settlement
tags:
  - Category/Settlement
Community-Size: Outpost
Alignment: Chaotic Evil
Government: Autocracy
type: Settlement
politics: Lordship
leader: 
guildsgroups:
  - Thieves Guild 1
  - Cult 1
  - Guiled 1
region:
  - This area
  - Of this area
size: Small city
population: 0
commonraces:
  - Elves
  - Dwarves
  - Humans 
religion:
  - Lathander
exports:
  - Something
imports:
  - Something Else
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
> ###### Geography
> Type |  Stat |
> ---|---|
> Type | `=this.type` |
> Size | `=this.size` |
> Region | `=this.region` |
> ###### Politics
> Type |  Stat |
> ---|---|
> Govt Type | `=this.politics` |
> Ruler | `=this.leader` |
> Defense | `=this.defences` |
> ###### Organizations
> Type |  Stat |
> ---|---|
> Guilds & Groups | `=this.guildsgroups` |
> ###### Society
> Type |  Stat |
> ---|---|
> Population | `=this.population` |
> Races | `=this.commonraces` |
> Temples | `=this.religion`  |
> ###### Commerce
> Type |  Stat |
> ---|---|
> Exports | `=this.exports` |
> Imports | `=this.imports` |
