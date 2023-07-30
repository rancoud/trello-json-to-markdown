# Trello JSON to Markdown
Convert trello JSON export file in Markdown.  
Has options for Obsidian, [Kanban Obsidian Plugin](https://github.com/mgmeyers/obsidian-kanban) and [Projects Obsidian Plugin](https://github.com/marcusolsson/obsidian-projects).  
Use [JSZip v3.10.1](https://github.com/Stuk/jszip) when generating zip file for Projects Obsidian Plugin.

## How to use?

### Export Trello Board in JSON
1. Go to your Trello board
2. Click on `Show menu`
3. Click on `... Plus`
4. Click on `Print and export`
5. Select `Export in JSON`
6. Download the file

### Convert Trello JSON in Markdown
1. Open the file with an editor
2. Copy the content
3. Open the file `trello-json-to-markdown.html` in a browser
4. Paste the content in the input Trello JSON
5. Select the options you want to use  
6. Click on proceed  
7. Copy the output markdown

## Supports:
- [X] lists
- [X] cards
  - [X] description
  - [X] checklists
  - [X] comments
- [X] add Kanban Obsidian Plugin
- [X] labels as tags for Obsidian
  - [X] optional
  - [X] add prefix and or suffix
- [X] include archived
  - [X] lists
  - [X] cards
- [X] add Projects Obsidian Plugin