# lime_multiwindow_crash
Example code with lime crashing when using multiple windows

It looks like vertexbuffers are being freed while the other window is still using them.
