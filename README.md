# Assuring Safe Interaction Between Run-time Adaptations Using Refinement Types

This paper presents our work in the integration of COP with Refinement types, to verify the completeness of adaptations, assuring that the applications remain safe, under any interactions between adaptations

Current target: COLA - 

## Structure 

* preamble: contains all package and command definitions. Everything should be set by now, but if something needs defining this is the place to do it (look inside to see the structure)
* bibfiles
    * local.bib: contains all local bib references i.e., references used for this paper specifically. Most references should be added here
    * bib folder: this folder contains many references used for multiple purposes, in particular the _compsci.bib_ file contains many references on software engineering, programming languages, and adaptive systems. Check here if the reference exists before adding it to the _local.bib_ file
* acronyms.tex: contains all Acronyms used in the paper (look into the file for example of the definition). Acronyms are used with the \ac{ACRONYM} command
* contents: The folder containing the paper content. A file per section or a larger modularity for big sections (as needed).
* tables: The folder containing all tables to be included in the paper
* figures: The folder containing the **vectorized (e.g., pdf, svg)** images included in the paper. optionally, this folder can have a subfolder to include images' source (e.g., tikz, omnigraffle, etc).
* data: Folder to include all relevant data from the experiments for the paper


## Useful commands

* Pointers to objects in the text (e.g., images, tables, code, sections, code-line, ....) are referenced using the fancyref package using the command \fref{} respectively starting with (img:, tab:, lst:, sec:, ln:, ....)
* _\authorcomment[TYPE]{AUTHOR}{COMMENT}_ is used to leave annotation inlined with the text. Comments only appear in draft mode (the option in the documentclass in the _main.tex_ file) and are invisible otherwise. TYPE can be comment, missing, idea, note, and author.
* _\ie \eg \cf_ are used respectively for the abbreviations i.e., e.g., cf.
* listings are defined according to each specific language in the _preamble_ file and generate their own environment (e.g., _\ctxraits[....]{....}_ generates a contexts traits listing).
