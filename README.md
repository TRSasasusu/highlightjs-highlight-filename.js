# highlightjs-highlight-filename.js
Filename highlighting plugin for [Highlight.js](https://highlightjs.org/)

[DEMO](https://trsasasusu.github.io/highlightjs-highlight-filename.js/)

## Install

Get from CDN,

```
<script src="//cdn.jsdelivr.net/gh/TRSasasusu/highlightjs-highlight-filename.js@1.0.0/highlightjs-highlight-filename.min.js"></script>
```

or download from this repository.

## Usage

Include `highlightjs-highlight-filename.min.js` after highlight.js.

```
<script src="path/to/highlight.min.js"></script>
<script src="path/to/highlightjs-highlight-filename.min.js"></script>
```

Initialize after highlight.js.

```
hljs.initHighlightingOnLoad();
hljs.initHighlightFilenameOnLoad([
    {filename: 'main.c'},
    {filename: 'program.py', backgroundColor: 'white', color: '#000'},
    {filename: 'main.cpp', backgroundColor: '#111'},
]);
```

## License

MIT License
