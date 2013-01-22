Graasp - android app
====================

This project contains a simple Android app that wraps the Graasp website (http://graasp.epfl.ch) with data loading feedback.

The app consists of a WebView to display the Graasp website (http://graasp.epfl.ch). Feedback on the loading of the WebView is shown in the top bar.

Known Issues
------------

* The URL of the WebView should be saved and reloaded when the Activity is reloaded.
* The Graasp website should be slightly reformated when a mobile device is used, e.g. the top bar should resize better.

Future work
-----------

* The loading bar should also be shown when data is loading triggered by a user interaction.
* An integration of the Graasp notification would be interesting
* Data downloaded from Graasp could be saved on the mobile device
