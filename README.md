
# Asciiquarium is an aquarium/sea animation in ASCII art.

Original: https://robobunny.com/projects/asciiquarium/html/
By: Kirk Baucom <kbaucom@schizoid.com>

LICENSE: GNU GENERAL PUBLIC LICENSE - Version 2, June 1991

Installation
------------

Asciiquarium is a perl script, so all you have to do is make sure
it's executable and put it somewhere convenient.

  Slackware 15.0
  ------
    Need perl-Curses:
       https://slackbuilds.org/repository/15.0/perl/perl-Curses/

    Clone and Run
        git clone https://github.com/ryuuzaki42/asciiquarium
        cd asciiquarium/
        ./asciiquarium
        ./tiftquarium

    # Or download the packages in releases:
        https://github.com/ryuuzaki42/asciiquarium/releases

Usage
-----

Command line arguments:

    -b, black and white mode
    -c, "classic" mode, only show species from asciiquarium 1.1
    -f number, Number of fish (like -f 10)

While running:

    q - quit
    r - redraw (will recreate all entities)
    p - toggle pause
    mouse scroll - next draw (temporary speedups)

The *original* README:

```text
       Asciiquarium v1.1
                    by Kirk Baucom <kbaucom@schizoid.com>
                          http://www.robobunny.com

Asciiquarium is an aquarium/sea animation in ASCII art.

Installation
------------

Asciiquarium is a single perl script, so all you have to do is make sure
it's executable and put it somewhere convenient, like /usr/local/bin or
/usr/local/games.

  Ubuntu
  ------

  Out-of-the-box ubuntu doesn't satisfy the Requirements below, so
  here's how to get them:
  1) Get perl's curses package which is available from apt:
       sudo apt-get install libcurses-perl
  2) Run
       cpan
     at the shell.  Agree to the defaults for everything.
     To leave cpan, type
       quit
  3) Type
    sudo cpan Term::Animation

Requirements
------------

You must have the Term::Animation module, which you can get from
http://www.cpan.org. The Term::Animation module also requires the Curses
module, which you can also get from CPAN. This program will only run on
platforms that have a Curses library (so it won't work on Windows, but
you might get it to run under cygwin).

Usage
-----

Command line arguments:
    -c  "classic" mode, only show species from Asciiquarium 1.0

While running:
    q   quit
    r   redraw (will recreate all entities)
    p   toggle pause

Contributors
------------

New fish species backported from the Android live wallpaper and
other minor improvements by Claudio Matsuoka.

Pretty much all of the ASCII art was done by Joan Stark:
http://www.geocities.com/SoHo/7373/

Anything that she didn't do, I don't have a source for.

```

This repository is a fork from [sandsmark's asciiquarium][], witch is a fork of [cmatsuoka's asciiquarium][],
with new fish species backported from the Android live wallpaper and other minor
improvements by Claudio Matsuoka. It also merges contributions found in
that repository's [Pull Requests][]:

- [Added objects from Kirk's version][] by [driechers][] with art originally by
  Kirk Baucom
- [Added yellow submarine][] by [driechers][] with art originally by Carl
  Pilcher as found at [https://ascii.co.uk/art/submarine][]
- [Add sword fish][] by [robert1003][] with art from
  [https://ascii.co.uk/art/fish][]

And more:

- [Added info some update info of polettix][] by [polettix][]
- Help message (-h or --help) by [ryuuzaki42][]
- Count of fish (-f number, like -f 10) by [ryuuzaki42][]
- Spaces instead tabs by [ryuuzaki42][]

"Update" to version 1.2

[Perl]: https://www.perl.org/
[Installing Perl Modules]: https://github.polettix.it/ETOOBUSY/2020/01/04/installing-perl-modules/
[cmatsuoka's asciiquarium]: https://github.com/cmatsuoka/asciiquarium
[sandsmark's asciiquarium]: https://github.com/sandsmark/asciiquarium
[Pull Requests]: https://github.com/cmatsuoka/asciiquarium/pulls
[robert1003]: https://github.com/robert1003
[Add sword fish]: https://github.com/cmatsuoka/asciiquarium/pull/12
[https://ascii.co.uk/art/fish]: https://ascii.co.uk/art/fish
[driechers]: https://github.com/driechers
[Added yellow submarine]: https://github.com/cmatsuoka/asciiquarium/pull/6
[https://ascii.co.uk/art/submarine]: https://ascii.co.uk/art/submarine
[Added objects from Kirk's version]: https://github.com/cmatsuoka/asciiquarium/pull/5
[polettix]: https://github.com/polettix
[Added info some update info of polettix]: https://github.com/polettix/asciiquarium
[ryuuzaki42]: https://github.com/ryuuzaki42
