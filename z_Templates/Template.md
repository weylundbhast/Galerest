
---
AssociatedGroup: 
Gender: 
Race: 
Age: 
Class: 
Alignment: 
Character-Role: 
Location: 
AssociatedGroup: 

---

<% tp.file.title %>
<% await tp.file.move("/Galerest/Deities/" + tp.file.title) %>

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