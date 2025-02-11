# Insecure Script Injection via innerHTML

This repository demonstrates a common yet easily overlooked bug in HTML involving the insecure use of `innerHTML` to inject script tags.  Dynamically adding script tags using `innerHTML` can lead to cross-site scripting (XSS) vulnerabilities and unexpected behavior.

The `bug.html` file shows the problematic code, where a script tag with an alert is added to the page.  The `solution.html` file shows how to safely inject scripts using a more secure method involving DOM manipulation avoiding innerHTML.