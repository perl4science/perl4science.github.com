---
layout: page
title: "Modules and Projects"
comments: true
sharing: true
footer: true
---

On of the key features of Perl is [CPAN](http://cpan.org), the Comprehensive Perl Archive Network. CPAN is a huge collection of modules published by authors all over the world, there is a module availble to do almost any task! There are several front end search engines to CPAN, including the vernerable [search.cpan.org](http://search.cpan.org) and the newer [metacpan.org](http://metacpan.org).

There are of course other scientific Perl projects which are not hosted on CPAN. We hope to highlight these on this site, but we also want to encourage all module authors to consider publishing to CPAN, not only for the free testing, but to allow easy code reuse in the typical Perl way. If you would like help packaging your module for CPAN please let us know, we would love to help get you started.

So CPAN or not here are a list of useful modules and projects, perhaps a blurb about what they do and a link to relevant repositories and documentation. If you have more to add, let us know, or [send a pull request]({{ root_url }}/howto).

##Pure Mathematics

###Numerical Modules/Libraries

* [Perl Data Language](http://pdl.perl.org) - PDL turns Perl into a free, array-oriented, numerical language
* [PerlGSL](https://metacpan.org/module/PerlGSL) - new project to provide the [Gnu Scientific Library](http://www.gnu.org/software/gsl/) to Perl with a Perlish feel
* [Math::GSL](https://metacpan.org/module/Math::GSL) - another wrapper of the GSL for Perl, this one made using [SWIG](http://www.swig.org/)
* [Math::Cephes](https://metacpan.org/module/Math::Cephes) - Perl interface to the [cephes](http://www.netlib.org/cephes/) library. Provides over 150 mathematical functions 
* [Math::Pari](https://metacpan.org/module/Math::Pari) - Perl interface to the [PARI](http://pari.math.u-bordeaux.fr/) library for numerical/scientific/number-theoretic calculations


###Plotting

* [PDL::Graphics::Prima](https://metacpan.org/module/PDL::Graphics::Prima) - A new graphics engine for PDL based on the [Prima](https://metacpan.org/module/Prima) toolkit
* [PDL::Graphics::Gnuplot](https://metacpan.org/module/PDL::Graphics::Gnuplot) - An interface between PDL and [Gnuplot](http://gnuplot.info)
* [WebService::Plotly](https://metacpan.org/pod/WebService::Plotly) - access the [plot.ly](https://plot.ly/) API for online plotting

###Statistics

* [PDL::Stats](https://metacpan.org/module/PDL::Stats) - Many useful routines for doing statistical analysis using PDL. Note that the docs might render better on its [project site](http://pdl-stats.sf.net) 
* [Statistics::R](https://metacpan.org/module/Statistics::R) - A bridge between Perl and the statistical language [R](http://www.r-project.org/)

###Units

* [Physics::Unit](https://metacpan.org/module/Physics::Unit) - Manipulate physics units and dimensions
* [MooseX::Types::NumUnit](https://metacpan.org/module/MooseX::Types::NumUnit) - (Ab)use [Moose](https://metacpan.org/module/Moose)'s type coercions to handle inputs with units. Uses `Physics::Unit` internally.

###Symbolic Mathematics

* [Math::Symbolic](https://metacpan.org/module/Math::Symbolic) - Perl implementation of symbolic mathematics
* [Math::Mathematica](https://metacpan.org/module/Math::Mathematica) - A bridge between Perl and the proprietary symbolic language [Mathematica](http://www.wolfram.com/mathematica/)

##Physics

###Astrophysics

* [Field Line Universal relaXer (FLUX)](http://flux.boulder.swri.edu/wiki/index.php/Main_Page) - is a fluxon model that follows magnetic field evolution in a conductive atmosphere, with exactly prescribed field topology.

###Electron Microscopy

* [Physics::UEMColumn](https://metacpan.org/module/Physics::UEMColumn) - an implementation of the Analytic Gaussian (AG) electron pulse propagation model, presented by [Michalik and Sipe](http://dx.doi.org/10.1063/1.2178855) and extended by [Berger and Schroeder](http://dx.doi.org/10.1063/1.3512847)

###Experiment Analysis

* [Demeter](http://bruceravel.github.com/demeter/) - a comprehensive system for processing and analyzing X-ray Absorption Spectroscopy data.

###High Energy

* [SOOT](https://metacpan.org/module/SOOT) - Perl interface to CERN's [ROOT](http://root.cern.ch/) system

###Optics

* [Physics::RayTransfer](https://metacpan.org/module/Physics::RayTransfer) - Object-oriented ray transfer analysis. Designed with special attention to laser cavity stability analysis. (If you are looking for graphic rendering, this probably isn't what you are looking for.)

##Biology

* [biodiverse](http://code.google.com/p/biodiverse/) - a tool for the spatial analysis of biological and related diversity
* [BioPerl](http://www.bioperl.org/) - a community effort to produce Perl code which is useful in biology

##Artificial Intelligence/Machine Learning

* [PerlGP](http://perlgp.org/) - "The Open Source Perl Genetic Programming System"
* [Darwin Tunes](http://darwintunes.org/) - "evolutionary music engine", uses both PDL and PerlGP to evolve music. Source: [github](https://github.com/bobular/DarwinTunes), Articles: [PNAS](http://www.pnas.org/content/early/2012/06/12/1203182109), [New Scientist](http://www.newscientist.com/blogs/culturelab/2010/08/the-experimental-evolution-of-music-and-snowball-the-dancing-cockatoo.html)
* [Clairlib](http://www.clairlib.org/index.php/Main_Page) - "The Clair library is a suite of open-source Perl modules intended to simplify a number of generic tasks in natural language processing (NLP), information retrieval (IR), and network analysis (NA)."
* [Algorithm::LibLinear](https://metacpan.org/pod/Algorithm::LibLinear) - A Perl binding for [LIBLINEAR](http://www.csie.ntu.edu.tw/~cjlin/liblinear/), a library for classification/regression using linear SVM and logistic regression

##Parallel Computing

* [MCE](https://metacpan.org/module/MCE) - Many-Core Engine for Perl. Provides parallel processing capabilities. Several examples are provided in [this thread](https://groups.google.com/forum/?fromgroups=#!topic/the-quantified-onion/2cSWXogt5Xs).

###[MPI](http://www.mcs.anl.gov/research/projects/mpi/)

* [Parallel::MPI](https://metacpan.org/module/Parallel::MPI) - basic bindings to the MPI library
* [Parallel::MPI::Simple](https://metacpan.org/module/Parallel::MPI::Simple) - a simplified, more Perlish interface to MPI
* [PDL::Parallel::MPI](https://metacpan.org/module/PDL::Parallel::MPI) - extension to Parallel::MPI with helpful PDL-specific commands

###GPU Computing

* [OpenCL](https://metacpan.org/module/OpenCL) - bindings to the OpenCL library
* [CUDA::Minimal](https://github.com/run4flat/perl-CUDA-Minimal) - a minimal, Perlish interface to CUDA

###Simple fork-based Parallelization

* [perlfork](http://perldoc.perl.org/perlfork.html) - Perl's built-in fork (and fork emulation on Windows)
* [forks](p3rl.org/forks) - drop-in replacement for Perl's threads module that uses forks; only works on Unixish systems
* [Parallel::ForkManager](https://metacpan.org/module/Parallel::ForkManager) - simpler way to manage parallel tasks using forks
* [Parallel::Loops](https://metacpan.org/module/Parallel::Loops) - wrapper over Parallel::ForkManager that also provides a simple means for shared data; communicates data back to parent using Storable and shared file handles, so not designed for large exchanges of data

###Simple Perl thread-based Parallelization

* [perlthrtut](http://perldoc.perl.org/perlthrtut.html) - Perl's built-in threads
* [forks](https://metacpan.org/module/forks) - drop-in replacement for Perl's threads module that uses forks; only works on Unixish systems
* Thread:: - many thread-related modules on CPAN are in the Thread:: namespace


##Hardware

[Lab::Measurement](https://metacpan.org/release/Lab-Measurement) - access measurement hardware for testing using lab hardware
