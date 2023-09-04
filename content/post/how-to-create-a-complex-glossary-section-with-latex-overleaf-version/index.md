---
title: How to create a complex Glossary section with Latex (Overleaf version)
date: 2023-09-04T13:34:32.054Z
draft: true
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
% % Solution 1: unsorted (option 4 without bib2gls)
% % \usepackage[nonumberlist,acronym,symbols]{glossaries-extra} 

% % Solution 2: sorted (option 2 makeindex)
% \usepackage[nonumberlist,acronym]{glossaries} 
% % \usepackage[nonumberlist,acronym,automake,order=letter,sort=def]{glossaries}

% Solution 3: multiple glossaries (option 2 makeindex)
% \usepackage[nonumberlist,acronym,section=section,nogroupskip,style=short]{glossaries}
% \glssetwidest{ABCDEF}% widest name[![enter image description here][2]][2]
% \newglossary{operator}{opes}{opeo}{Operators and Relations}
% \newglossary{const}{cons}{cono}{Constants and Physical Magnitudes}
% \newglossary{gnss}{gnss}{gnso}{GNSS Measurements and Error Sources}
% \newglossary{set}{sets}{seto}{Interval and Set Representations}
% \newglossary{state}{stas}{stao}{State Estimation and Uncertainty Modeling}
% \newglossary{raim}{rais}{raio}{Integrity Monitoring Parameters}

% solution 4: multiple-layer 'alttree' (option 2 makeindex)
\usepackage[style=alttree,nonumberlist,acronym,nogroupskip,toc]{glossaries}


% list of acronyms
\loadglsentries{chapters/acronyms}

% % list of symbols
\makeglossaries
% \makenoidxglossaries
\loadglsentries{chapters/symbols}
% \loadglsentries{chapters/symbols_S3.tex}
% \addcontentsline{toc}{chapter}{Acronyms}
    % \glsaddall
    % \printacronyms
    % \printglossary[type=\acronymtype]
    % \printunsrtglossary[type=\acronymtype]
    % \clearpage
    
    % \addcontentsline{toc}{chapter}{Notation and Nomenclature}
    % \chapter*{Notation and Nomenclature}
    % \printnoidxglossaries
    % \printglossaries
    % \printglossary[title=Notation and Nomenclature]
    % \printunsrtglossary[title=Notation and Nomenclature]
    % \printnoidxglossary
    % \cleardoublepage
    
    % Solution 3
    % \addchap{Acronyms, Notations and Nomenclatures}
    % % This chapter lists all acronyms, notations and nomenclatures mentioned across this dissertation.
    % % Now print actual glossaries
    % \glsaddallunused
    % % \printglossaries%[style=alttreeX,title={Acronyms, Notations and Nomenclatures}]
    % \printglossary[type=\acronymtype]
    % \printglossary[type=operator]
    % \printglossary[type=const]
    % \printglossary[type=set]
    % \printglossary[type=gnss]
    % \printglossary[type=state]
    % \printglossary[type=raim]
    
    % Solution 4
    \glssetwidest[0]{ABCDEF}\setglossarystyle{alttree}
    \printglossary[type=\acronymtype]
    
    \glssetwidest[0]{A}\glssetwidest[1]{ABCDEF}\setglossarystyle{alttree}
    \printglossary[title={Notations and Nomenclatures}]

l﻿atexmkrc
add_cus_dep( 'opeo','opes', 0, 'glo2gls' );
add_cus_dep( 'cono','cons', 0, 'glo2gls' );
add_cus_dep( 'gnso','gnss', 0, 'glo2gls' );
add_cus_dep( 'seto','sets', 0, 'glo2gls' );
add_cus_dep( 'stao','stas', 0, 'glo2gls' );
add_cus_dep( 'raio','rais', 0, 'glo2gls' );


