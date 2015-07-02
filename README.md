# Ulysses Table of Contents Sheet

This is a JavaScript based TOC Ulysses-III-sheet, that can be added to existing Ulysses projects, without the need to change any of your CSS-style-sheets.

Auto-generates **Table of Content "on the fly"**, with choice of multi-level TOC numbering, bullets, or plain TOC links.

Also uses CSS auto-numbering of Headings, matching the TOC numbering.  
(Can just be commented out, if not wanted)

Place it as first sheet, or just after front-matter-sheet/main-title-sheet of your project.

It can also be inserted anywhere else in the document structure,  
but then make sure that the `<div id="contents">` tag is inserted above first heading to be included in the TOC.

Works with any of Ulysses HTML-styles and preview, but not with Rich Text-styles.

Copy and Paste the complete text from **_Ulysses-TOC-Sheet.txt_** into an empty Ulysses sheet, and place it after front matter sheet, or as first sheet if so desired.

Feel free to fix and improve :)

### Disclaimer

`<style>` sections (used here for Headnings- and multilevel TOC-numbering) are not strictly allowed in `<body>` section. It seems to work in newer versions of Safari, Chrome and Firefox, and IE. But not in some older verions of IE, or if compability-mode is activated. So if heading numbers and multilevel TOC numbering is needed, turn of compability-mode in IE.  
(If that does not work, try to move these two CSS sections into your Ulysses HTML style of choice)

