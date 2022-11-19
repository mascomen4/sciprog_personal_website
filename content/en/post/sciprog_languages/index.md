---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Languages of Scientific Programming"
subtitle: "sciprog languages"
summary: ""
authors: []
tags: []
categories: []
date: 2022-10-10T23:19:57+03:00
lastmod: 2022-10-10T23:19:57+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

The first stage in the development of computer technology refers to the period that goes before the start of World War II and lasted until the early 40s.

During World War II, the primary task of computed case computers was to determine ballistic trajectories for solving differential motion features.

In the early 1950s, the first languages ​​began to appear that used symbolic notation systems. Grace Hopper led the Univac group that developed the A-0 language, and John Backus created the Speedcoding language for the IBM 701. Both of these languages ​​established themselves for translating simple arithmetic expressions into executable machine code.

The real breakthrough came in 1957, when Backus led the thought on the FORTRAN language, or formula translator (FORmula TRANslator).

At an early stage of development, FORTRAN was focused on numerical calculations, but in the end there was a completely finished programming language that implements structure control, conditional I / O statements. Few suggested that a language capable of competing with assembly language, in which machine instructions were coded by hand, the main task was the initially executable code, so many operators were developed taking into account the specifics of the IBM 704 computer.

The FORTRAN language concept of the three-branch transition mechanism stemmed from the IBM 407 hardware architecture, and statements such as READ INPUT TAPE are written quite fancifully today. All this did not look very elegant, but at that time they did not pay attention to the saturation of programming, but they noticed that the language was moving around writing programs that ran fairly quickly on a computer of the mentioned type.

FORTRAN is a very successful language and is covered almost until the 70s. The next version of FORTRAN was released in 1958 and became known as FORTRAN II, after several years of FORTRAN IV.

each case of computer production implemented a new version of the language for their computers, then, of course, chaos reigned. In 1966, FORTRAN IV became a standard under the name FORTRAN 66 and from a technical point of view at the international level, as a result of which the FORTRAN 77 and FORTRAN 90 standards were adopted.

FORTRAN proved so widespread in Europe that IBM would dominate the computer industry.

The German Society for Applied Mathematics (German Society for Applied Mathematics - GAMM) has set up a committee to develop a universal language. At the same time, the Association for Computing Machinery (ACM) introduced a similar committee in the US. Despite the fact that the Europeans had a mention of dominance in America, both committees merged into one. This committee developed IAL (International Algorithmic Language). The proposed name ALGOL (ALGOrithmic Language) was initially rejected. But since it became common, the official name of IAL had to be subsequently changed to ALGOL 58. A new version appeared in 1960, and ALGOL 60 (with significant changes made in 1962) from the 60s to the early 70s. last century was the standard academic programming language.

While FORTRAN was being developed for use on the IBM 704, the designers of ALGOL had very different goals, namely:

1. Make the notation in ALGOL closer to the standard mathematical one.

2. ALGOL must be adapted to describe algorithms.

3. ALGOL programs must be compiled into machine language.

4. ALGOL should not be dedicated to a specific machine architecture.

All these goals happened in 1958 unattainable. In order to be architecture independent, I/O capabilities were not included in this language; special procedures arose for such operations. It was also the federal independence of the language from the computer architecture, but at the same time it led to the fact that each implementation could be incompatible with any other. Although ALGOL was not successful in Europe, it never achieved commercial success in America, but its influence on other languages ​​was still quite large. As an example, we offer a version of the IAL language developed by Schwartz (Jules Schwartz) of System Development Corporation (CDS), JOVIAL (Jules' Own Version of IAL). This language is used by the US Air Force for applied tasks.

Backus was the editor of the report that observed the ALGOL language. It uses a syntax detection system that tests the concept of a context-free language developed by Chomsky. This is how the development of formal grammars in the field of programming languages ​​took place. Backus and Naur contributed a huge
