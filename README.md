# lime_multiwindow_crash
Example code with lime crashing when using multiple windows

It will run for while but it WILL always segfault at some point.
It looks like vertexbuffers are being freed while the other window is still using them.
