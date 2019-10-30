# IXL-EasyCopyScores-Bookmarklet
A bookmarklet that helps you copy/get the scores of students with one click without downloading the excel and modifying it to get socres.  Save your time teachers ! ;)

<h1>How to Install this bookmarklet</h1>

Make a new bookmark in your browser (right-click on the bookmarks bar and click Add Page...)

For the "Name" you might put "Get Scores".
Copy the code block below, paste this into the "URL" of a new bookmark.

```javascript

javascript:(function(){var $i,c=document.getElementsByClassName("chart-smartscore-column"),liste=[];for($i=1;$i<c.length;$i++)c[$i].innerText?c[$i]=c[$i]:c[$i].innerText="0",liste.push(c[$i].innerText);prompt("Copy to clipboard: Ctrl+C, Enter",liste.join("\n"));})();

```

