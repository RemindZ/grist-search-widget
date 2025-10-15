# Grist Column Search Widget

A simple search bar for Grist that lets you search through a specific column and navigate through the results with keyboard shortcuts and smart filtering.

## What it does

Type a search term and the widget finds all matching rows in your chosen column. Use the Previous/Next buttons or keyboard shortcuts to jump between matches. Shows you which match you're on (e.g., "3 of 7").

## Features

- **Partial or exact matching** - Toggle between finding text anywhere in cells vs. exact matches only
- **Keyboard shortcuts** - Navigate matches without touching your mouse
- **Debounced search** - Smart 300ms delay prevents lag while you type
- **Clear button** - One-click reset to start over
- **Auto-navigation** - Automatically selects the matching row in your table
- **Match counter** - Always know where you are in the results

## Keyboard Shortcuts

- `Enter` - Jump to next match
- `Shift + Enter` - Jump to previous match
- `Esc` - Clear search and reset

## How to use

1. Add as a Custom Widget in Grist with "Read table" access ([https://remindz.github.io/grist-search-widget](https://remindz.github.io/grist-search-widget))
2. Map the SearchColumn to the text column you want to search
3. Start typing to search (searches automatically as you type)
4. Use the toggle to switch between partial and exact matching
5. Click Previous/Next or use keyboard shortcuts to navigate results

## Match Modes

- **Partial match** (default): Finds "cat" in "category", "scattered", etc.
- **Exact match**: Only matches cells that exactly equal your search term (case-insensitive)

Perfect for quickly finding and navigating through specific entries in large tables.
