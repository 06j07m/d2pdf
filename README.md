# d2pdf

(About)[#about] ~ (Installation)[#installation] ~ (Usage)[#usage]

## About

D2L's built-in PDF viewer is cramped and difficult to use. Here is a 
bookmarklet[^what's that?] that allows you to open the current pdf in a new window.


## Installation

### Option 1: if your browser supports drag-and-drop bookmarks...

Drag and drop the link below into your bookmarks/favourites bar

<a href="javascript:window.open(window.location.origin + window.frames[0].document.getElementsByTagName('d2l-pdf-viewer').item(0).src);" title="d2pdf">d2pdf bookmarklet</a>

### Option 1: make your own bookmarklet!

1. Make a new bookmark in your browser's bookmarks/favourites bar
2. Give it a recognizable name in the "Name" fiel, such as "d2pdf"
3. Paste the code from `d2pdf.js` into the "URL" field

## Usage

Navigate to the "Content" tab in D2L (or whatever your school calls D2L). Open
a pdf. Click on the bookmarklet.



[^what's that?]: https://dev.to/ahandsel/introduction-to-bookmarklets-javascript-everywhere-280m

