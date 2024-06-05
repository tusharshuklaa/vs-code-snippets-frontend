# Useful VS Code Snippets for a Frontend Developer
This document provides an overview of the VS Code snippets available in the `fe-snippets.json` file. These snippets are designed to speed up your coding process by providing pre-written code blocks for common tasks.

### Available Snippets
Here's a brief description of each snippet:

- CSS/SCSS
  - TODO CSS Comment: Adds a todo comment in CSS, SCSS, and LESS files.
  - CSS Region: Creates a foldable region for code between region comments in CSS, SCSS, and LESS files.
  - Media Query: Generic code for media query.
  - Mobile Media Query: Media query for mobile devices.
  - Tablet Media Query: Media query for small laptop or tablet devices including mobiles as well.
  - Tablet Only Media Query: Media query for small laptop or tablet devices only.
  - Desktop Media Query: Media query for desktop/laptop.
  - Absolute Center: Center an item vertically and horizontally.
- Javascript
  - console info: Prints console info.
  - console log: Prints console log.
  - TODO JS Comment: Adds a todo comment in JS, TS, and React TS files.
  - JS Region: Creates a foldable region for code between region comments in JS, TS, JSX files.
- React
  - Import React: Imports react in file.
  - React Basic Functional Component: Creates a basic react function component.
  - React Basic Functional Component with Interface: Creates a basic react function component in typescript with props defined as an interface.
  - React Basic Functional Component with Type: Creates a basic react function component in typescript with props defined as a type.
  - React useState: Adds basic syntax for useState with dynamic cursors.
  - React useEffect: Adds basic syntax for useEffect with dynamic cursors.
  - React useCallback: Adds basic syntax for useCallback with dynamic cursors.
  - React useMemo: Adds basic syntax for useMemo with dynamic cursors.
- Others
  - Next.js 14 use client: Adds a use client text. Should be added at the top of a client component.
  - Jest basic test: Creates a basic react testing library test file with a snapshot test for a component.

### Creating Custom VS Code Snippets
To create your own custom VS Code snippets:

Open the Command Palette (Cmd+Shift+P on macOS or Ctrl+Shift+P on Windows/Linux) and select Preferences: Configure User Snippets.
Click on New Global Snippets file... and give it a name.
In the opened JSON file, you can start adding your snippets. Each snippet is defined under a snippet name and has a prefix, body, and description.
Here's an example of a simple snippet that logs a message to the console:

```json
{
  "Print to console": {
    "prefix": "log",
    "body": [
      "console.log('$1');",
      "$2"
    ],
    "description": "Log output to console"
  }
}
```

### Using Snippets
To use a snippet, simply start typing the prefix of the snippet in your editor and you will see it suggested in the autocomplete dropdown. Press Enter or Tab to insert the snippet.

> Remember, snippets can greatly speed up your coding process by reducing the amount of boilerplate code you have to write. Happy coding!
