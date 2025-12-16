xf86-input-void - null input driver for XLibre server
-----------------------------------------------------

This is a null input driver for the XLibre X server.

It doesn't connect to any physical device, and it never delivers any events.
It functions as both a pointer and keyboard device, and may be used as the
X server's core pointer and/or core keyboard.

Its purpose is to allow Xservers pre-version 1.4 to operate without
a core pointer and/or core keyboard.

The primary development code repository can be found at:

  https://github.com/X11Libre/xf86-input-void

Please submit bug reports and requests to merge patches there.
