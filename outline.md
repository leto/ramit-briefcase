# Open Source Achievements

* Converted Parrot VM to Git
    * Over ten years of history across two version control systems was converted,
    and much of the build process had to be refactored to use Git instead of Subversion.
* PL/Parrot : Parrot VM embedded into PostgreSQL
    * This makes PIR, Parrot Intermediate Representation, available as PL language, which 
    stored procedures can be written in. It also allows for any language running on Parrot
    to easily become PL.
* PL/Perl6  : Rakudo Perl 6 embedded into PostgreSQL
    * This uses PL/Parrot to embed an implementation of Perl 6 and allows writing stored
    procedures in Perl 6. For instance, a Perl 6 grammar can be defined once and then
    every call to a stored procedure can see if it parses in that grammar.
* Helped add IPv6 support to Parrot
    * This was no minor feat, as Parrot support Linux, *BSD, Windows and Solaris.
* Jitterbug : Continuous integration system for Git
    * This continuous integration system currently runs test suites and emails
    on build failures. It currently knows how to run tests for Perl 5, Perl 6, Parrot
    and Makefile-based projects. Running Python and Ruby are features that will
    come soon. Currently Jitterbug drops in as a post-receive hook on Github, but it
    can also be used with pure-Git.

# Leadership Achievements

* Mentor, The Perl Foundation, Google Summer of Code 2008
    * Mentored Thierry Moisan on Math::GSL
* Mentor/Org Admin, The Perl Foundation and Parrot Foundation, GSoC 2009
    * Mentored Bob Kuo on Math::Primality
* Co-mentor, RTEMS, GSoC 2010
    * Mentored Bob Kuo on porting Parrot VM to the RTEMS real-time OS
* Org Admin, The Perl Foundation and Parrot Foundation, GSoC 2010
    * Managed X students and Y mentors
* Org Admin, The Perl Foundation and Parrot Foundation, Google Code-In 2010
    * Managed X students and Y mentors
* Co-founder of PDX Hackathon
    * Local tech event that is attended by 30 or more people, weekly

# Writing and Publications

* Git Workflow for Parrot Developers
    * Wrote document that describes the entire process of using Git to hack on Parrot, along with a list of git terminology explained in terms that mere mortals can understand.

* Google Summer of Code Student Guide: Flip Bits Not Burgers, Co-Author
    * A X page manual for prospective students that describes how to integrate into open source communities.

* Google Summer of Code: Mentor and Org Admin Guide, Co-Author
    * A X page manual for mentors and admins on how to be effective and avoid common pitfalls.


