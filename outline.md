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
* WWW::Phylobox : Perl 5 interface to phylobox.com
    * Phylobox.com is a web app on Google App Engine that helps evolutionary biologist
    visualize phylogenies, which are graphs of how species and groups of species are related.
    This was written at a hackathon at the National Evolutionary Synthesis Center (NESCent),
    which is an NSF-funded research center for aggregrating evolutionary data.

# Leadership Achievements

* Mentor, The Perl Foundation, Google Summer of Code 2008
    * Mentored Thierry Moisan on Math::GSL, a Perl 5 interface to the GNU Scientific Library. This
    is currently one of the few CPAN modules that integrates SWIG into the build process.
* Mentor/Org Admin, The Perl Foundation and Parrot Foundation, GSoC 2009
    * Mentored Bob Kuo on Math::Primality, a CPAN module implementing advanced primality algorithms.
    * Managed 9 students and 9 mentors.
* Co-mentor, RTEMS, GSoC 2010
    * Mentored Bob Kuo on porting Parrot VM to the RTEMS real-time OS.
* Org Admin, The Perl Foundation and Parrot Foundation, GSoC 2010.
    * Managed 10 students and 10 mentors.
* Org Admin, The Perl Foundation and Parrot Foundation, Google Code-In 2010
    * Managed roughly a dozen volunteer mentors and dozens of students.
* Co-founder of PDX Hackathon
    * Local tech event that is attended by 30 or more people, every week.

# Writing and Publications

* Git Workflow for Parrot Developers
    * A document that describes the entire process of using Git to hack on Parrot, along with a list of git terminology explained in terms that mere mortals can understand. This includes cloning a new repository, merging branches, keeping branches in sync and accepting pull requests on Github.

* Google Summer of Code Student Guide: Flip Bits Not Burgers, Co-Author
    * A Creative Commons licensed manual for prospective students that describes how to integrate into open source communities.

* Google Summer of Code: Mentor and Org Admin Guide, Co-Author
    * A Creative Commons licesned manual for mentors and admins on how to be effective and avoid common pitfalls.

* The Sol Genomics Network: Growing Tomatoes using Perl
    ** Aureliano Bombarely, et al
    ** Nucleic Acid Research Oct (2010)
    ** This publication describes http://solgenomics.net, which is the main project that I currently work on.

* Solitary Wave Families of a Generalized Microstructure PDE
    ** J. Leto and S. R. Choudhury
    ** Communications in Nonlinear Science and Numerical Simulation 14 (2009) 1999
    ** This paper arose from my masters thesis and describes special exact closed-form solutions to nonlinear partial differential equations, using the theory of reversible operators and bilinear operators.

* Nonlinear convection at a Porous Flat Plate with Application to Heat Transfer from a Dike
    ** K. Vajravelu, J.R. Cannon, J.Leto, et al
    ** Journal of Mathematical Analysis and Applications, 277 (2003), no. 2, 609
    ** This is an applied mathematics paper that uses the theory of differential equations to prove the existence and uniqueness of certain equations arising in engineering applications for dams which are subject to temperature gradients.

* On Solutions of Some Nonlinear Differential Equations Arising in Third Grade Fluid Flows
    ** K. Vajravelu, J.R. Cannon, D. Rollins, J.Leto
    ** International Journal of Engineering Science 40 (2002) 1791
    ** This is an applied mathematics paper that uses the theory of differential equations to prove the existence and uniqueness of certain equations arising in industrial applications relating to non-Newtonian fluids.

* Writing A Useful Program with NASM
    ** Assembly Programming Journal 9 (2000)
    ** This article is a HOWTO about assembly programming for beginners, and gives example code for NASM.

