pyHook
----------
Branch of pyHook v1.5.1 source code found here: http://pyhook.sourceforge.net/

Known bugs
----------
- PyInstaller can't build single-file executables using pyHook. This may be
  fixed in 1.5.1, but hasn't been tested.
- pyHook is reported to break dead keys on non-US-english keyboards.
- WM_CHAR messages are not intercepted by pyHook, even if SubscribeKeyChar() or
  SubscribeKeyAll() are used to set the callback function.

Limitations
-----------
- pyHook will not work on Win9x (no messages show up) as it uses hooks which
  are not present in Windows systems prior to NT 4.0 SP3.

Website
-------
Visit http://pyhook.sourceforge.net for older binaries, documentation, and tutorials.

Bug reports and feature requests for this branch should be reported here: https://github.com/maxmac12/pyHook/issues
