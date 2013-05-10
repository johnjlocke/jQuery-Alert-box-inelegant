jQuery-Alert-box-inelegant
==========================

An alert box appears when you click on a link to a page that does not exist. Very inelegant, needs to be improved.

How it works:
--------------

Inline JavaScript that fires during an onclick() event, reveals the hidden div that contains the alert. 

Why this solution needs to be improved:
-----------------------------------------

Each instance of the onclick() event needs to be added to each link, and later removed, as the pages get built out.


Odd things built in:
----------------------

The anchors tags "#" just lead to the top of the page in many browsers, hence two different alert boxes. Clicking one "X" toggles both boxes shut.





