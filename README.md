# adamantium-element <span style="float: right">[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/deblanco/adamantium-editor)</span>

Polymer (1) element that displays a WYSIWYG text editor.

## Installation

Clone or dowload the Github repo or via bower:

```bash
bower install adamantium-editor
```

## Usage

Import the element in your polymer project and attach it:

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="adamantium-editor.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<script src="../webcomponentsjs/webcomponents-lite.js"></script>

<adamanitum-editor id="editor" body-text="This is a text"></adamantium-editor>
```

Includes a **get()** method for get typed text.

### Demo: https://jsfiddle.net/esq1e2et/

---

License: MIT