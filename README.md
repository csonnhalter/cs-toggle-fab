[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/csonnhalter/cs-scroll)
# \<cs-toggle-fab\>

The fab changes on tap between two icons and has an optional tooltip. A wrapper for `<paper-fab>` and `<paper-tooltip>`.
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="cs-toggle-fab.html">
    <link rel="import" href="../iron-icons/social-icons.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<cs-toggle-fab tip="Press me and I will change!" >
</cs-toggle-fab>
<cs-toggle-fab do-icon="social:sentiment-dissatisfied" done-icon="social:sentiment-satisfied">
</cs-toggle-fab>
```