Developer Tools
=============

Purpose
-------

The purpose of this lecture is to teach students the basic features of developer tools that will be useful for them in debugging HTML and CSS. 


Lecture Notes
----------------

Open dev tools with a keyboard shortcut, or using right-click -> inspect element.

The elements tab shows you the DOM
- Explain the difference between DOM and HTML
- Show how to make temporary HTML/CSS edits
- Show how to find out if a CSS style is being applied to an element, if it is valid (yellow triangle), or if it is overridden (strikethrough), and what stylesheet it comes from.
    Inspect element (via right-click)

The console tab will show you javascript errors
- Before asking for help: Did you check your console?
- Also useful for quickly testing out javascript, e.g. "does push return a value?"

The Network tab will show you how long files take to download
- Use the network tab to confirm that necessary files did actually download
- status codes 200 and 304 are good. 404 means that the file was not found.
