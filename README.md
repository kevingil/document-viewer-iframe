# Document Viewer
>Javascript document viewer for < iframes > with touch drag and zoom

Drop in file, easy to use.

## How to use
Just add main.js and main.css to the header of your file

<pre>
function init() {
  // Example size, must include width and height of content in px
  const catalog = new Catalog('921', '1196')
}
document.addEventListener("DOMContentLoaded", () => {
  init()
});
</pre>
