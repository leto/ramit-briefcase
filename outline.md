# Free Software/Open Source Achievements

> I have commit bits to dozens of open source projects and have been actively contributing
to open source projects for over ten years in half a dozen languages.

### Converted [Parrot Virtual Machine](http://parrot.org) to Git

Over ten years of history across two version control systems was converted, and
large parts of the configure subsystem and test suite had to be refactored to
use Git instead of Subversion. This also involved writing developer
documentation on the new [Git workflow](https://github.com/parrot/parrot/blob/master/docs/project/git_workflow.pod) for Parrot Developers
, as well as a document describing [Git terminology](https://github.com/parrot/parrot/blob/master/docs/project/git_terminology.pod).

### Redesigning Parrot Internals: [M0](http://leto.net/dukeleto.pl/2011/05/what-is-m0.html)

I am currently involved in redesigning the very core of Parrot so an efficient JIT can be implemented
on top of it.

### [Mimosa](http://gmod.github.com/mimosa): Miniature Model Organism Sequence Aligner

One of my current projects is writing an extremely well-tested web application
for bioinformatics researchers to align sequence data from the comfort of their
web browser.

### Fixed an obscure bug in the Perl 5 debugger

This involved reading and understanding the entire source code of the Perl 5
debugger.  I can't say that I have ever been the same since. This bug would
cause any failing test to pass, under certain versions of the Perl debugger, at
my previous job. Fixing the bug involved fixing a bug where undefined symbols
were being created and writing tests for the Perl 5 debugger to make sure this
kind of thing doesn't happen again.

### Helped add and test IPv6 support to Parrot

This was no minor feat, as Parrot supports Linux, *BSD, Windows and Solaris. It also
involved writing tests which dealt with the different kinds of IPv6 error conditions
that various operating systems return and allowing the tests to be run in parallel.

### [PL/Parrot](http://pl.parrot.org) : Parrot VM embedded into PostgreSQL

This makes PIR, Parrot Intermediate Representation, available as PostgreSQL
stored procedure Language (PL).  It also allows for any language running on
Parrot to easily become PL.

### [PL/Perl6](http://pl.parrot.org)  : Rakudo Perl 6 embedded into PostgreSQL
This uses PL/Parrot to embed Rakudo Perl 6 and allows writing stored
procedures in Perl 6. For instance, a Perl 6 grammar can be defined once and then
every call to a stored procedure can see if it parses in that grammar.

### [Perl 6 Spec Test Suite](https://github.com/perl6/roast)
I originally got involved with Perl 6 by adding many tests relating to mathematical functions in Perl 6,
including logarithm, complex numbers, and finding arbitrary roots of real and complex numbers.

### [Math::GSL](https://metacpan.org/release/Math-GSL)

This CPAN modules allows access to the GNU Scientific Library, written in C,
from Perl 5.  This allows scientists and researchers to access the thousands of
scientific computing functions in GSL from a quick-to-write dynamic language.
This module uses SWIG to generate wrappers to the massive GSL C library, and
contains thousands of tests to verify that the various functions and algorithms
are working correctly.

### [Math::Primality](https://metacpan.org/release/Math-Primality)

This CPAN module uses the GNU Multiprecision library to implement advanced
prime-checking or primality functions. It can be used to do number theory
research in Perl 5 efficiently. It also contains thousands of tests to ensure
that researchers can trust their calculations.

### [Math::ODE](https://metacpan.org/release/Math-ODE)

This is a pure Perl implementation of the 4th Order Runge-Kutta algorithm to quickly
solve systems of ordinary differential equations. Contains various tests which verify
the numeric solutions are within the expected tolerance of known exact solutions.

### Helped add IPv6 support to Parrot

This was no minor feat, as Parrot supports Linux, *BSD, Windows and Solaris and
the tests must handle the many different implementations of IPv6 across these
operating systems.

### [Jitterbug](https://github.com/franckcuny/jitterbug) : Cross Language Continuous Integration for Git

This continuous integration system currently runs test suites and emails on
build failures. It currently knows how to run tests for Perl 5/6, Parrot and
Makefile-based projects. Running Python and Ruby are features that will come
soon. Currently Jitterbug drops in as a post-receive hook on Github, but it can
also be used with pure Git.

### [WWW::Phylobox](https://github.com/leto/www-phylobox) : Perl 5 interface to phylobox.com

Phylobox.com is a web app on Google App Engine that helps evolutionary
biologists visualize phylogenies, which are graphs of how species and groups of
species are related.  This was written at a hackathon at the National
Evolutionary Synthesis Center (NESCent), which is an NSF-funded research center
for aggregrating evolutionary data.

# Leadership Achievements

> I enjoy being the leader of a team of very smart people and solving hard problems.

### Org Admin, The Perl Foundation and Parrot Foundation, Google Code-In 2010
* Managed roughly a dozen volunteer mentors and dozens of students, who worked on a variety
of Parrot Virtual Machine and Perl 5/6 tasks.

### Org Admin, The Perl Foundation and Parrot Foundation, GSoC 2010.
* Managed 10 students and 10 mentors working on a variety of Parrot Virtual Machine and Perl 5/6 tasks.

### Mentor/Org Admin, The Perl Foundation and Parrot Foundation, GSoC 2009
* Mentored Bob Kuo on Math::Primality, a CPAN module implementing advanced primality algorithms.
* Managed 9 students and 9 mentors on many Parrot/Perl projects.

### Co-founder of PDX Hackathon, 2008
* Local tech event that is attended by 30 or more people, every week.

### Mentor, The Perl Foundation, Google Summer of Code 2008
* Mentored Thierry Moisan on Math::GSL, a Perl 5 interface to the GNU Scientific Library. This
is currently one of the few CPAN modules that integrates SWIG into the build process.

### Org Admin and mentor, Parrot Foundation, GSoC 2011.
* Overseeing 8 students and mentors, and mentoring a student to add GMP bindings to Parrot
and hence all languages that run on Parrot.

### Org Admin, The Perl Foundation and Parrot Foundation, Google Code-In 2010
* Managed roughly a dozen volunteer mentors and dozens of students.

### Co-mentor, RTEMS, GSoC 2010
* Mentored Bob Kuo on porting Parrot VM to the RTEMS real-time OS.

# Writing and Publications

> I enjoy writing technical specifications, publishing academic papers and writing about open source.

### [Test Driven Enlightenment](https://github.com/lydiapintscher/Open-Advice/blob/master/qualityassurance/JonathanLeto.tex): A Chapter in the upcoming book "Open Advice"

I had the pleasure of writing a chapter for Lydia Pintscher's upcoming book
called "Open Advice", which contains a plethora of amazing information from
many dozens of awesome people about getting involved in Free and Open source
software.


### [Perl and Parrot Spread Open Source Love](http://google-opensource.blogspot.com/2010/10/perl-and-parrot-spread-open-source-love.html)

This blog post appeared on the Google Open Source Blog.

### [Git Workflow](https://github.com/parrot/parrot/blob/master/docs/project/git_workflow.pod) for Parrot Developers

A document that describes the entire process of using Git to hack on Parrot,
along with a list of git terminology explained in terms that mere mortals can
understand. This includes cloning a new repository, merging branches, keeping
branches in sync and accepting pull requests on Github.

### Google Summer of Code Student Guide: Flip Bits Not Burgers, Co-Author

A Creative Commons licensed manual for prospective students that describes how
to integrate into open source communities.

### Google Summer of Code: Mentor and Org Admin Guide, Co-Author

A Creative Commons licensed manual for mentors and admins on how to be
effective and avoid common pitfalls.

### The Sol Genomics Network: Growing Tomatoes using Perl
 * Aureliano Bombarely, et al
 * Nucleic Acid Research Oct (2010)

This publication describes http://solgenomics.net, which is one of the main projects that I currently work on.

### Solitary Wave Families of a Generalized Microstructure PDE

 * J. Leto and S. R. Choudhury
 * Communications in Nonlinear Science and Numerical Simulation 14 (2009) 1999

This paper arose from my masters thesis and describes brand new, exact closed-form
solutions to nonlinear partial differential equations, using the theory of
reversible operators and bilinear operators. Finding solutions to equations that nobody
has ever solved before is quite fun.

### Nonlinear convection at a Porous Flat Plate with Application to Heat Transfer from a Dike
 * K. Vajravelu, J.R. Cannon, J.Leto, et al
 * Journal of Mathematical Analysis and Applications, 277 (2003), no. 2, 609

This is an applied mathematics paper that uses the theory of differential
equations to prove the existence and uniqueness of certain equations arising
in engineering applications for dams which are subject to temperature
gradients. I am responsible for all the numerics in this paper, which was part of
an undergraduate research grant I worked on.

### On Solutions of Some Nonlinear Differential Equations Arising in Third Grade Fluid Flows
 * K. Vajravelu, J.R. Cannon, D. Rollins, J.Leto
 * International Journal of Engineering Science 40 (2002) 1791

This is an applied mathematics paper that uses the theory of differential
equations to prove the existence and uniqueness of certain equations arising in
industrial applications relating to non-Newtonian fluids. I did all the numerics in this
paper and actually wrote the CPAN module [Math::ODE](https://metacpan.org/release/Math-ODE/) to solve the equations numerically.

### Writing A Useful Program with NASM
 * Assembly Programming Journal 9 (2000)

This article is a HOWTO about assembly programming for beginners, and gives example code for NASM.
