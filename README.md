# Software Foundation Solution

Software Foundations Textbook Solution

There are some unsolved problems like 'informal proof'.

If you have any questions or find problem in solution, please tell me via [issue](https://github.com/Ailrun/software_foundations_solution/issue).

**IMPORTANT: This repository is written based on Coq8.5pl2.**  
You can download Coq8.5pl1 in [this link](https://coq.inria.fr/download).

## Table Of Contents

- [Table Of Contents](#table-of-contents)
- [About Software Foundations](#about-software-foundations)
- [Table Of Solutions](#table-of-solutions)
  - [Solutions Grouped By Road Map](#solutions-grouped-by-road-map)
    - [Blue Arrow Of Road Map](#blue-arrow-of-road-map)
    - [Others Of Road Map](#others-of-road-map)
- [Whole Solutions](#whole-solutions)
- [Author Of This Solutions](#author-of-this-solutions)

## About Software Foundations

Software Foundations is the textbook for Software Foundations course in University of Pennsylvania (Pennsylvania, US) and Programming Language course in Seoul National University (Seoul, Korea) and ... (Give me additional info about).

You can download the latest version of the book in [this link](https://www.cis.upenn.edu/~bcpierce/sf/current/index.html).  
**This repository based on version 4.0. (Version of book in the link may will changed.)**

This book deals with not only automatic proof, but also mathematical formalization of softwares using [Coq](https://coq.inria.fr/) language. For more detail information, please check [the preface of book](https://www.cis.upenn.edu/~bcpierce/sf/current/Preface.html)

## Table Of Solutions

Status columns in next tables have one of the following values.
- Nothing : There is nothing to solve in the file.
- Solved : File is already solved. If you find any error or you have proposal, please report it using [issue](https://github.com/Ailrun/software_foundations_solution/issue)
- Unsolved : File is not solved yet.
- Unchecked : Not checked whether there is problem or not, yet.

### Solutions Grouped By Road Map

#### Blue Arrow Of Road Map

| Section Title   | Coq File                                | HTML File                                     | Status    | Updated at |
|-----------------|-----------------------------------------|-----------------------------------------------|:---------:|-----------:|
| Preface         | [Preface.v](./book/Preface.v)           | [Preface.html](./book/Preface.html)           | Nothing   | 2016/07/07 |
| Basics          | [Basics.v](./book/Basics.v)             | [Basics.html](./book/Basics.html)             | Unchecked | 2016/07/07 |
| Induction       | [Induction.v](./book/Induction.v)       | [Induction.html](./book/Induction.html)       | Unchecked | 2016/07/07 |
| Lists           | [Lists.v](./book/Lists.v)               | [Lists.html](./book/Lists.html)               | Unchecked | 2016/07/07 |
| Poly            | [Poly.v](./book/Poly.v)                 | [Poly.html](./book/Poly.html)                 | Unchecked | 2016/07/07 |
| Tactics         | [Tactics.v](./book/Tactics.v)           | [Tactics.html](./book/Tactics.html)           | Unchecked | 2016/07/07 |
| Logic           | [Logic.v](./book/Logic.v)               | [Logic.html](./book/Logic.html)               | Unchecked | 2016/07/07 |
| IndProp         | [IndProp.v](./book/IndProp.v)           | [IntProp.html](./book/IntProp.html)           | Unchecked | 2016/07/07 |
| Maps            | [Maps.v](./book/Maps.v)                 | [Maps.html](./book/Maps.html)                 | Nothing   | 2016/07/07 |
| *SfLib*&#42;    | [SfLib.v](./book/SfLib.v)               | [SfLib.html](./book/SfLib.html)               | Nothing   | 2016/07/07 |
| Imp             | [Imp.v](./book/Imp.v)                   | [Imp.html](./book/Imp.html)                   | Unchecked | 2016/07/07 |
| Equiv           | [Equiv.v](./book/Equiv.v)               | [Equiv.html](./book/Equiv.html)               | Unchecked | 2016/07/07 |
| Hoare           | [Hoare.v](./book/Hoare.v)               | [Hoare.html](./book/Hoare.html)               | Unchecked | 2016/07/07 |
| Hoare2          | [Hoare2.v](./book/Hoare2.v)             | [Hoare2.html](./book/Hoare2.html)             | Unchecked | 2016/07/07 |
| Smallstep       | [Smallstep.v](./book/Smallstep.v)       | [Smallstep.html](./book/Smallstep.html)       | Unchecked | 2016/07/07 |
| Auto            | [Auto.v](./book/Auto.v)                 | [Auto.html](./book/Auto.html)                 | Nothing   | 2016/07/07 |
| Types           | [Types.v](./book/Types.v)               | [Types.html](./book/Types.html)               | Unchecked | 2016/07/07 |
| Stlc            | [Stlc.v](./book/Stlc.v)                 | [Stlc.html](./book/Stlc.html)                 | Unchecked | 2016/07/07 |
| StlcProp        | [StlcProp.v](./book/StlcProp.v)         | [StlcProp.html](./book/StlcProp.html)         | Unchecked | 2016/07/07 |
| MoreStlc        | [MoreStlc.v](./book/MoreStlc.v)         | [MoreStlc.html](./book/MoreStlc.html)         | Unchecked | 2016/07/07 |
| Typechecking    | [Typechecking.v](./book/TypeChecking.v) | [Typechecking.html](./book/Typechecking.html) | Nothing   | 2016/07/07 |
| References      | [References.v](./book/References.v)     | [References.html](./book/References.html)     | Unchecked | 2016/07/07 |
| Sub             | [Sub.v](./book/Sub.v)                   | [Sub.html](./book/Sub.html)                   | Unchecked | 2016/07/07 |
| Records         | [Records.v](./book/Records.v)           | [Records.html](./book/Records.html)           | Unchecked | 2016/07/07 |
| RecordSub       | [RecordSub.v](./book/RecordSub.v)       | [RecordSub.html](./book/RecordSub.html)       | Unchecked | 2016/07/07 |
| Postscript      | [Postscript.v](./book/Postscript.v)     | [Postscript.html](./book/Postscript.html)     | Nothing   | 2016/07/07 |

&#42; Not in blue arrow sequence, but necessary for this sequence.

#### Others Of Road Map

| Section Title   | Coq File                                  | HTML File                                       | Status    | Updated at |
|-----------------|-------------------------------------------|-------------------------------------------------|:---------:|-----------:|
| Rel             | [Rel.v](./book/Rel.v)                     | [Rel.html](./book/Rel.html)                     | Unchecked | 2016/07/07 |
| ProofObjects    | [ProofObjects.v](./book/ProofObjects.v)   | [ProofObjects.html](./book/ProofObjects.html)   | Unchecked | 2016/07/07 |
| IndPrinciples   | [IndPrinciples.v](./book/IndPrinciples.v) | [IndPrinciples.html](./book/IndPrinciples.html) | Unchecked | 2016/07/07 |
| PE              | [PE.v](./book/PE.v)                       | [PE.html](./book/PE.html)                       | Unchecked | 2016/07/07 |
| ImpCEvalFun     | [ImpCEvalFun.v](./book/ImpCEvalFun.v)     | [ImpCEvalFun.html](./book/ImpCEvalFun.html)     | Unchecked | 2016/07/07 |
| ImpParser       | [ImpParser.v](./book/ImpParser.v)         | [ImpParser.html](./book/ImpParser.html)         | Unchecked | 2016/07/07 |
| Extraction      | [Extraction.v](./book/Extraction.v)       | [Extraction.html](./book/Extraction.html)       | Unchecked | 2016/07/07 |
| HoareAsLogic    | [HoareAsLogic.v](./book/HoareAsLogic.v)   | [HoareAsLogic.html](./book/HoareAsLogic.html)   | Unchecked | 2016/07/07 |
| LibTactics      | [LibTactics.v](./book/LibTactics.v)       | [LibTactics.html](./book/LibTactics.html)       | Nothing   | 2016/07/07 |
| UseTactics      | [UseTactics.v](./book/UseTactics.v)       | [UseTactics.html](./book/UseTactics.html)       | Unchecked | 2016/07/07 |
| UseAuto         | [UseAuto.v](./book/UseAuto.v)             | [UseAuto.html](./book/UseAuto.html)             | Unchecked | 2016/07/07 |
| Norm            | [Norm.v](./book/Norm.v)                   | [Norm.html](./book/Norm.html)                   | Unchecked | 2016/07/07 |

## Whole Solutions

## Author Of This Solutions

Junyoung Clare Jang, Ailrun
- [Github](https://github.com/Ailrun)
- [Github Blog](https://ailrun.github.io/)
