---
layout: page
title: "Modules and Projects"
comments: true
sharing: true
footer: true
---

On of the key features of Perl is [CPAN](http://cpan.org), the Comprehensive Perl Archive Network. CPAN is a huge collection of modules published by authors all over the world, there is a module availble to do almost any task! There are several front end search engines to CPAN, including the vernerable [search.cpan.org](http://search.cpan.org) and the newer [metacpan.org](http://metacpan.org). There is a shortcut site, which you will often see used on this page, which allows smart linking to CPAN documentation as well as Perl core documentation, [p3rl.org](http://p3rl.org). Try [p3rl.org/open](http://p3rl.org/open) or [p3rl.org/PerlGSL::DiffEq](http://p3rl.org/PerlGSL::DiffEq) to see how it works.

There are of course other scientific Perl projects which are not hosted on CPAN. We hope to highlight these on this site, but we also want to encourage all module authors to consider publishing to CPAN, not only for the free testing, but to allow easy code reuse in the typical Perl way. If you would like help packaging your module for CPAN please let us know, we would love to help get you started.

So CPAN or not here are a list of useful modules and projects, perhaps a blurb about what they do and a link to relevant repositories and documentation. If you have more to add, let us know, or [send a pull request]({{ root_url }}/howto).

##Pure Mathematics

###Numerical Modules/Libraries

* [Perl Data Language](http://pdl.perl.org) - PDL turns Perl into a free, array-oriented, numerical language
* [PerlGSL](http://p3rl.org/PerlGSL) - new project to provide the [Gnu Scientific Library](http://www.gnu.org/software/gsl/) to Perl with a Perlish feel
* [Math::GSL](http://p3rl.org/Math::GSL) - another wrapper of the GSL for Perl, this one made using [SWIG](http://www.swig.org/)
* [Math::Cephes](http://p3rl.org/Math::Cephes) - Perl interface to the [cephes](http://www.netlib.org/cephes/) library. Provides over 150 mathematical functions 
* [Math::Pari](http://p3rl.org/Math::Pari) - Perl interface to the [PARI](http://pari.math.u-bordeaux.fr/) library for numerical/scientific/number-theoretic calculations


###Plotting

* [PDL::Graphics::Prima](http://p3rl.org/PDL::Graphics::Prima) - A new graphics engine for PDL based on the [Prima](http://p3rl.org/Prima) toolkit
* [PDL::Graphics::Gnuplot](http://p3rl.org/PDL::Graphics::Gnuplot) - An interface between PDL and [Gnuplot](http://gnuplot.info)

###Statistics

* [PDL::Stats](http://p3rl.org/PDL::Stats) - Many useful routines for doing statistical analysis using PDL. Note that the docs might render better on its [project site](http://pdl-stats.sf.net) 
* [Statistics::R](http://p3rl.org/Statistics::R) - A bridge between Perl and the statistical language [R](http://www.r-project.org/)

###Units

* [Physics::Unit](http://p3rl.org/Physics::Unit) - Manipulate physics units and dimensions
* [MooseX::Types::NumUnit](http://p3rl.org/MooseX::Types::NumUnit) - (Ab)use [Moose](http://p3rl.org/Moose)'s type coercions to handle inputs with units. Uses `Physics::Unit` internally.

###Symbolic Mathematics

* [Math::Symbolic](http://p3rl.org/Math::Symbolic) - Perl implementation of symbolic mathematics
* [Math::Mathematica](http://p3rl.org/Math::Mathematica) - A bridge between Perl and the proprietary symbolic language [Mathematica](http://www.wolfram.com/mathematica/)

##Parallel Computing

###[MPI](http://www.mcs.anl.gov/research/projects/mpi/)

* [Parallel::MPI](http://p3rl.org/Parallel::MPI) - basic bindings to the MPI library
* [Parallel::MPI::Simple](http://p3rl.org/Parallel::MPI::Simple) - a simplified, more Perlish interface to MPI
* [PDL::Parallel::MPI](http://p3rl.org/PDL::Parallel::MPI) - extension to Parallel::MPI with helpful PDL-specific commands

###GPU Computing

* [OpenCL](http://p3rl.org/OpenCL) - bindings to the OpenCL library
* [CUDA::Minimal](https://github.com/run4flat/perl-CUDA-Minimal) - a minimal, Perlish interface to CUDA

##Physics

###Optics

* [Physics::RayTransfer](http://p3rl.org/Physics::RayTransfer) - Object-oriented ray transfer analysis. Designed with special attention to laser cavity stability analysis. (If you are looking for graphic rendering, this probably isn't what you are looking for.)

###High Energy

* [SOOT](http://p3rl.org/SOOT) - Perl interface to CERN's [ROOT](http://root.cern.ch/) system

##Biology

* [BioPerl](http://www.bioperl.org/) - a community effort to produce Perl code which is useful in biology

##Artificial Intelligence/Machine Learning

* [PerlGP](http://perlgp.org/) - "The Open Source Perl Genetic Programming System"
* [Darwin Tunes](http://darwintunes.org/) - "evolutionary music engine", uses both PDL and PerlGP to evolve music. Source: [github](https://github.com/bobular/DarwinTunes), Articles: [PNAS](http://www.pnas.org/content/early/2012/06/12/1203182109), [New Scientist](http://www.newscientist.com/blogs/culturelab/2010/08/the-experimental-evolution-of-music-and-snowball-the-dancing-cockatoo.html)
