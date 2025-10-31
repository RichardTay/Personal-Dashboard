==============================
Workspace Dashboard (v6)
==============================
Author: Charlie
Last Edited: 2025-10-31

Overview
--------
This dashboard serves as a unified personal workspace hub with quick access to tools,
apps, and platforms across multiple categories. Version 6 is fully flattened (no sub-tabs)
and formatted for easy manual editing in any text editor.

Core Features
-------------
• Clean header layout with top-right toolbar:
  - 🌓 Theme toggle
  - 📥 Import JSON
  - 📤 Export JSON
  - ⭐ Starred-only view toggle
  - ⏰ Live clock display

• Interactive functions:
  - `/` key focuses the search bar
  - Enter opens the first result
  - ↑ / ↓ navigate cards
  - Numbers 1–9 open corresponding cards
  - `S` to star/unstar a card
  - `F` to toggle "Starred only" view
  - Drag & Drop: reorder cards or move between sections
  - Persistent layout and favorites saved to browser localStorage

• JSON Import/Export
  - You can export all starred links as a JSON file.
  - Import them later or on another device to restore your setup.

• Structure
  - Writing & Communication
  - Social & Start
  - AI & Tools
  - Publishing & Stores
  - DeFi & Farms

Editing Notes
-------------
• The file is formatted for readability.
• Add or edit cards by copying existing <a class="card"> blocks.
• Each <div class="grid" id="grid-..."> section corresponds to a main category.
• Avoid adding nested divs unless necessary for layout.

Maintenance Tips
----------------
• Version header at the top records author, date, and version number.
• Always keep a backup before major edits.
• Browser cache may need a hard refresh (Ctrl/Cmd + F5) to see layout changes.
• DODO farm is correctly placed under DeFi & Farms (no duplicates).

Enjoy your organized workspace! ✨
