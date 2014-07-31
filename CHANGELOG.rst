=========
Changelog
=========

Forthcoming
-----------

module/highgui/window_QT.xxx updates:

* Detect and set multiThreads variable in cvNamedWindow.
* Define an autoBlockingConnection type for sending data to the main thread.
* Apply autoBlockingConnection for all invoked methods.
* Don't autoBlock everything, particular the destruction methods as QApp might already be down.
