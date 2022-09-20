# Toast UI
This is a fork of the Toast UI [CDN files](https://www.jsdelivr.com/package/npm/@toast-ui/editor).
It contains the minified Javascript file without ES modules and CommonJS requires.
It can be used by just including it with a script tag in the index.html.

```javascript
<script src="https://github.com/42BV/toastui/blob/main/toastui-editor-all.min.js"></script>
```

See [TOAST UI editor](https://github.com/nhn/tui.editor) for documentation on how to use the editor.

## Internationalization (i18n)
The i18n folder contains the internationalization files. They can be used by including them after
the Javascript script. Example:

```javascript
<script src="https://github.com/42BV/toastui/blob/main/toastui-editor-all.min.js"></script>
<script src="https://github.com/42BV/toastui/blob/main/i18n/nl-nl.js"></script>
```

See [TOAST UI internationalization](https://nhn.github.io/tui.editor/latest/tutorial-example16-i18n).