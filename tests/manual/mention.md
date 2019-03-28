## Mention

The minimal mention configuration with a static list of autocomplete feed:

### Configuration

The feed:

- Barney
- Lily
- Marshall
- Robin
- Ted

### Interaction

You can interact with mention panel with keyboard:

- Move arrows up/down to select an item.
- Use <kbd>enter</kbd> or <kbd>tab</kbd> to insert a mention into the documentation. 
- The <kbd>esc</kbd> should close the panel.

Mention panel should be closed on:
- Click outside the panel view.
- Changing selection - like placing it in other part of text.

### Editing behavior:

The mention should be removed from the text when:

- typing inside a mention
- removing characters from a mention
- breaking the mention (<kbd>enter</kbd>)
- pasting part of a mention