mplayersh
=========

Command-line wrapper to extend arguments for MPlayer

Usage
-----
::

    $ ./mplayersh [-seconds SECONDS] [-minutes MINUTES] [...] -filename FILENAME

Example
-------
Play filename.wmv starting from 00:09:18 for 30 seconds (twice)::

    $ ./mplayersh -seconds 30 -ss 00:09:18 -loop 2 filename.wmv

Play filename.wmv starting from 00:12:00 for 10.4 minutes (forever)::

    $ ./mplayersh -minutes 10.4 -ss 00:12:00 -loop 0 filename.wmv

