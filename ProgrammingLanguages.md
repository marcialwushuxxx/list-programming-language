# ProgrammingLanguages

<div class="foswikiTopic"><a name="foswikiTOC"></a><div class="foswikiToc"> <ul>
<li> <a href="#Statically_typed_languages"> Statically typed languages </a> <ul>
<li> <a href="#Haskell"> Haskell </a>
</li> <li> <a href="#ML"> ML </a>
</li> <li> <a href="#Java_and_C_35"> Java and C# </a>
</li> <li> <a href="#Algebraic_languages"> Algebraic languages </a>
</li> <li> <a href="#Logic_languages"> Logic languages </a>
</li> <li> <a href="#Wirth_39s_languages"> Wirth's languages </a>
</li> <li> <a href="#Experimental"> Experimental </a>
</li> <li> <a href="#Procedural"> Procedural </a>
</li></ul> 
</li> <li> <a href="#Logic_frameworks_44_theorem_provers_and_proof_assistants"> Logic frameworks, theorem provers and proof assistants </a>
</li> <li> <a href="#Dynamically_typed_languages"> Dynamically typed languages </a> <ul>
<li> <a href="#Scheme"> Scheme </a>
</li> <li> <a href="#Scripting_languages"> Scripting languages </a>
</li> <li> <a href="#Logic_languages_AN1"> Logic languages </a>
</li> <li> <a href="#Other"> Other </a>
</li></ul> 
</li> <li> <a href="#Document_languages"> Document languages </a> <ul>
<li> <a href="#Typesetting"> Typesetting </a>
</li> <li> <a href="#Markup_languages"> Markup languages </a>
</li> <li> <a href="#Literate_Programming"> Literate Programming </a>
</li></ul> 
</li> <li> <a href="#Miscellaneous"> Miscellaneous </a>
</li></ul> 
</div>
<p></p>
There are many interesting and useful <a href="/web/20160307000748/http://foswiki.cs.uu.nl/foswiki/bin/view/Techno/ProgrammingLanguageTheoryTextsOnline">ProgrammingLanguageTheoryTextsOnline</a>.
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://www.google.com/" target="_top">Google</a> has a <a href="https://web.archive.org/web/20160307000748/http://directory.google.com/Top/Computers/Programming/Languages/" target="_top">directory of programmming language websites</a>.
<p></p>
<p></p>
<h1><a name="Statically_typed_languages"></a>  Statically typed languages </h1>
<p></p>
<h2><a name="Haskell"></a>  Haskell </h2>
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://www.haskell.org/" target="_top">Haskell</a>
is a non-strict, polymorphic functional language with type inference and controlled side effects and supports overloading via type classes. Haskell implementations include compilers
(<a href="https://web.archive.org/web/20160307000748/http://www.haskell.org/ghc/" target="_top">GHC</a>, <a href="https://web.archive.org/web/20160307000748/http://www.cs.york.ac.uk/fp/nhc98" target="_top">NHC98</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.cs.chalmers.se/~augustss/hbc.html" target="_top">HBC</a>)
and interpreters (GHC and
<a href="https://web.archive.org/web/20160307000748/http://www.haskell.org/hugs/" target="_top">Hugs</a>).
Most implementations support extensions such as existential types and multiparameter type classes.
<a href="https://web.archive.org/web/20160307000748/http://www.generic-haskell.org/" target="_top">Generic Haskell</a>
is a preprocessor which extends Haskell with the ability to define functions which recurse over types.
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://www.cse.ogi.edu/~mpj/goferarc/index.html" target="_top">Gofer</a>
is a not-quite-Haskell predecessor of Hugs.
<a href="https://web.archive.org/web/20160307000748/http://www.cs.kun.nl/~clean/" target="_top">Concurrent Clean</a>
is a Haskell-like language with uniqueness typing.
<p></p>
<h2><a name="ML"></a>  ML </h2>
<p></p>
ML is a strict, polymorphic functional language with uncontrolled side effects, type inference and a powerful system of parametrizable modules.
<a href="https://web.archive.org/web/20160307000748/http://cm.bell-labs.com/cm/cs/what/smlnj/doc/FAQ/index.html" target="_top">SML FAQ</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.faqs.org/faqs/meta-lang-faq/" target="_top">ML FAQ</a>,
<a href="https://web.archive.org/web/20160307000748/http://foxnet.cs.cmu.edu/sml.html" target="_top">Info</a>.
<a href="https://web.archive.org/web/20160307000748/http://cm.bell-labs.com/cm/cs/what/smlnj/index.html" target="_top">SML/NJ</a>
is a robust compiler with extensions like first-class continuations and higher-order functors. <a href="https://web.archive.org/web/20160307000748/http://www.dina.kvl.dk/~sestoft/mosml.html" target="_top">Moscow ML</a>
is a popular lightweight compiler supporting recursive modules.
<a href="https://web.archive.org/web/20160307000748/http://www.mlton.org/" target="_top">MLton</a>
is a whole-program optimizing compiler.
The <a href="https://web.archive.org/web/20160307000748/http://www.it-c.dk/research/mlkit" target="_top">ML Kit</a>
is a modular reference implementation of the language.
<a href="https://web.archive.org/web/20160307000748/http://www.dcs.ed.ac.uk/home/mlj/" target="_top">MLj</a>
is a compiler which targets Java.
<a href="https://web.archive.org/web/20160307000748/http://www.cl.cam.ac.uk/Research/TSG/SMLNET/" target="_top">SML.NET</a>
is a compiler for a variant of Standard ML which targets Microsoft's .NET.
The new
<a href="https://web.archive.org/web/20160307000748/http://www.cs.bell-labs.com/~jhr/sml/basis/index.html" target="_top">SML Basis</a>
library is part of the standard.
<a href="https://web.archive.org/web/20160307000748/http://www.informatik.uni-bremen.de/~cxl/sml_tk/" target="_top">SML/Tk</a> is a Tk interface.
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://pauillac.inria.fr/ocaml/" target="_top">Objective Caml</a>
(also see <a href="https://web.archive.org/web/20160307000748/http://pauillac.inria.fr:80/caml/" target="_top">CAML</a>)
is a pragmatic ML variant with OO extensions.
<a href="https://web.archive.org/web/20160307000748/http://www.ocaml.org/" target="_top">ocaml.org</a>
has many useful links.
<a href="https://web.archive.org/web/20160307000748/http://research.microsoft.com/projects/ilx/fsharp.htm" target="_top">F#</a>
is (nearly) an implementation of CAML which targets .NET.
<a href="https://web.archive.org/web/20160307000748/http://pauillac.inria.fr/jocaml/" target="_top">JoCaml</a>
extends Ocaml with high-level features for distributed programming based on the
<a href="https://web.archive.org/web/20160307000748/http://join.inria.fr/" target="_top">join calculus</a>.
<a href="https://web.archive.org/web/20160307000748/http://cs-www.cs.yale.edu/homes/taha/MetaOCaml/" target="_top">MetaOCaml</a>
is a derivative of Ocaml with compile-time reflection.
<p></p>
<h2><a name="Java_and_C_35"></a>  Java and C# </h2>
<p></p>
Java is a statically typed object-oriented language very similar to C++, which
typically runs atop a virtual machine.
<a href="https://web.archive.org/web/20160307000748/http://www.javasoft.com/nav/read/Tutorial/index.html" target="_top">Tutorial</a>,
<a href="https://web.archive.org/web/20160307000748/http://java.sun.com/j2se" target="_top">Latest JDK</a>,
<a href="https://web.archive.org/web/20160307000748/http://splash.javasoft.com/beans/" target="_top">JavaBeans</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.gamelan.com/" target="_top">Gamelan</a>,
<a href="https://web.archive.org/web/20160307000748/http://pizzacompiler.sourceforge.net/" target="_top">Pizza</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.research.avayalabs.com/user/wadler/gj/" target="_top">GJ</a>.
There are a ton of resources and libraries available for Java:
<a href="https://web.archive.org/web/20160307000748/http://java.sun.com/blueprints/" target="_top">BluePrints</a>,
<a href="https://web.archive.org/web/20160307000748/http://developer.java.sun.com/developer/" target="_top">Developer Connection</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.jars.com/" target="_top">jars.com</a>,
<a href="https://web.archive.org/web/20160307000748/http://java.foundries.sourceforge.net/" target="_top">Java Foundry</a> at
<a href="https://web.archive.org/web/20160307000748/http://www.sourceforge.net/" target="_top">SourceForge</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.jguru.com/" target="_top">jGuru</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.cafeaulait.org/" target="_top">Cafe au Lait Java FAQs, News and Resources</a>.
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://msdn.microsoft.com/vstudio/techinfo/articles/upgrade/Csharpintro.asp" target="_top">C#</a>
is Microsoft's answer to Java; it runs atop the
<a href="https://web.archive.org/web/20160307000748/http://msdn.microsoft.com/net" target="_top">.NET platform</a>,
which (unlike the Java platform) is intended to support multiple source
languages.
<a href="https://web.archive.org/web/20160307000748/http://www.c-sharpcorner.com/" target="_top">C# Corner</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.csharptoday.com/" target="_top">C# Today</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.csharphelp.com/" target="_top">C# Help</a>.
<a href="https://web.archive.org/web/20160307000748/http://www.go-mono.com/" target="_top">Mono</a>
is an open source implementation of .NET for UNIX. 
<p></p>
<h2><a name="Algebraic_languages"></a>  Algebraic languages </h2>
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://www.cwi.nl/projects/MetaEnv" target="_top">ASF+SDF</a>
is a generic environment for language specification.
<a href="https://web.archive.org/web/20160307000748/http://maude.csl.sri.com/" target="_top">Maude</a> is a reflective language based on rewriting logic.
<a href="https://web.archive.org/web/20160307000748/http://www.cs.tu-berlin.de/~opal/" target="_top">OPAL</a> is actually higher-order, but has an algebraic flavor to it.
Other members of this group are:
<a href="https://web.archive.org/web/20160307000748/http://oldwww.comlab.ox.ac.uk/oucl/research/obj3.html" target="_top">OBJ</a> and
<a href="https://web.archive.org/web/20160307000748/http://www.ldl.jaist.ac.jp/cafeobj" target="_top">CafeOBJ</a>.
Also see
<a href="https://web.archive.org/web/20160307000748/http://www-cse.ucsd.edu/users/goguen/projs/halg.html" target="_top">Joseph Goguen's Hidden Algebra page</a>
and the
<a href="https://web.archive.org/web/20160307000748/http://oldwww.comlab.ox.ac.uk/oucl/groups/declarative/HSA/ha.html" target="_top">Oxford Hidden Algebra page</a>.
<a href="https://web.archive.org/web/20160307000748/http://www.txl.ca/index.html" target="_top">TXL</a>
is a hybrid functional/rule-based language with unification, implied iteration
and deep pattern match.
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://www.cpsc.ucalgary.ca/Research/charity/home.html" target="_top">Charity</a>
is a terminating, polymorphic language supporting type inference and
algebraic, and higher-order coalgebraic, datatypes.
<a href="https://web.archive.org/web/20160307000748/http://www-staff.socs.uts.edu.au/~cbj/FISh/index.html" target="_top">FISh</a>
is an array programming language based on the idea: Function = Imperative +
Shape.
<p></p>
<h2><a name="Logic_languages"></a>  Logic languages </h2>
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://www.cs.mu.oz.au/research/mercury/" target="_top">Mercury</a>
is a polymorphic logic/functional language with controlled side effects
supporting static declaration of modes and determinism for logical predicates.
<p></p>
<h2><a name="Wirth_39s_languages"></a>  Wirth's languages </h2>
<p></p>
Niklaus Wirth has created several languages of note, all procedural, of which Pascal is
the best known.
<a href="https://web.archive.org/web/20160307000748/http://www.pascal-central.com/" target="_top">Pascal Central</a>.
Brian Kernighan
(co-designer of C) wrote a famous diatribe,
<a href="https://web.archive.org/web/20160307000748/http://www.lysator.liu.se/c/bwk-on-pascal.html" target="_top">Why Pascal Is Not My Favorite Programming Language</a>.
See also the
<a href="https://web.archive.org/web/20160307000748/http://www.research.digital.com/SRC/modula-3/html/home.html" target="_top">Modula-3 Home Page</a> and
<a href="https://web.archive.org/web/20160307000748/http://www.research.digital.com/SRC/modula-3/html/srcm3.html" target="_top">Digital's SRC Modula-3</a>.
Shortcut to the
<a href="https://web.archive.org/web/20160307000748/http://www.research.digital.com/SRC/m3defn/html/m3.html" target="_top">Modula-3 Language Definition</a>.
Oberon is interesting for its tight integration with the Oberon operating
system. See:
<a href="https://web.archive.org/web/20160307000748/http://www.oberon.ethz.ch/" target="_top">ETH Oberon</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.oberon.ch/" target="_top">Oberon Microsystems</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.ssw.uni-linz.ac.at/Oberon.html" target="_top">Oberon System V4</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.math.tau.ac.il/~guy/Oberon" target="_top">The Oberon Reference Site</a> and
<a href="https://web.archive.org/web/20160307000748/http://www.factorial.com/hosted/webrings/oberon" target="_top">The Oberon Webring</a>.
<p></p>
<h2><a name="Experimental"></a>  Experimental </h2>
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://research.microsoft.com/vault/" target="_top">Vault</a>
is a low-level, safe, C-like language with functional features,
generics, modules and resource-tracking types.
<a href="https://web.archive.org/web/20160307000748/http://www.research.att.com/projects/cyclone/" target="_top">Cyclone</a>
is another C-like
language with tagged unions, parametric polymorphism, pattern-matching,
exceptions, structural typing for records and parametrized typedefs.
<a href="https://web.archive.org/web/20160307000748/http://www.ps.uni-sb.de/alice/" target="_top">Alice</a>
is an SML variant descended, at least in spirit, from
<a href="https://web.archive.org/web/20160307000748/http://www.mozart-oz.org/" target="_top">Mozart</a>.
<a href="https://web.archive.org/web/20160307000748/http://www.aldor.org/" target="_top">Aldor</a>
was originally intended as an extension language for the
computer algebra system AXIOM; it supports dependent and first-class
types.
<a href="https://web.archive.org/web/20160307000748/http://www.stratego-language.org/" target="_top">Stratego</a>
is a language for specifying program transformations via
rewriting strategies.
<a href="https://web.archive.org/web/20160307000748/http://www.cs.chalmers.se/~augustss/cayenne" target="_top">Cayenne</a>
is a programming language with dependent types;
type checking in Cayenne is undecidable (i.e., the checker may not terminate),
but the system is extremely expressive.
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://www.iam.unibe.ch/~scg/Research/Piccola/" target="_top">Piccola</a>
is a language based on
Milner's pi-calculus, designed to make it easy to define high-level connectors
for composing and coordinating software components written in other
languages.
<a href="https://web.archive.org/web/20160307000748/http://nice.sourceforge.net/" target="_top">Nice</a>
is an OO language based on Java, with parametric types,
higher-order functions and multi-methods.
<a href="https://web.archive.org/web/20160307000748/http://lamp.epfl.ch/~odersky/scala/" target="_top">Scala</a>
is a concurrent, object-oriented, functional language with a special focus on
web services, and designed as a successor to
<a href="https://web.archive.org/web/20160307000748/http://lamp.epfl.ch/funnel/" target="_top">Funnel</a>,
a language based on the Join calculus which combines FP with Petri
nets.
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://www-formal.stanford.edu/jmc/elephant/elephant.html" target="_top">Elephant 2000</a>
is a language from
<a href="https://web.archive.org/web/20160307000748/http://www-formal.stanford.edu/jmc/" target="_top">John McCarthy</a> (of LISP fame) based on speech-acts.
<a href="https://web.archive.org/web/20160307000748/http://www.gerbil.org/tom/" target="_top">TOM</a>
is an OO language that tries to support unplanned reuse of code.
<a href="https://web.archive.org/web/20160307000748/http://www.visviva.com/transframe/intro.htm" target="_top">Transframe</a>
is an OO language that lets dynamically and statically typed code interoperate
via run-time code generation.
<a href="https://web.archive.org/web/20160307000748/http://www.cs.man.ac.uk/arch/projects/ufo.html" target="_top">UFO</a>
Unites Functions and Objects.
<p></p>
<h2><a name="Procedural"></a>  Procedural </h2>
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://www.adahome.com/" target="_top">Ada</a>
is a procedural language with subtyping and parametrizable modules, intended
for heavy-duty military and industrial applications. See also
<a href="https://web.archive.org/web/20160307000748/http://www.gnat.com/" target="_top">Ada Core Technologies</a>,
home of the GNAT compiler.
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://pike.roxen.com/" target="_top">Pike</a>
is a fast statically typed scripting language. 
<p></p>
<h1><a name="Logic_frameworks_44_theorem_provers_and_proof_assistants"></a>  Logic frameworks, theorem provers and proof assistants </h1>
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://www.cs.kun.nl/~janz/yarrow" target="_top">Yarrow</a>
is a proof assistant for pure type systems with subtyping.
<a href="https://web.archive.org/web/20160307000748/http://www.dcs.ed.ac.uk/home/lego/" target="_top">LEGO</a>
is a proof assistant implementing Edinburgh LF, the (Generalized) Calculus of
Constructions and Unified Theory of Dependent Types.
<a href="https://web.archive.org/web/20160307000748/http://www.dcs.ed.ac.uk/home/isabelle/" target="_top">Isabelle</a>
is a generic theorem prover with tactics and tacticals.
<a href="https://web.archive.org/web/20160307000748/http://www.dcs.glasgow.ac.uk/~tfm/fmt/hol.html" target="_top">HOL</a>
is a theorem prover for higher-order logic.
<a href="https://web.archive.org/web/20160307000748/http://www.cs.cornell.edu/Info/Projects/NuPrl/nuprl.html" target="_top">Nuprl</a>
is a theorem prover based on a significant extension of Martin-Lof's
Intuitionistic Type Theory.
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://pauillac.inria.fr/coq/coq-eng.html" target="_top">COQ</a>
is a proof assistant for the Calculus of Inductive Constructions.
<a href="https://web.archive.org/web/20160307000748/http://pvs.csl.sri.com/" target="_top">PVS</a> is a verification system including a
specification language based on classical, typed, higher-order logic and a
theorem prover.
<a href="https://web.archive.org/web/20160307000748/http://www-2.cs.cmu.edu/~twelf/" target="_top">Twelf</a>
includes the LF framework with type reconstruction, the Elf
constraint logic programming language and an inductive meta-theorem prover for
LF.
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://web.cs.ualberta.ca/~piotr/Mizar/" target="_top">The Mizar Project</a>
is a long-term effort aimed at developing software to support a working
mathematician in preparing papers, including a natural deduction language for
expressing mathematics over Tarski-Grothendieck set theory.
<p></p>
<h1><a name="Dynamically_typed_languages"></a>  Dynamically typed languages </h1>
<p></p>
<h2><a name="Scheme"></a>  Scheme </h2>
<p></p>
Scheme is a minimalist functional language with uncontrolled side effects and
a hygienic macro system. It descends from LISP.
<a href="https://web.archive.org/web/20160307000748/http://www.drscheme.org/" target="_top">DrScheme</a>
is a full-featured Scheme environment including a graphic IDE, debugger, help
system and GUI library, well-suited for classroom use.
<a href="https://web.archive.org/web/20160307000748/http://www.iro.umontreal.ca/~gambit/" target="_top">Gambit Scheme</a>,
<a href="https://web.archive.org/web/20160307000748/http://www-sop.inria.fr/mimosa/fp/Bigloo/" target="_top">Bigloo</a>,
(<a href="https://web.archive.org/web/20160307000748/http://www.scheme.com/petitecs.html" target="_top">Petite</a>)
<a href="https://web.archive.org/web/20160307000748/http://www.scheme.com/" target="_top">Chez Scheme</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.sof.ch/dan/qscheme/index-e.html" target="_top">QScheme</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.malgil.com/sxm/" target="_top">SXM</a>,
<a href="https://web.archive.org/web/20160307000748/http://sisc.sourceforge.net/" target="_top">SISC</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.schemers.org/" target="_top">Schemers.Org</a>,
the <a href="https://web.archive.org/web/20160307000748/http://www.cs.indiana.edu/scheme-repository/home.html" target="_top">Scheme Repository</a>.
<p></p>
<h2><a name="Scripting_languages"></a>  Scripting languages </h2>
<p></p>
What these languages seem to have in common is that they are all dynamically
typed and procedural, with lots of built-in datatypes and a strong emphasis on
syntax and text-processing. Also, it seems all of them are implemented either
as interpreters, or as compilers targeting a virtual machine, and support
garbage collection.
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://www.python.org/" target="_top">Python</a>
(and the Java-targeting implementation
<a href="https://web.archive.org/web/20160307000748/http://www.jython.org/" target="_top">Jython</a>)
is an OO language with closures, exceptions and resumptions.
<a href="https://web.archive.org/web/20160307000748/http://www.ruby-lang.org/" target="_top">Ruby</a>
is a single inheritance OO language with closures.
<a href="https://web.archive.org/web/20160307000748/http://www.nickle.org/" target="_top">Nickle</a>
is a desk calculator language with optional static type checking.
<a href="https://web.archive.org/web/20160307000748/http://www.lua.org/" target="_top">Lua</a>
is lightweight language designed for extending applications.
<a href="https://web.archive.org/web/20160307000748/http://www.perl.org/" target="_top">Perl</a>
is a language with OO extensions and built-in support for text-processing.
<a href="https://web.archive.org/web/20160307000748/http://www.cs.arizona.edu/icon/" target="_top">Icon</a>
supports "goal-directed evaluation".
<a href="https://web.archive.org/web/20160307000748/http://www.tcl.tk/" target="_top">Tcl</a>
is a language for gluing applications together and interfacing with the Tk
graphical toolkit.
The
<a href="https://web.archive.org/web/20160307000748/http://www.musikwissenschaft.uni-mainz.de/~ag/q/" target="_top">Q language</a>
is based on term rewriting.
<a href="https://web.archive.org/web/20160307000748/http://www2.hursley.ibm.com/rexx/" target="_top">Rexx</a>
is a procedural language developed at IBM. See also
<a href="https://web.archive.org/web/20160307000748/http://www-3.ibm.com/software/ad/obj-rexx/" target="_top">Object Rexx</a>,
an OO extension, and
<a href="https://web.archive.org/web/20160307000748/http://www2.hursley.ibm.com/netrexx/" target="_top">NetRexx</a>,
which targets Java.
<p></p>
<h2><a name="Logic_languages_AN1"></a>  Logic languages </h2>
<p></p>
Prolog is the de facto standard here, for intuitionistic logic:
<a href="https://web.archive.org/web/20160307000748/http://www.swi-prolog.org/" target="_top">SWI-Prolog</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.sics.se/sicstus.html" target="_top">SICStus Prolog</a>,
<a href="https://web.archive.org/web/20160307000748/http://pauillac.inria.fr/~diaz/gnu-prolog" target="_top">GNU Prolog</a>,
<a href="https://web.archive.org/web/20160307000748/http://yap.sourceforge.net/" target="_top">YAP Prolog</a>,
<a href="https://web.archive.org/web/20160307000748/http://xsb.sourceforge.net/" target="_top">XSB</a>.
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://www.cs.rmit.edu.au/lygon/" target="_top">Lygon</a> is based on linear logic.
<p></p>
<h2><a name="Other"></a>  Other </h2>
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://www.erlang.org/" target="_top">Erlang</a>
has built-in support for concurrency, distributed computation and fault
tolerance. Erlang is used in several large telecommunication systems at
<a href="https://web.archive.org/web/20160307000748/http://www.ericsson.se/" target="_top">Ericsson</a>.
See also
<a href="https://web.archive.org/web/20160307000748/http://goanna.cs.rmit.edu.au/~geoff/erlang/index.html" target="_top">Gerl</a>.
<p></p>
<p></p>
Objective C is an extension of C with constructs for dynamically typed
object-oriented programming. See
<a href="https://web.archive.org/web/20160307000748/http://www.swarm.org/resources-objc.html" target="_top">Objective C Resources</a> at swarm.org.
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://www.cs.washington.edu/research/projects/cecil/cecil/www/cecil-home.html" target="_top">Cecil</a>
is a pure OO language with multi-methods; the Vortex compiler uses a
whole-program optimizer to largely eliminate unnecessary dispatches.
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://education.mit.edu/starlogo/" target="_top">StarLogo</a>
is an updated version of the well known
<a href="https://web.archive.org/web/20160307000748/http://el.www.media.mit.edu/groups/logo-foundation/" target="_top">LOGO</a>
language.
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://www.mozart-oz.org/" target="_top">Mozart</a> is a multiparadigm language based on Oz,
which supports declarative programming, object-oriented programming, constraint
programming, and concurrency as part of a coherent whole.
<p></p>
<h1><a name="Document_languages"></a>  Document languages </h1>
<p></p>
<h2><a name="Typesetting"></a>  Typesetting </h2>
<p></p>
TeX is a typesetting program created by
<a href="https://web.archive.org/web/20160307000748/http://www-cs-staff.stanford.edu/~knuth/" target="_top">Donald Knuth</a>,
based on a macro programming language. It is widely used in academia and
research circles, not least because of its unequaled support for mathematical
typography. Many useful macro packages are available from the
<a href="https://web.archive.org/web/20160307000748/http://xxx.lanl.gov/help/CTANservers.html" target="_top">CTAN servers</a>.
<a href="https://web.archive.org/web/20160307000748/http://www.ens.fr/omega/" target="_top">Omega</a>
is a 16-bit version of TeX supporting Unicode.
<a href="https://web.archive.org/web/20160307000748/http://tex.loria.fr/index.html" target="_top">(La)TeX Navigator</a>
is a portal.
<a href="https://web.archive.org/web/20160307000748/http://www.inf.bme.hu/~pts/textrace" target="_top">TeXtrace</a>
converts TeX fonts to Type 1 fonts, which is important for producing PDF files
legible in Acrobat.
<p></p>
<a href="https://web.archive.org/web/20160307000748/http://snark.ptc.spbu.ru/~uwe/lout/lout.html" target="_top">Lout</a>
is a document formatting system similar to TeX which produces PostScript and PDF.
<p></p>
<h2><a name="Markup_languages"></a>  Markup languages </h2>
<p></p>
XML is a markup language related to HTML widely used in industry.
See the
<a href="https://web.archive.org/web/20160307000748/http://www.w3c.org/xml" target="_top">W3C XML Page</a>,
the <a href="https://web.archive.org/web/20160307000748/http://xml.coverpages.org/xml.html" target="_top">XML Cover Pages</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.xml.com/" target="_top">xml.com</a>
and
<a href="https://web.archive.org/web/20160307000748/http://www.cafeconleche.org/" target="_top">Cafe con Leche XML News and Resources</a>.
<p></p>
SGML is a predecessor of XML which is still used in many places. See
<a href="https://web.archive.org/web/20160307000748/http://xml.coverpages.org/sgml.html" target="_top">SGML Cover Pages</a>.
<a href="https://web.archive.org/web/20160307000748/http://www.oasis-open.org/cover/dsssl.html" target="_top">DSSSL</a>
is an ISO standard for formatting and transforming SGML documents,
based on a superset of the Scheme programming language.
<a href="https://web.archive.org/web/20160307000748/http://www.netfolder.com/DSSSL/" target="_top">OpenJade</a>
is an implementation of DSSSL based on James Clark's earlier
<a href="https://web.archive.org/web/20160307000748/http://www.jclark.com/jade/" target="_top">Jade</a> (also
<a href="https://web.archive.org/web/20160307000748/http://www.jclark.com/dsssl/" target="_top">James Clark's DSSSL Page</a>).
There is a
<a href="https://web.archive.org/web/20160307000748/http://www.mulberrytech.com/dsssl/dssslist/" target="_top">DSSSL Mailing List</a>.
<p></p>
<h2><a name="Literate_Programming"></a>  Literate Programming </h2>
<p></p>
See the
<a href="https://web.archive.org/web/20160307000748/http://www.desy.de/user/projects/LitProg.html" target="_top">DESY Literate Programming Library</a>
for a summary. 
<p></p>
<h1><a name="Miscellaneous"></a>  Miscellaneous </h1>
<p></p>
If it exists (or once did), you will probably find it in the the
<a href="https://web.archive.org/web/20160307000748/http://cuiwww.unige.ch/langlist" target="_top">Language List</a>.
Other kinds of information are available at
<a href="https://web.archive.org/web/20160307000748/ftp://parcftp.parc.xerox.com/pub/ilu/ilu.html" target="_top">Inter-Language Unification</a>
and
<a href="https://web.archive.org/web/20160307000748/http://www-white.media.mit.edu:80/~tpminka/PLE/" target="_top">Programming Language Exploration</a>.
<p></p>
Here are some quick links to other programming languages and related projects:
the
<a href="https://web.archive.org/web/20160307000748/http://suif.stanford.edu/suif/suif.html" target="_top">SUIF Compiler</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.llnl.gov/sisal" target="_top">Sisal</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.cs.hmc.edu/~hodas/research/lolli/" target="_top">Lolli</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.cogs.susx.ac.uk/users/adrianh/poplog.html" target="_top">Poplog</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.icsi.berkeley.edu/~sather/" target="_top">Sather</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.r-project.org/" target="_top">The R Project for Statistical Computing</a>,
<a href="https://web.archive.org/web/20160307000748/http://merd.sourceforge.net/" target="_top">merd</a>,
<a href="https://web.archive.org/web/20160307000748/http://flarelang.sourceforge.net/" target="_top">Flare</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.speculate.de/styx/index.html" target="_top">Styx Scanner &amp; Parser Generator</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.risc.uni-linz.ac.at/projects/basic/hpgp" target="_top">High Performance Generic Programming Project</a>,
the <a href="https://web.archive.org/web/20160307000748/http://cime.lri.fr/" target="_top">CiME Rewrite Tool</a>,
<a href="https://web.archive.org/web/20160307000748/http://avram.sourceforge.net/" target="_top">avram</a>,
the <a href="https://web.archive.org/web/20160307000748/http://ivm.sourceforge.net/" target="_top">Internet Virtual Machine</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.bagley.org/~doug/shootout/" target="_top">The Great Computer Language Shootout</a>,
<a href="https://web.archive.org/web/20160307000748/http://dada.perl.it/shootout" target="_top">The Great Win32 Computer Language Shootout</a>,
<a href="https://web.archive.org/web/20160307000748/http://www.cs.orst.edu/~budd/leda.html" target="_top">Leda</a>.
<p></p>
Broken links:
<a href="https://web.archive.org/web/20160307000748/http://www-fide.dcs.st-andrews.ac.uk/Info/Napier88.html" target="_top">Napier88</a>  at St. Andrews, and
<a href="https://web.archive.org/web/20160307000748/http://www.informatik.uni-kiel.de/inf/Kluge/KiR/" target="_top">KiR</a> at Kiel.
<p></p>
-- <a class="foswikiNewLink" href="/web/20160307000748/http://foswiki.cs.uu.nl/foswiki/bin/edit/Main/FrankAtanassow?topicparent=Techno.ProgrammingLanguages" rel="nofollow" title="Create this topic">FrankAtanassow</a> - 23 Sep 2002 </div>
