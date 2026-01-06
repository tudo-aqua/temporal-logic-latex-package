# Latex package for Temporal Logic Operators

## Overview

The package defines functions for rendering the temporal operators defined in
the **Linear Temporal Logic** (_LTL_), **Metric Temporal Logic** (_MTL_), **Metric First-order 
Temporal Logic** (_MFOTL_), and **Counting Metric First-order Temporal Binding Logic** (_CMFTBL_). The package 
defines various functions with variants in order to include or omit optional 
parameters to the operators like the optional interval.

## Build the package

If you want to generate the necessary `.sty` file and the documentation for this
package you can do this with the following steps:  

1. Generate `.sty` file from `.ins` file with the command:  
		`latex temporal-logic.ins`
2. Generate documentation with the command:  
		`latexmk -pdf temporal-logic.dtx`

## Copyright and License

Copyright (C) 2026 Dominik Schmid

This work may be distributed and/or modified under the conditions of the LaTeX
Project Public License, either version 1.3c of this license or (at your option)
any later version. The latest version of this license is in
http://www.latex-project.org/lppl.txt and version 1.3c or later is part of all
distributions of LaTeX version 2005/12/01 or later.
