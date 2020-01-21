# IXL-EasyCopyScores-Bookmarklet
A bookmarklet that helps you copy/get the scores of students with one click without downloading the excel and modifying it to get socres.  Save your time teachers ! ;)

<h1>How to Install this bookmarklet</h1>

Make a new bookmark in your browser (right-click on the bookmarks bar and click Add Page...)

For the "Name" you might put "Get Scores".
Copy the code block below (do triple click to higlight all codes) , paste this into the "URL" of a new bookmark.

```javascript

javascript:(function(){var $i,c=document.getElementsByClassName("chart-smartscore-column"),liste=[];for($i=1;$i<c.length;$i++)c[$i].innerText?c[$i]=c[$i]:c[$i].innerText="0",liste.push(c[$i].innerText);prompt("Copy to clipboard: Ctrl+C, Enter",liste.join("\n"));})();

```

That's it ! Now navigate to IXL and filter only 1 class and 1 subjects to see scores. Than, clikc on the bookmark that you just created, a small window pops up and shows you the scores in a format we can use, just do CTRL+ C to copy and go to your grade book and do CTRL+V to paste, ta da ! It should be entered for all students ! 

PS: Make sure you have your students in last name order on IXL to mathc them in SIS gradebook.

<img src="https://media0.giphy.com/media/11sBLVxNs7v6WA/giphy.gif"/>
