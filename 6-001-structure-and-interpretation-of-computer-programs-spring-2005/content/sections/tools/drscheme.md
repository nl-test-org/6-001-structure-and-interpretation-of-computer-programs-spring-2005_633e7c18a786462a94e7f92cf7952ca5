---
course_id: 6-001-structure-and-interpretation-of-computer-programs-spring-2005
layout: course_section
parent_title: Tools
title: A Note About DrScheme
type: course
uid: c2d4cdeaaa1d3f4804e1507a4d93aa69

---

[DrScheme](http://www.plt-scheme.org/software/drscheme/) is The [Rice University Programming Languages Team](http://www.cs.rice.edu/CS/PLT/)'s graphical user interface to a Scheme system for students. A quick examination of the latest version was encouraging. And DrScheme is **free**.

DrScheme has some innovative user-interface features not found in MIT Scheme: text is color-coded, for example to highlight (in red) undefined variables; it has a syntax analysis command which, for example, can display arrows from occurrences of variables to their definitions elsewhere in the code; it has several output modes in addition to the standard one, for example an output mode which shows sharing in lists, and another output mode in which values are printed as canonical INPUT expressions - in this mode, for example, the list value which is the result of evaluating (cons 1 (cons (+ 2 3) '())) prints out as (list 1 5). DrScheme also has Windows menu control of most features, and error messages that are more clear than those in MIT Scheme.

To run satisfactorily, it requires at least 20 MB of RAM and a 150 MHZ processor. It has extensive online documentation.