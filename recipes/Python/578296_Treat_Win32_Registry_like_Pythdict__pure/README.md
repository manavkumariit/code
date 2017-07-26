## Treat the Win32 Registry like a Python dict -- pure python

Originally published: 2012-10-20 13:54:01
Last updated: 2012-10-20 13:54:02
Author: Grizzly Nyo

This class wraps most of the win32api functions for accessing a registry. It will read and write all win32 registry types, and will de/serialize python objects to registry keys when a string or integer representation is not possible.