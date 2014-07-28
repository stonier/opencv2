### OpenCV: Open Source Computer Vision Library

#### Fork Details

This experiments with adding multi-thread capability to the qt imshow module.

* Check threads and set the variable multiThreads appropriately when calling cvNamedWindow.
* Intelligently invoke requests to the guiReceiver as BlockingQueued or Direct Connections.
 * There is a new helper function (autoBlockingConnection) to do this.
