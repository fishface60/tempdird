# tempdird
D-Bus daemon for a service which makes temporary directories for you, and gives you a file descriptor which when closed, causes the daemon to clean up your tempdir, so you don't need to do it before exiting.
