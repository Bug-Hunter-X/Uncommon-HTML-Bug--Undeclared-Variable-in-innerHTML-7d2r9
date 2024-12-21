# Uncommon HTML Bug: Undeclared Variable in innerHTML

This repository demonstrates an uncommon bug in HTML that can be tricky to debug.  The issue arises from attempting to use a JavaScript variable within the `innerHTML` property of an HTML element before the variable has been declared or assigned a value. This results in a silent failure; the browser doesn't throw an error but the expected change to the HTML content does not occur.

The `bug.html` file showcases the problematic code.  The `solution.html` file presents the corrected version.