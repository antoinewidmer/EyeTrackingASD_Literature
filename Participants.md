```dataviewjs 
let sectionTitle = "## Participants"; // Change this to the section you want to extract

// Get all notes in a specific folder (change folder name if needed)
let notes = dv.pages('"NotesConnectToPapers"');

// Loop through notes to extract the section
for (let note of notes) {
    let file = app.vault.getAbstractFileByPath(note.file.path);
    let content = await app.vault.read(file);
    let regex = new RegExp(`${sectionTitle}([\\s\\S]*?)(##|$)`, "i"); // Find section content

    let match = content.match(regex);
    if (match) {
        dv.header(3, note.file.name); // Display the note's title
        dv.paragraph(match[1].trim()); // Show extracted section
        
    }
}
```
