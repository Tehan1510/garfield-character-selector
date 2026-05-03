# Garfield Character Selector

A simple, no-dependency HTML page that lets you browse the main cast of the Garfield comic strip. Pick a character from the dropdown and their photo appears instantly.

## Characters

| Name | Description |
|------|-------------|
| Garfield | The lasagna-loving, Monday-hating tabby cat |
| Odie | Jon's lovable, tongue-wagging beagle |
| Nermal | The world's cutest kitten (self-proclaimed) |
| Pooky | Garfield's beloved teddy bear |
| Jon | Garfield's hapless but well-meaning owner |

## Project Structure

```
garfield-character-selector/
├── index.html       # App — markup, logic, and all
└── images/
    ├── Garfield.jpg
    ├── Jon.jpg
    ├── Nermal.jpg
    ├── Odie.jpg
    └── Pooky.jpg
```

## Getting Started

No build step or server required — just open the file directly in a browser.

```bash
git clone https://github.com/your-username/garfield-character-selector.git
cd garfield-character-selector
open index.html   # macOS
# or double-click index.html in your file explorer
```

## How It Works

The character list is stored in a JavaScript array. On page load the script populates a `<select>` dropdown from that array. When the selection changes, the `src` of the `<img>` tag is updated to `images/<CharacterName>.jpg` — no network requests, no frameworks.

To add a new character, drop their image into the `images/` folder and add their name to the `characters` array in `index.html`.

## Tech Stack

- Pure HTML, CSS, and JavaScript
- Zero dependencies
