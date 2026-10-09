# Multiple form labels example

A test page for the "multiple form labels" accessibility error.

- `index.html` has the error. The Last Name input has two labels ("First Name" and "Last Name"), because both `<label>` elements use `for="lastName"`. Screen readers announce both, and Voice Control matches the field when you say "Click First Name."
- `fixed.html` has the fix. Each input has one label whose `for` value matches the input's `id`.
- `styles.css` holds the shared styles.

To host it, push these files to a repo and turn on GitHub Pages (Settings > Pages > Deploy from branch > `main` / root).
