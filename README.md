*This repository was created for the xontrib that xonsh [contains by default](https://github.com/xonsh/xonsh/tree/main/xontrib).* 

# xontrib-coreutils

Additional core utilities that are implemented in xonsh.

The current list includes:
* cat
* echo
* pwd
* tee
* tty
* yes

In many cases, these may have a lower performance overhead than the
posix command line utility with the same name. This is because these
tools avoid the need for a full subprocess call. Additionally, these
tools are cross-platform.
