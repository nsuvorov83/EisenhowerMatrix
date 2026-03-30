# Eisenhower Matrix — Smart Task Manager with Subtasks & WIP Limit

A visual task planner based on the **Eisenhower Matrix** with drag-and-drop, nested subtasks (up to 5 levels), batch operations, WIP, and data export/import.

## Key Features

- **4 quadrants**: Urgent & Important / Important & Not Urgent / Delegate / Eliminate
- **Nested subtasks** – up to 5 levels, progress indicators
- **Drag & drop** – move between quadrants, change parent tasks
- **WIP limit** – max 3 active tasks at once
- **Batch operations** – multi-select (Ctrl+Click), complete, delete, copy, paste, make subtask, promote
- **Inline editing** – click title to rename, add subtasks
- **Customizable quadrants** – names, descriptions, colors
- **Text import** – supports indentation (3 spaces or Tab) for hierarchy
- **Backup/Restore** – JSON export/import
- **i18n** – Russian / English (auto-detects browser language)

## Tech Stack

- Pure HTML5 / CSS3 / JavaScript (ES6)
- LocalStorage
- No external dependencies

## Quick Start

1. Download `EisenhowerMatrix.html`
2. Open in any modern browser
3. All data saves locally

## Import Format Example
Main task
   Subtask 1 (level 2)
      Sub-subtask (level 3)
   Subtask 2
Another main task

## License
MIT

**Live demo** – just open the HTML file in your browser.