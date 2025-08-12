xf86-input-void - null input driver for Xorg server
---------------------------------------------------

This is a null input driver for the Xorg X server.

It doesn't connect to any physical device, and it never delivers any events.
It functions as both a pointer and keyboard device, and may be used as the
X server's core pointer and/or core keyboard.

Its purpose is to allow Xorg servers pre-version 1.4 to operate without
a core pointer and/or core keyboard.

All questions regarding this software should be directed at the
Xorg mailing list:

  https://lists.x.org/mailman/listinfo/xorg

The primary development code repository can be found at:

  https://gitlab.freedesktop.org/xorg/driver/xf86-input-void

Please submit bug reports and requests to merge patches there.

For patch submission instructions, see:

  https://www.x.org/wiki/Development/Documentation/SubmittingPatches

