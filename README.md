# Unhandled HTML Dialog Element

This repository demonstrates a common yet subtle error in HTML: the improper use of the &lt;dialog&gt; element without accompanying JavaScript to manage its open/close state.  The `bug.html` file showcases the error, while `solution.html` provides the corrected version.

## Bug Description
The &lt;dialog&gt; element, while semantically useful for creating dialog boxes, requires JavaScript to control its visibility.  Simply including the &lt;dialog&gt; element doesn't automatically display it or provide a way to close it.  This results in an inaccessible and unusable dialog box for users.

## Solution
The solution involves adding simple JavaScript to open and close the dialog when needed, making the dialog interactive and user-friendly.
