# Awesome Standard ML

Useful things for the Standard ML programming language.

# Language definition

- [SML Family website](http://sml-family.org/)
- [Definition of Standard ML (SML'90)](http://sml-family.org/sml90-defn.pdf)
- **[Definition of Standard ML (SML'97)](http://sml-family.org/sml97-defn.pdf)**
- [Full grammar of SML'97 syntax](https://people.mpi-sws.org/~rossberg/sml.html)
- [Defects in SML'97](https://people.mpi-sws.org/~rossberg/hamlet/defects.pdf)
- [Mechanization of Standard ML](https://github.com/SMLFamily/The-Mechanization-of-Standard-ML)
- [Successor ML](https://github.com/SMLFamily/Successor-ML)

# Tutorials

- [Programming in Standard ML (Robert Harper)](https://www.cs.cmu.edu/~rwh/introsml/) (and [PDF version](https://www.cs.cmu.edu/~rwh/isml/book.pdf))
- [Programming in Standard ML '97: An Online Tutorial (Stephen Gilmore)](http://www.dcs.ed.ac.uk/home/stg/NOTES/)
- [Tips for Computer Scientists on Standard ML (Revised) (Mads Tofte)](https://web.archive.org/web/20130310061500/http://www.itu.dk/people/tofte/publ/tips.pdf)
- [A Gentle Introduction to ML (Andrew Cummings)](https://web.archive.org/web/20100209123129/http://www.dcs.napier.ac.uk/course-notes/sml/manual.html)
- [Programming Languages course notes (Dan Grossman)](https://courses.cs.washington.edu/courses/cse341/19sp/#lectures)
- [Introduction to Standard ML (Atsushi Ohori)](https://www.pllab.riec.tohoku.ac.jp/smlsharp/smlIntroSlides.pdf)
- [Standard ML Programming at Wikibooks](https://en.wikibooks.org/wiki/Standard_ML_Programming)

# Courses

- [CMU CS 15-150: Functional Programming](https://www.cs.cmu.edu/~15150/)
- [Cornell CS312: Data Structures and Functional Programming](https://www.cs.cornell.edu/courses/cs312/)

# Modules

- [Modules Matter Most](http://macqueenfest.cs.uchicago.edu/slides/harper.pdf): presentation and rationale of the module system
- [Essentials of Standard ML Modules (Mads Tofte)](https://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.165.95&rank=1)

# References

- [smlhelp](https://smlhelp.github.io/)
- [Unix System Programming with SML](http://mlton.org/References.attachments/Shipman02.pdf)
- [SML at Rosetta Code](https://rosettacode.org/wiki/Category:Standard_ML)

# Data structures

- [Purely Functional Data Structures](https://www.cs.cmu.edu/~rwh/theses/okasaki.pdf)

# Implementations

- [SML/NJ (Standard ML of New Jersey)](http://www.smlnj.org/): the canonical SML compiler
- [MLton](http://mlton.org/): very advanced whole-program optimizing compiler
  - [MaPLe](https://github.com/MPLLang): fork-join parallelism extension for MLton
- [Poly/ML](https://polyml.org): good compiler with threads and concurrent GC
- [CakeML](https://cakeml.org/): verified self-hosting subset of SML
- [Alice ML](https://www.ps.uni-saarland.de/alice/): SML with extensions for concurrent, distributed, and constraint programming
- [Moscow ML](https://mosml.org/): lightweight compiler and interpreter
- [HaMLet](https://people.mpi-sws.org/~rossberg/hamlet/): self-hosting SML interpreter written entirely in SML
- [MLKit](https://elsman.com/mlkit/): new compiler with versatile GC
- [SML#](https://www.pllab.riec.tohoku.ac.jp/smlsharp/): new compiler with practical language extensions
- [MLWorks](https://github.com/Ravenbrook/mlworks): old commercial compiler from Harlequin, open-sourced by Ravenbrook
- [SML.NET](https://www.cl.cam.ac.uk/research/tsg/SMLNET/): compiler targeting the .NET Common Language Runtime
- [MLj](http://www.dcs.ed.ac.uk/home/mlj/): compiles a SML subset to JVM bytecode
- [SMLtoJs](https://github.com/melsman/mlkit/blob/master/README_SMLTOJS.md): SML-to-JavaScript transpiler
- [SOSML](https://github.com/SOSML/SOSML): Online Interpreter for Standard ML, written in TypeScript
- [WebML](https://github.com/KeenS/webml): WebAssembly compiler and REPL that runs on browsers
- [LunarML](https://github.com/minoki/LunarML): transpile to Lua
- [Morel](https://github.com/julianhyde/morel): Standard ML interpreter, with relational extensions, implemented in Java
- [Further implementation overview](http://www.macs.hw.ac.uk/ultra/skalpel/html/sml.html): provides
  additional information per implementation, such as FFI, availability of REPL.

# Standard libraries (de jure and de facto)

- [Standard ML Basis Library](http://sml-family.org/Basis/)
- [Concurrent ML](http://cml.cs.uchicago.edu)
- [SML/NJ library](https://www.smlnj.org/doc/smlnj-lib/) also ships with MLton

# Extra Libraries

- [`MLton` structure](http://www.mlton.org/MLtonStructure)
- [Libraries for MLton](http://mlton.org/Libraries)
- [cmlib](https://github.com/standardml/cmlib) basic library of algorithms and data structures

# Further libraries with support for multiple implementations

- [sml-rmath](https://github.com/mclements/sml-rmath) library supporting seven SML
  implementations/dialects (for the [Rmath library](https://packages.debian.org/sid/r-mathlib))
- [sml-iconv](https://github.com/kni/sml-iconv) library supporting MLton and Poly/ML, based on FFI,
  providing bindings for iconv

# Build tools

- [Smackage](https://github.com/standardml/smackage): package manager for many implementations
- [SML/NJ Compilation Manager (CM)](https://smlnj.org/doc/CM/);
  for SML/NJ, also partly supported by MLton;
  also see the [Compiler Hacker's Guide to CM](https://github.com/sml-nj/smlnj/tree/master/sml/system)
- [PreML](https://github.com/br0ns/PreML): preprocessor for SML
- [smlformat](https://github.com/jluningp/smlformat): auto-formatter for the Standard ML language
  (based on SML/NJ)

# Applications

- [FoxNet](https://www.cs.cmu.edu/~fox/foxnet.html): TCP/IP stack in SML

# Commentary

- [Existential Type - a blog by Robert Harper](https://existentialtype.wordpress.com/)
- [Critique of Standard ML by Andrew Appel](http://sml-family.org/papers/Appel-critique-SML.pdf)
- [Reflections on Standard ML by David MacQueen](http://sml-family.org/papers/MacQueen-reflections.pdf)

# Community

- Freenode #sml IRC channel
- [Standard ML Reddit](https://www.reddit.com/r/sml/)
- [Standard ML Reddit Wiki](https://www.reddit.com/r/sml/wiki/index)
- [Standard ML implementers mailing list](https://sourceforge.net/p/sml/mailman/sml-implementers/)
- [Carnegie Mellon University (CMU) School of Computer Science](https://www.cs.cmu.edu)
