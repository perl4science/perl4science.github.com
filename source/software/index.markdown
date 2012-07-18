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

##Numerical Software

* [Perl Data Language](http://pdl.perl.org) - PDL turns Perl into a free, array-oriented, numerical language
* [PerlGSL](http://p3rl.org/PerlGSL) - new project to provide the [Gnu Scientific Library](http://www.gnu.org/software/gsl/) to Perl with a Perlish feel
* [Math::GSL](http://p3rl.org/Math::GSL) - another wrapper of the GSL for Perl, this one made using [SWIG](http://www.swig.org/)
* [Math::Cephes](https://p3rl.org/Math::Cephes) - a numerical library of mathematical functions


###Plotting

* [PDL::Graphics::Prima](http://p3rl.org/PDL::Graphics::Prima) - A new graphics engine for PDL based on the [Prima](http://p3rl.org/Prima) toolkit
* [PDL::Graphics::Gnuplot](http://p3rl.org/PDL::Graphics::Gnuplot) - An interface between PDL and [Gnuplot](http://gnuplot.info)

###Statistics

* [PDL::Stats](http://p3rl.org/PDL::Stats) - Many useful routines for doing statistical analysis using PDL. Note that the docs might render better on its [project site](http://pdl-stats.sf.net) 

###Units

* [Physics::Unit](http://p3rl.org/Physics::Unit) - Manipulate physics units and dimensions
* [MooseX::Types::NumUnit](http://p3rl.org/MooseX::Types::NumUnit) - (Ab)use [Moose](http://p3rl.org/Moose)'s type coercions to handle inputs with units. Uses `Physics::Unit` internally.


##Physics

###Optics

* [Physics::RayTransfer](http://p3rl.org/Physics::RayTransfer) - Object-oriented ray transfer analysis. Designed with special attention to laser cavity stability analysis. (If you are looking for graphic rendering, this probably isn't what you are looking for.)

##Biology

* [BioPerl](http://www.bioperl.org/) - a community effort to produce Perl code which is useful in biology

##Artificial Intelligence/Machine Learning

* [PerlGP](http://perlgp.org/) - "The Open Source Perl Genetic Programming System"
* [Darwin Tunes](http://darwintunes.org/) - "evolutionary music engine", uses both PDL and PerlGP to evolve music. Source: [github](https://github.com/bobular/DarwinTunes), Articles: [PNAS](http://www.pnas.org/content/early/2012/06/12/1203182109), [New Scientist](http://www.newscientist.com/blogs/culturelab/2010/08/the-experimental-evolution-of-music-and-snowball-the-dancing-cockatoo.html)
