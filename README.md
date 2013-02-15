VimSync
=======

VimSync is a server for collaborative real-time editing in Vim, made with
[node-vim-netbeans](/clehner/node-vim-netbeans).

Usage
-----

	$ cd vimsync
    $ git submodule init
    $ git submodule update
	$ node vimsync.js

Todo
----

- Try to maintain client cursor position when receiving text changes.
- Open a buffer on connect with a splash screen / useful information.
- Integrate a ShareJS server for collaborative editing in the browser.
- Detect and recover from inconsistent client states.
- Cleanup code and remove commented-out lines.
