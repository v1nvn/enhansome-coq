# Awesome Coq [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

[<img src="coq-logo.svg" align="right" width="100" alt="coq-community logo" title="Awesome Coq is a coq-community project">](https://github.com/coq-community/manifesto) ⭐ 68 | 🐛 37 | 📅 2025-03-31

> A curated list of awesome Coq libraries, plugins, tools, and resources.

The [Coq proof assistant](https://coq.inria.fr) provides a formal language to write mathematical definitions, executable algorithms, and theorems, together with an environment for semi-interactive development of machine-checked proofs.

Contributions welcome! Read the [contribution guidelines](https://github.com/coq-community/awesome-coq/blob/master/CONTRIBUTING.md) ⭐ 375 | 🐛 8 | 📅 2025-11-05 first.

## Contents

* [Projects](#projects)
  * [Frameworks](#frameworks)
  * [User Interfaces](#user-interfaces)
  * [Libraries](#libraries)
  * [Package and Build Management](#package-and-build-management)
  * [Plugins](#plugins)
  * [Puzzles and Games](#puzzles-and-games)
  * [Tools](#tools)
  * [Type Theory and Mathematics](#type-theory-and-mathematics)
  * [Verified Software](#verified-software)
* [Resources](#resources)
  * [Community](#community)
  * [Blogs](#blogs)
  * [Books](#books)
  * [Course Material](#course-material)
  * [Tutorials and Hints](#tutorials-and-hints)

***

## Projects

### Frameworks

* [Verdi](https://github.com/uwplse/verdi) ⭐ 618 | 🐛 5 | 🌐 Rocq Prover | 📅 2026-01-27 - Framework for formally verifying distributed systems implementations.
* [Fiat](https://github.com/mit-plv/fiat) ⭐ 157 | 🐛 2 | 🌐 Rocq Prover | 📅 2026-01-27 - Mostly automated synthesis of correct-by-construction programs.
* [ConCert](https://github.com/AU-COBRA/ConCert) ⭐ 124 | 🐛 5 | 🌐 Rocq Prover | 📅 2026-01-25 - Framework for smart contract testing and verification featuring a code extraction pipeline to several smart contract languages.
* [Hoare Type Theory](https://github.com/imdea-software/htt/) ⭐ 84 | 🐛 0 | 🌐 Rocq Prover | 📅 2025-06-12 - A shallow embedding of sequential separation logic formulated as a type theory.
* [CoqEAL](https://github.com/CoqEAL/CoqEAL) ⭐ 74 | 🐛 8 | 🌐 Rocq Prover | 📅 2026-01-20 - Framework to ease change of data representations in proofs.
* [SSProve](https://github.com/SSProve/ssprove) ⭐ 73 | 🐛 14 | 🌐 Rocq Prover | 📅 2026-02-05 - Framework for modular cryptographic proofs based on the Mathematical Components library.
* [Q\*cert](https://github.com/querycert/qcert) ⭐ 57 | 🐛 32 | 🌐 Coq | 📅 2024-07-17 - Platform for implementing and verifying query compilers.
* [FCF](https://github.com/adampetcher/fcf) ⭐ 55 | 🐛 7 | 🌐 Rocq Prover | 📅 2025-10-02 - Framework for proofs of cryptography.
* [FreeSpec](https://github.com/lthms/FreeSpec) ⭐ 53 | 🐛 7 | 🌐 Coq | 📅 2024-01-16 - Framework for modularly verifying programs with effects and effect handlers.
* [VCFloat](https://github.com/VeriNum/vcfloat) ⭐ 32 | 🐛 6 | 🌐 Rocq Prover | 📅 2026-01-09 - Framework for verifying C programs with floating-point computations.
* [Hybrid](https://www.site.uottawa.ca/~afelty/HybridCoq/) - System for reasoning using higher-order abstract syntax representations of object logics.
* [Iris](https://iris-project.org) - Higher-order concurrent separation logic framework.
* [VST](https://vst.cs.princeton.edu) - Toolchain for verifying C code inside Coq in a higher-order concurrent, impredicative separation logic that is sound w\.r.t. the Clight language of the CompCert compiler.

### User Interfaces

* [jsCoq](https://github.com/jscoq/jscoq) ⭐ 537 | 🐛 80 | 🌐 TypeScript | 📅 2026-01-21 - Port of Coq to JavaScript, which enables running Coq projects in a browser.
* [VsCoq](https://github.com/coq-community/vscoq) ⭐ 432 | 🐛 180 | 🌐 OCaml | 📅 2025-12-10 - Language server and extension for the Visual Studio Code and VSCodium editors.
* [VsCoq Legacy](https://github.com/coq-community/vscoq/tree/vscoq1) ⭐ 432 | 🐛 180 | 🌐 OCaml | 📅 2025-12-10 - Backwards-compatible extension for the Visual Studio Code and VSCodium editors using Coq's legacy XML protocol.
* [Company-Coq](https://github.com/cpitclaudel/company-coq) ⭐ 359 | 🐛 104 | 🌐 Emacs Lisp | 📅 2025-08-17 - IDE extensions for Proof General's Coq mode.
* [Coqtail](https://github.com/whonore/Coqtail) ⭐ 314 | 🐛 39 | 🌐 Python | 📅 2026-02-07 - Interface for Coq based on the Vim text editor.
* [Coq LSP](https://github.com/ejgallego/coq-lsp) ⭐ 197 | 🐛 142 | 🌐 OCaml | 📅 2026-02-04 - Language server and extension for the Visual Studio Code and VSCodium editors with custom document checking engine.
* [Jupyter kernel for Coq](https://github.com/EugeneLoy/coq_jupyter) ⭐ 95 | 🐛 15 | 🌐 Python | 📅 2024-09-03 - Coq support for the Jupyter Notebook web environment.
* [Waterproof editor](https://github.com/impermeable/waterproof) ⭐ 44 | 🐛 32 | 🌐 JavaScript | 📅 2024-03-19 - Educational environment for writing mathematical proofs in interactive notebooks.
* [opam-switch-mode](https://github.com/ProofGeneral/opam-switch-mode) ⭐ 9 | 🐛 1 | 🌐 Emacs Lisp | 📅 2023-08-02 - IDE extension for Proof General to locally change or reset the opam switch from a menu or using a command.
* [Tree Sitter Rocq](https://github.com/lamg/tree-sitter-rocq) ⭐ 3 | 🐛 0 | 🌐 Rocq Prover | 📅 2025-08-17 - Partial Rocq tree-sitter grammar useful for syntax highlighting in text editors like [Helix](https://github.com/helix-editor/helix) ⭐ 42,871 | 🐛 1,436 | 🌐 Rust | 📅 2026-02-10, but not recommended for full parsing of Rocq code.
* [CoqIDE](https://coq.inria.fr/refman/practical-tools/coqide.html) - Standalone graphical tool for interacting with Coq.
* [Proof General](https://proofgeneral.github.io) - Generic interface for proof assistants based on the extensible, customizable text editor Emacs.

### Libraries

* [Interaction Trees](https://github.com/DeepSpec/InteractionTrees) ⭐ 242 | 🐛 31 | 🌐 Rocq Prover | 📅 2026-01-22 - Library for representing recursive and impure programs.
* [coq-haskell](https://github.com/jwiegley/coq-haskell) ⭐ 171 | 🐛 2 | 🌐 Coq | 📅 2023-10-15 - Library smoothing the transition to Coq for Haskell users.
* [ExtLib](https://github.com/coq-community/coq-ext-lib) ⭐ 137 | 🐛 21 | 🌐 Rocq Prover | 📅 2025-10-02 - Collection of theories and plugins that may be useful in other Coq developments.
* [Formalised Undecidable Problems](https://github.com/uds-psl/coq-library-undecidability) ⭐ 130 | 🐛 17 | 🌐 Coq | 📅 2026-01-02 - Library of undecidable problems and reductions between them.
* [Metalib](https://github.com/plclub/metalib) ⭐ 75 | 🐛 3 | 🌐 Coq | 📅 2025-03-26 - Library for programming language metatheory using locally nameless variable binding representations.
* [Relation Algebra](https://github.com/damien-pous/relation-algebra) ⭐ 50 | 🐛 2 | 🌐 Rocq Prover | 📅 2026-01-27 - Modular formalization of algebras with heterogeneous binary relations as models.
* [Coq record update](https://github.com/tchajed/coq-record-update) ⭐ 48 | 🐛 7 | 🌐 Rocq Prover | 📅 2025-11-25 - Library which provides a generic way to update Coq record fields.
* [Regular Language Representations](https://github.com/coq-community/reglang) ⭐ 47 | 🐛 1 | 🌐 Coq | 📅 2025-04-23 - Translations between different definitions of regular languages, including regular expressions and automata.
* [TLC](https://github.com/charguer/tlc) ⭐ 40 | 🐛 0 | 🌐 Rocq Prover | 📅 2026-01-20 - Non-constructive alternative to Coq's standard library.
* [Algebra Tactics](https://github.com/math-comp/algebra-tactics) ⭐ 38 | 🐛 14 | 🌐 Rocq Prover | 📅 2025-09-15 - Ring and field tactics for Mathematical Components.
* [CoLoR](https://github.com/fblanqui/color) ⭐ 37 | 🐛 0 | 🌐 Rocq Prover | 📅 2026-01-27 - Library on rewriting theory, lambda-calculus and termination, with sub-libraries on common data structures extending the Coq standard library.
* [Simple IO](https://github.com/Lysxia/coq-simple-io) ⭐ 33 | 🐛 4 | 🌐 Rocq Prover | 📅 2025-12-17 - Input/output monad with user-definable primitive operations.
* [FCSL-PCM](https://github.com/imdea-software/fcsl-pcm) ⭐ 32 | 🐛 0 | 🌐 Rocq Prover | 📅 2025-06-09 - Formalization of partial commutative monoids as used in verification of pointer-manipulating programs.
* [Hahn](https://github.com/vafeiadis/hahn) ⭐ 29 | 🐛 7 | 🌐 Coq | 📅 2024-06-25 - Library for reasoning on lists and binary relations.
* [Bedrock Bit Vectors](https://github.com/mit-plv/bbv) ⭐ 28 | 🐛 7 | 🌐 Rocq Prover | 📅 2025-10-28 - Library for reasoning on fixed precision machine words.
* [Mczify](https://github.com/math-comp/mczify) ⭐ 28 | 🐛 5 | 🌐 Rocq Prover | 📅 2025-12-09 - Library enabling Micromega arithmetic solvers to work when using Mathematical Components number definitions.
* [ALEA](https://github.com/coq-community/alea) ⭐ 25 | 🐛 2 | 🌐 Coq | 📅 2021-11-03 - Library for reasoning on randomized algorithms.
* [Bignums](https://github.com/coq/bignums) ⭐ 25 | 🐛 2 | 🌐 Rocq Prover | 📅 2026-02-10 - Library of arbitrarily large numbers.
* [LibHyps](https://github.com/Matafou/LibHyps) ⭐ 22 | 🐛 1 | 🌐 Rocq Prover | 📅 2025-12-05 - Library of Ltac tactics to manage and manipulate hypotheses in proofs.
* [CertiGraph](https://github.com/Salamari/CertiGraph) ⭐ 18 | 🐛 5 | 🌐 Coq | 📅 2025-08-21 - Library for reasoning about directed graphs and their embedding in separation logic.
* [MathComp Extra](https://github.com/thery/mathcomp-extra) ⭐ 5 | 🐛 1 | 🌐 Rocq Prover | 📅 2026-01-28 - Extra material for the Mathematical Components library, including the AKS primality test and RSA encryption and decryption.
* [Coq-Kruskal](https://github.com/DmxLarchey/Coq-Kruskal) ⭐ 0 | 🐛 0 | 📅 2024-12-06 - Collection of libraries related to rose trees and Kruskal's tree theorem.
* [CoqInterval](https://gitlab.inria.fr/coqinterval/interval/) - Tactics for performing proofs of inequalities on expressions of real numbers.
* [Coq-std++](https://gitlab.mpi-sws.org/iris/stdpp) - Extended alternative standard library for Coq.
* [Flocq](https://gitlab.inria.fr/flocq/flocq) - Formalization of floating-point numbers and computations.
* [Paco](http://plv.mpi-sws.org/paco/) - Library for parameterized coinduction.

### Package and Build Management

* [Coq Platform](https://github.com/coq/platform) ⭐ 225 | 🐛 63 | 🌐 Shell | 📅 2026-02-05 - Curated collection of packages to support Coq use in industry, education, and research.
* [Coq Nix Toolbox](https://github.com/coq-community/coq-nix-toolbox) ⭐ 50 | 🐛 39 | 🌐 Nix | 📅 2026-02-10 - Nix helper scripts to automate local builds and continuous integration for Coq.
* [Docker-Coq](https://github.com/coq-community/docker-coq) ⭐ 39 | 🐛 6 | 🌐 Shell | 📅 2025-05-13 - Docker images for many versions of Coq.
* [coq-community Templates](https://github.com/coq-community/templates) ⭐ 16 | 🐛 27 | 🌐 Mustache | 📅 2025-10-30 - Templates for generating configuration files for Coq projects.
* [Docker-MathComp](https://github.com/math-comp/docker-mathcomp) ⭐ 6 | 🐛 5 | 🌐 Dockerfile | 📅 2025-11-24 - Docker images for many combinations of versions of Coq and the Mathematical Components library.
* [coq\_makefile](https://coq.inria.fr/refman/practical-tools/utilities.html) - Build tool distributed with Coq and based on generating a makefile.
* [Coq Package Index](https://coq.inria.fr/opam/www/) - Collection of Coq packages based on opam.
* [Debian Coq packages](https://people.debian.org/~jpuydt/coq_platform.html) - Coq-related packages available in the testing distribution of Debian.
* [Docker-Coq GitHub Action](https://github.com/marketplace/actions/docker-coq-action) - GitHub container action that can be used with Docker-Coq or Docker-MathComp.
* [Dune](https://dune.build) - Composable and opinionated build system for OCaml and Coq (former jbuilder).
* [Nix](https://nixos.org/nix/) - Package manager for Linux and other Unix systems, supporting atomic upgrades and rollbacks.
* [Nix Coq packages](https://search.nixos.org/packages?channel=unstable\&query=coqPackages) - Collection of Coq-related packages for Nix.
* [opam](https://opam.ocaml.org) - Flexible and Git-friendly package manager for OCaml and Coq with multiple compiler support.

### Plugins

* [MetaCoq](https://github.com/MetaCoq/metacoq) ⭐ 503 | 🐛 95 | 🌐 Rocq Prover | 📅 2026-02-06 - Project formalizing Coq in Coq and providing tools for manipulating Coq terms and developing certified plugins.
* [QuickChick](https://github.com/QuickChick/QuickChick) ⭐ 281 | 🐛 95 | 🌐 Rocq Prover | 📅 2026-01-27 - Plugin for randomized property-based testing.
* [CoqHammer](https://github.com/lukaszcz/coqhammer) ⭐ 237 | 🐛 23 | 🌐 OCaml | 📅 2025-12-02 - General-purpose automated reasoning hammer tool that combines learning from previous proofs with the translation of problems to automated provers and the reconstruction of found proofs.
* [Equations](https://github.com/mattam82/Coq-Equations) ⭐ 236 | 🐛 92 | 🌐 Coq | 📅 2026-02-05 - Function definition package for Coq.
* [Coq-Elpi](https://github.com/LPCIC/coq-elpi) ⭐ 182 | 🐛 113 | 🌐 Rocq Prover | 📅 2026-02-09 - Extension framework based on λProlog providing an extensive API to implement commands and tactics.
* [SMTCoq](https://github.com/smtcoq/smtcoq) ⭐ 164 | 🐛 43 | 🌐 OCaml | 📅 2026-02-04 - Tool that checks proof witnesses coming from external SAT and SMT solvers.
* [Hierarchy Builder](https://github.com/math-comp/hierarchy-builder) ⭐ 104 | 🐛 112 | 🌐 Rocq Prover | 📅 2026-01-28 - Collection of commands for declaring Coq hierarchies based on packed classes.
* [Unicoq](https://github.com/unicoq/unicoq) ⭐ 58 | 🐛 10 | 🌐 OCaml | 📅 2026-01-30 - Plugin that replaces the existing unification algorithm with an enhanced one.
* [Mtac2](https://github.com/Mtac2/Mtac2) ⭐ 56 | 🐛 71 | 🌐 Rocq Prover | 📅 2026-02-02 - Plugin adding typed tactics for backward reasoning.
* [Waterproof proof language](https://github.com/impermeable/coq-waterproof) ⭐ 49 | 🐛 26 | 🌐 Rocq Prover | 📅 2026-02-04 - Plugin providing a language for writing proof scripts in a style that resembles non-mechanized mathematical proof.
* [Paramcoq](https://github.com/coq-community/paramcoq) ⭐ 44 | 🐛 9 | 🌐 Rocq Prover | 📅 2026-01-08 - Plugin to generate parametricity translations of Coq terms.
* [AAC Tactics](https://github.com/coq-community/aac-tactics) ⭐ 36 | 🐛 7 | 🌐 OCaml | 📅 2025-10-28 - Tactics for rewriting universally quantified equations, modulo associativity and commutativity of some operator.
* [Coinduction](https://github.com/damien-pous/coinduction) ⭐ 24 | 🐛 3 | 🌐 Rocq Prover | 📅 2025-11-14 - Plugin for doing proofs by enhanced coinduction.
* [Gappa](https://gitlab.inria.fr/gappa/coq) - Tactic for discharging goals about floating-point arithmetic and round-off errors.
* [Itauto](https://gitlab.inria.fr/fbesson/itauto) - SMT-like tactics for combined propositional reasoning about function symbols, constructors, and arithmetic.
* [Ltac2](https://coq.inria.fr/refman/proof-engine/ltac2.html) - Experimental typed tactic language similar to Coq's classic Ltac language.
* [Tactician](https://coq-tactician.github.io) - Interactive tool which learns from previously written tactic scripts across all the installed Coq packages and suggests the next tactic to be executed or tries to automate proof synthesis fully.

### Puzzles and Games

* [Name the Biggest Number](https://github.com/codyroux/name-the-biggest-number) ⭐ 64 | 🐛 0 | 🌐 Coq | 📅 2022-09-13 - Repository for submitting proven contenders for the title of biggest number in Coq.
* [Hanoi](https://github.com/thery/hanoi) ⭐ 26 | 🐛 0 | 🌐 Rocq Prover | 📅 2026-01-29 - The Tower of Hanoi puzzle in Coq, including generalizations and theorems about configurations.
* [Coqoban](https://github.com/coq-community/coqoban) ⭐ 24 | 🐛 1 | 🌐 Coq | 📅 2025-01-03 - Coq implementation of Sokoban, the Japanese warehouse keepers' game.
* [T2048](https://github.com/thery/T2048) ⭐ 22 | 🐛 0 | 🌐 Rocq Prover | 📅 2026-01-30 - Coq version of the 2048 sliding tile game.
* [Sudoku](https://github.com/coq-community/sudoku) ⭐ 19 | 🐛 0 | 🌐 Coq | 📅 2022-11-14 - Formalization and solver of the Sudoku number-placement puzzle in Coq.
* [Natural Number Game](https://github.com/uncomputable/natural-number-game) ⭐ 6 | 🐛 0 | 🌐 Coq | 📅 2022-11-10 - Coq version of the natural number game developed for the Lean prover.
* [Mini-Rubik](https://github.com/thery/minirubik) ⭐ 5 | 🐛 0 | 🌐 Rocq Prover | 📅 2026-01-29 - Coq formalization and solver of the 2x2x2 version of the Rubik's Cube puzzle.

### Tools

* [Sail](https://github.com/rems-project/sail) ⭐ 841 | 🐛 286 | 🌐 Sail | 📅 2026-02-10 - Tool for specifying instruction set architecture (ISA) semantics of processors and generating Coq definitions.
* [Cosette](https://github.com/uwdb/Cosette) ⭐ 684 | 🐛 28 | 🌐 Lean | 📅 2024-12-18 - Automated solver for reasoning about SQL query equivalences.
* [Ott](https://github.com/ott-lang/ott) ⭐ 401 | 🐛 37 | 🌐 OCaml | 📅 2026-01-15 - Tool for writing definitions of programming languages and calculi that can be translated to Coq.
* [Alectryon](https://github.com/cpitclaudel/alectryon) ⭐ 285 | 🐛 39 | 🌐 HTML | 📅 2025-09-15 - Collection of tools for writing technical documents that mix Coq code and prose.
* [CoqOfOCaml](https://github.com/clarus/coq-of-ocaml) ⭐ 271 | 🐛 18 | 🌐 OCaml | 📅 2024-08-05 - Tool for generating idiomatic Coq from OCaml code.
* [SerAPI](https://github.com/ejgallego/coq-serapi) ⭐ 137 | 🐛 2 | 🌐 Coq | 📅 2025-11-27 - Tools and OCaml library for (de)serialization of Coq code to and from JSON and S-expressions.
* [coq-dpdgraph](https://github.com/coq-community/coq-dpdgraph) ⭐ 97 | 🐛 24 | 🌐 OCaml | 📅 2026-02-09 - Tool for building dependency graphs between Coq objects.
* [hs-to-coq](https://github.com/plclub/hs-to-coq) ⭐ 93 | 🐛 59 | 🌐 Coq | 📅 2025-06-24 - Converter from Haskell code to equivalent Coq code.
* [PyCoq](https://github.com/ejgallego/pycoq) ⭐ 57 | 🐛 25 | 🌐 OCaml | 📅 2022-01-10 - Set of bindings and libraries for interacting with Coq from inside Python 3.
* [coq-tools](https://github.com/JasonGross/coq-tools) ⭐ 44 | 🐛 52 | 🌐 Python | 📅 2025-12-17 - Scripts for manipulating Coq developments.
  * [`find-bug.py`](https://github.com/JasonGross/coq-tools/blob/master/find-bug.py) ⭐ 44 | 🐛 52 | 🌐 Python | 📅 2025-12-17 - Automatically minimizes source files producing an error, creating small test cases for Coq bugs.
  * [`absolutize-imports.py`](https://github.com/JasonGross/coq-tools/blob/master/absolutize-imports.py) ⭐ 44 | 🐛 52 | 🌐 Python | 📅 2025-12-17 - Processes source files to make loading of dependencies robust against shadowing of file names.
  * [`inline-imports.py`](https://github.com/JasonGross/coq-tools/blob/master/inline-imports.py) ⭐ 44 | 🐛 52 | 🌐 Python | 📅 2025-12-17 - Creates stand-alone source files from developments by inlining the loading of all dependencies.
  * [`minimize-requires.py`](https://github.com/JasonGross/coq-tools/blob/master/minimize-requires.py) ⭐ 44 | 🐛 52 | 🌐 Python | 📅 2025-12-17 - Removes loading of unused dependencies.
  * [`move-requires.py`](https://github.com/JasonGross/coq-tools/blob/master/move-requires.py) ⭐ 44 | 🐛 52 | 🌐 Python | 📅 2025-12-17 - Moves all dependency loading statements to the top of source files.
  * [`move-vernaculars.py`](https://github.com/JasonGross/coq-tools/blob/master/move-vernaculars.py) ⭐ 44 | 🐛 52 | 🌐 Python | 📅 2025-12-17 - Lifts many vernacular commands and inner lemmas out of proof script blocks.
  * [`proof-using-helper.py`](https://github.com/JasonGross/coq-tools/blob/master/proof-using-helper.py) ⭐ 44 | 🐛 52 | 🌐 Python | 📅 2025-12-17 - Modifies source files to include proof annotations for faster parallel proving.
* [lngen](https://github.com/plclub/lngen) ⭐ 32 | 🐛 0 | 🌐 Haskell | 📅 2024-10-22 - Tool for generating locally nameless Coq definitions and proofs.
* [coq2html](https://github.com/xavierleroy/coq2html) ⭐ 31 | 🐛 1 | 🌐 OCaml | 📅 2024-08-23 - Alternative HTML documentation generator for Coq.
* [mCoq](https://github.com/EngineeringSoftware/mcoq) ⭐ 29 | 🐛 4 | 🌐 Java | 📅 2020-10-13 - Mutation analysis tool for Coq projects.
* [Roosterize](https://github.com/EngineeringSoftware/roosterize) ⭐ 22 | 🐛 2 | 🌐 Python | 📅 2022-09-06 - Tool for suggesting lemma names in Coq projects.
* [Autosubst-ocaml](https://github.com/uds-psl/autosubst-ocaml) ⭐ 19 | 🐛 7 | 🌐 Coq | 📅 2025-11-24 - Tool that generates Coq code for handling binders in syntax, such as for renaming and substitutions.
* [Trakt](https://github.com/ecranceMERCE/trakt) ⭐ 15 | 🐛 6 | 🌐 Prolog | 📅 2026-02-10 - Generic goal preprocessing tool for proof automation tactics.
* [coq-scripts](https://github.com/JasonGross/coq-scripts) ⭐ 9 | 🐛 0 | 🌐 Coq | 📅 2025-03-04 - Scripts for dealing with Coq files, including tabulating proof times.
* [Rocqnavi](https://github.com/affeldt-aist/rocqnavi) ⭐ 3 | 🐛 15 | 🌐 HTML | 📅 2026-01-27 - Fork of coq2html that adds indexes, clickable notations, Markdown and LaTeX formatting in comments, and more.
* [CFML](https://gitlab.inria.fr/charguer/cfml2) - Tool for proving properties of OCaml programs in separation logic.
* [coqdoc](https://coq.inria.fr/refman/using/tools/coqdoc.html) - Standard documentation tool that generates LaTeX or HTML files from Coq code.
* [Menhir](http://gallium.inria.fr/~fpottier/menhir/) - Parser generator that can output Coq code for verified parsers.

### Type Theory and Mathematics

* [Homotopy Type Theory](https://github.com/HoTT/Coq-HoTT) ⭐ 1,369 | 🐛 142 | 🌐 Rocq Prover | 📅 2026-01-29 - Development of homotopy-theoretic ideas.
* [UniMath](https://github.com/UniMath/UniMath) ⭐ 1,001 | 🐛 152 | 🌐 Rocq Prover | 📅 2026-02-09 - Library which aims to formalize a substantial body of mathematics using the univalent point of view.
* [Category Theory in Coq](https://github.com/jwiegley/category-theory) ⭐ 792 | 🐛 7 | 🌐 Rocq Prover | 📅 2026-01-09 - Axiom-free formalization of category theory.
* [Analysis](https://github.com/math-comp/analysis) ⭐ 236 | 🐛 135 | 🌐 Rocq Prover | 📅 2026-02-09 - Library for classical real analysis compatible with Mathematical Components.
* [Four Color Theorem](https://github.com/coq-community/fourcolor) ⭐ 228 | 🐛 1 | 🌐 Rocq Prover | 📅 2025-10-14 - Formal proof of the Four Color Theorem, a landmark result of graph theory.
* [GeoCoq](https://github.com/GeoCoq/GeoCoq) ⭐ 205 | 🐛 6 | 🌐 Rocq Prover | 📅 2025-11-17 - Formalization of geometry based on Tarski's axiom system.
* [Math Classes](https://github.com/coq-community/math-classes) ⭐ 168 | 🐛 12 | 🌐 Rocq Prover | 📅 2026-01-09 - Abstract interfaces for mathematical structures based on type classes.
* [CoRN](https://github.com/coq-community/corn) ⭐ 115 | 🐛 8 | 🌐 Rocq Prover | 📅 2026-01-09 - Library of constructive real analysis and algebra.
* [Infotheo](https://github.com/affeldt-aist/infotheo) ⭐ 74 | 🐛 21 | 🌐 Rocq Prover | 📅 2026-01-23 - Formalization of information theory and linear error-correcting codes.
* [Monae](https://github.com/affeldt-aist/monae) ⭐ 74 | 🐛 20 | 🌐 Rocq Prover | 📅 2025-12-19 - Monadic effects and equational reasoning.
* [Finmap](https://github.com/math-comp/finmap) ⭐ 51 | 🐛 18 | 🌐 Rocq Prover | 📅 2025-11-05 - Extension of Mathematical Components with finite maps, sets, and multisets.
* [CoqPrime](https://github.com/thery/coqprime) ⭐ 43 | 🐛 1 | 🌐 Rocq Prover | 📅 2026-01-28 - Library for certifying primality using Pocklington and Elliptic Curve certificates.
* [Graph Theory](https://github.com/coq-community/graph-theory) ⭐ 41 | 🐛 3 | 🌐 Rocq Prover | 📅 2025-10-30 - Formalized graph theory results.
* [Odd Order Theorem](https://github.com/math-comp/odd-order) ⭐ 37 | 🐛 3 | 🌐 Rocq Prover | 📅 2025-11-05 - Formal proof of the Odd Order Theorem, a landmark result of finite group theory.
* [Gaia](https://github.com/coq-community/gaia) ⭐ 31 | 🐛 1 | 🌐 Rocq Prover | 📅 2025-06-27 - Implementation of books from Bourbaki's Elements of Mathematics, including set theory and number theory.
* [Coqtail Math](https://github.com/coq-community/coqtail-math) ⭐ 16 | 🐛 0 | 🌐 Rocq Prover | 📅 2025-10-20 - Library of mathematical results ranging from arithmetic to real and complex analysis.
* [Completeness and Decidability of Modal Logic Calculi](https://github.com/coq-community/comp-dec-modal) ⭐ 12 | 🐛 1 | 🌐 Coq | 📅 2024-08-11 - Soundness, completeness, and decidability for the logics K, K\*, CTL, and PDL.
* [Puiseuxth](https://github.com/roglo/puiseuxth) ⭐ 4 | 🐛 0 | 🌐 Rocq Prover | 📅 2026-02-08 - Proof of Puiseux's theorem and computation of roots of polynomials of Puiseux's series.
* [Coquelicot](https://gitlab.inria.fr/coquelicot/coquelicot) - Formalization of classical real analysis compatible with the standard library and focusing on usability.
* [Mathematical Components](http://math-comp.github.io) - Formalization of mathematical theories, focusing in particular on group theory.

### Verified Software

* [Fiat-Crypto](https://github.com/mit-plv/fiat-crypto) ⭐ 805 | 🐛 172 | 🌐 Rocq Prover | 📅 2026-02-07 - Cryptographic primitive code generation.
* [Jasmin](https://github.com/jasmin-lang/jasmin) ⭐ 329 | 🐛 131 | 🌐 Rocq Prover | 📅 2026-02-10 - Formalized language and verified compiler for high-assurance and high-speed cryptography.
* [JSCert](https://github.com/jscert/jscert) ⭐ 205 | 🐛 8 | 🌐 Coq | 📅 2024-02-05 - Coq specification of ECMAScript 5 (JavaScript) with verified reference interpreter.
* [Verdi Raft](https://github.com/uwplse/verdi-raft) ⭐ 194 | 🐛 15 | 🌐 Coq | 📅 2023-12-08 - Implementation of the Raft distributed consensus protocol, verified in Coq using the Verdi framework.
* [CertiCoq](https://github.com/CertiCoq/certicoq) ⭐ 158 | 🐛 22 | 🌐 Rocq Prover | 📅 2026-02-09 - Verified compiler from Gallina, the internal language of Coq, down to CompCert's Clight language.
* [Ceramist](https://github.com/certichain/ceramist) ⭐ 124 | 🐛 0 | 🌐 Coq | 📅 2020-04-13 - Verified hash-based approximate membership structures such as Bloom filters.
* [RISC-V Specification in Coq](https://github.com/mit-plv/riscv-coq) ⭐ 116 | 🐛 7 | 🌐 Rocq Prover | 📅 2026-01-05 - Definition of the RISC-V processor instruction set architecture and extensions.
* [WasmCert-Coq](https://github.com/WasmCert/WasmCert-Coq/) ⭐ 114 | 🐛 4 | 🌐 Rocq Prover | 📅 2026-02-09 - Formalization in Coq of the WebAssembly (aka Wasm) 1.0 specification.
* [Functional Algorithms Verified in SSReflect](https://github.com/clayrat/fav-ssr) ⭐ 50 | 🐛 15 | 🌐 Rocq Prover | 📅 2025-10-08 - Purely functional verified implementations of algorithms for searching, sorting, and other fundamental problems.
* [Stable sort algorithms in Coq](https://github.com/pi8027/stablesort) ⭐ 25 | 🐛 2 | 🌐 Rocq Prover | 📅 2025-12-10 - Generic and modular proofs of correctness, including stability, of mergesort functions.
* [Tarjan and Kosaraju](https://github.com/math-comp/tarjan) ⭐ 18 | 🐛 0 | 🌐 Rocq Prover | 📅 2025-10-14 - Verified implementations of algorithms for topological sorting and finding strongly connected components in finite graphs.
* [CompCert](http://compcert.inria.fr) - High-assurance compiler for almost all of the C language (ISO C99), generating efficient code for the PowerPC, ARM, RISC-V and x86 processors.
* [Incremental Cycles](https://gitlab.inria.fr/agueneau/incremental-cycles) - Verified OCaml implementation of an algorithm for incremental cycle detection in graphs.
* [lambda-rust](https://gitlab.mpi-sws.org/iris/lambda-rust) - Formal model of a Rust core language and type system, a logical relation for the type system, and safety proofs for some Rust libraries.
* [Prosa](https://gitlab.mpi-sws.org/RT-PROOFS/rt-proofs) - Definitions and proofs for real-time system schedulability analysis.
* [Vélus](http://velus.inria.fr) - Verified compiler for a Lustre/Scade-like dataflow synchronous language.

## Resources

### Community

* [Official Coq wiki](https://github.com/coq/coq/wiki) ⭐ 5,350 | 🐛 2,537 | 🌐 OCaml | 📅 2026-02-10
* [Mathematical Components wiki](https://github.com/math-comp/math-comp/wiki) ⭐ 668 | 🐛 160 | 🌐 Rocq Prover | 📅 2026-02-04
* [Coq-community package maintenance project](https://github.com/coq-community/manifesto) ⭐ 68 | 🐛 37 | 📅 2025-03-31
* [100 famous theorems proved using Coq](https://github.com/coq-community/coq-100-theorems) ⭐ 61 | 🐛 4 | 🌐 HTML | 📅 2025-11-26
* [Official Coq website](https://coq.inria.fr)
* [Official Coq manual](https://coq.inria.fr/refman/)
* [Official Coq standard library](https://coq.inria.fr/stdlib/)
* [Official Coq Discourse forum](https://coq.discourse.group)
* [Official Coq Zulip chat](https://coq.zulipchat.com)
* [Official Coq-Club mailing list](https://sympa.inria.fr/sympa/arc/coq-club)
* [Official Coq X/Twitter](https://x.com/CoqLang)
* [Coq Zulip chat archive](https://coq.gitlab.io/zulip-archive/)
* [Coq subreddit](https://www.reddit.com/r/Coq/)
* [Coq tag on Stack Overflow](https://stackoverflow.com/questions/tagged/coq)
* [Coq tag on Theoretical Computer Science Stack Exchange](https://cstheory.stackexchange.com/questions/tagged/coq)
* [Coq tag on Proof Assistants Stack Exchange](https://proofassistants.stackexchange.com/questions/tagged/coq)
* [Coq keyword on Zenodo](https://zenodo.org/search?q=keywords%3A%22Coq%22)
* [Planet Coq link aggregator](https://coq.pl-a.net)

### Blogs

* [Coq Exchange: ideas and experiment reports about Coq](https://project.inria.fr/coqexchange/news/)
* [Gagallium](http://gallium.inria.fr/blog)
* [Gregory Malecha's blog](https://gmalecha.github.io)
* [Joachim Breitner's blog posts on Coq](http://www.joachim-breitner.de/blog/tag/Coq)
* [Lysxia's blog](https://blog.poisson.chat)
* [MIT PLV blog posts on Coq](http://plv.csail.mit.edu/blog/category/coq.html)
* [PLClub Blog](https://www.seas.upenn.edu/~plclub/blog/)
* [Poleiro: a Coq blog by Arthur Azevedo de Amorim](http://poleiro.info)
* [Ralf Jung's blog posts on Coq](https://www.ralfj.de/blog/categories/coq.html)
* [Thomas Letan's blog posts on Coq](https://soap.coffee/~lthms/tags/coq.html)

### Books

* [Modeling and Proving in Computational Type Theory](https://github.com/uds-psl/MPCTT) ⭐ 120 | 🐛 0 | 🌐 Rocq Prover | 📅 2025-08-06 - Book covering topics in computational logic using Coq, including foundations, canonical case studies, and practical programming.
* [Hydras & Co.](https://github.com/coq-community/hydra-battles) ⭐ 81 | 🐛 12 | 🌐 Coq | 📅 2025-01-22 - Continuously in-progress book and library on Kirby and Paris' hydra battles and other entertaining formalized mathematics in Coq, including a proof of the Gödel-Rosser first incompleteness theorem.
* [Coq'Art](https://www.labri.fr/perso/casteran/CoqArt/) - The first book dedicated to Coq.
* [Software Foundations](https://softwarefoundations.cis.upenn.edu) - Series of Coq-based textbooks on logic, functional programming, and foundations of programming languages, aimed at being accessible to beginners.
  * [Volume 1: Logical Foundations](https://softwarefoundations.cis.upenn.edu/lf-current/index.html) - Introduction to functional programming, basic concepts of logic, and computer-assisted theorem proving.
  * [Volume 2: Programming Language Foundations](https://softwarefoundations.cis.upenn.edu/plf-current/index.html) - Introduction to the theory of programming languages, including operational semantics, Hoare logic, and static type systems.
  * [Volume 3: Verified Functional Algorithms](https://softwarefoundations.cis.upenn.edu/vfa-current/index.html) - Demonstration of how a variety of fundamental data structures can be specified and verified.
  * [Volume 4: QuickChick](https://softwarefoundations.cis.upenn.edu/qc-current/index.html) - Introduction to tools for combining randomized property-based testing with formal specification and proof.
  * [Volume 5: Verifiable C](https://softwarefoundations.cis.upenn.edu/vc-current/index.html) - An extended tutorial on specifying and verifying C programs using the Verified Software Toolchain.
  * [Volume 6: Separation Logic Foundations](https://softwarefoundations.cis.upenn.edu/slf-current/index.html) - An introduction to separation logic and how to build program verification tools on top of it.
* [Certified Programming with Dependent Types](http://adam.chlipala.net/cpdt/) - Textbook about practical engineering with Coq which teaches advanced practical tricks and a very specific style of proof.
* [Program Logics for Certified Compilers](https://www.cs.princeton.edu/~appel/papers/plcc.pdf) - Book that explains how to construct program logics using separation logic, accompanied by a formal model in Coq which is applied to the Clight programming language and other examples.
* [Formal Reasoning About Programs](http://adam.chlipala.net/frap/) - Book that simultaneously provides a general introduction to formal logical reasoning about the correctness of programs and to using Coq for this purpose.
* [Programs and Proofs](https://ilyasergey.net/pnp/) - Book that gives a brief and practically-oriented introduction to interactive proofs in Coq which emphasizes the computational nature of inductive reasoning about decidable propositions via a small set of primitives from the SSReflect proof language.
* [Computer Arithmetic and Formal Proofs](https://www.sciencedirect.com/book/9781785481123/computer-arithmetic-and-formal-proofs) - Book that describes how to formally specify and verify floating-point algorithms in Coq using the Flocq library.
* [The Mathematical Components book](https://math-comp.github.io/mcb/) - Book oriented towards mathematically inclined users, focusing on the Mathematical Components library and the SSReflect proof language.

### Course Material

* [Lectures on Software Foundations](https://github.com/clarksmr/sf-lectures) ⭐ 151 | 🐛 0 | 🌐 HTML | 📅 2024-04-30 - Material on the Software Foundations series of textbooks, including a series of YouTube videos.
* [Mechanized Semantics](https://github.com/xavierleroy/cdf-mech-sem) ⭐ 70 | 🐛 0 | 🌐 Coq | 📅 2024-04-09 - Companion Coq sources for a course on programming language semantics at Collège de France.
* [Program Logics](https://github.com/xavierleroy/cdf-program-logics) ⭐ 41 | 🐛 0 | 🌐 Coq | 📅 2021-04-14 - Companion Coq sources for a course on program logics at Collège de France.
* [Floating-Point Numbers and Formal Proof](https://github.com/thery/FlocqLecture) ⭐ 8 | 🐛 0 | 🌐 Rocq Prover | 📅 2026-01-31 - Introductory course on Coq real numbers and floating-point numbers from the Flocq library.
* [MathComp School](https://github.com/gares/math-comp-school-2022) ⭐ 6 | 🐛 1 | 🌐 Coq | 📅 2022-12-15 - Coq sources for lessons and exercises that introduce the SSReflect proof language and the Mathematical Components library.
* [An Introduction to MathComp-Analysis](https://staff.aist.go.jp/reynald.affeldt/documents/karate-coq.pdf) - Lecture notes on getting started with the Mathematical Components library and using it for classical reasoning and real analysis.
* [Foundations of Separation Logic](https://chargueraud.org/teach/verif/) - Introduction to using separation logic to reason about sequential imperative programs in Coq.
* [Introduction to the Theory of Computation](https://gitlab.com/umb-svl/turing) - Formalization to support an undergraduate course on the theory of computation, including languages and Turing machines.
* [Program verification with types and logic](https://gitlab.science.ru.nl/program-verification/course-2023-2024) - Lectures and exercise material for a course in programming language semantics, type systems and program logics, using Coq, at Radboud University Nijmegen.
* [Proofs and Reliable Programming using Coq](https://team.inria.fr/stamp/proofs-and-reliable-programming-using-coq-2022/) - Introduction to developing and verifying programs with Coq.

### Tutorials and Hints

* [Tricks in Coq](https://github.com/coq-community/coq-tricks) ⭐ 538 | 🐛 7 | 🌐 Coq | 📅 2025-05-28 - Tips, tricks, and features in Coq that are hard to discover.
* [Coq'Art Exercises and Tutorials](https://github.com/coq-community/coq-art) ⭐ 127 | 🐛 2 | 🌐 Coq | 📅 2025-02-15 - Coq code and exercises from the Coq'Art book, including additional tutorials.
* [Lemma Overloading](https://github.com/coq-community/lemma-overloading) ⭐ 27 | 🐛 4 | 🌐 Coq | 📅 2025-03-28 - Demonstration of design patterns for programming and proving with canonical structures.
* [MathComp Tutorial Materials](https://github.com/math-comp/tutorial_material) ⭐ 17 | 🐛 1 | 🌐 Coq | 📅 2023-10-29 - Source code for Mathematical Components tutorials.
* [Coq in a Hurry](http://cel.archives-ouvertes.fr/inria-00001173) - Introduction to how Coq can be used to define logical concepts and functions and reason about them.
* [Coq requirements in Common Criteria evaluations](https://inria.hal.science/hal-04452421) - Guide on how to write readable and reviewable Coq code in high assurance applications.
* [Coq Tactics in Plain English](https://charlesaverill.github.io/ctpe/) - Guide to Coq tactics with explanations and examples.
* [Learn X in Y minutes where X=Coq](https://learnxinyminutes.com/docs/coq/) - Whirlwind tour of Coq as a language.
* [Mike Nahas's Coq Tutorial](https://mdnahas.github.io/doc/nahas_tutorial.html) - Basics of using Coq to write formal proofs.
