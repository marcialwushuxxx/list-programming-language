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



# ProgrammingLanguageTheoryTextsOnline

<div class="foswikiTopic"><a name="foswikiTOC"></a><div class="foswikiToc"> <ul>
<li> <a href="#Obligatory_plea"> Obligatory plea </a>
</li> <li> <a href="#Reference_texts"> Reference texts </a>
</li> <li> <a href="#Notes_and_tutorials"> Notes and tutorials </a>
</li> <li> <a href="#Other_texts"> Other texts </a>
</li> <li> <a href="#Resources"> Resources </a>
</li> <li> <a href="#Submission_guidelines"> Submission guidelines </a>
</li> <li> <a href="#Administration"> Administration </a>
</li></ul> 
</div>
<p></p>
This is a collection of programming language theory texts and resources, all
of which are <strong>freely available</strong> over the Internet.
<p></p>
Many valuable reference texts on programming language theory, previously only
available in paper form, have in recent years become publicly accessible from
the net. I list here the ones I know of; below that you will also find a much
broader list of lecture notes and tutorials, other interesting reading, plus a
collection of related resources.
<p></p>
<h1><a name="Obligatory_plea"></a>  Obligatory plea </h1>
<p></p>
If you know of any other texts or resources which might belong here, please
add them to this list by editing this page.
(Does your submission belong in this list? See the <a href="#SubmissionGuidelines" class="foswikiCurrentTopicLink">#SubmissionGuidelines</a>.)
<p></p>
I hope other authors will also make an effort, when possible, to get their
books online, especially if the book goes out of print.
<p></p>
Part of the reason PL theory and advanced programming languages seem
impenetrable to other communities is that learning materials are hard to
obtain, or demand a sizeable investment of resources (time, money, ...) even
if the potential reader is only exploring the subject.
<p></p>
<a name="ReferenceTexts"></a>
<h1><a name="Reference_texts"></a>  Reference texts </h1>
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www-swiss.ai.mit.edu/~hal/hal.html" target="_top">Harold Abelson</a> and <a href="https://web.archive.org/web/20160426010223/http://www-swiss.ai.mit.edu/~gjs/gjs.html" target="_top">Gerald Jay Sussman</a> with Julie Sussman.
<strong>Structure and Interpretation of Computer Programs.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://mitpress.mit.edu/sicp/full-text/book/book.html" target="_top">MIT</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.isg.sfu.ca/~hak/" target="_top">Hassan Ait-Kaci</a>.
<strong>Warren's Abstract Machine: A Tutorial Reconstruction.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.isg.sfu.ca/~hak/documents/wam.html" target="_top">link</a>)
<p></p>
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cs.unibo.it/~asperti/" target="_top">Andrea Asperti</a> and <a href="https://web.archive.org/web/20160426010223/http://www.di.ens.fr/users/longo" target="_top">Giussepe Longo</a>.
<strong>Categories, Types and Structures. An introduction to Category Theory for the working computer scientist.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.di.ens.fr/users/longo/download.html" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cs.kun.nl/~henk/" target="_top">Henk Barendregt</a>.
<strong>Lambda Calculi with Types.</strong>
(<a href="https://web.archive.org/web/20160426010223/ftp://ftp.cs.kun.nl/pub/CompMath.Found/HBKJ.ps.Z" target="_top">compressed PS</a>)
<p></p>
--.
<strong>The Lambda Calculus.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.elpress.com/readittoc.jsp?Book=0444875085" target="_top">currently broken link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://euclid.math.mcgill.ca/~barr/" target="_top">Michael Barr</a> and <a href="https://web.archive.org/web/20160426010223/http://www.cwru.edu/artsci/math/wells/" target="_top">Charles Wells</a>.
<strong>Toposes, Triples and Theories.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cwru.edu/artsci/math/wells/pub/ttt.html" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.thoralf.uwaterloo.ca/" target="_top">Stanley N. Burris</a> and H.P. Sankappanavar.
<strong>A Course in Universal Algebra.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.thoralf.uwaterloo.ca/htdocs/ualg.html" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.lsv.ens-cachan.fr/~comon/?lang=en" target="_top">Hubert Comon</a>, <strong>et al.</strong>
<strong>Tree Automata Techniques and Applications.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.grappa.univ-lille3.fr/tata/" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.math.uni-hamburg.de/home/diestel/" target="_top">Reinhard Diestel</a>.
<strong>Graph Theory.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.math.uni-hamburg.de/home/diestel/books/graph.theory/" target="_top">link</a>) 
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cs.engr.uky.edu/~raphael/" target="_top">Raphael Finkel</a>.
<strong>Advanced Programming Language Design.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.awprofessional.com/catalog/product.asp?product_id={92E30B39-5D91-45F9-9919-D202BE6341F9}&amp;selectDescTypeId={A80972E0-1077-4518-954C-44E43E341DF7}" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cs.vu.nl/~dick/" target="_top">Dick Grune</a> and <a href="https://web.archive.org/web/20160426010223/http://www.cs.vu.nl/~ceriel/" target="_top">Ceriel J.H. Jacobs</a>.
<strong>Parsing Techniques - A Practical Guide.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cs.vu.nl/~dick/PTAPG.html" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www-2.cs.cmu.edu/~rwh/" target="_top">Robert Harper</a>.
<strong>Programming Languages: Theory and Practice. (Draft)</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www-2.cs.cmu.edu/~rwh/plbook/" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cogs.susx.ac.uk/users/matthewh/" target="_top">Matthew Hennessy</a>.
<strong>Semantics of Programming Languages.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cogs.susx.ac.uk/users/matthewh/semnotes.ps.gz" target="_top">gzipped PS/2up</a>, <a href="https://web.archive.org/web/20160426010223/http://www.cl.cam.ac.uk/Teaching/2000/Semantics/" target="_top">Andrew Pitts' course material</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.diku.dk/~neil/" target="_top">N.D. Jones</a>, C.K. Gomard and <a href="https://web.archive.org/web/20160426010223/http://www.dina.dk/~sestoft/" target="_top">P. Sestoft</a>.
<strong>Partial Evaluation and Automatic Program Generation.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.dina.dk/~sestoft/pebook/pebook.html" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://web.comlab.ox.ac.uk/oucl/people/carroll.morgan.html" target="_top">Carroll Morgan</a>.
<strong>Programming from Specifications.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://web.comlab.ox.ac.uk/oucl/publications/books/PfS/" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://kurt.cla.kobe-u.ac.jp/~hayashi/index-english.html" target="_top">Susumu Hayashi</a> and <a href="https://web.archive.org/web/20160426010223/http://www602.math.ryukoku.ac.jp/~nakano" target="_top">Hiroshi Nakano</a>.
<strong>PX: A Computational Logic.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www602.math.ryukoku.ac.jp/~nakano/papers/freePXbook.pdf" target="_top">PDF</a>, <a href="https://web.archive.org/web/20160426010223/http://kurt.cla.kobe-u.ac.jp/~hayashi/PXbook.html" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.daimi.au.dk/~hrn/" target="_top">Hanne Riis Nielson</a> and <a href="https://web.archive.org/web/20160426010223/http://www.daimi.au.dk/~fn/" target="_top">Flemming Nielson</a>.
<strong>Semantics With Applications: A Formal Introduction.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.daimi.au.dk/~bra8130/Wiley_book/wiley.html" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cs.chalmers.se/~bengt/" target="_top">Bengt Nordstrom</a> and <a href="https://web.archive.org/web/20160426010223/http://www.cs.chalmers.se/~kentp/" target="_top">Kent Petersson</a> and <a href="https://web.archive.org/web/20160426010223/http://www.cs.chalmers.se/~smith/" target="_top">Jan M. Smith</a>.
<strong>Programming in Martin-Lof's Type Theory: An Introduction.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cs.chalmers.se/Cs/Research/Logic/book/" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://research.microsoft.com/Users/simonpj/" target="_top">Simon Peyton Jones</a> and David R. Lester.
<strong>Implementing functional languages: a tutorial.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.research.microsoft.com/Users/simonpj/Papers/papers.html" target="_top">link</a>,
<a href="https://web.archive.org/web/20160426010223/http://www.research.microsoft.com/Users/simonpj/Papers/student.ps.gz" target="_top">compressed PS</a>,
<a href="https://web.archive.org/web/20160426010223/http://www.research.microsoft.com/Users/simonpj/Papers/pjlester-1.11.tar.Z" target="_top">sources</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cs.kun.nl/~rinus/" target="_top">Rinus Plasmeijer</a> and <a href="https://web.archive.org/web/20160426010223/http://www.cs.kun.nl/~marko/" target="_top">Marko van Eekelen</a>.
<strong>Functional Programming and Parallel Graph Rewriting.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cs.kun.nl/~clean/Manuals/Addison__Wesley_book/addison__wesley_book.html" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cs.jhu.edu/~scott/" target="_top">Scott F. Smith</a>.
<strong>Programming Languages.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cs.jhu.edu/~scott/plbook/" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.dcs.qmw.ac.uk/~pt/" target="_top">Paul Taylor</a>.
<strong>Practical Foundations of Mathematics.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.dcs.qmw.ac.uk/~pt/Practical_Foundations/" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cs.ukc.ac.uk/people/staff/sjt/" target="_top">Simon Thompson</a>.
<strong>Type Theory and Functional Programming.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cs.ukc.ac.uk/people/staff/sjt/TTFP/" target="_top">link</a>)
<p></p>
<a name="NotesAndTutorials"></a>
<h1><a name="Notes_and_tutorials"></a>  Notes and tutorials </h1>
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.luca.demon.co.uk/" target="_top">Luca Cardelli</a> and <a href="https://web.archive.org/web/20160426010223/http://www.cs.brown.edu/people/pw/" target="_top">Peter Wegner</a>.
<strong>On understanding types, data abstraction and polymorphism.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://research.microsoft.com/Users/luca/Papers/OnUnderstanding.ps" target="_top">PS/letter</a>,
<a href="https://web.archive.org/web/20160426010223/http://research.microsoft.com/Users/luca/Papers/OnUnderstanding.pdf" target="_top">PDF/letter</a>,
<a href="https://web.archive.org/web/20160426010223/http://research.microsoft.com/Users/luca/Papers/OnUnderstanding.A4.ps" target="_top">PS/A4</a>,
<a href="https://web.archive.org/web/20160426010223/http://research.microsoft.com/Users/luca/Papers/OnUnderstanding.A4.pdf" target="_top">PDF/A4</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.di.ens.fr/~castagna/" target="_top">Giuseppe Castagna</a>.
<strong>Subtyping and Object-oriented Programming</strong>.
(<a href="https://web.archive.org/web/20160426010223/http://www.di.ens.fr/~castagna/TEACHING/dea_ens.html" target="_top">course page</a>,
<a href="https://web.archive.org/web/20160426010223/ftp://ftp.ens.fr/pub/dmi/users/castagna/TEACHING/dea-spp.ps.gz" target="_top">gzipped PS</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cs.cornell.edu/home/rc/" target="_top">Robert Constable</a>.
<strong>Typed Logic.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cs.cornell.edu/cs671-fa99/" target="_top">link</a>,
<a href="https://web.archive.org/web/20160426010223/http://www.cs.cornell.edu/cs671-fa99/typed%20logic/index.html" target="_top">HTML</a>,
<a href="https://web.archive.org/web/20160426010223/http://www.cs.cornell.edu/cs671-fa99/postscript%20files/mark99.ps" target="_top">PS</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cis.upenn.edu/~jean/home.html" target="_top">Jean H. Gallier</a>.
<strong>Constructive Logics. Part I: A Tutorial on Proof Systems and Typed lambda-Calculi.</strong>
(<a href="https://web.archive.org/web/20160426010223/ftp://ftp.cis.upenn.edu/pub/papers/gallier/conslog1.dvi.Z" target="_top">compressed DVI</a>)
<p></p>
--.
<strong>Constructive Logics. Part II: Linear Logic and Proof Nets.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cis.upenn.edu/~jean/gallier-old-pubs.html" target="_top">link</a>,
<a href="https://web.archive.org/web/20160426010223/http://www.cis.upenn.edu/~jean/gallier-old-pubs.html" target="_top">compressed DVI</a>,
<a href="https://web.archive.org/web/20160426010223/ftp://ftp.cis.upenn.edu/pub/papers/gallier/conslog2.ps.Z" target="_top">compressed PS</a>)
<p></p>
--.
<strong>On the Correspondence between Proofs and lambda-Terms.</strong>
(<a href="https://web.archive.org/web/20160426010223/ftp://ftp.cis.upenn.edu/pub/papers/gallier/cahiers.ps.Z" target="_top">compressed PS</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cl.cam.ac.uk/users/mjcg/" target="_top">Mike Gordon</a>.
<strong>Introduction to Functional Programming.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cl.cam.ac.uk/Teaching/FuncProg/FuncProg.html" target="_top">link</a>)
<p></p>
--.
<strong>Specification and Verification I.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cl.cam.ac.uk/Teaching/2000/SpecVer1/" target="_top">link - 2000 ed.</a>)
<p></p>
--.
<strong>Specification and Verification II.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cl.cam.ac.uk/Teaching/1999/SpecVer2/" target="_top">link - 1999 ed.</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cl.cam.ac.uk/users/jrh" target="_top">John Harrison</a>.
<strong>Introduction to Functional Programming (1996/7).</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cl.cam.ac.uk/Teaching/Lectures/funprog-jrh-1996/index.html" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cs.bham.ac.uk/~axj" target="_top">Achim Jung</a> and <a href="https://web.archive.org/web/20160426010223/http://www.dcs.ed.ac.uk/home/samson" target="_top">Samson Abramsky</a>.
Domain Theory.
(<a href="https://web.archive.org/web/20160426010223/http://www.cs.bham.ac.uk/~axj/pub/papers/handy.ps.gz" target="_top">gzipped PS</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cwi.nl/~kurz" target="_top">Alexander Kurz</a>.
<strong>Coalgebras and Modal Logic.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cwi.nl/~kurz/cml-esslli01.html" target="_top">link</a>)
<p></p>
Per Martin-Lof.
<strong>On the Meanings of the Logical Constants and the Justifications of the Logical Laws.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cs.cornell.edu/cs671-fa99/martin.html" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cs.chalmers.se/~bengt/" target="_top">Bengt Nordstrom</a>,
<a href="https://web.archive.org/web/20160426010223/http://www.cs.chalmers.se/~kentp/" target="_top">Kent Petersson</a> and
<a href="https://web.archive.org/web/20160426010223/http://www.cs.chalmers.se/~smith/" target="_top">Jan M. Smith</a>.
<strong>Martin-Lof's Type Theory.</strong>
(<a href="https://web.archive.org/web/20160426010223/ftp://ftp.cs.chalmers.se/pub/cs-reports/papers/smith/hlcs.ps.gz" target="_top">gzipped PS</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cl.cam.ac.uk/users/lcp/" target="_top">Lawrence C. Paulson</a>.
<strong>Foundations of Functional Programming.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cl.cam.ac.uk/Teaching/2000/FoundsCS/" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cs.cmu.edu/~fp/" target="_top">Frank Pfenning</a>.
<strong>Automated Theorem Proving.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cs.cmu.edu/~fp/courses/atp/handouts.html" target="_top">link</a>)
<p></p>
--.
<strong>Computation and Deduction.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cs.cmu.edu/~fp/courses/comp-ded/handouts.html" target="_top">link</a>)
<p></p>
Wesley Phoa.
<strong>An introduction to fibrations, topos theory, the effective topos and modest sets.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.lfcs.informatics.ed.ac.uk/reports/92/ECS-LFCS-92-208/ECS-LFCS-92-208.ps.gz" target="_top">gzipped PS</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cl.cam.ac.uk/~amp12/" target="_top">Andrew M. Pitts</a>.
<strong>Lecture Notes on Types.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cl.cam.ac.uk/Teaching/2000/Types/" target="_top">link</a>)
<p></p>
--.
<strong>Operational Semantics and Program Equivalence.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www-sop.inria.fr/oasis/Caminha00/opespe.ps" target="_top">PS</a>)
<p></p>
--.
<strong>Categorical Logic.</strong>
(<a href="https://web.archive.org/web/20160426010223/ftp://ftp.cl.cam.ac.uk/papers/amp12/catl.ps.gz" target="_top">gzipped PS</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.dcs.ed.ac.uk/home/gdp/" target="_top">Gordon Plotkin</a>.
<strong>Pisa Notes (on Domain Theory).</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.dcs.ed.ac.uk/home/gdp/publications/" target="_top">link</a>,
<a href="https://web.archive.org/web/20160426010223/http://www.dcs.ed.ac.uk/home/gdp/publications/Domains.ps.gz" target="_top">gzipped PS</a>,
<a href="https://web.archive.org/web/20160426010223/http://www.dcs.ed.ac.uk/home/gdp/publications/Domains_a4.ps.gz" target="_top">gzipped PS/A4</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.disi.unige.it/person/RosoliniG" target="_top">Giuseppe Rosolini</a>.
<strong>Sheaves.</strong>
(gzipped PS:
<a href="https://web.archive.org/web/20160426010223/http://jazz.pst.informatik.uni-muenchen.de/spring-school99/topos.ps.gz" target="_top">A4</a>,
<a href="https://web.archive.org/web/20160426010223/http://www.pst.informatik.uni-muenchen.de/spring-school99/topos_l.ps.gz" target="_top">US</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.mathematik.uni-muenchen.de/~schwicht/" target="_top">Helmut Schwichtenberg</a>.
<strong>Proof Theory.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.mathematik.uni-muenchen.de/~schwicht/lectures/proofth/ss99/pt99.ps.Z" target="_top">compressed PS</a>,
<a href="https://web.archive.org/web/20160426010223/http://www.mathematik.uni-muenchen.de/~schwicht/lectures/proofth/ss99/pt99.dvi.Z" target="_top">compressed DVI</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.diku.dk/users/rambo/" target="_top">Morten Heine B. Sorenson</a> and <a href="https://web.archive.org/web/20160426010223/http://zls.mimuw.edu.pl/~urzy/home.html" target="_top">Pawel Urzyczyn</a>.
<strong>Lectures on the Curry-Howard Isomorphism.</strong>
(gzipped PS)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.mathematik.tu-darmstadt.de/~streicher/" target="_top">Thomas Streicher</a>.
<strong>Fibred Categories.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.mathematik.tu-darmstadt.de/~streicher/FIBR/fib.ps.gz" target="_top">gzipped PS</a>)
<p></p>
<a name="OtherTexts"></a>
<h1><a name="Other_texts"></a>  Other texts </h1>
<p></p>
Texts in this section are interesting, though not directly
related to programming language theory.
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www.cs.umaine.edu/~chaitin" target="_top">G.J. Chaitin</a>.
<strong>The Unknowable.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.cs.umaine.edu/~chaitin/unknowable/index.html" target="_top">link</a>)
<p></p>
<a href="https://web.archive.org/web/20160426010223/http://www-2.cs.cmu.edu/~koopman" target="_top">Philip J. Koopman, Jr.</a>
<strong>Stack Computers: the new wave.</strong>
(<a href="https://web.archive.org/web/20160426010223/http://www.mathematik.tu-darmstadt.de/~streicher/FIBR/fib.ps.gz" target="_top">link</a>)
<p></p>
<a name="MoreResources"></a>
<h1><a name="Resources"></a>  Resources </h1>
<p></p>
If you are interested in these topics, you can find additional resources (mostly in the forms of technical articles and theses) via:
<p></p> <ul>
<li> <a href="https://web.archive.org/web/20160426010223/http://citeseer.nj.nec.com/cs" target="_top">NEC's CS ResearchIndex</a>
</li> <li> Mark Leone's <a href="https://web.archive.org/web/20160426010223/http://www.cs.cmu.edu/~mleone/language-research.html" target="_top">Programming Language Research</a> page
</li> <li> Mark Leone's <a href="https://web.archive.org/web/20160426010223/http://www.cs.cmu.edu/afs/cs.cmu.edu/user/mleone/web/language-people.html" target="_top">Researchers in Programming Languages and Compilers</a> page
</li> <li> <a href="https://web.archive.org/web/20160426010223/http://www.afm.sbu.ac.uk/fm/" target="_top">WWW Virtual Library: Formal Methods</a>
</li> <li> <a href="https://web.archive.org/web/20160426010223/http://xxx.lanl.gov/archive/cs/intro.html" target="_top">Computing Research Repository (CoRR)</a>
</li> <li> <a href="https://web.archive.org/web/20160426010223/http://www.dcs.qmw.ac.uk/SEL-HPC/Articles/" target="_top">SEL-HPC</a> is inactive, but still occasionally useful.
</li> <li> Indiana's <a href="https://web.archive.org/web/20160426010223/http://www.cs.indiana.edu:800/cstr/search" target="_top">Unified Computer Science TR Index (UCSTRI)</a>
</li> <li> Cornell's <a href="https://web.archive.org/web/20160426010223/http://cs-tr.cs.cornell.edu/" target="_top">Networked Computer Science Technical Reference Library (NCSTRL)</a>
</li> <li> <a href="https://web.archive.org/web/20160426010223/http://liinwww.ira.uka.de/bibliography/index.html" target="_top">The Collection of Computer Science Bibliographies</a>
</li> <li> CMU's <a href="https://web.archive.org/web/20160426010223/http://www.cs.cmu.edu/afs/cs.cmu.edu/user/jblythe/Mosaic/cs-reports.html" target="_top">On-line CS Techreports</a>
</li> <li> <a href="https://web.archive.org/web/20160426010223/http://cora.whizbang.com/" target="_top">Cora Research Paper Search</a>
</li> <li> <a href="https://web.archive.org/web/20160426010223/http://www.coalgebra.net/" target="_top">Coalgebra network online library</a>
</li> <li> Paderborn's <a href="https://web.archive.org/web/20160426010223/http://www.uni-paderborn.de/fachbereich/AG/agmadh/WWW/english/scripts.html" target="_top">Collection of Lecture Notes, Surveys and Papers</a>
</li> <li> <a href="https://web.archive.org/web/20160426010223/http://www.md.chalmers.se/~rjmh" target="_top">John Hughes</a>' <a href="https://web.archive.org/web/20160426010223/http://www.md.chalmers.se/~rjmh/tutorials.html" target="_top">tutorial papers in functional programming</a>
</li> <li> <a href="https://web.archive.org/web/20160426010223/http://www.google.com/" target="_top">Google</a> is a good search engine for technical topics.
</li> <li> <a href="https://web.archive.org/web/20160426010223/http://lambda.weblogs.com/" target="_top">Lambda the Ultimate</a> is a weblog on programming languages. Amongst other things, it offers a list of <a href="https://web.archive.org/web/20160426010223/http://lambda.weblogs.com/design-docs" target="_top">language design</a> documents and <a href="https://web.archive.org/web/20160426010223/http://lambda.weblogs.com/papers" target="_top">research papers</a>.
</li> <li> <a href="https://web.archive.org/web/20160426010223/http://lsi.uniovi.es/~labra/APL.html" target="_top">Advanced Programming Languages</a> (<a href="https://web.archive.org/web/20160426010223/http://lsi.uniovi.es/~labra" target="_top">Jose Emilio Labra Gayo</a>)
</li> <li> a list of <a href="/web/20160426010223/http://foswiki.cs.uu.nl/foswiki/bin/view/Techno/ProgrammingLanguages">ProgrammingLanguages</a> on this server
</li> <li> <a href="https://web.archive.org/web/20160426010223/http://hypatia.dcs.qmw.ac.uk/" target="_top">Hypatia</a> (broken)
</li> <li> <a href="https://web.archive.org/web/20160426010223/http://readscheme.org/" target="_top">readscheme.org</a>
</li></ul> 
<p></p>
<a name="SubmissionGuidelines"></a>
<h1><a name="Submission_guidelines"></a>  Submission guidelines </h1>
<p></p>
Most importantly, any submission must include a URL to the full text of the
manuscript: this is not an 
<em>online list of texts</em>,
but rather
<em>a list of online texts</em>.
Also, the text should be freely accessible; so, texts which belong to
some sort of private digital library (like the ACM Digital Library or
Elsevier's collection) are not admissible.
<p></p>
This list focuses on book-length reference works which treat major topics
in programming language theory, mathematical semantics and foundations,
particularly texts which have gone out of print. It would be nice if we could
assemble a set of texts which are representative of a master's degree
curriculum in programming language theory or computational mathematics.
<p></p>
On the other hand, do not dismiss interesting-looking material only
because it is too short, or because it does not treat a central topic, or
because it is too specific. If you know of something valuable which does not
quite fit the guidelines above, consider putting it in the
<a href="#OtherTexts" class="foswikiCurrentTopicLink">#OtherTexts</a> category.
<p></p>
Dissertations, theses and technical articles are not really suitable for this
list, unless they provide an accessible (or: the unique) introduction to, or
tutorial for, a relatively broad and/or important topic. Conversely, a survey
would need to treat its topic in considerable depth to be included here.
<p></p>
Lecture notes and tutorials are acceptable, provided they are readable as
self-contained manuscripts. Because there are so many manuscripts here of this
type, please try to submit material which minimizes overlap with existing
entries.
<p></p>
<h1><a name="Administration"></a>  Administration </h1>
<p></p>
This Wiki page is adapted from my (<a class="foswikiNewLink" href="/web/20160426010223/http://foswiki.cs.uu.nl/foswiki/bin/edit/Main/FrankAtanassow?topicparent=Techno.ProgrammingLanguageTheoryTextsOnline" rel="nofollow" title="Create this topic">FrankAtanassow</a>'s)
<a href="https://web.archive.org/web/20160426010223/http://www.cs.uu.nl/~franka/ref" target="_top">PLT Online</a> page.
<p></p>
For now, both versions will coexist
and I will probably add any updates to this page to my own page as well, and vice versa.
If this Wiki version sees a lot of activity and takes off, and does not evolve too far
from my original purpose (outlined in the
<a href="#SubmissionGuidelines" class="foswikiCurrentTopicLink">#SubmissionGuidelines</a> above),
then I may trash my page and redirect page views to this Wiki.
<p></p>
-- <a class="foswikiNewLink" href="/web/20160426010223/http://foswiki.cs.uu.nl/foswiki/bin/edit/Main/FrankAtanassow?topicparent=Techno.ProgrammingLanguageTheoryTextsOnline" rel="nofollow" title="Create this topic">FrankAtanassow</a> - 23 Sep 2002 </div>
